SEDAC LLC — Analysis Tool Suite
Science | Engineering | Design | Art | Craft
CAGE: 18S33 | UEI: FFYTDK9ZBK48 | WOSB | SBIR Eligible | Huntsville, Alabama
sedacsystems.com | caitlin@sedacsystems.com

About
Browser-based human factors and system safety analysis tools built on MIL-STD-1472H, MIL-STD-882E, and DoDI 5000.95 HSI compliance requirements.
No installation required. All tools run entirely client-side in any modern browser.

Built by Caitlin Ryan (CTO) and Chris Bartlett (CEO), co-founders of SEDAC LLC — a two-person Woman-Owned Small Business with combined 15+ years in Army Aviation and UAS human systems engineering. The underlying SysML models of MIL-STD-1472H and MIL-STD-882E are published separately at [INCOSE SELab / SEDAC LLC].

Tool Index
MIL-STD-882E System Safety Suite: Tool | Task | Status 
System Requirements Hazard Analysis (SRHA) Task 203: Operational
Preliminary Hazard Analysis (PHA) Task 202: In development
Hazard Tracking System (HTS) Task 106: In development
System Safety Management Dashboard Task 101: Planned
Subsystem Hazard Analysis (SSHA) Task 204: Planned

MIL-STD-1472H / HSI Suite: Tool | Standard | Status 
NASA TLX Workload Analyzer NASA TLX: Operational
Anthropometric Fit Analysis MIL-STD-1472H: Operational
1472H Section Compliance Checklist MIL-STD-1472H: Planned
HETR Workload Summary Generator MIL-STD-46855A: Planned
HSI Domain Coverage Matrix DoDI 5000.95: Planned

Shared Data Schema
All tools in both suites accept a common CSV input schema. Load your program's data once; run the full ESOH/HSI compliance stack.
Core files (all analysis tools):
hazards.csv — hazard registry with severity, probability, and RAC fields
requirements.csv — safety requirements with hazard trace linkage
project.csv — program metadata

CSV templates are available in the /data-schema/ folder with field definitions and example data.

Data Handling and Privacy
This tool suite processes no data server-side.
All analysis runs entirely in your browser. No data you enter — including program names, hazard descriptions, operator measurements, workload scores, or any other information — is transmitted to SEDAC LLC or any third party. No cookies, no tracking, no analytics.

User responsibilities:
You are responsible for ensuring that data entered into these tools is handled in accordance with your program's data classification and handling requirements.
Tools are designed for use with unclassified data only. Do not enter classified, CUI, or export-controlled information into any browser-based tool hosted on an uncontrolled network.
If this tool is used to collect data from human subjects (e.g., NASA TLX workload assessments from operators), users are responsible for obtaining appropriate IRB approval or institutional review in accordance with their organization's human subjects research policies.

SEDAC LLC is not responsible for data handling practices of downstream users or licensees.

Attribution
When citing or referencing these tools in reports, papers, or deliverables, use:

SEDAC LLC Analysis Tool Suite (CAGE: 18S33). Workload Assessment (NASA TLX Methodology). Available at github.com/SEDAC-LLC. Licensed CC BY-NC 4.0.

For NASA TLX implementation specifically:

Workload assessment conducted using SEDAC LLC's implementation of the NASA Task Load Index (TLX) methodology (Hart & Staveland, 1988). This tool is not affiliated with or endorsed by NASA.

License
This tool suite is released under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).
✅ Free for non-commercial, academic, and U.S. Government use
✅ Modifications and derivative works permitted with attribution
❌ Commercial use (paid contracts, proprietary enterprise tools, revenue-generating applications) requires a separate license from SEDAC LLC

Commercial licensing inquiries: caitlin@sedacsystems.com
See LICENSE for full terms.

Contact
Caitlin Ryan — Co-Founder, CTO
caitlin@sedacsystems.com
Chris Bartlett — Co-Founder, CEO
SEDAC.LLC@outlook.com
sedacsystems.com | Huntsville, Alabama
