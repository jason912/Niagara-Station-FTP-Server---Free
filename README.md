GlineFtpServer — Niagara Station Embedded FTP Server

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
