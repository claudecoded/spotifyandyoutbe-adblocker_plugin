# 🚫 iOS AdBlock Guide & Filters

A practical, centralized guide to help iOS (iPhone & iPad) users block annoying ads in popular apps like **YouTube** and **Spotify** without needing a Jailbreak.

---

## 🚀 Quick Start Guide

iOS has strict limitations when it comes to browser-based adblock extensions working inside native apps. To completely bypass ads, choose one of the two standard methods below.

---

## 🛠️ Method 1: DNS-Level Blocking (Easiest)

This method blocks requests that apps send to known ad-serving servers. It works system-wide but might miss some YouTube video ads due to how Google streams content.

### Step-by-Step Setup:
1. Open **Safari** on your iPhone or iPad.
2. Go to the [AdGuard DNS Public Setup](https://adguard-dns.io).
3. Scroll down to **Method 2: Manual Configuration** and select **iOS**.
4. Tap **Download Profile** and allow the website to download a configuration file.
5. Open your iOS **Settings** app, tap **Profile Downloaded** at the top, and tap **Install** (enter your passcode if prompted).
6. Go to **Settings > General > VPN & Device Management > DNS** and ensure **AdGuard DNS** is selected.

---

## 📱 Method 2: Modified Apps via AltStore (Definitive Solution)

Since YouTube and Spotify constantly update their ad delivery, installing modified apps (Sideloading) is the only 100% effective way to get Premium features and zero ads.

### Prerequisites:
* A computer (**Windows** or **macOS**).
* Your iPhone/iPad and a USB cable.
* An Apple ID (we recommend creating a secondary/burner Apple ID for security).

### Step 1: Install AltServer on your Computer
* **macOS:** Download [AltStore](https://altstore.io), move it to your Applications folder, open it, and click the AltStore icon in the menu bar to install the Mail Plug-in.
* **Windows:** Download the Windows version from [AltStore](https://altstore.io). You must also install the desktop versions of **iTunes** and **iCloud** (do not use the Microsoft Store versions).

### Step 2: Install AltStore on your iOS Device
1. Connect your iPhone/iPad to your computer via USB.
2. Trust the computer on your iOS device if prompted.
3. Click the AltStore icon on your computer menu bar/system tray, select **Install AltStore**, and choose your connected device.
4. Enter your Apple ID and password (sent securely directly to Apple).
5. On your iOS device, go to **Settings > General > VPN & Device Management**, tap your Apple ID, and select **Trust**.
6. **Crucial for iOS 16+:** Go to **Settings > Privacy & Security**, scroll down to **Developer Mode**, turn it on, and restart your device.

### Step 3: Sideload the Modded Apps
1. Open **Safari** on your iOS device and download the latest `.ipa` file for the app you want:
   * **YouTube:** Search GitHub for **uYouEnhanced** or **uYouPlus**.
   * **Spotify:** Search GitHub for **EeveeSpotify**.
2. Keep your iOS device connected to the same Wi-Fi network as your computer (with AltServer running).
3. Open the **AltStore** app on your phone, go to the **My Apps** tab, and tap the **"+"** icon in the top-left corner.
4. Select the downloaded `.ipa` file.
5. Wait for the installation to finish. The app will now appear on your home screen completely ad-free!

> ⚠️ **Note:** Sideloaded apps using a free Apple ID must be "refreshed" once every 7 days. Simply open AltStore while on the same Wi-Fi as your computer and tap "Refresh All".

---

## 📋 Our Custom Blocklists

If you prefer using advanced network tools like Pi-hole, AdGuard Home, or NextDNS, you can manually import our community filters (Right-click and select "Copy Link Address"):

*   [YouTube Filters](filters/youtube-blocklist.txt) — *Focused on telemetry and tracking domains.*
*   [Spotify Filters](filters/spotify-blocklist.txt) — *Blocks known audio ad delivery streams.*

---

## 🤝 How to Contribute

Ad domains change constantly. If you encounter a new ad on YouTube or Spotify for iOS:
1. Open an **Issue** reporting the problem.
2. Check our [Contributing Guide](CONTRIBUTING.md) to submit a **Pull Request** updating the files inside the `/filters` directory.

---

## ⚖️ Disclaimer

This repository is for strictly educational purposes. We do not host, distribute, or link directly to copyrighted files. Using modded apps and adblockers is done at your own risk.
