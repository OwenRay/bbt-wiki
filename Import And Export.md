---
title: Saving and Restoring Waypoints and Depth Maps
nav_order: 6
---

# Saving and Restoring Waypoints and Depth Maps

## Table of Contents

- [Introduction](#introduction)
- [Waypoints](#waypoints)
    - [Export waypoints (.gpx)](#export-waypoints-gpx)
    - [Import waypoints (.gpx)](#import-waypoints-gpx)
- [Depth Maps](#depth-maps)
    - [Export depth maps (.bbtmap)](#export-depth-maps-bbtmap)
    - [Import depth maps (.bbtmap)](#import-depth-maps-bbtmap)
- [Best Practices](#best-practices)
- [Troubleshooting](#troubleshooting)
- [File Types Summary](#file-types-summary)

## Introduction
This guide explains how to back up (export) and restore (import) your fishing waypoints and your created depth maps in the Baitboats app.

- Waypoints export to a standard `.gpx` file.
- Depth maps export to a `.bbtmap` file (Baitboats mapping archive).

> Tip: We recommend sending the exported files to yourself via email or saving them to Google Drive. This keeps your data safe and makes it easy to restore on a new phone.

## Waypoints

### Export waypoints (.gpx)
1. Open the app and go to the Settings tab (gear icon).
2. Tap "Import / Export".
3. Tap "Export Waypoints".
4. Choose where to send/save the file:
    - Email it to yourself, or
    - Save it to Google Drive (or another cloud service), or
    - Share via your preferred app.

Result: A file similar to `spots.gpx` that contains all your current waypoints (name + location).

### Import waypoints (.gpx)
Option A — From inside the app:
1. Open Settings → "Import / Export".
2. Tap "Import Waypoints".
3. Pick a `.gpx` file from your device or cloud storage (e.g., Google Drive).

Option B — From another app (share/open-in):
1. Find the `.gpx` file in your email or cloud app.
2. Open the file and choose Baitboats if asked.
3. The app will import the waypoints automatically.

Notes:
- Duplicate waypoint names are allowed; you can rename them later in the app.
- Coordinates are imported exactly from the `.gpx` (WGS84 lat/lon).

## Depth Maps

### Export depth maps (.bbtmap)
1. Open Settings → "Import / Export".
2. Tap "Export Mapping".
3. Choose how to share/save the file:
    - Email to yourself, or
    - Save to Google Drive (recommended), or
    - Use any other storage/share option.

Result: A `.bbtmap` file containing your depth map clusters. Keep this file safe.

### Import depth maps (.bbtmap)
1. Open Settings → "Import / Export".
2. Tap "Import Mapping".
3. Select the `.bbtmap` file from your device or cloud storage.

After import: Your previously created depth maps will be available again in the app.

> Important: The `.bbtmap` file is specific to Baitboats. Don’t unzip it or open it with other apps. Use the in-app "Import Mapping" option to restore.
> {: .warning}

## Best Practices
- Back up regularly:
    - After a fishing trip, export both Waypoints and Mapping.
    - Send the files to yourself via email or save to Google Drive.
- Use clear names (e.g., `LakeTranquil-2025-06-15.gpx`, `LakeTranquil-2025-06-15.bbtmap`).
- Do a quick test once: export and then import on the same device so you’re familiar with the process.

## Troubleshooting
- I can’t find my file when importing:
    - Ensure the extension matches: `.gpx` for waypoints, `.bbtmap` for depth maps.
    - If using Google Drive, you can try downloading the file first or choose "Open with" → Baitboats.

- Nothing happens when opening from email/cloud:
    - Download the file locally, then use Settings → "Import Waypoints" or "Import Mapping".

- Import failed or the data looks incomplete:
    - Make sure the file is not corrupted and fully uploaded/downloaded.
    - For waypoints, verify it’s a valid GPX file. For mapping, ensure it’s the original `.bbtmap` created by the app.

- Moving to a new device:
    - On the old device, export Waypoints and Mapping and send them to yourself (email/Drive).
    - On the new device, install the app and import both files from your email/Drive.

## File Types Summary
- Waypoints: `.gpx` (open standard)
- Depth maps: `.bbtmap` (Baitboats mapping archive)

Keep both safe by emailing them to yourself or storing in Google Drive.
