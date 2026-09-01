# Incident Report 001 — Suspicious File Detection

## 1. Incident Summary

**Incident ID:** INC-001
**Severity:** Medium
**Status:** Investigating
**Detection Source:** Wazuh SIEM
**Affected Endpoint:** Ubuntu Linux
**Analyst:** Henry Anietie

## 2. Description

A suspicious file was created on the monitored Ubuntu endpoint and generated a security event in Wazuh.

The event was investigated using Wazuh logs and security intelligence to determine whether the file represented a potential security threat.

## 3. Investigation

The following activities were performed:

* Reviewed the Wazuh alert.
* Identified the affected endpoint.
* Examined the suspicious file.
* Reviewed relevant security logs.
* Investigated the file using VirusTotal.
* Checked the available Indicators of Compromise (IOCs).
* Assessed the potential impact of the event.

## 4. Indicators of Compromise

| Indicator           | Value                |
| ------------------- | -------------------- |
| Endpoint            | Ubuntu Linux         |
| File                | Suspicious test file |
| Detection Source    | Wazuh                |
| Threat Intelligence | VirusTotal           |

## 5. Analysis

The alert was investigated to determine whether the detected activity represented malicious behavior.

The available evidence was reviewed and correlated with security intelligence before determining the appropriate response.

## 6. Response

The suspicious activity was documented and investigated.

Additional monitoring was recommended to identify any related activity on the endpoint.

## 7. Lessons Learned

This investigation demonstrated the importance of:

* SIEM alert monitoring
* Log analysis
* IOC investigation
* Threat intelligence
* Endpoint monitoring
* Security incident documentation

## 8. Tools Used

* Wazuh
* Ubuntu Linux
* Kali Linux
* VirusTotal
* VirtualBox

## 9. Evidence

Screenshots and supporting evidence will be added to the `screenshots` directory.
