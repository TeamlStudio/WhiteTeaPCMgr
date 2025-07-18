# BaiCha PC Manager - README

## Overview
BaiCha PC Manager is a comprehensive Windows system optimization and security tool developed using Python and PyQt5. It provides a user-friendly interface for virus scanning, software monitoring, system optimization, and file quarantine management.

## Features

### 1. Virus Scanning
- Quick scan for common locations (Downloads, Desktop, Temp folders)
- Full disk scan
- Custom scan for user-selected directories
- Signature-based detection (filename, content, and hash matching)
- Quarantine functionality for infected files

### 2. Software Monitoring
- Real-time monitoring of newly installed software
- Detection of suspicious software based on keywords
- Software uninstallation capability
- Automatic blocking of suspicious installations (configurable)

### 3. System Optimization
- Temporary file cleaning
- Browser cache cleaning
- Startup program optimization
- Disk defragmentation
- Memory freeing
- One-click optimization combining all features

### 4. Quarantine Management
- View quarantined files
- Restore files to original locations
- Permanently delete quarantined files

### 5. Settings
- Toggle real-time protection
- Configure network protection
- Set auto-start with Windows
- Enable automatic virus definition updates

## Technical Details
- **Language**: Python 3
- **GUI Framework**: PyQt5
- **System Requirements**: Windows 7/8/10/11
- **Admin Privileges**: Required for full functionality

## Installation
1. Ensure Python 3.6+ is installed
2. Install required packages:
   ```
   pip install pyqt5 psutil pywin32
   ```
3. Run the application:
   ```
   python baicha.py
   ```

## Usage Notes
- The application will automatically request administrator privileges when launched
- For best protection, keep real-time protection enabled
- Regular scans are recommended (weekly or bi-weekly)
- Use the one-click optimization feature periodically to maintain system performance

## Disclaimer
This software is provided "as-is" without warranties. The developers are not responsible for any system issues that may arise from its use. Users should always maintain backups of important data.
