# Office 2024 Deployment Guide

## Office Customization Tool

**Link:** https://config.office.com/deploymentsettings

## Office Deployment Tool

**Link:** https://www.microsoft.com/en-us/download/details.aspx?id=49117

## Installation Steps

### 1. Run Office Deployment Tool as Administrator

1. Open the `officedeploymenttool_19628-20192.exe` file as an Administrator
2. Complete the requirements as specified

### 2. Configure Office Deployment

#### Open Command Prompt as Administrator

```cmd
move dir Office2024 file
cd c:/Office2024
setup /configure Configuration.xml
```

## Office / Windows Activation

### Open PowerShell as Administrator

Run the following command:

```powershell
irm https://get.activated.win | iex
```

## Notes

- Ensure all commands are executed with Administrator privileges
- Follow each step in the order specified
- The Configuration.xml file should be properly configured before running the setup command
