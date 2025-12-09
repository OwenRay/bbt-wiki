---
title: Bathymetric Mapping Guide
nav_order: 1
parent: Maps
---

# Bathymetric Mapping Guide

## Table of Contents

- [Introduction](#introduction)
- [What is Bathymetric Mapping?](#what-is-bathymetric-mapping)
- [Requirements](#requirements)
- [Creating Your First Depth Map](#creating-your-first-depth-map)
- [Understanding the 3D View](#understanding-the-3d-view)
- [Known Issues and Limitations](#known-issues-and-limitations)
- [Mapping Settings Explained](#mapping-settings-explained)
- [Managing Your Maps](#managing-your-maps)
- [Tips for Better Mapping](#tips-for-better-mapping)
- [Troubleshooting](#troubleshooting)

## Introduction

Welcome to the Mapping feature of your Baitboats app! This guide will help you understand how to create detailed bathymetric maps of your fishing waters. Bathymetric maps show the underwater terrain, including depths and contours, which can help you find the best fishing spots.

## What is Bathymetric Mapping?

Bathymetric mapping is the process of measuring and charting the depths of water bodies. In simple terms, it's like creating a topographic map of the underwater landscape. These maps can reveal:

- Deep holes where fish might be hiding
- Underwater ridges and drop-offs
- Shallow areas to avoid
- Changes in depth that attract different species of fish

## Requirements

- 3D maps require Android 13 or newer
- A bait boat with a compatible sonar:
    - Wi-Fish
    - Vexilar
    - Pulse
    - Horizon

## Creating Your First Depth Map

### Step 1: Prepare Your Equipment

1. Make sure your baitboat is properly connected to the app
2. Ensure your sonar device is working correctly:
    - **Wi-Fish**: Keep the Wi-Fish app open while mapping
    - **Vexilar**: Close the Vexilar app while mapping
    - **Pulse**: Keep open while mapping and make sure NMEA forwarding is turned on and set to port 3500
    - **Horizon**: For now: close while mapping, they're working on a software release to get this fixed.

### Step 2: Enable Mapping

1. First put the boat in the water
2. Go to the Settings tab (gear icon)
3. Find "Depth Mapping" section
4. Toggle "Enable mapping" to toggled on
5. Make sure "Show depth map" is also toggled on

### Step 3: Gather Depth Points

To create a detailed map, you need to collect depth readings from various points in the water:

1. Use your autopilot or radio handset to move the boat around the lake
2. The app automatically collects depth points as your boat moves
3. Try to cover the entire area you want to map by moving in a grid pattern
4. For best results, move slowly and maintain a consistent speed

> **Tip**: The app collects depth points when your boat moves at least 0.25 meters from the last recorded position. Moving in a grid pattern with overlapping paths will create the most detailed maps.

### Step 4: View Your Map

As you collect depth points, the app will automatically build a bathymetric map:

1. The map will appear as a color-coded overlay on your regular map
2. Different colors represent different depths
3. To view the map in 3D, tilt your view by placing two fingers on the screen and swiping up

## Understanding the 3D View

When you tilt the map, you'll see a three-dimensional representation of the underwater terrain:

- Waters appear as "cut-outs" in the 3D map, showing the actual depth profile
- Deeper areas appear lower in the 3D view
- The color scheme and relief helps to visualize different depth ranges in 2d

### The "Cut-Out" Effect

The "cut-out" effect means that water areas are displayed "under" the land in the 3D map, with the depth accurately represented. This gives you a realistic view of the underwater landscape.

However, this can sometimes cause visual issues:
- Sudden deep areas might appear as steep drops and be obscured by the bank side, make sure to rotate the map to get a different angle
- If lakes are missing from the map or have changed over time the wrongly plotted land might obscure the depth view
    - In this case make sure to try the alternative map (Region maps or Google maps)

## Known Issues and Limitations

### Tilted Mode Rendering Issue

Sometimes if you start mapping while in tilted mode (3D view), the map won't render properly. To fix this:

1. Swip down to switch back to top-down view (untilted)
2. Wait a moment for the map to refresh
3. Then tilt the view again

### Satellite View Limitation

Currently, satellite view and depth maps cannot be used together. If you want to view your depth map:

1. Make sure the satellite view is turned OFF in settings
2. Use the standard map view instead

## Mapping Settings Explained

### Basic Settings

- **Enable mapping**: Turns the mapping feature on or off
- **Show depth map**: Toggles the visibility of your created depth maps
- **Color scheme**: Choose different color patterns to represent depths

## Managing Your Maps

### Exporting Maps

To save your mapping data for backup or sharing:

1. Go to Settings
2. Scroll to the Depth Mapping section
3. Tap "Export Mapping Data"
4. Choose a location to save the file

For detailed, app-specific export instructions and file type info, see:
- [Import & Export → Export depth maps (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap)

### Importing Maps

To import saved mapping data:

1. Go to Settings
2. Scroll to the Depth Mapping section
3. Tap "Import Mapping Data"
4. Select the mapping data file you want to import

More details and tips are available here:
- [Import & Export → Import depth maps (.bbtmap)](/Import%20And%20Export.html#import-depth-maps-bbtmap)

### Deleting Maps

To remove the current depth map:

1. Go to Settings
2. Scroll to the Depth Mapping section
3. Tap "Delete Current Map"
4. Confirm the deletion when prompted

> **Warning**: Deleting a map is permanent and cannot be undone. Always export your maps before deleting them if you think you might need them later.

You can [export your maps here](/Import%20And%20Export.html#export-depth-maps-bbtmap).

## Tips for Better Mapping

- Map during calm weather conditions for more accurate depth readings
- Cover the same area multiple times to increase data density
- Move in a grid pattern for the most complete coverage
- Start with a small area to get familiar with the process
- Export your maps regularly to avoid data loss

Learn how to [export depth maps (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap).
- Use lower boat speeds for more accurate depth readings
- Focus on areas with interesting features like drop-offs or underwater structures

## Troubleshooting

- **Map not appearing**: Make sure "Show depth map" is enabled in settings
- **Inaccurate depths**: Check your sonar connection and ensure it's properly calibrated
- **App performance issues**: Try reducing the "Render Resolution" setting
- **Map looks distorted**: You may need more data points; try covering the area more thoroughly
- **Map is mostly one single color**: The depth range is automatically determined from the highest and lowest point under water. There may have been a wrong reading that pushed the lower range into the extremes. Make sure to only gather depth points when your boat is in the water to prevent false readings.
- **Larger maps**: Larger maps may take longer to build. So, especially on older devices, some patience is needed. No indicator is currently shown while building the map.

---

We hope this guide helps you make the most of the mapping feature in your Baitboats app. Happy fishing and mapping!
