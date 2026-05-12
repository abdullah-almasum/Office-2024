# Office 2024 Deployment Repository

Welcome to the Office 2024 Deployment repository! This repository contains tools, configurations, and documentation for deploying Microsoft Office 2024 in your organization.

## 📋 Overview

This repository provides a complete guide for:
- Deploying Office 2024 across systems
- Configuring Office deployment settings
- Activating Office and Windows
- Managing Office deployment configurations

## 🚀 Quick Start

### Prerequisites
- Windows operating system
- Administrator access
- Office 2024 installation files
- Active internet connection (for activation)

### Installation

1. **Download Office Deployment Tool**
   - Visit: https://www.microsoft.com/en-us/download/details.aspx?id=49117

2. **Run as Administrator**
   - Right-click `officedeploymenttool_19628-20192.exe`
   - Select "Run as Administrator"

3. **Navigate to Installation Directory**
   ```cmd
   cd c:/Office2024
   ```

4. **Configure and Install**
   ```cmd
   setup /configure Configuration.xml
   ```

5. **Activate Office**
   - Open PowerShell as Administrator
   - Run: `irm https://get.activated.win | iex`

## 📁 Repository Structure

```
Office-2024/
├── README.md                    # This file
├── DEPLOYMENT_GUIDE.md         # Detailed deployment instructions
├── Configuration.xml           # Office deployment configuration file
└── officedeploymenttool_*.exe  # Office Deployment Tool executable
```

## 🔧 Configuration

### Customize Office Deployment

1. Visit: https://config.office.com/deploymentsettings
2. Configure your Office settings
3. Download the generated `Configuration.xml`
4. Place the file in your deployment directory

## 📖 Documentation

For detailed step-by-step instructions, see [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)

Key sections include:
- Office Customization Tool setup
- Command Prompt deployment commands
- Office and Windows activation procedures

## ⚙️ System Requirements

- **OS:** Windows 10 or later
- **RAM:** 4 GB minimum
- **Storage:** 3 GB free space
- **Administrator Privileges:** Required
- **Internet Connection:** Required for activation

## 🔐 Security Notes

⚠️ **Important:**
- Always run installers and PowerShell commands as Administrator
- Ensure your Configuration.xml is properly configured before deployment
- Use official Microsoft sources only
- Keep your activation credentials secure

## 🤝 Support

For issues or questions:
1. Review the [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)
2. Check Microsoft Office documentation
3. Contact your system administrator

## 📝 License

This repository is for Office 2024 deployment purposes. Ensure you have proper licensing for your Office installations.

## 📞 Useful Links

- **Office Customization Tool:** https://config.office.com/deploymentsettings
- **Office Deployment Tool:** https://www.microsoft.com/en-us/download/details.aspx?id=49117
- **Microsoft Office Documentation:** https://docs.microsoft.com/en-us/deployoffice/

---

**Last Updated:** May 12, 2026

**Repository Owner:** [Abdullah Al Masum](https://github.com/abdullah-almasum)
