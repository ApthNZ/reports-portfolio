
# Threat Report - Crazy Domains Phishing Campaign

**Report Metadata**

| Attribute                              | Value                                |
| -------------------------------------- | ------------------------------------ |
| **Author**                             | Andrew Wilkinson                     |
| **Published Date**                     | >>Date                               |
| **Report Version**                     | >>Version                            |
| **Report Reliability/Credibility**     | >> (>>Reliability, >>Credibility)    |
| **Threat Actor Infrastructure Status** | Active as of published date          |
| **TLP**                                | Clear                                |


**Contents**

| Section                           | Page Number |
| --------------------------------- | ----------- |
| 1. Report Summary                 | 2           |


\newpage

# 1. Report Summary
>>


# 2. Report Purpose and Scope
Through the event analysis and compilation of this report, the Author had three goals:

1. Gather enough information for an actionable report to >>Vendor
2. Gather enough information for a comprehensive and actionable report to the New Zealand National Cyber Security Centre (NCSC), and
3. Take advantage of learning opportunities, specifically around data collection and use of MISP.

The scope of this report was constrained to focus on:

1. Data collection relevant to >>Vendor and the NCSC,
2. Data clearly related to the event, and
3. Data that could be collected passively (e.g. dig, whois).

Left out of scope were:

1. Data points that were correlate-able but not clearly related to the event,
2. Any data not available from public sources, and
3. Data collection using active scanning of threat actor infrastructure.

The Author assesses the reliability and credibility of this report as >>Assess according to the Admiralty Scale:
 - External sources are assessed as >>Assess


# 3. Event Detection and Timeline
### 3.1 Event Overview
TTPs are mapped to MITRE ATT&CK.
More information on infrastructure is available in the Observed Data and Correlations section.

**Adversary:** >>

**Victim:** >>

**Infrastructure:**

- >>

**Capabilities/TTPs:** Credential Harvesting

- >>

### 3.2 Timeline

| Date (NZDT) | Event                            | Notes                                                                                                  |
| ----------- | -------------------------------- | ------------------------------------------------------------------------------------------------------ |
| >>          | >>                               | >>                                                                                                     |



# 4. Observed Data and Correlations
Full dataset is available at: 
>>GH Link

### 4.1 Infrastructure Map
The infrastructure map below was generated in MISP; STIX and MISP files are available at:
>>GH Link
>>Image


### 4.2 Attack Chain
>>Image

| Activity                          | Reference   |
| --------------------------------- | ----------- |
| >>                                | >>         |


# 5. Analytical Judgments
### 5.1 Analysis Summary

 - >>Estimative language

### 5.2 Analysis Detail
 - >>ACH


# 6. Indicators of Compromise
### 6.1 Atomic Indicators

| IOC | Type | Context |
| ----------------------------------- | ------------ | ---------------------------------------- |
| >>IOC| >>Type      | >>Context                                                                |

### 6.2 Behavioural Indicators
**Use of Fake List Values in Email Header**
>>Indicators


# 7. Recommendations
The Author lacks specific knowledge of report recipient capabilities, and as such the recommendations below are brief and generic.

| Recommendation                                                                                      | Justification                                                                                                                                          |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| >>Recommendation                                                                                    | >>Justification                                |



# 8. Sources
Reliability and Credibility scores are assessed according to the Admiralty Scale:

|       | Reliability of the Collection Capability |       | Credibility of the Information Collected |
| ----- | ---------------------------------------- | ----- | ---------------------------------------- |
| **A** | Completely reliable                      | **1** | Completely credible                      |
| **B** | Usually reliable                         | **2** | Probably true                            |
| **C** | Fairly reliable                          | **3** | Possibly true                            |
| **D** | Not usually reliable                     | **4** | Doubtful                                 |
| **E** | Unreliable                               | **5** | Improbable                               |
| **F** | Reliability cannot be judged             | **6** | Truth cannot be judged                   |

| Source | Purpose | Reliability | Credibility | Notes |
| ------------ | ---------------------- | ------------ | ---------------------- | ---------------------- |
| ANY.RUN | Sandbox analysis of phishing link. | **B** — Well-known sandbox. | **3** — Sandbox may not reflect real-world execution. | PCAP extracted from ANY.RUN. |


# 9. Artifacts & References
### 9.1 Artifacts
Artifacts available for download at: 
>>GH Link

 - >>List


### 9.2 References
| Reference                                                    | Use in This Report                                                                                                                                   | URL                                                                                                                           |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Admiralty Scale**                                          | Reliability and Credibility of sources, and the overall report.                                                                                      | [Link](https://www.researchgate.net/publication/328858953_Improving_Information_Evaluation_for_Intelligence_Production) |
| **Traffic Light Protocol**                                   | Ensuring sensitive information is shared with the appropriate audience.                                                                              | [Link](https://www.ncsc.govt.nz/protect-your-organisation/traffic-light-protocol/)                                    |
| **Intelligence Community Directive 203, Analytic Standards** | Improve the usefulness of the report through consistency with intelligence community best practices, and specific use of expressions of probability. | [Link](https://www.dni.gov/files/documents/ICD/ICD-203.pdf)                                                           |
| **MITRE ATT&CK**                                             | Mapping of adversary tactics and techniques.                                                                                                         | [Link](https://attack.mitre.org/)                                                                                       |

