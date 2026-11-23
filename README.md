# IMISS Logs

[![Latest Release](https://img.shields.io/github/v/release/nekofied143/IMISSReceiver?logo=github&label=Latest%20Release)](https://github.com/nekofied143/IMISSReceiver/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/nekofied143/IMISSReceiver/total?label=Downloads&logo=github&color=blue)](https://github.com/nekofied143/IMISSReceiver/releases)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Material 3](https://img.shields.io/badge/UI-Material%203-6750A4)
![Time Zone](https://img.shields.io/badge/Time%20Zone-PHT-2563EB)

**IMISS Logs** is an Android companion app for the **Integrated Management Information System Section (IMISS) Work Logs** system. It helps IMISS technical staff monitor assigned work logs, update ticket progress, and refer active tasks to colleagues directly from their mobile devices.

Designed for day-to-day technical support operations, the app keeps work-log management focused and consistent across duty shifts.

**[Download the latest release](https://github.com/nekofied143/IMISSReceiver/releases/latest)** · [View all releases](https://github.com/nekofied143/IMISSReceiver/releases)

## Overview

IMISS Logs provides a mobile-friendly way to handle essential work-log activities without navigating the full desktop system. Staff sign in with their existing IMISS accounts to view assigned tickets, document progress, and coordinate handoffs when needed.

The app supports three main goals:

- **Visibility:** Keep assigned work logs organized and easy to review.
- **Accountability:** Record ticket progress and referral reasons.
- **Continuity:** Help staff transfer active work between colleagues or duty shifts.

## Key Features

| Feature | Description |
| --- | --- |
| **Staff account sign-in** | Access the app using an existing IMISS staff account, with session persistence and reconnection handling at startup. |
| **Assigned work-log queue** | See only assigned tickets, organized into **Open**, **In Progress**, and **Resolved** tabs. |
| **Status counts and navigation** | Review ticket counts and swipe horizontally between status tabs. |
| **Ticket progress tracking** | Move work logs through **Open → In Progress → Resolved** and optionally add remarks to document actions taken. |
| **Staff referrals** | Refer an active ticket to a colleague, selecting a referral category and entering a required reason. |
| **Assignment notifications** | Receive alerts about newly assigned work logs when notifications are enabled. |
| **Manual refresh** | Pull down to refresh the work-log queue on demand. |
| **In-app updates** | Update an existing installation directly through the app without uninstalling it. |
| **Adaptive appearance** | Use a Material 3 interface that follows the device's light or dark theme on supported phones and tablets. |
| **Philippine Time** | View timestamped ticket remarks in **Philippine Time (PHT)** for consistent activity records. |

## Getting Started

### Requirements

| Requirement | Details |
| --- | --- |
| **Device** | Android phone or tablet |
| **Android version** | Android 7.0 (API level 24) or later |
| **User account** | Active IMISS staff account |
| **Initial password setup** | Temporary passwords must be changed through the main IMISS web portal before app sign-in. |

### Installation

IMISS Logs is distributed through the **Releases** section of this GitHub repository. Download the latest available Android APK from the official release assets.

1. Open the repository's [Releases page](https://github.com/nekofied143/IMISSReceiver/releases) (or select **Releases** in the repository sidebar).
2. Choose the release marked **Latest** (or use the [latest-release shortcut](https://github.com/nekofied143/IMISSReceiver/releases/latest)).
3. Expand **Assets**, if necessary, and download the `.apk` installation file.
4. Open the downloaded APK on your Android device and follow the on-screen installation prompts.
5. If Android blocks installation from that source, enable **Allow from this source** for the app you used to open the APK, only after verifying that the release is from the official repository.
6. Launch **IMISS Logs** and sign in with your existing IMISS staff credentials.

> **Security note:** Download APKs only from this repository's official Releases page. Avoid third-party mirrors and disable permission to install unknown apps afterward if it is no longer needed.

> **Account note:** If you have a temporary password, change it on the main IMISS web portal before signing in to the Android app.

### Updating the App

**Existing users can update IMISS Logs directly inside the app.** You do not need to uninstall the current version or manually download an APK for routine updates.

1. Use the app's built-in update feature when an update is available.
2. Follow the instructions shown by the app and Android to complete the update.
3. Reopen IMISS Logs if prompted.

You can also review the latest version and its release notes on the [GitHub Releases page](https://github.com/nekofied143/IMISSReceiver/releases/latest). For a fresh installation, use the APK provided under that release's **Assets**.

> **Update safety:** Do not uninstall the app merely to update it. If an in-app update fails, contact your IMISS system administrator. Use only updates provided by the app or the official GitHub repository.

## Using the App

### 1. Sign in

Launch the app and enter your IMISS staff account credentials. If your account still uses a temporary password, update it through the main IMISS web portal before signing in.

### 2. Review assigned tickets

Use the three status tabs to organize your work:

| Status | Meaning |
| --- | --- |
| **Open** | Assigned work that has not yet been started. |
| **In Progress** | Work currently being handled. |
| **Resolved** | Work marked as completed. |

Swipe between tabs or select a tab directly. Pull down to refresh when you need the latest available work-log information.

### 3. Update ticket progress

1. Open an assigned ticket under **Open**.
2. Tap **Start Progress** when you begin working on it.
3. Add a remark if you need to document the action taken.
4. When the work is complete, tap **Mark Resolved**.
5. Add a final remark if needed.

**Status flow:** `Open → In Progress → Resolved`

### 4. Refer an active ticket

When another staff member needs to take over an active work log:

1. Select the active ticket and tap **Refer**.
2. Choose the colleague who will receive the referral.
3. Select the appropriate category:
   - **Next Duty** — for a handoff to the next duty shift.
   - **Unable to Perform** — when you cannot carry out the task.
   - **Other** — for another referral reason.
4. Enter the **required referral reason**.
5. Complete the referral using the app's confirmation flow.

A clear referral reason helps the receiving staff member understand why the task was handed over.

### 5. Stay informed

Enable app notifications if you want alerts for new assignments. You can also pull down to refresh the ticket list manually.

## Notifications

To receive assignment alerts, make sure notifications are allowed for IMISS Logs:

1. Open **Settings → Apps → IMISS Logs → Notifications** on your Android device (menu names vary by manufacturer).
2. Enable notifications for the app, if the option is available.
3. Check that the device has connectivity to the IMISS service.
4. If alerts do not appear, open the app and pull down to refresh the assigned work-log list.

On Android versions that request notification permission, allow it when prompted. If alerts are delayed or missing, also check **Battery** settings for IMISS Logs and whether Android is restricting its background activity. Exact options vary by device; avoid disabling system-wide battery protections unnecessarily. Connectivity, Do Not Disturb, and manufacturer-specific power-saving settings may also affect alerts. Manual refresh remains available.

## Quick Reference

| I want to… | Action |
| --- | --- |
| Check new assigned work | Open the **Open** tab |
| Begin working on a ticket | Tap **Start Progress** |
| Record what I did | Add a ticket remark during a status update |
| Complete a ticket | Tap **Mark Resolved** |
| Hand off active work | Tap **Refer**, select a colleague and category, and enter a reason |
| Refresh assigned work logs | Pull down to refresh |
| Update the installed app | Use the built-in app update feature |

## Troubleshooting

| Issue | What to check |
| --- | --- |
| **Cannot sign in** | Confirm your IMISS credentials and whether a temporary password must first be changed on the main web portal. |
| **No assigned tickets appear** | Check the selected status tab, then pull down to refresh. The app displays tickets assigned to your account. |
| **New assignments are not appearing** | Refresh the queue and check that your device has connectivity to the IMISS service. |
| **No assignment alerts** | Check notification permission, Do Not Disturb, connectivity, and whether battery settings restrict background activity. Open the app and refresh to check for assignments. |
| **In-app update fails** | Check connectivity, retry using the app’s update feature, and contact your IMISS administrator if the problem continues. Do not uninstall the app as a first step. |
| **App cannot reconnect** | Check connectivity to the IMISS environment and contact your IMISS administrator if the issue continues. |

## Frequently Asked Questions

**Do I need a separate account for the Android app?**  
No. Sign in using your existing authorized IMISS staff account.

**Why can’t I sign in with my temporary password?**  
Change the temporary password through the main IMISS web portal first, then sign in to the app.

**Why can’t I see a work log?**  
The app shows work logs assigned to your account. Check **Open**, **In Progress**, and **Resolved**, then refresh. Contact your administrator if an expected assignment is still missing.

**How do I update an installed app?**  
Use the built-in update feature in IMISS Logs and follow the on-screen instructions. You do not need to uninstall the existing app.

**Where can I get the latest APK for a new installation?**  
Use the official [GitHub Releases page](https://github.com/nekofied143/IMISSReceiver/releases). Avoid third-party downloads.

**Where can I see what changed in a release?**  
Read the notes on the [Releases page](https://github.com/nekofied143/IMISSReceiver/releases).

**Does the Downloads badge show the number of users?**  
No. It counts GitHub release-asset downloads, not unique people, devices, or installations.

## Privacy and Responsible Use

Work-log concerns and remarks may contain operational or sensitive information. Follow your organization's privacy and information-handling policies when using IMISS Logs.

- Record only information needed to document and resolve a work log.
- Avoid including passwords, access tokens, or unnecessary patient or personal information in remarks or referrals.
- Do not share screenshots, ticket details, or account credentials with unauthorized people.
- Report suspected account misuse or accidental disclosure through your organization's approved channels.

This section describes **staff usage practices**, not a claim about the app's encryption, storage, or data-retention implementation.

## Support and Issue Reporting

For login problems, missing assignments, update failures, or service concerns, contact your designated **IMISS system administrator**. When reporting a problem, include the app version (if known), Android version, a short description, and the steps that led to the issue.

Do **not** include passwords, authentication tokens, patient details, or other sensitive work-log information in public GitHub issues. Share sensitive diagnostics only through approved internal channels.

## Usage and Access

IMISS Logs is intended for **authorized IMISS technical staff**. It is a companion to the existing IMISS Work Logs system; staff authentication and work-log access are handled through the IMISS environment.

For account access or permission changes, contact your designated **IMISS system administrator**.

---

*IMISS Logs — Manage assigned work, document progress, and coordinate handoffs from Android.*
