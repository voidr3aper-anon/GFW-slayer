# GFW-Slayer

<p align="center">
  <img src="https://github.com/voidr3aper-anon/GFW-slayer/blob/main/Logo.png" width="350" />
</p>

Welcome to **GFW-Slayer**, a collection of serverless configurations designed to provide unrestricted access to the internet. Built by **void** (GitHub: @voidr3aper-anon), this repo empowers users in censored regions like china , Iran and Russia to bypass firewalls, sanctions, and restrictions. Whether you're facing blocks on AI tools like Grok or general internet throttling, these configs act as a powerful weapon against censorship, ensuring freedom of information and seamless connectivity.

These configurations leverage advanced techniques such as JA3 and JA4 jamming to evade detection and blocking, allowing access to sanctioned sites and services without interruptions. No servers needed—just plug them into your V2Ray client and go!

## Features
- **Serverless Setup**: No need for your own servers; these configs work out-of-the-box with public resources.
- **Anti-Censorship Jamming**: Built-in unti JA3 and JA4 fingerprinting techniques to prevent blocking on sites like Grok AI and other sanctioned platforms.
- **Iran/Russia-Friendly**: Optimized for high-censorship environments, including DNS overrides and fragmentation to bypass GFW-like systems.
- **Multiple Variants**: Choose between global, Iran-specific, and advanced XhTTP/DOH modes for different use cases.
- **Easy Integration**: Compatible with popular V2Ray apps on Android, Windows, linux , and more.
- **Privacy-Focused**: Routes traffic securely while blocking unwanted IPs and domains.
- **Open Source**: Free to use, modify, and contribute—fight censorship together!

## How to Use
These configs are designed for V2Ray-compatible clients (e.g., V2RayNG on Android, V2RayN on Windows/linux). Simply add them as subscription links to your app for automatic updates and easy access.

