# ⚡ Ping-Monitor - Track Network Uptime Easily

[![Download Ping-Monitor](https://img.shields.io/badge/Download-Ping--Monitor-brightgreen?style=for-the-badge&logo=github)](https://github.com/flasholuwawo-code/Ping-Monitor/releases)

---

## 🖥️ What is Ping-Monitor?

Ping-Monitor is a simple app that helps you check if your servers or websites are online. It sends regular ping tests to your chosen devices and tells you if they respond or not. If a server goes offline, the app can alert you by email.

The tool works quietly in the background, logging your server’s status over time. This helps you see when a site or service was down and how long it stayed offline. It stores configuration and results securely.

---

## 🔍 Key Features

- Monitor multiple devices or servers using their IP address or domain name.
- Receive email alerts if a server stops responding.
- Save and encrypt settings safely on your computer.
- View detailed logs of downtime and response times.
- Runs on Windows and works well without needing programming skills.
- Uses simple batch scripts and PowerShell for background work.
- Display status in an easy-to-understand format.
- Minimal setup required.

---

## ⚙️ System Requirements

- Windows 10 or later (64-bit recommended)
- At least 2 GB of RAM
- 200 MB of free disk space
- Internet connection for email alerts and ping tests
- An email account to send alerts (SMTP details needed)

---

## 🚀 Getting Started

Before you start, make sure your computer meets the system requirements above, and you know the IP addresses or domain names you want to monitor. Also, have your email server details handy if you want to use email alerts.

---

## 📥 Download and Install Ping-Monitor

Click the button below to visit the latest Ping-Monitor release page on GitHub. This page contains all available versions of the software.

[![Download Ping-Monitor](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge&logo=github)](https://github.com/flasholuwawo-code/Ping-Monitor/releases)

### How to download and run Ping-Monitor

1. Open the release page from the button above.
2. Find the latest version listed at the top. Look for an `.exe` file, usually named like `Ping-Monitor-vX.X.exe`.
3. Click the `.exe` file to download it to your computer. Choose a folder you can find easily, such as your Desktop or Downloads folder.
4. After download completes, double-click the `.exe` file to start the installation.
5. Follow the on-screen setup instructions. You can accept all default settings.
6. The app will launch automatically when installed. If not, open it from the Start menu or desktop shortcut.

---

## 🛠️ Setting Up Your First Monitor

1. Open Ping-Monitor.
2. Click **Add New Monitor**.
3. Enter the IP address or web address you want to check.
4. Set how often you want the app to ping the server (default is every 5 minutes).
5. Enter your email details if you want alerts:
   - SMTP server address (for example, smtp.gmail.com)
   - Your email address
   - Your password (the app stores this securely)
6. Click **Save** to start monitoring that server.

You can add as many servers as you want by repeating these steps.

---

## 📊 Viewing Results and Logs

The main screen shows each server’s current status: 

- **Online** means the last ping succeeded.
- **Offline** means the last ping failed.

Click on any server in the list to see detailed logs. You’ll find dates and times of any downtime, how long it lasted, and ping response times.

---

## ✉️ Email Alerts

When a server goes offline, Ping-Monitor automatically sends you an alert email. This helps you act quickly if your website or service is down.

To set up alerts:

- Fill in your SMTP settings in the setup section.
- Test your email setup inside the app before saving.
- You will receive alerts until the server is back online.

---

## 🔐 Secure Configuration

Ping-Monitor encrypts your saved settings and passwords. This keeps your information safe even if someone accesses the computer.

---

## 🛡️ Running Ping-Monitor as a Service (Optional)

If you want Ping-Monitor to run without opening the app every time:

- Use the built-in option to install it as a Windows service.
- This allows it to start automatically when Windows boots.
- Monitors will keep running in the background without needing you to log in.

You can enable this option from the settings menu.

---

## 📂 File Locations and Logs

- Configuration files are stored securely on your computer in encrypted form.
- Logs are saved in the app’s folder under **Logs**.
- You can open these logs with any text editor to review past activity.

---

## ❓ Troubleshooting Tips

### Ping requests not working

- Check if your firewall allows Ping-Monitor to send ping requests.
- Make sure the target server is reachable from your network.
  
### Not receiving email alerts

- Verify your SMTP server and email login details are correct.
- Check your internet connection.
- Look at the app’s logs for any email errors.

### App won’t start or crashes

- Try running the app as administrator.
- Reinstall from the latest version on the release page.

---

## 📚 Additional Resources

You can find help and report issues on this repository’s GitHub page under the Issues tab.

For instructions on configuring your email server, check your email provider’s support site.

---

## ⚙️ Advanced Options

- Use PowerShell scripts included to customize monitoring tasks.
- Export logs to HTML reports for easy sharing.
- Enable encrypted backups of your configuration files.

---

## 🔗 Useful Links

- [Ping-Monitor Releases](https://github.com/flasholuwawo-code/Ping-Monitor/releases)  
- [GitHub Repository](https://github.com/flasholuwawo-code/Ping-Monitor)  

---

## 🤝 Support

For questions or help setting up, you can open an issue on GitHub or send feedback via the contact form on the repository page.