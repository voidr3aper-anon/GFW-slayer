<div align="center">

# 🚀 GFW-Slayer

<img src="https://github.com/voidr3aper-anon/GFW-slayer/blob/main/logo-new.png" width="350" alt="GFW-Slayer Logo" />

### *Serverless V2Ray Configurations for Unrestricted Internet Access*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/voidr3aper-anon/GFW-slayer?style=social)](https://github.com/voidr3aper-anon/GFW-slayer/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/voidr3aper-anon/GFW-slayer?style=social)](https://github.com/voidr3aper-anon/GFW-slayer/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/voidr3aper-anon/GFW-slayer)](https://github.com/voidr3aper-anon/GFW-slayer/commits/main)

---

</div>

## 📋 Table of Contents

- [🚀 GFW-Slayer](#-gfw-slayer)
    - [*Serverless V2Ray Configurations for Unrestricted Internet Access*](#serverless-v2ray-configurations-for-unrestricted-internet-access)
  - [📋 Table of Contents](#-table-of-contents)
  - [🌟 Overview](#-overview)
  - [✨ Features](#-features)
  - [📱 How to Use](#-how-to-use)
    - [1️⃣ Install a V2Ray Client](#1️⃣-install-a-v2ray-client)
    - [2️⃣ Add Subscription Links](#2️⃣-add-subscription-links)
    - [2️⃣ Add Subscription Links](#2️⃣-add-subscription-links-1)
    - [3️⃣ Select and Connect](#3️⃣-select-and-connect)
    - [3️⃣ Select and Connect](#3️⃣-select-and-connect-1)
    - [4️⃣ Tips for Best Performance](#4️⃣-tips-for-best-performance)
  - [📦 Config Details](#-config-details)
  - [📦 Config Details](#-config-details-1)
    - [🔐 Technical Details](#-technical-details)
  - [🔧 Professional / Advanced Usage](#-professional--advanced-usage)
    - [🔗 VPN Chaining and Proxy Mode](#-vpn-chaining-and-proxy-mode)
      - [📖 Step-by-Step Guide](#-step-by-step-guide)
      - [💡 Advanced Tips for Chaining](#-advanced-tips-for-chaining)
      - [❓ Why Chain V2Ray with Another VPN?](#-why-chain-v2ray-with-another-vpn)
      - [🔧 Troubleshooting Chained Connections](#-troubleshooting-chained-connections)
    - [⚙️ Customizing DNS and Blocked IPs](#️-customizing-dns-and-blocked-ips)
      - [🔍 If the Config Doesn't Work](#-if-the-config-doesnt-work)
      - [🌐 Customizing DNS Servers](#-customizing-dns-servers)
      - [🚫 Replacing Blocked IPs](#-replacing-blocked-ips)
      - [📝 Region-Specific Examples](#-region-specific-examples)
      - [🔄 Updating Your Repo](#-updating-your-repo)
  - [❓ Troubleshooting](#-troubleshooting)
  - [⚠️ Disclaimer](#️-disclaimer)
  - [🤝 Contributing](#-contributing)
  - [📞 Contact](#-contact)

---

## 🌟 Overview

Welcome to **GFW-Slayer**, a collection of serverless configurations designed to provide unrestricted access to the internet. Built by **void** (GitHub: @voidr3aper-anon), this repo empowers users in censored regions like China, Iran and Russia to bypass firewalls, sanctions, and restrictions. Whether you're facing blocks on AI tools like Grok or general internet throttling, these configs act as a powerful weapon against censorship, ensuring freedom of information and seamless connectivity.

These configurations leverage advanced techniques such as **JA3 and JA4 jamming** to evade detection and blocking, allowing access to sanctioned sites and services without interruptions. No servers needed—just plug them into your V2Ray client and go!

---

## ✨ Features

- 🎯 **Serverless Setup**: No need for your own servers; these configs work out-of-the-box with public resources.
- 🛡️ **Anti-Censorship Jamming**: Built-in anti JA3 and JA4 fingerprinting techniques to prevent blocking on sites like Grok AI and other sanctioned platforms.
- 🌍 **Multi-Region Support**: Optimized for high-censorship environments (Iran/China/Russia), including DNS overrides and fragmentation to bypass GFW-like systems.
- 🔀 **Multiple Variants**: Choose between global, Iran-specific, China-specific, Russia-specific, and advanced XhTTP/DOH modes for different use cases.
- 📲 **Easy Integration**: Compatible with popular V2Ray apps on Android, Windows, Linux, and more.
- 🔒 **Privacy-Focused**: Routes traffic securely while blocking unwanted IPs and domains.
- 💎 **Open Source**: Free to use, modify, and contribute—fight censorship together!

---

## 📱 How to Use
These configs are designed for V2Ray-compatible clients (e.g., V2RayNG on Android, V2RayN on Windows/Linux). Simply add them as subscription links to your app for automatic updates and easy access.

### 1️⃣ Install a V2Ray Client

| Platform | Client | Download Link |
|----------|--------|---------------|
| 📱 Android | V2RayNG | [GitHub](https://github.com/2dust/v2rayNG) |
| 💻 Windows/Linux | V2RayN | [GitHub](https://github.com/2dust/v2rayN) |
| 🍎 iOS | Shadowrocket / Quantumult X | App Store (Paid) |
| 🌐 Other | Any V2Ray/XRay core | Check for V2Ray/XRay core support |

### 2️⃣ Add Subscription Links

In your V2Ray app, go to the subscription section and add one or more of these URLs:

<table>
<tr>
<th>🌍 Config Type</th>
<th>📥 Subscription URL</th>
</tr>
<tr>
<td><b>Global V2Ray Configs</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json
```

</td>
</tr>
<tr>
<td><b>🇮🇷 Iran-Friendly Configs</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json
```

</td>
</tr>
<tr>
<td><b>🇨🇳 China-Friendly Configs</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-china-friendly.json
```

</td>
</tr>
<tr>
<td><b>🇷🇺 Russia-Friendly Configs</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-russia-friendly.json
```

</td>
</tr>
</table>

These links point to JSON arrays of configurations. Your app will import multiple profiles (e.g., "ATOMIC-IR", "ATOMIC-GLOBAL-Android/windows-only", etc.) for you to select from.

### 3️⃣ Select and Connect

- ✅ Update subscriptions in the app.
- ✅ Choose a profile based on your needs (e.g., "ATOMIC-iran" for Iran-specific routing or "ATOMIC-XhTTP-new-era" for advanced features).
- ✅ Connect and enjoy unrestricted internet access!

### 4️⃣ Tips for Best Performance

- 🔄 Test different profiles to find the one that works best in your region.
- ⚙️ Enable sniffing and domain overriding in your client settings if needed.
- 🔐 For DNS issues, profiles with DOH (DNS over HTTPS) servers are recommended.
- 🧩 If you encounter blocks, switch to a profile with fragmentation enabled.

---

## 📦 Config Details
---

This repo includes **four main configuration files**, each optimized for different regions and use cases:

<table>
<tr>
<th>📄 Config File</th>
<th>🎯 Target Region</th>
<th>⚡ Key Features</th>
</tr>
<tr>
<td><code>serverless-v2ray.json</code></td>
<td>🌍 Global</td>
<td>Contains advanced configs like "ATOMIC-IR", "ATOMIC-GLOBAL-Android/windows-only", "ATOMIC-XhTTP-new-era", "ATOMIC-XhTTP-DOH", and "ATOMIC-Force". Ideal for worldwide use with strong anti-censorship features.</td>
</tr>
<tr>
<td><code>serverless-iran-freindly.json</code></td>
<td>🇮🇷 Iran</td>
<td>Tailored for Iran, with profiles like "ATOMIC-iran" and "ATOMIC-iran-DOH". Includes Iran-specific routing (e.g., direct access to .ir domains) and DOH for secure DNS.</td>
</tr>
<tr>
<td><code>serverless-china-friendly.json</code></td>
<td>🇨🇳 China</td>
<td>Designed for China, with profiles like "ATOMIC-china" and "ATOMIC-china-DOH". Routes .cn domains and IPs directly while fragmenting international traffic.</td>
</tr>
<tr>
<td><code>serverless-russia-friendly.json</code></td>
<td>🇷🇺 Russia</td>
<td>Optimized for Russia, with profiles like "ATOMIC-russia" and "ATOMIC-russia-DOH". Routes .ru domains and IPs directly for better performance.</td>
</tr>
</table>

### 🔐 Technical Details

All configs use:
- **VLESS with TLS** for secure connections
- **Fragmentation** for evasion of deep packet inspection
- **Blackhole routing** for blocked IPs
- **Smart routing**: Routes local/private IPs directly while fragmenting international traffic
- **Hidden tricks** and optimizations that you'll discover as you use them! (the firewall eventually feels them too) 😉

---

## 🔧 Professional / Advanced Usage

This section covers advanced techniques for power users who want to maximize privacy, bypass sophisticated censorship, or customize configurations for specific needs.

### 🔗 VPN Chaining and Proxy Mode

To maximize your ability to bypass censorship and enhance privacy, you can configure your V2Ray client in **proxy mode** and chain it with other VPNs. This setup routes your V2Ray traffic through another VPN, combining the anti-censorship features of GFW-Slayer with the additional encryption and anonymity of a secondary VPN.

To maximize your ability to bypass censorship and enhance privacy, you can configure your V2Ray client in **proxy mode** and chain it with other VPNs. This setup routes your V2Ray traffic through another VPN, combining the anti-censorship features of GFW-Slayer with the additional encryption and anonymity of a secondary VPN.

#### 📖 Step-by-Step Guide

**Step 1: Set Up V2Ray in Proxy Mode**

- Open your V2Ray client (e.g., V2RayNG on Android, V2RayN on Windows, or Shadowrocket on iOS).
- Import one of the GFW-Slayer subscription links:
  - **Global Configs**:
    ```
    https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json
    ```
  - **Region-Specific Configs**: 
    ```
    https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json
    ```
    *(Replace `iran` with `china` or `russia` for other regions)*

- Select a profile (e.g., "ATOMIC-iran" or "ATOMIC-XhTTP-DOH") and connect.
- Ensure your V2Ray client is set to **SOCKS** or **HTTP** proxy mode:
  - **V2RayNG**: Go to **Settings** > **SOCKS Proxy** or **HTTP Proxy** and note the local proxy address (e.g., `127.0.0.1:10808` for SOCKS or `127.0.0.1:10809` for HTTP).
  - **V2RayN**: Check **Settings** > **Local Port** for the SOCKS/HTTP port.
  - **Shadowrocket**: Enable **Global Proxy** and select the SOCKS or HTTP profile.
- Verify that V2Ray is running and the proxy is active (test by browsing a blocked site).

**Step 2: Install and Configure a Secondary VPN**
**Step 2: Install and Configure a Secondary VPN**

- Choose a VPN service that supports SOCKS5 or HTTP proxy input (e.g., NordVPN, ProtonVPN, or any VPN with manual proxy settings). Alternatively, use another V2Ray or Shadowsocks instance.
- Install the VPN app on your device or configure it manually if it supports custom proxy settings.
- In the VPN's settings, configure it to use the V2Ray proxy as its upstream proxy:
  - **For SOCKS5**: Set the proxy server to `127.0.0.1` and the port to `10808` (or the SOCKS port from your V2Ray client).
  - **For HTTP**: Set the proxy server to `127.0.0.1` and the port to `10809` (or the HTTP port from your V2Ray client).
  - **Example for NordVPN** (if supported): Go to **Settings** > **Advanced** > **Custom Proxy** and enter the V2Ray SOCKS/HTTP details.
- If the VPN doesn't support custom proxy input, you can use tools like **Proxifier** (Windows/macOS) or **ProxyCap** to route the VPN's traffic through V2Ray's proxy.

**Step 3: Chain the Connection**

- Start V2Ray first and ensure it's connected.
- Launch the secondary VPN and connect through the V2Ray proxy.
- The connection chain will look like this:  
  ```
  Your Device → V2Ray (GFW-Slayer Config) → Secondary VPN → Internet
  ```
- This setup routes your traffic through V2Ray's anti-censorship mechanisms first, then through the VPN for additional encryption and IP masking.

**Step 4: Test the Connection**

- Visit a blocked site (e.g., Grok AI or other sanctioned services) to confirm the chain is working.
- Check your IP address using a site like `whatismyipaddress.com` to ensure it's masked by the secondary VPN.
- If you encounter issues, verify that:
  - ✅ V2Ray is running and the proxy ports are correct.
  - ✅ The secondary VPN supports SOCKS5/HTTP proxy input or is routed correctly via Proxifier/ProxyCap.
  - ✅ Firewalls or antivirus software aren't blocking the proxy ports.

#### 💡 Advanced Tips for Chaining

- 🎯 **Choose the Right Profile**: Use a V2Ray profile with fragmentation (e.g., "ATOMIC-XhTTP-new-era") for better evasion in high-censorship regions.
- 🔐 **DNS Security**: Use profiles with DOH (DNS over HTTPS) like "ATOMIC-iran-DOH" or "ATOMIC-XhTTP-DOH" to prevent DNS leaks.
- 🔗 **Multiple VPNs**: For extra obfuscation, you can chain multiple VPNs (e.g., V2Ray → VPN1 → VPN2), but this may slow your connection.
- ⚡ **Performance**: Chaining VPNs can reduce speed. Test different combinations of V2Ray profiles and VPN providers to find the best balance.
- 🛠️ **Proxifier/ProxyCap**: If your VPN doesn't support proxy input, use these tools to force the VPN's traffic through V2Ray's SOCKS/HTTP proxy.

#### ❓ Why Chain V2Ray with Another VPN?

- 🛡️ **Enhanced Evasion**: V2Ray's JA3 and JA4 jamming bypasses censorship, while the secondary VPN adds another layer of obfuscation.
- 🔒 **Privacy Boost**: The VPN hides your V2Ray traffic from ISPs and provides a different IP for added anonymity.
- 🌐 **Flexibility**: Combine GFW-Slayer's serverless configs with trusted VPNs for specific use cases (e.g., accessing region-locked content).

#### 🔧 Troubleshooting Chained Connections

- ❌ **Connection Fails**: Ensure V2Ray is running before starting the VPN. Check proxy ports and settings.
- 🐌 **Slow Speeds**: Try a different V2Ray profile or a closer VPN server location.
- 🚫 **Blocked Sites Still Inaccessible**: Switch to a DOH-enabled profile or test with a different VPN provider.
- 📋 **Logs**: Enable logging in V2Ray (set `loglevel` to `debug` temporarily) to diagnose issues, then revert to `none` for privacy.

> **By combining GFW-Slayer's V2Ray configs with another VPN, you can create a robust, censorship-resistant connection that keeps you free online!**

---

### ⚙️ Customizing DNS and Blocked IPs

If the GFW-Slayer configurations don't work as expected in your region, you may need to customize the DNS servers and blocked IP addresses to better suit your country's internet environment. The default configurations are optimized for Iran, but you can adapt them for other regions like China, Russia, or elsewhere by following these steps.

#### 🔍 If the Config Doesn't Work

- ✅ **Check Connectivity**: Ensure your V2Ray client is correctly set up and the subscription links are added properly. Test with different profiles (e.g., "ATOMIC-iran", "ATOMIC-china-DOH") to see if one works better.
- 🌐 **Network Issues**: Verify that your internet connection is stable and that firewalls or antivirus software aren't blocking V2Ray's ports (e.g., 10808 for SOCKS, 10809 for HTTP, 10853 for DNS).
- 🔄 **Censorship Updates**: Censorship methods evolve, so configs may need tweaks. Check the GitHub issues page for community updates or report your issue.

#### 🌐 Customizing DNS Servers

The default DNS servers in the configs (e.g., `78.157.42.100` for Iran, `114.114.114.114` for China, or `77.88.8.8` for Russia) may not work optimally in your country. To improve performance and bypass DNS-based censorship:

**1. Find Local DNS Servers**

<table>
<tr>
<th>🌍 Region</th>
<th>🔧 Recommended DNS Servers</th>
</tr>
<tr>
<td><b>Global</b></td>
<td><code>8.8.8.8</code> (Google), <code>1.1.1.1</code> (Cloudflare)</td>
</tr>
<tr>
<td><b>🇨🇳 China</b></td>
<td><code>114.114.114.114</code> (Public DNS), <code>223.5.5.5</code> (AliDNS)</td>
</tr>
<tr>
<td><b>🇷🇺 Russia</b></td>
<td><code>77.88.8.8</code> (Yandex), <code>94.250.250.250</code> (SkyDNS)</td>
</tr>
<tr>
<td><b>🔐 DOH (Recommended)</b></td>
<td><code>https://1.1.1.1/dns-query</code>, <code>https://mozilla.cloudflare-dns.com/dns-query</code></td>
</tr>
</table>

**2. Edit the Config**

- Download the relevant config file (`serverless-iran-friendly.json`, `serverless-china-friendly.json`, or `serverless-russia-friendly.json`).
- Open it in a text editor (e.g., Notepad++ or VS Code).
- Locate the `"dns"` > `"servers"` section. For example:
  ```json
  "servers": [
    "78.157.42.100",
    "78.157.42.101",
    "8.8.8.8",
    "104.21.83.62",
    "172.67.214.246",
    "185.236.104.104"
  ]
  ```
- Replace the listed servers with your chosen DNS servers. For DOH profiles, update the URLs in the `"servers"` array.
- also in some configs  there is `8.8.8.8` somwhere . u can change it to see what happens. (usefull for networks like irancell  that blocks dns anti spoofing) 
- Save the file and re-import it into your V2Ray client, or host it on your GitHub repo and update the subscription link.

**3. Test DNS**

Use a site like [dnsleaktest.com](https://dnsleaktest.com) to ensure your DNS queries are resolved by your chosen servers and not leaking to your ISP.

#### 🚫 Replacing Blocked IPs

The configs block specific IPs (`10.10.34.34`, `10.10.34.35`, `10.10.34.36`) that are associated with censorship infrastructure in Iran. These IPs are unlikely to apply in other countries, so you should replace them with IPs relevant to your region's censorship systems:

**Identify Blocked IPs**

- Research IPs used by your country's censorship or monitoring systems (e.g., Great Firewall in China, Roskomnadzor in Russia). You may find these in online forums, GitHub issues, or anti-censorship communities.
- **Example**: In China, you might block IPs associated with GFW deep packet inspection servers. In Russia, check for Roskomnadzor-related IPs.
- If unsure, you can remove these IPs to avoid accidental blocking, but this may reduce effectiveness against local censorship.

**Edit the Config**

- Open the config file in a text editor.
- Find the `"routing"` > `"rules"` section with the blocked IPs:
  ```json
  {
    "ip": [
      "10.10.34.34",
      "10.10.34.35",
      "10.10.34.36"
    ],
    "outboundTag": "block",
    "type": "field"
  }
  ```
- Replace the IPs with those relevant to your country, or remove the rule if no specific IPs need blocking.
- Save the file and re-import it into your V2Ray client or update your GitHub-hosted file.

**Test the Changes**

- Connect to the updated config and try accessing blocked sites. If issues persist, double-check the IPs or consult community resources for your country.

#### 📝 Region-Specific Examples

**For China 🇨🇳**
- **DNS**: Replace with `114.114.114.114` and `223.5.5.5`, or use DOH (`https://1.1.1.1/dns-query`).
- **Blocked IPs**: Replace `10.10.34.34`, etc., with known GFW-related IPs (research required, as these vary).

**For Russia 🇷🇺**
- **DNS**: Use `77.88.8.8` (Yandex) or `94.250.250.250` (SkyDNS), or stick with DOH servers.
- **Blocked IPs**: Replace with IPs linked to Roskomnadzor or blocked services (check community lists).

#### 🔄 Updating Your Repo

- After editing, upload the modified config to your GitHub repo (`GFW-slayer`) and update the subscription link in your V2Ray client.
- Share your custom configs with the community via pull requests to help others in your region!

> **By tailoring DNS and blocked IPs to your country, you can optimize GFW-Slayer for your specific censorship environment. If you need help finding DNS servers or blocked IPs, check GitHub issues or anti-censorship forums for your region.**

---

## ❓ Troubleshooting
---

## ⚠️ Disclaimer

- ⚖️ This tool is for ** freedom-of-information purposes only**. Use it responsibly and in compliance with local laws :).
- 📊 Performance may vary based on your network and location—censorship evolves, so configs may need updates.
- 🚫 **No warranties provided**; test thoroughly before relying on these configs.
- 🔐 If you're in a high-risk area, combine with other privacy tools like Tor for added security.
- © **Copyright Notice**: This project and all configurations are created by **void** (@voidr3aper-anon). Please respect intellectual property rights.

---

## 🤝 Contributing

Contributions are welcome! If you have improvements, new configs, or fixes:

1. 🍴 Fork the repo
2. 🔧 Make your changes
3. ✅ Test thoroughly
4. 📝 Submit a pull request with a clear description

Issues and feature requests? [Open an issue here](https://github.com/voidr3aper-anon/GFW-slayer/issues).

---

## 📞 Contact

<div align="center">

Built  by **void** ([@voidr3aper-anon](https://github.com/voidr3aper-anon))

For questions or support, reach out via [GitHub Issues](https://github.com/voidr3aper-anon/GFW-slayer/issues)

---

⭐ **Star the repo if it helps you break free—let's slay the GFW together!** 🌐🚀

</div>
