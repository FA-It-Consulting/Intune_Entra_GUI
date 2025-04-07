# Intune & Entra Report Generator

This tool allows you to quickly retrieve information from Microsoft Intune and Microsoft Entra ID (Azure AD) based on a list of device names.

## ✅ Features

- 🖥️ GUI-based interface
- 📂 CSV file selector
- 🔍 Queries Microsoft Intune and Microsoft Entra
- 📊 Exports report to Desktop
- 🧩 Displays your logo (optional)

## 🧰 Requirements

- Windows PowerShell
- Microsoft.Graph PowerShell module (automatically installed if not present)
- Microsoft Graph permissions:
  - `Device.Read.All`
  - `User.Read.All`
  - `Directory.Read.All`

## 📁 CSV Format

Your input CSV file should look like this:

```csv
DeviceName
PABLP028
PABLP048
CGNLP100
...
