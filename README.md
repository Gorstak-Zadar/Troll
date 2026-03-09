# 🔧 Troll

> PowerShell script that **removes network bridges** — runs at logon via scheduled task. Includes Unbridge.cmd. Part of security/hardening.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🌐 **Remove Network Bridge** | Uses netsh bridge show adapter, removes bridges |
| ⏰ **Logon Task** | `RunTrollAtLogon` under SYSTEM |
| 📂 **Copy** | Installs to `C:\Windows\Setup\Scripts\Bin` |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\Troll.ps1
```

---

<p align="center">
  <sub>🛡️ Gorstak Network Hardening</sub>
</p>
