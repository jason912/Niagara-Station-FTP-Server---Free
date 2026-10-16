# Niagara-Station-FTP-Server---Free 🆓

[![Niagara 4.14+](https://img.shields.io/badge/Niagara-4.14%2B-blue)](https://www.tridium.com)
[![Free to use](https://img.shields.io/badge/Free_to_use-brightgreen)](LICENSE)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> **🆓 A free, built-in FTP server for your Niagara Station — upload, download, and manage files with any standard FTP client.**

---

## What Is It?

GlineFtpServer adds a lightweight FTP server directly inside your Niagara Station. No external software, no extra configuration — just enable it and connect with FileZilla or any FTP client.

---

## Quick Start

```bash
# 1. Copy glineFtpServer-rt.jar to your modules/ directory

# 2. Restart station

# 3. Open Station Services view → Right-click → New → FtpService

# 4. Set your own FTP Username and FTP Password

# 5. Configure port (default: 2222)

# 6. Connect via FTP client pointing to the station IP, port 2222, PASV mode

# 7. The FTP server is restricted to the station's Files/ directory
```

You can list, upload, download, delete, rename files and create/remove directories within the `Files/` directory.

> If you set `Enabled = false`, the change requires a station restart to take effect.

---

## Features

| Feature | Support |
|---------|:-------:|
| Free to use | ✅ |
| Standard FTP protocol | ✅ |
| FileZilla compatible | ✅ Tested |
| Custom username/password | ✅ Configurable |
| Port selection | ✅ Configurable (default 2222) |
| PASV mode | ✅ Required |
| Station Files/ directory only | ✅ Security boundary |

---

## Pricing

**🆓 Free** — no license required, no trial, no limitations.

---

## Commercial Contact

Need a custom FTP service with extended features? We build custom modules.

- **Email**: [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com)
- **WhatsApp**: [+86 138 0199 0968](https://wa.me/8613801909968)

**Shanghai Gline Net Co., Ltd.** — Your Partner in Smarter Automation

Module: glineFtpServer-rt v1.0.1 | Vendor: Shanghai Gline Net Co. | Platform: Niagara N4.14 / N4.15

────────────────────────────────────────────────────────────────────────────────

### What It Does

Adds a built-in FTP server to your Niagara Station. Tested with FileZilla and other standard FTP clients.

### Installation

Copy glineFtpServer-rt.jar to Niagara Station services. The module is signed with the default gline.certificate. You can find the gline certificate in my other repositories.
<img width="143" height="144" alt="ftp" src="https://github.com/user-attachments/assets/9705c409-ee87-4966-a34c-8981b41d9351" />

### Configuration

1. Open Station Services view → Right-click → New → FtpService
2. Set your own FTP Username and FTP Password
3. Port (default: 2222) is configurable
4. Connect via FTP client pointing to the station IP, port 2222, using PASV mode

### File Access

The FTP server is restricted to the station's Files/ directory only. You can list, upload, download, delete, rename
files and create/remove directories within it.

### ⚠️ Important — Disable Behavior

If you set Enabled = false, the change requires a station restart to take effect. The FTP server will continue running
until restarted.

### Further Development

For custom development requests, email jason.zhang@gline-net.com

---

## Commercial Support

This module is free of charge under the MIT License (see [LICENSE](LICENSE)).

For production deployments requiring warranty, priority support, or custom
development, commercial support is available.

- Email: jason.zhang@gline-net.com
- WhatsApp: +86 138 0199 0968
- Web: [www.glineweb.com](https://www.glineweb.com)

Shanghai Gline Net Co., Ltd.
