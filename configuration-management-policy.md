# Configuration Management Policy

Wildfire Labs standardizes and automates configuration management through the use of Ansible scripts as well as documentation of all changes to production systems and networks. Ansible automatically configures all Wildfire Labs systems according to established and tested policies, and is used as part of our Disaster Recovery plan and process.

## **Applicable Standards**

### **HITRUST Common Security Framework**

* 06 - Configuration Management

### **HIPAA Security Rule**

* 164.310\(a\)\(2\)\(iii\) Access Control & Validation Procedures

## **Configuration Management Policies**

1. Ansible is used to standardize and automate configuration management.
2. OSSEC is used to scan systems every 2 hours and on reboot. These scans capture file system changes and also unauthorized or malicious software.
3. No systems are deployed into Wildfire Labs environments without approval of the Wildfire Labs Security Officer.
4. All changes to production systems, network devices, and firewalls are approved by the Wildfire Labs Security Officer before they are implemented. Additionally, all changes are tested before they are implemented in production.
5. An up-to-date inventory of systems is maintained using Google spreadsheets and architecture diagrams hosted on Google Drive. All systems are categorized as production and utility to differentiate based on criticality.
6. Clocks are synchronized across all systems using NTP. Modifying time data on systems is restricted.
7. All front end functionality \(developer dashboards and portals\) is separated from backend \(database and app servers\) systems by being deployed on separate servers and in different Virtual Private Networks.
8. All software and systems are tested using unit tests, feature tests, and end to end tests.
9. All committed code is reviewed to assure software code quality and proactively detect potential security issues in development.
10. Wildfire Labs utilizes development and staging environments that mirror production to assure proper function.
11. Wildfire Labs also deploys environments locally using Virtualbox to assure functionality before moving to staging or production.

