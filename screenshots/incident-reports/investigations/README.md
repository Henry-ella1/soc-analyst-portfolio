# 🔎 Security Investigations

This directory documents security investigations performed using the Wazuh SIEM and other security tools.

## Investigation Process

The investigations follow a basic SOC workflow:

1. **Alert Identification**

   * Review the Wazuh alert.
   * Identify the affected endpoint.
   * Determine the alert severity.

2. **Alert Analysis**

   * Examine the event details.
   * Review timestamps and affected processes/files.
   * Identify suspicious indicators.

3. **IOC Investigation**

   * Investigate IP addresses, domains, file hashes, or filenames when available.
   * Use threat-intelligence sources to gather additional context.

4. **Impact Assessment**

   * Determine what system or resource was affected.
   * Assess whether the activity appears malicious or benign.

5. **Response**

   * Document the findings.
   * Recommend appropriate containment or remediation actions.

6. **Documentation**

   * Record the investigation and supporting evidence.
   * Store relevant screenshots and findings in this repository.

## Investigations

| ID      | Investigation                 | Status  |
| ------- | ----------------------------- | ------- |
| INV-001 | Suspicious File Investigation | Completeed|

Additional investigations will be added as the SOC home lab develops.
