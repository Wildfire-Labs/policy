# Untitled

## Data Integrity Policy

Wildfire Labs takes data integrity very seriously. As stewards and partners of Wildfire Labs Customers, we strive to assure data is protected from unauthorized access and that it is available when needed. The following policies drive many of our procedures and technical settings in support of the Wildfire Labs mission of data protection.

## **Applicable Standards**

### **HITRUST Common Security Framework**

* 10.b - Input Data Validation

### **HIPAA Security Rule**

* 164.308\(a\)\(8\) - Evaluation

## **Data Integrity Policies**

Production systems that create, receive, store, or transmit Customer data \(hereafter “Production Systems”\) must follow the guidelines described in this section.

1. **Disabling Non-essential Services**
   * All Production Systems must disable services that are not required to achieve the business purpose or function of the system.
2. **Monitoring Login Attempts**
   * All access to Production Systems must be logged. This is done following the Wildfire Labs Auditing Policy.
3. **Prevention of Malware on Production Systems**
   * All Production Systems must have OSSEC running and set to scan the system every 2 hours and at reboot to assure no malware is present. Detected malware is evaluated and removed.
   * All Production Systems are to only be used for Wildfire Labs business needs.
4. **Patch Management**
   * Patches, application, and system OS versions are kept up to date at all times. New versions are tested.
   * Administrators subscribe to mailing lists to assure up to date on the current version of all Wildfire Labs managed software on Production Systems.
5. **Intrusion Detection and Vulnerability Scanning**
   * Production Systems are monitored using IDS systems. Suspicious activity is logged and alerts are generated.
   * Vulnerability scanning of Production Systems must occur on a predetermined, regular basis, no less than annually. Currently it is weekly. Scans are reviewed by Security Officer, with defined steps for risk mitigation, and retained for future reference.
6. **Production System Security**
   * System, network, and server security is managed and maintained by the Security Officer.
   * Up to date system lists and architecture diagrams are kept for all Production environments.
   * Access to Production Systems is controlled using centralized tools and two-factor authentication.
7. **Production Data Security**
   * Reduce the risk of compromise of Production Data.
   * Implement and/or review controls designed to protect Production Data from improper alteration or destruction.
   * All Production Data at rest is stored on encrypted volumes.
   * Ensure that Confidential data is stored in a manner that supports user access logs and automated monitoring for potential security incidents.
   * Ensure Wildfire Labs customer Production Data is segmented and only accessible to customers authorized to access data.
8. **Transmission Security**
   * All data transmission is encrypted end to end. Encryption is not terminated at the network endpoint, and is carried through to the application.
   * Encryption keys and machines that generate keys are protected from unauthorized access.
   * System logs of all transmissions of Production Data access. These logs must be available for audit.
   * Encryption keys are limited to use for one year and then must be regenerated.
   * In the case of Wildfire Labs provided APIs, provide mechanisms to assure a person sending or receiving data is authorized to send and save data.

