# IMISS Logs

**IMISS Logs** is the Android mobile companion app for the **Integrated Management Information System Section (IMISS) Work Logs** system. It is designed as a focused, pocket-sized receiver for IMISS technical staff so they can monitor tickets assigned to them, update service progress in real time, and hand off tasks to colleagues when needed.

---

## Overview

Instead of navigating a full desktop dashboard on a phone, staff can sign in with their existing IMISS account and immediately see only the work logs assigned to them. Everything is organized around a clean, single-direction workflow—helping teams respond faster, keep ticket activity documented, and stay coordinated across shifts.

---

## Key Features

- **Staff Portal Access**
  Sign in using your existing IMISS staff account with automatic session persistence and graceful server reconnection on startup.
- **Assigned-Only Queue**
  View only the work logs assigned to you, organized across **Open**, **In Progress**, and **Resolved** tabs with live ticket counts and smooth horizontal swiping.
- **One-Tap Status Progression**
  Move tickets forward from **Open → In Progress → Resolved** and optionally record remarks on the action taken, timestamped in Philippine Time (PHT).
- **Staff Referral Workflow**
  Refer an active work log to another staff member when passing work to the next duty shift or when unable to perform the task, with a required referral reason for clear team accountability.
- **Assignment Alerts & Auto-Refresh**
  Pull down to refresh anytime, or enable notifications to get alerted when new work logs arrive.
- **Adaptive Light & Dark Design**
  Clean Material 3 interface that automatically adapts to your device's light or dark theme on both phones and tablets.

---

## Typical Workflow

1. **Sign In** — Log in with the staff credentials provided by your system administrator.
2. **Track & Update** — Review incoming **Open** requests, tap **Start Progress** when beginning work, and **Mark Resolved** once completed.
3. **Refer When Needed** — Tap **Refer** on an active ticket, choose a colleague, select a category (**Next Duty**, **Unable to Perform**, or **Other**), and enter your reason for the handoff.

---

## Requirements

- **Platform:** Android 7.0 (API 24) or higher
- **Account:** Active IMISS staff account (first-time users should update any temporary password on the main IMISS web portal before signing in)

---

## Building the App

```bash
# Build the debug APK
gradle assembleDebug

# Run unit tests
gradle :app:testDebugUnitTest
```
