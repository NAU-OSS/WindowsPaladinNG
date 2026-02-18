# WindowsPaladinNG

## Description
**WindowsPaladinNG** is an open-source security project designed to enhance the security and protection of the Windows platform. While Windows Defender covers many threats, issues in recent versions of Windows 11 has shown gaps in real-world security, especially for users who "sail the high seas".

## Requirements
  - Windows 10 or 11
  - PowerShell 5.1 or newer
  - Admin Privileges

## Installation

### Prefered
  1. Download the zip file
  2. extract
  3. import main module ''Import-Module .\WindowsPaladinNG.ps1 ''

### Or clone the repo

  1. [gitclone](https://github.com/TheRock2000/WindowsPaladinNG.git)
  2. cd to WindowsPaladinNG folder
  3. import main module ''Import-Module .\WindowsPaladinNG.ps1 ''

## Usage Example:
  ### Scan Directory: 
    Invoke-PaladinScan -Path "C:\Users\Me\Downloads" 
  ### Full System Scan:
     Invoke-PaladinFullScan 
  ### Export Latest Scan Report
     Export-PaladinReport -OutputPath "C:\WindowsPaladinNG\Reports\scan-report.txt"

## Project Status
Just started

## Contact Information
Do not contact me directly. Use Issue tracker to request features or report bugs, thanks though.
