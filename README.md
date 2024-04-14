# Security Engineering

This project aims to make cybersecurity and systems security engineering standards and guidance more accessible and actionable. Here, you willl find CSV files containing structured data extracted from a variety of standards and sources.

**Why This Project Matters**

Cybersecurity standards and guidance are a crucial mechanism for engineering better, more secure systems and managing risk. However, this information is often provided in non-usable formats (e.g., embedded tables within a .pdf) or spread across many different documents or sources, making it difficult to utilize effectively or evaluate holistically. This project addresses these challenges by:

- **Centralizing Data:** Aggregating data from disparate documents and sources.
- **Enhancing Usability:** Converting data into CSV files that can be easily manipulated and analyzed.
- **Facilitating Relationships:** Relating and integrate data through junction tables.

**Table Of Contents:**

- [Getting Started](#getting-started)
- [Airtable](#airtable)
- [CSV Files](#csv-files)
- [Junction Tables](#junction-tables)
- [Questions and Feedback?](#questions-and-feedback)

## Getting Started

You can use the CSV files in this repository to:

- Integrate cybersecurity standards data into your tools and workflows.
- Analyze relationships between different standards and requirements.
- Develop applications or services that leverage centralized, structured security data.

## Airtable

[**Airtable Database**](https://airtable.com/appIfMZL3Q2ydSFFk/shrT54RhWgP8oeoKI "Airtable Database")

Airtable is a cloud-based software platform that combines the functionality of a database with the ease of use of a spreadsheet. It allows users to create and share relational databases with a simple, user-friendly interface. 

To enhance usability and accessibility, this project features a relational database created in Airtable that organizes and links the CSV files containing cybersecurity standards. This setup allows for a dynamic and interactive way to explore and relate the data across various security standards.

**Database Schema**
Below is a screenshot of the database scheme configured within Airtable. Here is a [**link**](https://airtable.com/appIfMZL3Q2ydSFFk/shrT54RhWgP8oeoKI/tblzmbXeKrcG7FiFE/viwGxbuWwIFDXSEbu?blocks=biped4Irb3IzRtqjD&bip=full "link") directly to the database scheme extension.

![Database Schema](https://github.com/thalient-ai/Security-Engineering/blob/main/Images/database_schema.PNG?raw=true "Database Schema")

## CSV Files

| .csv File | Title | Publish Date | Source URL | Notes |
| :------------ | :------------ | :------------ | :------------ | :------------ |
| [NIST SP 800-53 Revision 5](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-53r5.csv "NIST SP 800-53 Revision 5") | Security and Privacy Controls for Information Systems and Organizations | September 2020 | [[Source]](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final  "[Source]") | Includes Chapter 3 and Table C-1 from Appendix C. |
| [NIST SP 800-53A Revision 5](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-53Ar5.csv "NIST SP 800-53A Revision 5") | Assessing Security and Privacy Controls in Information Systems and Organizations | January 2022 | [[Source]](https://csrc.nist.gov/pubs/sp/800/53/a/r5/final "[Source]") | Includes Chapter 4 Assessment Methods and Objects. Does not include Assessment Objectives.
| [NIST SP 800-53B Revision 5](http://https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-53Br5.csv "NIST SP 800-53B Revision 5") |  Control Baselines for Information Systems and Organizations | September 2020 (includes updates as of December 2020) | [[Source]](https://csrc.nist.gov/pubs/sp/800/53/b/upd1/final "[Source]") | Includes Table 3-1 from Chapter 3 |
| [NIST SP 800-171 Revision 2](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-171r2.csv "NIST SP 800-171 Revision 2") | Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations | February 2020 (includes updates as of January 28, 2021) | [[Source]](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final "[Source]") | Includes Chapter 3 |
| [NIST SP 800-172](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-172.csv "NIST SP 800-172") | Enhanced Security Requirements for Protecting Controlled Unclassified Information: A Supplement to NIST Special Publication 800-171 | February 2021 | [[Source]](https://csrc.nist.gov/pubs/sp/800/172/final "[Source]")| Includes Chapter 3 |
| [CNSSI 1253](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/CNSSI%201253.csv "CNSSI 1253") | Security Categorization and Control Selection for National Security Systems | August 2022 | [[Source]](https://www.cnss.gov/CNSS/issuances/Instructions.cfm "[Source]")| Includes Tables D-1 through D-20 |
| [CSEIG](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/CSEIG%20CSA.csv "CSEIG") | Cyber Survivability Endorsement (CSE) Implementation Guide (CSEIG), Version 3.0 | July 2022 | [[Source]](https://events.afcea.org/afceacyber23/Custom/Handout/Speaker0_Session10259_1.pdf "[Source]")| Includes Table 5.1 and Section 13 |
| [DISA CCI](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/DISA%20CCI.csv "DISA CCI") | Defense Information Systems Agency (DISA) Control Correlation Identifiers (CCIs) | January 2024 | [[Source]](https://public.cyber.mil/stigs/cci/ "[Source]") | Limited to CCIs applicable to NIST SP 800-53 Revision 5 |
| [NIST SP 800-160 Volume 2 Revision 1 - Techniques](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-160v2%20-%20Techniques.csv "NIST SP 800-160 Volume 2 - Resiliency Techniques")| Developing Cyber-Resilient Systems: A Systems Security Engineering Approach | December 2021 | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]")| Includes Table D-4. Contains "Uncertainty" error from Appendix E. |
| [NIST SP 800-160 Volume 2 Revision 1 - Approaches](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/NIST%20800-160v2%20-%20Approaches.csv "NIST SP 800-160 Volume 2 Revision 1 - Approaches") | Developing Cyber-Resilient Systems: A Systems Security Engineering Approach | December 2021 | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]")| Includes Table D-4. Contains "Trust-Based Usage Restriction", "Standard practice", and "Contextual Uncertainy" errors from Appendices E and F
| [ATT&CK Tactics](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/ATT%26CK%20-%20Tactics.csv "ATT&CK Tactics") | MITRE ATT&CK Version 14.1 | As of April 2024 |  [[Source]](https://attack.mitre.org/resources/attack-data-and-tools/ "[Source]")| Includes combined set of Enterprise, Mobile, and Industrial Control Systems |
| [ATT&CK Techniques](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/ATT%26CK%20-%20Techniques.csv "ATT&CK Technqiues") | MITRE ATT&CK Version 14.1 | As of April 2024 | [[Source]](https://attack.mitre.org/resources/attack-data-and-tools/ "[Source]") | Includes combined set of Enterprise, Mobile, and Industrial Control Systems |
| [ATT&CK Mitigations](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/ATT%26CK%20-%20Mitigations.csv "ATT&CK Mitigations") | MITRE ATT&CK Version 14.1 | As of April 2024 |  [[Source]](https://attack.mitre.org/resources/attack-data-and-tools/ "[Source]") | Includes combined set of Enterprise, Mobile, and Industrial Control Systems. Also contains Candidate Mitigations from NIST SP 800-160 Volume 2. | 
| [CAPEC](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/CAPEC.csv "CAPEC") | MITRE Common Attack Pattern Enumeration and Classification (CAPEC), Version 3.9 | As of April 2024 | [[Source]](https://capec.mitre.org/data/downloads.html "[Source]") |
| [CWE](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/CWE.csv "CWE") | MITRE Common Weakness Enumeration (CWE), Version 4.14 | As of April 2024 | [[Source]](https://cwe.mitre.org/data/downloads.html "[Source]") | Contains the combined set of Software Development, Hardware Development, and Research Concept CWEs
| [ISO 27001 / 27002](https://github.com/thalient-ai/Security-Engineering/blob/main/Data/ISO%2027001_27002.csv "ISO 27001 / 27002") | Information security, cybersecurity and privacy protection: Information security management systems: Requirements | October 2022 | [[Source]](https://www.iso.org/standard/27001 "[Source]")

## Junction Tables

| .csv File  | URL | Notes |
| :------------ | :------------ | :------------ |
| [NIST SP 800-53 Revision 5 & DISA CCI](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_CCI.csv "NIST SP 800-53 Revision 5 & DISA CCI")| [[Source]](https://public.cyber.mil/stigs/cci/ "[Source]") | Mapping derived from DISA CCIs|
|[NIST SP 800-53 Revision 5 & CSEIG](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_CSEIG.csv "NIST SP 800-53 Revision 5 & CSEIG") | [[Source]](https://www.mitre.org/sites/default/files/2024-01/PR-22-0359-Mapping-Cyber-Resiliency-to-the-CSEIG-CSA-Revision-1.pdf "[Source]") | Mapping derived from MITRE Technical Report MTR210700R1 - Cyber Resiliency Framework and Cyber Survivability Attributes: Mapping Cyber Resiliency to the CSEIG CSAs (Revision 1)|
| [NIST SP 800-53 Revision 5 & ISO 27001:2022](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_ISO%2027001.csv "NIST SP 800-53 Revision 5 & ISO 27001")| [[Source]](https://csrc.nist.gov/projects/olir/informative-reference-catalog/details?referenceId=99#/ "[Source]")| Mapping derived from NIST National Online Informative References (OLIR) Program|
|[NIST SP 800-53 Revision 5 & MITRE ATT&CK Techniques](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_ATT%26CK%20Technique.csv "NIST SP 800-53 Revision 5 & ATT&CK Techniques")| [[Source]](https://center-for-threat-informed-defense.github.io/mappings-explorer/external/nist/ "[Source]") | Mapping derived from MITRE Center for Threat Informed Defense|
|[NIST SP 800-53 Revision 5 & NIST SP 800-171 Revision 2](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_800-171r2.csv "NIST SP 800-53 Revision 5 & NIST SP 800-171 Revision 2") | [[Source]](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final "[Source]") | Mapping derived from NIST SP 800-171 Revision 2 Tables D-1 through D-14. Does not include the mapping to ISO 27001:2013.
|[NIST SP 800-53 Revision 5 & NIST SP 800-172](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-172.csv "NIST SP 800-53 Revision 5 & NIST SP 800-172") | [[Source]](https://csrc.nist.gov/pubs/sp/800/172/final "[Source]") | Mapping derived from NIST SP 800-172 Tables C-1 through C-14
|[NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Techniques](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_800-160v2%20Techniques.csv "NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Techniques") | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]") | Mapping derived from NIST SP 800-160 Volume 2 Revision 1|
|[NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Mitigations](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_800-160v2%20Mitigations.csv "NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Mitigations") | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]") | Mapping derived from NIST SP 800-160 Volume 2 Revision 1|
|[NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Approaches](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-53r5_800-160v2%20Approaches.csv "NIST SP 800-53 Revision 5 & NIST SP 800-160 Volume 2 Approaches") | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]") | Mapping derived from NIST SP 800-160 Volume 2 Revision 1|
|[NIST SP 800-160 Volume 2 Techniques & Approaches](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-160v2%20Techniques_Approaches.csv "NIST SP 800-160 Volume 2 Techniques & Approaches") | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]") | Mapping derived from NIST SP 800-160 Volume 2 Revision 1|
|[NIST SP 800-160 Volume 2 & MITRE ATT&CK](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-160v2_ATT%26CK.csv "NIST SP 800-160 Volume 2 & MITRE ATT&CK") | [[Source]](https://csrc.nist.gov/pubs/sp/800/160/v2/r1/final "[Source]") | Mapping derived from NIST SP 800-160 Volume 2 Revision 1|
|[NIST SP 800-160 Volume 2 & CSEIG Cyber Survivability Attributes](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20800-160v2_CSEIG.csv "NIST SP 800-160 Volume 2 & CSEIG Cyber Survivability Attributes") | [[Source]](https://www.mitre.org/sites/default/files/2024-01/PR-22-0359-Mapping-Cyber-Resiliency-to-the-CSEIG-CSA-Revision-1.pdf "[Source]") | Mapping derived from MITRE Technical Report MTR210700R1 - Cyber Resiliency Framework and Cyber Survivability Attributes: Mapping Cyber Resiliency to the CSEIG CSAs (Revision 1)|
|[MITRE ATT&CK Techniques & Mitigations](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20ATT%26CK%20Techniques_Mitigations.csv "MITRE ATT&CK Techniques & Mitigations") | [[Source]](https://attack.mitre.org/resources/attack-data-and-tools/ "[Source]") | Mapping derived from MITRE ATT&CK v14.1. Combines Enterprise, Mobile, and Industrial Control System data sets|
|[MITRE ATT&CK Techniques & Tactics](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20ATT%26CK%20Techniques_Tactics.csv "MITRE ATT&CK Techniques & Tactics")  | [[Source]](https://attack.mitre.org/resources/attack-data-and-tools/ "[Source]") | Mapping derived from MITRE ATT&CK v14.1. Combines Enterprise, Mobile, and Industrial Control System data sets|
|[MITRE ATT&CK & MITRE CAPEC](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20ATT%26CK_CAPEC.csv "MITRE ATT&CK & MITRE CAPEC") | [[Source]](https://cwe.mitre.org/data/index.html "[Source]") | Derived from Common Attack Pattern Enumeration and Classification (CAPEC) Version 3.9
|[MITRE CAPEC & MITRE CWE](https://github.com/thalient-ai/Security-Engineering/blob/main/Junction%20Tables/Junction%20-%20CAPEC_CWE.csv "MITRE CAPEC & MITRE CWE") | [[Source]](https://cwe.mitre.org/data/index.html "[Source]") | Mapping derived from MITRE Common Weakness Enumeration (CWE) Version 4.14

## Questions and Feedback

Please submit issues for any technical questions/concerns, leave comments in Airtable, or contact brandyn@thalient.ai directly for general inquiries.
