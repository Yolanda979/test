# Application User Guide

Welcome to our application! Follow this guide to get started and learn about the features available.

# Table of Contents

- [Getting Started](#getting-started)
- [Feature Modules Introduction](#feature-modules-introduction)
    - [2.1 Loading Media Files](#loading-media-files)
    - [2.2 CSV](loading-csv-files)
    - [2.3 Management](#management)
- [Usage Instructions](#usage-instructions)
    - [3.1 Data Reading](#data-reading)
        - [3.1.1 Video/Audio File Reading](#videoaudio-file-reading)
        - [3.1.2 CSV File Reading](#csv-file-reading)
    - [3.2 Label Settings](#label-settings)
    - [3.3 Marking](#marking)
    - [3.4 Saving](#saving)
    - [3.5 Exporting](#exporting)
- [Contact Us](#contact-us)

## Getting Started

First, please install and download the application, then proceed to the main interface.

## Feature Modules Introduction

### Loading Media Files

- **"Double Click to Add Media File"**: Add video or audio files as source material.

### Loading CSV Files

- **"Double Click to Add CSV File"**: Annotate the video or audio file by adding a CSV file.

### Management

- You can add labels and change their colors through the "segmentation manager".

## Usage Instructions

### Data Reading

#### Video/Audio File Reading

- Double-click **"Double Click to Add Media File"** to add video or audio files.

#### CSV File Reading

- Double-click **"Double Click to Add CSV File"** to add a CSV file.
- A "Data Setup" interface will appear, set up the X-axis and Y-axis.
    - The X-axis usually involves time or index-related data, which is automatically placed on the X-axis by the system. You can move its position using the `<` or `>` buttons.
    - For Y-axis titles, double-clicking will automatically move them to the exclude area; similarly, data in the exclude area can be moved back into Y-axis by double-clicking.

### Label Settings

- Click on the settings button in "segmentation manager" to add, delete, name, or modify label colors.
- The up/down arrow buttons in the top right corner allow you to adjust the display order of labels.
- The bottom right corner is for importing/exporting label settings files (.lbit format).

### Marking 

- Use buttons at the bottom right of the main interface for fast forward, rewind, speed adjustment, and pause functions when adding markers.
- You can use shortcut keys for quick marking.
    - Enabling `Auto add next segment: ON` in Options allows automatically adding a next marker after completing one.
    - Select regions for marking; press `esc` to exit selection mode or right-click to return to a previous layer.

### Saving 

- Save with shortcut key `Ctrl+S` or by clicking `File->Save`, generating a .sigit file.
    - Reopen files with shortcut key `Ctrl+O` or by clicking `File->Open Sigit File`.

### Exporting 

- Click `File->Export` to export annotated files with options like "Target Folder” and “Allow multiple labels in one segment".
- For batch exporting multiple project files at once, click `File->Batch Export` and select a folder containing several project files; this exports them as label files.

## Contact Us

For further assistance, please contact us through:

- Email: support@example.com