# Windows_PowerShell_Activity_Investigation
SOC Analyst L1 Project demonstrating Windows PowerShell Script Block Logging, Event ID 4104 investigation, PowerShell activity monitoring, and security event analysis using Windows Event Viewer.

## Project Overview

This project demonstrates a practical SOC Analyst L1 investigation focused on Windows PowerShell activity monitoring using PowerShell Script Block Logging and Windows Event Viewer.

The investigation focuses on Event ID **4104**, which records PowerShell script block content.

## Objectives

- Enable PowerShell Script Block Logging.
- Generate controlled PowerShell activity.
- Investigate Event ID 4104.
- Analyze captured PowerShell script content.
- Understand the security significance of PowerShell execution monitoring.

## Tools & Technologies

- Windows 11
- Windows PowerShell
- Windows Event Viewer
- Windows Registry
- PowerShell Operational Logs

## Investigation Performed

1. Enabled PowerShell Script Block Logging through Windows Registry.
2. Executed harmless PowerShell commands.
3. Accessed PowerShell Operational Logs in Event Viewer.
4. Filtered events using Event ID 4104.
5. Investigated Script Block Text.
6. Verified logging using a unique test marker:
   `SOC_LAB_VERIFICATION_4104`

## Key Findings

- Successfully enabled PowerShell Script Block Logging.
- Identified and investigated Event ID 4104.
- Verified that PowerShell script block content was recorded.
- Captured two test-related Event ID 4104 records.
- Learned how to recognize potentially suspicious PowerShell execution techniques.

## Learning Outcomes

- Windows Event Log investigation
- PowerShell activity monitoring
- Script Block Logging configuration
- Event ID analysis
- Basic SOC investigation and documentation

## Conclusion

This hands-on project improved my understanding of Windows endpoint monitoring and PowerShell activity investigation from a SOC Analyst perspective.

**Project Status:** Completed

**Category:** Cybersecurity | SOC Analyst L1 | Windows Log Analysis

*This was a controlled lab exercise using harmless PowerShell commands. No real security incident was identified.*