1. **Install a V2Ray Client**:
   - Android: [V2RayNG](https://github.com/2dust/v2rayNG)
   - Windows/linux: [V2RayN](https://github.com/2dust/v2rayN)
   - Other platforms: Check for V2Ray/XRay core support.

2. **Add Subscription Links**:
   In your V2Ray app, go to the subscription section and add one or both of these URLs:
   - **Global V2Ray Configs**: https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json
   - **Iran-Friendly Configs**: https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json
   
   These links point to JSON arrays of configurations. Your app will import multiple profiles (e.g., "ATOMIC-IR", "ATOMIC-GLOBAL-Android/windows-only", etc.) for you to select from.

3. **Select and Connect**:
   - Update subscriptions in the app.
   - Choose a profile based on your needs (e.g., "ATOMIC-iran" for Iran-specific routing or "ATOMIC-XhTTP-new-era" for advanced features).
   - Connect and enjoy unrestricted internet access!

4. **Tips for Best Performance**:
   - Test different profiles to find the one that works best in your region.
   - Enable sniffing and domain overriding in your client settings if needed.
   - For DNS issues, profiles with DOH (DNS over HTTPS) servers are recommended.
   - If you encounter blocks, switch to a profile with fragmentation enabled.

## Config Details
This repo includes two main files:

- **serverless-v2ray.json**: Contains global and advanced configs like "ATOMIC-IR", "ATOMIC-GLOBAL-Android/windows-only", "ATOMIC-XhTTP-new-era", "ATOMIC-XhTTP-DOH", and "ATOMIC-Force". Ideal for worldwide use with strong anti-censorship features.
- **serverless-iran-freindly.json**: Tailored for Iran, with profiles like "ATOMIC-iran" and "ATOMIC-iran-DOH". Includes Iran-specific routing (e.g., direct access to .ir domains) and DOH for secure DNS.

All configs use VLESS with TLS, fragmentation for evasion, and blackhole routing for blocked IPs. They route Iranian/private IPs directly while fragmenting international traffic. and tones of hidden tricks that you will here the 



## Using Proxy Mode with V2Ray and Chaining VPNs

To maximize your ability to bypass censorship and enhance privacy, you can configure your V2Ray client in **proxy mode** and chain it with other VPNs. This setup routes your V2Ray traffic through another VPN, combining the anti-censorship features of GFW-Slayer with the additional encryption and anonymity of a secondary VPN. Here's how to set it up:

### Step-by-Step Guide

1. **Set Up V2Ray in Proxy Mode**:
   - Open your V2Ray client (e.g., V2RayNG on Android, V2RayN on Windows, or Shadowrocket on iOS).
   - Import one of the GFW-Slayer subscription links:
     - Global Configs: `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json`
     - Iran-Friendly Configs: `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json`
   - Select a profile (e.g., "ATOMIC-iran" or "ATOMIC-XhTTP-DOH") and connect.
   - Ensure your V2Ray client is set to **SOCKS** or **HTTP** proxy mode:
     - In V2RayNG: Go to **Settings** > **SOCKS Proxy** or **HTTP Proxy** and note the local proxy address (e.g., `127.0.0.1:10808` for SOCKS or `127.0.0.1:10809` for HTTP).
     - In V2RayN: Check **Settings** > **Local Port** for the SOCKS/HTTP port.
     - In Shadowrocket: Enable **Global Proxy** and select the SOCKS or HTTP profile.
   - Verify that V2Ray is running and the proxy is active (test by browsing a blocked site).

2. **Install and Configure a Secondary VPN**:
   - Choose a VPN service that supports SOCKS5 or HTTP proxy input (e.g., NordVPN, ProtonVPN, or any VPN with manual proxy settings). Alternatively, use another V2Ray or Shadowsocks instance.
   - Install the VPN app on your device or configure it manually if it supports custom proxy settings.
   - In the VPN's settings, configure it to use the V2Ray proxy as its upstream proxy:
     - For SOCKS5: Set the proxy server to `127.0.0.1` and the port to `10808` (or the SOCKS port from your V2Ray client).
     - For HTTP: Set the proxy server to `127.0.0.1` and the port to `10809` (or the HTTP port from your V2Ray client).
     - Example for NordVPN (if supported): Go to **Settings** > **Advanced** > **Custom Proxy** and enter the V2Ray SOCKS/HTTP details.
   - If the VPN doesn't support custom proxy input, you can use tools like **Proxifier** (Windows/macOS) or **ProxyCap** to route the VPN's traffic through V2Ray's proxy.

3. **Chain the Connection**:
   - Start V2Ray first and ensure it's connected.
   - Launch the secondary VPN and connect through the V2Ray proxy.
   - The connection chain will look like this:  
     `Your Device -> V2Ray (GFW-Slayer Config) -> Secondary VPN -> Internet`
   - This setup routes your traffic through V2Ray's anti-censorship mechanisms first, then through the VPN for additional encryption and IP masking.

4. **Test the Connection**:
   - Visit a blocked site (e.g., Grok AI or other sanctioned services) to confirm the chain is working.
   - Check your IP address using a site like `whatismyipaddress.com` to ensure it's masked by the secondary VPN.
   - If you encounter issues, verify that:
     - V2Ray is running and the proxy ports are correct.
     - The secondary VPN supports SOCKS5/HTTP proxy input or is routed correctly via Proxifier/ProxyCap.
     - Firewalls or antivirus software aren't blocking the proxy ports.

5. **Advanced Tips**:
   - **Choose the Right Profile**: Use a V2Ray profile with fragmentation (e.g., "ATOMIC-XhTTP-new-era") for better evasion in high-censorship regions.
   - **DNS Security**: Use profiles with DOH (DNS over HTTPS) like "ATOMIC-iran-DOH" or "ATOMIC-XhTTP-DOH" to prevent DNS leaks.
   - **Multiple VPNs**: For extra obfuscation, you can chain multiple VPNs (e.g., V2Ray -> VPN1 -> VPN2), but this may slow your connection.
   - **Performance**: Chaining VPNs can reduce speed. Test different combinations of V2Ray profiles and VPN providers to find the best balance.
   - **Proxifier/ProxyCap**: If your VPN doesn't support proxy input, use these tools to force the VPN's traffic through V2Ray's SOCKS/HTTP proxy.

### Why Chain V2Ray with Another VPN?
- **Enhanced Evasion**: V2Ray's JA# and JA$ jamming bypasses censorship, while the secondary VPN adds another layer of obfuscation.
- **Privacy Boost**: The VPN hides your V2Ray traffic from ISPs and provides a different IP for added anonymity.
- **Flexibility**: Combine GFW-Slayer's serverless configs with trusted VPNs for specific use cases (e.g., accessing region-locked content).

### Troubleshooting
- **Connection Fails**: Ensure V2Ray is running before starting the VPN. Check proxy ports and settings.
- **Slow Speeds**: Try a different V2Ray profile or a closer VPN server location.
- **Blocked Sites Still Inaccessible**: Switch to a DOH-enabled profile or test with a different VPN provider.
- **Logs**: Enable logging in V2Ray (set `loglevel` to `debug` temporarily) to diagnose issues, then revert to `none` for privacy.

By combining GFW-Slayer's V2Ray configs with another VPN, you can create a robust, censorship-resistant connection that keeps you free online!


## Disclaimer
- This tool is for freedom-of-information purposes only. Use it responsibly and in compliance with local laws.
- Performance may vary based on your network and location—censorship evolves, so configs may need updates.
- No warranties provided; test thoroughly.
- If you're in a high-risk area, combine with other privacy tools like Tor for added security.
- do not break the Copy right and mistake it for copy write. owner the auther :)


## Contributing
Contributions are welcome! If you have improvements, new configs, or fixes:
- Fork the repo.
- Make your changes.
- Submit a pull request.

Issues and feature requests? Open an issue here.

## Contact
Built with love (as you can see in configs :) by **void** (@voidr3aper-anon). For questions, reach out via GitHub issues.

Star the repo if it helps you break free—let's slay the GFW together! 🌐🚀
