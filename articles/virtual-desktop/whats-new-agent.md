---
title: What's new in the Azure Virtual Desktop Agent? - Azure
description: New features and product updates for the Azure Virtual Desktop Agent.
author: Heidilohr
ms.topic: overview
ms.date: 03/28/2022
ms.author: helohr
manager: femila
ms.custom: references_regions
---
# What's new in the Azure Virtual Desktop Agent?

The Azure Virtual Desktop Agent updates regularly. This article is where you'll find out about:

- The latest updates
- New features
- Improvements to existing features
- Bug fixes

Make sure to check back here often to keep up with new updates.

## Version 1.0.4230.1600

This update was released in March 2022 and includes the following changes:

- Fixes an issue with the agent health check result being empty for the first agent heart beat.
- Added Azure VM ID to the WVDAgentHealthStatus Log Analytics table.
- Updated the agent's update logic to install the Geneva Monitoring agent sooner.

## Version 1.0.4119.1500

This update was released in February 2022 and includes the following changes:

- Fixes an issue with arithmetic overflow casting exceptions.
- Updated the agent to now start the Azure Instance Metadata Service (IMDS) when the agent starts.
- Fixes an issue that caused Sandero name pipe service start ups to be slow when the VM has no registration information.
- General bug fixes and agent improvements.

## Version 1.0.4009.1500

This update was released in January 2022 and includes the following changes:

- Added logging to better capture agent update telemetry.
- Updated the agent's Azure Instance Metadata Service health check to be Azure Stack HCI-friendly.

## Version 1.0.3855.1400

This update was released December 2021 and has the following changes:

- Fixes an issue that caused an unhandled exception.
- This version now supports Azure Stack HCI by retrieving VM metadata from the Azure Arc service.
- This version now allows built-in stacks to be automatically updated if its version number is beneath a certain threshold.
- The UrlsAccessibleCheck health check now only gets the URL until the path delimiter to prevent 404 errors.

## Version 1.0.3719.1700

This update was released November 2021 and has the following changes:

- Updated agent error messages.
- Fixes an issue with the agent restarting every time the side-by-side stack was updated.
- General agent improvements.

## Version 1.0.3583.2600

This update was released October 2021 and it fixes an issue where upgrading from Windows 10 to Windows 11 disabled the side-by-side stack.

## Version 1.0.3373.2605

This update was released September 2021 and it fixes an issue with package deregistration getting stuck when using MSIX App Attach.

## Version 1.0.3373.2600

This update was released September 2021 and has the following changes:

- General agent improvements.
- Fixes issues with restarting the agent on Windows 7 VMs.
- Fixes an issue with fields in the WVDAgentHealthStatus table not showing up correctly.

## Version 1.0.3130.2900

This update was released July 2021 and has the following changes:

- General improvements and bug fixes.
- Fixes an issue with getting the host pool path for Intune registration.
- Added logging to better diagnose agent issues.
- Fixes an issue with orchestration timeouts.

## Version 1.0.3050.2500

This update was released July 2021 and has the following changes:

- Updated internal monitors for agent health.
- Updated retry logic for stack health.

## Version 1.0.2990.1500

This update was released April 2021 and has the following changes:

- Updated agent error messages.
- Added an exception that prevents you from installing non-Windows 7 agents on Windows 7 VMs.
- Has updated heartbeat service logic.

## Version 1.0.2944.1400

This update was released April 2021 and has the following changes:

- Placed links to the Azure Virtual Desktop Agent troubleshooting guide in the event viewer logs for agent errors.
- Added an additional exception for better error handling.
- Added the WVDAgentUrlTool.exe that allows customers to check which required URLs they can access.

## Version 1.0.2866.1500

This update was released March 2021 and it fixes an issue with the stack health check.

## Version 1.0.2800.2802

This update was released March 2021 and it has general improvements and bug fixes.

## Version 1.0.2800.2800

This update was released March 2021 and it fixes a reverse connection issue.

## Version 1.0.2800.2700

This update was released February 2021 and it fixes an access denied orchestration issue.
