# Intune Endpoint Management Mini-Lab

## Overview
A Microsoft Intune endpoint management lab using a Windows 11 Pro VM enrolled into Microsoft Entra ID to simulate real-world enterprise endpoint management workflows. Configured MDM enrollment, compliance policies, configuration profiles, remote app deployment, and device sync — with all workflows documented in osTicket and a knowledge base.

## What Was Configured

- **MDM Automatic Enrollment** — configured Intune automatic enrollment in Entra ID with a scoped security group to control which users can enroll Windows devices
- **Windows 11 Endpoint Enrollment** — enrolled WAKIM-ENDPT01 into Microsoft Intune via Entra ID, verified device appeared as managed and compliant in the Intune admin center
- **Windows Baseline Compliance Policy** — created and deployed a compliance policy requiring firewall, antivirus, antispyware, and Microsoft Defender Antimalware protection; verified compliance status on the enrolled endpoint
- **Configuration Profile** — created and deployed a Windows configuration profile to restrict access to Control Panel and PC settings; verified enforcement on the managed endpoint
- **Remote App Deployment** — deployed Adobe Acrobat Reader DC to the managed endpoint via Microsoft Store app assignment; confirmed silent installation through Intune notification and app availability on the device
- **Remote Device Sync** — triggered manual device sync from Intune admin center to validate remote device management communication
- **Helpdesk Ticket Documentation** — documented all endpoint management tasks as support tickets in osTicket from open to close following ITIL-aligned procedures
- **Knowledge Base Articles** — created internal knowledge base articles documenting the Windows 11 Intune enrollment process and Windows configuration profile deployment procedures

## Tools Used

- Microsoft Intune (admin center)
- Microsoft Entra ID
- Microsoft 365 Business Premium
- Windows 11 Pro
- VMware Workstation Pro
- osTicket

## Project Walkthrough

Full 45-slide walkthrough available in the file above.

## Related Projects

This lab is Part 4 of my homelab series:
- Part 1 — Active Directory Homelab: https://github.com/RoyWakim/AD-Helpdesk-Homelab
- Part 2 — Helpdesk Ticketing Lab: https://github.com/RoyWakim/Helpdesk-Ticketing-Lab
- Part 3 — Microsoft 365 / Entra ID Admin Lab: https://github.com/RoyWakim/M365-Entra-Admin-Lab

## Author

Roy Wakim
