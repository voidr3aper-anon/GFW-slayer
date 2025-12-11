<div align="center">

# 🚀 GFW-Slayer

<img src="https://github.com/voidr3aper-anon/GFW-slayer/blob/main/logo-new.png" width="350" alt="GFW-Slayer 标志" />

### *无服务器 V2Ray 配置，实现无限制的互联网访问*

[![许可证: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub 星标](https://img.shields.io/github/stars/voidr3aper-anon/GFW-slayer?style=social)](https://github.com/voidr3aper-anon/GFW-slayer/stargazers)
[![GitHub 分支](https://img.shields.io/github/forks/voidr3aper-anon/GFW-slayer?style=social)](https://github.com/voidr3aper-anon/GFW-slayer/network/members)
[![最后提交](https://img.shields.io/github/last-commit/voidr3aper-anon/GFW-slayer)](https://github.com/voidr3aper-anon/GFW-slayer/commits/main)

---

### 🌐 阅读其他语言 / Read in Other Languages

**[English](README.md)** | **[فارسی](README.fa.md)** | **[Русский](README.ru.md)** | **[中文](README.zh-CN.md)**

---

</div>

## 📋 目录

- [🚀 GFW-Slayer](#-gfw-slayer)
    - [*无服务器 V2Ray 配置，实现无限制的互联网访问*](#无服务器-v2ray-配置实现无限制的互联网访问)
    - [🌐 阅读其他语言 / Read in Other Languages](#-阅读其他语言--read-in-other-languages)
  - [📋 目录](#-目录)
  - [📁 仓库结构](#-仓库结构)
    - [🔗 快速访问（推荐新用户使用）](#-快速访问推荐新用户使用)
    - [🔄 旧版 URL（适用于现有用户）](#-旧版-url适用于现有用户)
  - [🌟 概述](#-概述)
  - [✨ 功能特性](#-功能特性)
  - [📱 使用方法](#-使用方法)
    - [1️⃣ 安装 V2Ray 客户端](#1️⃣-安装-v2ray-客户端)
    - [2️⃣ 添加订阅链接](#2️⃣-添加订阅链接)
      - [🆕 推荐 URL（有序结构）](#-推荐-url有序结构)
      - [🔄 旧版 URL（仍然有效）](#-旧版-url仍然有效)
    - [3️⃣ 选择并连接](#3️⃣-选择并连接)
    - [4️⃣ 获得最佳性能的技巧](#4️⃣-获得最佳性能的技巧)
  - [🌐 可以访问哪些网站](#-可以访问哪些网站)
    - [1) 通过 **JA3/JA4 指纹**封锁您的网站](#1-通过-ja3ja4-指纹封锁您的网站)
    - [2) 通过 **SNI/主机名**过滤在您所在国家被封锁的网站](#2-通过-sni主机名过滤在您所在国家被封锁的网站)
    - [3) **谷歌服务**（结果不一）](#3-谷歌服务结果不一)
    - [4) 具有**硬 IP 封锁**的域名](#4-具有硬-ip-封锁的域名)
    - [快速参考](#快速参考)
  - [📦 配置详情](#-配置详情)
    - [🔐 技术细节](#-技术细节)
  - [🔧 专业/高级用法](#-专业高级用法)
    - [🔗 VPN 链接和代理模式](#-vpn-链接和代理模式)
      - [📖 分步指南](#-分步指南)
      - [💡 链接的高级技巧](#-链接的高级技巧)
      - [❓ 为什么将 V2Ray 与另一个 VPN 链接？](#-为什么将-v2ray-与另一个-vpn-链接)
      - [🔧 链式连接故障排除](#-链式连接故障排除)
    - [⚙️ 自定义 DNS 和被封锁的 IP](#️-自定义-dns-和被封锁的-ip)
      - [🔍 如果配置不工作](#-如果配置不工作)
      - [🌐 自定义 DNS 服务器](#-自定义-dns-服务器)
      - [🚫 替换被封锁的 IP](#-替换被封锁的-ip)
      - [📝 特定地区的示例](#-特定地区的示例)
      - [🔄 更新您的仓库](#-更新您的仓库)
  - [❓ 故障排除](#-故障排除)
  - [⚠️ 免责声明](#️-免责声明)
  - [🤝 贡献](#-贡献)
  - [📞 联系方式](#-联系方式)

---

## 📁 仓库结构

此仓库分为两种主要访问方式：

### 🔗 快速访问（推荐新用户使用）
使用有序结构便于浏览和选择：
```
configs/
├── regional/           # 区域优化配置
│   ├── china/         # 🇨🇳 中国优化配置
│   ├── iran/          # 🇮🇷 伊朗优化配置  
│   └── russia/        # 🇷🇺 俄罗斯优化配置
└── general/           # 🌍 通用配置
```

### 🔄 旧版 URL（适用于现有用户）
所有原始订阅 URL 在根目录中保持活跃和稳定，以确保现有订阅继续正常工作。

---

## 🌟 概述

欢迎来到 **GFW-Slayer**，这是一个旨在提供无限制互联网访问的无服务器配置集合。由 **void**（GitHub: @voidr3aper-anon）打造，本仓库赋予审查地区（如中国、伊朗和俄罗斯）的用户绕过防火墙、制裁和限制的能力。无论您面临 AI 工具（如 Grok）的封锁还是一般的互联网限速，这些配置都是对抗审查的强大武器，确保信息自由和无缝连接。

这些配置利用诸如 **JA3 和 JA4 干扰**等先进技术来规避检测和封锁，允许不间断地访问受制裁的网站和服务。无需服务器——只需将它们插入您的 V2Ray 客户端即可使用！

---

## ✨ 功能特性

- 🎯 **无服务器设置**：无需自己的服务器；这些配置开箱即用，使用公共资源。
- 🛡️ **反审查干扰**：内置反 JA3 和 JA4 指纹技术，防止在 Grok AI 等受制裁平台上被封锁。
- 🌍 **多地区支持**：针对高审查环境（伊朗/中国/俄罗斯）进行优化，包括 DNS 覆盖和分片以绕过类似 GFW 的系统。
- 🔀 **多种变体**：在全球、伊朗专用、中国专用、俄罗斯专用和高级 XhTTP/DOH 模式之间选择，适用于不同的使用场景。
- 📲 **轻松集成**：兼容 Android、Windows、Linux 等平台上流行的 V2Ray 应用。
- 🔒 **注重隐私**：安全路由流量，同时封锁不需要的 IP 和域名。
- 💎 **开源**：免费使用、修改和贡献——一起对抗审查！

---

## 📱 使用方法

这些配置专为兼容 V2Ray 的客户端（例如 Android 上的 V2RayNG，Windows/Linux 上的 V2RayN）设计。只需将它们作为订阅链接添加到您的应用中，即可自动更新和轻松访问。

### 1️⃣ 安装 V2Ray 客户端

| 平台 | 客户端 | 下载链接 |
|------|--------|----------|
| 📱 Android | V2RayNG | [GitHub](https://github.com/2dust/v2rayNG) |
| 💻 Windows/Linux | V2RayN | [GitHub](https://github.com/2dust/v2rayN) |
| 🍎 iOS | Shadowrocket / Quantumult X | App Store（付费）|
| 🌐 其他 | 任何 V2Ray/XRay core | 检查 V2Ray/XRay core 支持 |

### 2️⃣ 添加订阅链接

在您的 V2Ray 应用中，转到订阅部分并添加以下一个或多个 URL：

#### 🆕 推荐 URL（有序结构）
<table>
<tr>
<th>🌍 配置类型</th>
<th>📥 订阅链接</th>
</tr>
<tr>
<td><b>🌍 通用 V2Ray 配置</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/configs/general/serverless-v2ray.json
```

</td>
</tr>
<tr>
<td><b>🔥 高级 V-Force 配置</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/configs/general/V-force.json
```

</td>
</tr>
<tr>
<td><b>🇮🇷 伊朗优化配置</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/configs/regional/iran/serverless-iran-friendly.json
```

</td>
</tr>
<tr>
<td><b>🇨🇳 中国优化配置</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/configs/regional/china/serverless-china-friendly.json
```

</td>
</tr>
<tr>
<td><b>🇷🇺 俄罗斯优化配置</b></td>
<td>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/configs/regional/russia/serverless-russia-friendly.json
```

</td>
</tr>
</table>

#### 🔄 旧版 URL（仍然有效）
对于现有用户，这些原始 URL 继续工作：
<details>
<summary>点击展开旧版 URL</summary>

```
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-china-friendly.json
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-russia-friendly.json
https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/V-force.json
```

</details>

这些链接指向配置的 JSON 数组。您的应用将导入多个配置文件（例如 "ATOMIC-IR"、"ATOMIC-GLOBAL-Android/windows-only" 等）供您选择。

### 3️⃣ 选择并连接

- ✅ 在应用中更新订阅。
- ✅ 根据您的需求选择配置文件（例如，"ATOMIC-iran" 用于伊朗专用路由，"ATOMIC-XhTTP-new-era" 用于高级功能）。
- ✅ 连接并享受无限制的互联网访问！

### 4️⃣ 获得最佳性能的技巧

- 🔄 测试不同的配置文件，找到最适合您所在地区的那个。
- ⚙️ 如有需要，在客户端设置中启用嗅探和域名覆盖。
- 🔐 对于 DNS 问题，建议使用带有 DOH（DNS over HTTPS）服务器的配置文件。
- 🧩 如果遇到封锁，切换到启用了分片的配置文件。

---

## 🌐 可以访问哪些网站

以下是使用 **GFW-Slayer** 配置文件时通常可以使用（和不能使用）的快速指南。实际结果取决于您的网络和您所在国家（例如伊朗/中国/俄罗斯）的审查更新。

### 1) 通过 **JA3/JA4 指纹**封锁您的网站
**可用。** 这些配置包括 **JA3/JA4 干扰**，因此对 TLS 握手进行指纹识别的网站和 AI 工具通常会打开。
- **示例：** Grok、ChatGPT、OpenAI 平台、Claude、一些 LLM/AI 仪表板和大多数 Cloudflare 网络后面的网站。
- **为什么可用：** 配置文件随机化/混淆 TLS 指纹以规避客户端指纹禁令。

### 2) 通过 **SNI/主机名**过滤在您所在国家被封锁的网站
**可用。** 当审查查看域名（SNI/ESNI）而不是硬 IP 封锁时，这些配置文件会对请求进行隧道/混淆。
- **示例：** YouTube、X（Twitter）、Instagram、Medium、Discord、Reddit、GitHub。
- **提示：** 如果一个配置文件很慢，切换到另一个（例如 DOH/分片变体）。

### 3) **谷歌服务**（结果不一）
**大部分可用，有警告。** 许多谷歌资产都能很好地打开，但严格执行**账户国家/账单地区/源 IP** 的服务可能仍然受限。
- **通常可以：** 搜索、Gmail、Drive、Docs、YouTube、Photos、Play（用户端）。
- **可能受限或不稳定：** Google Cloud Console（GCP）、Google Play **开发者**控制台、Payments/Merchant Center、一些地理围栏 API。
- **受限国家注意事项（例如伊朗）：** 基本访问通常有效；**开发者/账单操作**可能仍然失败，这是由于谷歌的政策检查与 **IP/账户国家**相关，而不仅仅是连接性。

### 4) 具有**硬 IP 封锁**的域名
**不可用。** 如果服务在 **IP 级别**被封锁（null-routed / blackholed / 网络边缘 RST），隧道主机名将无济于事。
- **示例：** Telegram（在某些地区经常执行广泛的 IP 范围封锁）和其他通过目标 IP 丢弃流量的服务。
- **解决方法：** 尝试不同的出口路径（另一个 VPN 跳、不同的代理链、Tor 桥接）——但不能保证。

---

### 快速参考

| 类别 | 典型结果 | 示例 | 说明 |
|------|---------|------|------|
| 基于 JA3/JA4 的封锁 | ✅ 可用 | Grok、ChatGPT、AI 仪表板 | 指纹干扰绕过客户端 TLS 禁令。|
| SNI/主机名国家封锁 | ✅ 可用 | YouTube、X、Instagram、Medium、Discord、Reddit、GitHub | 如果 DPI 激进，使用 DOH/分片配置文件。|
| 谷歌（一般）| ✅ 大部分可以 | 搜索、Gmail、Drive、Docs、YouTube | 在大多数情况下，登录和基本使用都很好。|
| 谷歌（开发者/账单）| ⚠️ 不一定 | GCP 控制台、Play Developer、Payments/Merchant | 由账户/账单地区和 IP 检查强制执行。|
| IP 级域名封锁 | ❌ 无法修复 | Telegram（经常）、其他硬 IP 丢弃 | 需要不同的出口 IP/链；不保证。|

> **提醒：** 如果某些东西停止工作，更新订阅，切换到另一个配置文件（例如 `…-DOH` 或分片变体），或按照本 README 中所述与另一个 VPN 链接。

---

## 📦 配置详情

此仓库包含**四个主要配置文件**，每个文件都针对不同的地区和使用场景进行了优化：

<table>
<tr>
<th>📄 配置文件</th>
<th>🎯 目标地区</th>
<th>⚡ 主要功能</th>
</tr>
<tr>
<td><code>serverless-v2ray.json</code></td>
<td>🌍 全球</td>
<td>包含高级配置，如 "ATOMIC-IR"、"ATOMIC-GLOBAL-Android/windows-only"、"ATOMIC-XhTTP-new-era"、"ATOMIC-XhTTP-DOH" 和 "ATOMIC-Force"。适合全球使用，具有强大的反审查功能。</td>
</tr>
<tr>
<td><code>serverless-iran-freindly.json</code></td>
<td>🇮🇷 伊朗</td>
<td>为伊朗量身定制，包含 "ATOMIC-iran" 和 "ATOMIC-iran-DOH" 等配置文件。包括伊朗专用路由（例如直接访问 .ir 域名）和用于安全 DNS 的 DOH。</td>
</tr>
<tr>
<td><code>serverless-china-friendly.json</code></td>
<td>🇨🇳 中国</td>
<td>为中国设计，包含 "ATOMIC-china" 和 "ATOMIC-china-DOH" 等配置文件。直接路由 .cn 域名和 IP，同时对国际流量进行分片。</td>
</tr>
<tr>
<td><code>serverless-russia-friendly.json</code></td>
<td>🇷🇺 俄罗斯</td>
<td>为俄罗斯优化，包含 "ATOMIC-russia" 和 "ATOMIC-russia-DOH" 等配置文件。直接路由 .ru 域名和 IP 以获得更好的性能。</td>
</tr>
</table>

### 🔐 技术细节

所有配置都使用：
- **VLESS with TLS** 用于安全连接
- **分片** 用于规避深度包检测
- **黑洞路由** 用于被封锁的 IP
- **智能路由**：直接路由本地/私有 IP，同时对国际流量进行分片
- **隐藏技巧**和优化，您在使用时会发现！（防火墙最终也会感受到它们）😉

---

## 🔧 专业/高级用法

本节介绍高级用户的先进技术，这些用户希望最大限度地提高隐私、绕过复杂的审查或为特定需求自定义配置。

### 🔗 VPN 链接和代理模式

为了最大限度地提高绕过审查和增强隐私的能力，您可以在**代理模式**下配置 V2Ray 客户端并将其与其他 VPN 链接。此设置通过另一个 VPN 路由您的 V2Ray 流量，结合 GFW-Slayer 的反审查功能与辅助 VPN 的额外加密和匿名性。

#### 📖 分步指南

**步骤 1：在代理模式下设置 V2Ray**

- 打开您的 V2Ray 客户端（例如 Android 上的 V2RayNG、Windows 上的 V2RayN 或 iOS 上的 Shadowrocket）。
- 导入 GFW-Slayer 订阅链接之一：
  - **全球配置**：
    ```
    https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-v2ray.json
    ```
  - **地区专用配置**： 
    ```
    https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/refs/heads/main/serverless-iran-freindly.json
    ```
    *（对于其他地区，将 `iran` 替换为 `china` 或 `russia`）*

- 选择一个配置文件（例如 "ATOMIC-iran" 或 "ATOMIC-XhTTP-DOH"）并连接。
- 确保您的 V2Ray 客户端设置为 **SOCKS** 或 **HTTP** 代理模式：
  - **V2RayNG**：转到 **Settings** > **SOCKS Proxy** 或 **HTTP Proxy** 并记下本地代理地址（例如 `127.0.0.1:10808` 用于 SOCKS 或 `127.0.0.1:10809` 用于 HTTP）。
  - **V2RayN**：检查 **Settings** > **Local Port** 以获取 SOCKS/HTTP 端口。
  - **Shadowrocket**：启用 **Global Proxy** 并选择 SOCKS 或 HTTP 配置文件。
- 验证 V2Ray 正在运行且代理处于活动状态（通过浏览被封锁的网站进行测试）。

**步骤 2：安装和配置辅助 VPN**

- 选择支持 SOCKS5 或 HTTP 代理输入的 VPN 服务（例如 NordVPN、ProtonVPN 或任何具有手动代理设置的 VPN）。或者，使用另一个 V2Ray 或 Shadowsocks 实例。
- 在您的设备上安装 VPN 应用，或者如果它支持自定义代理设置，则手动配置它。
- 在 VPN 的设置中，将其配置为使用 V2Ray 代理作为其上游代理：
  - **对于 SOCKS5**：将代理服务器设置为 `127.0.0.1`，端口设置为 `10808`（或来自您的 V2Ray 客户端的 SOCKS 端口）。
  - **对于 HTTP**：将代理服务器设置为 `127.0.0.1`，端口设置为 `10809`（或来自您的 V2Ray 客户端的 HTTP 端口）。
  - **NordVPN 示例**（如果支持）：转到 **Settings** > **Advanced** > **Custom Proxy** 并输入 V2Ray SOCKS/HTTP 详细信息。
- 如果 VPN 不支持自定义代理输入，您可以使用 **Proxifier**（Windows/macOS）或 **ProxyCap** 等工具通过 V2Ray 的代理路由 VPN 的流量。

**步骤 3：链接连接**

- 首先启动 V2Ray 并确保它已连接。
- 启动辅助 VPN 并通过 V2Ray 代理连接。
- 连接链将如下所示：  
  ```
  您的设备 → V2Ray（GFW-Slayer 配置）→ 辅助 VPN → 互联网
  ```
- 此设置首先通过 V2Ray 的反审查机制路由您的流量，然后通过 VPN 进行额外的加密和 IP 掩码。

**步骤 4：测试连接**

- 访问被封锁的网站（例如 Grok AI 或其他受制裁的服务）以确认链接正在工作。
- 使用 `whatismyipaddress.com` 等网站检查您的 IP 地址，以确保它被辅助 VPN 掩盖。
- 如果遇到问题，请验证：
  - ✅ V2Ray 正在运行且代理端口正确。
  - ✅ 辅助 VPN 支持 SOCKS5/HTTP 代理输入或通过 Proxifier/ProxyCap 正确路由。
  - ✅ 防火墙或杀毒软件没有阻止代理端口。

#### 💡 链接的高级技巧

- 🎯 **选择正确的配置文件**：使用带有分片的 V2Ray 配置文件（例如 "ATOMIC-XhTTP-new-era"）以在高审查地区获得更好的规避效果。
- 🔐 **DNS 安全性**：使用带有 DOH（DNS over HTTPS）的配置文件，如 "ATOMIC-iran-DOH" 或 "ATOMIC-XhTTP-DOH" 以防止 DNS 泄漏。
- 🔗 **多个 VPN**：为了额外的混淆，您可以链接多个 VPN（例如 V2Ray → VPN1 → VPN2），但这可能会降低您的连接速度。
- ⚡ **性能**：链接 VPN 可能会降低速度。测试 V2Ray 配置文件和 VPN 提供商的不同组合以找到最佳平衡。
- 🛠️ **Proxifier/ProxyCap**：如果您的 VPN 不支持代理输入，使用这些工具强制 VPN 的流量通过 V2Ray 的 SOCKS/HTTP 代理。

#### ❓ 为什么将 V2Ray 与另一个 VPN 链接？

- 🛡️ **增强规避**：V2Ray 的 JA3 和 JA4 干扰绕过审查，而辅助 VPN 添加了另一层混淆。
- 🔒 **隐私提升**：VPN 向 ISP 隐藏您的 V2Ray 流量，并为增加的匿名性提供不同的 IP。
- 🌐 **灵活性**：将 GFW-Slayer 的无服务器配置与可信赖的 VPN 结合用于特定用例（例如访问地区锁定的内容）。

#### 🔧 链式连接故障排除

- ❌ **连接失败**：确保在启动 VPN 之前 V2Ray 正在运行。检查代理端口和设置。
- 🐌 **速度慢**：尝试不同的 V2Ray 配置文件或更近的 VPN 服务器位置。
- 🚫 **被封锁的网站仍然无法访问**：切换到启用 DOH 的配置文件或使用不同的 VPN 提供商进行测试。
- 📋 **日志**：在 V2Ray 中启用日志记录（暂时将 `loglevel` 设置为 `debug`）以诊断问题，然后为了隐私恢复为 `none`。

> **通过将 GFW-Slayer 的 V2Ray 配置与另一个 VPN 结合，您可以创建一个强大的、抗审查的连接，让您在线自由！**

---

### ⚙️ 自定义 DNS 和被封锁的 IP

如果 GFW-Slayer 配置在您所在的地区未按预期工作，您可能需要自定义 DNS 服务器和被封锁的 IP 地址，以更好地适应您所在国家的互联网环境。默认配置针对伊朗进行了优化，但您可以按照以下步骤将它们适配到其他地区，如中国、俄罗斯或其他地方。

#### 🔍 如果配置不工作

- ✅ **检查连接**：确保您的 V2Ray 客户端设置正确且订阅链接已正确添加。测试不同的配置文件（例如 "ATOMIC-iran"、"ATOMIC-china-DOH"）看看哪个工作得更好。
- 🌐 **网络问题**：验证您的互联网连接稳定，防火墙或杀毒软件没有阻止 V2Ray 的端口（例如 10808 用于 SOCKS，10809 用于 HTTP，10853 用于 DNS）。
- 🔄 **审查更新**：审查方法不断演变，因此配置可能需要调整。检查 GitHub 问题页面以获取社区更新或报告您的问题。

#### 🌐 自定义 DNS 服务器

配置中的默认 DNS 服务器（例如伊朗的 `78.157.42.100`、中国的 `114.114.114.114` 或俄罗斯的 `77.88.8.8`）可能在您的国家无法最佳工作。要改善性能并绕过基于 DNS 的审查：

**1. 查找本地 DNS 服务器**

<table>
<tr>
<th>🌍 地区</th>
<th>🔧 推荐的 DNS 服务器</th>
</tr>
<tr>
<td><b>全球</b></td>
<td><code>8.8.8.8</code>（Google）、<code>1.1.1.1</code>（Cloudflare）</td>
</tr>
<tr>
<td><b>🇨🇳 中国</b></td>
<td><code>114.114.114.114</code>（公共 DNS）、<code>223.5.5.5</code>（阿里 DNS）</td>
</tr>
<tr>
<td><b>🇷🇺 俄罗斯</b></td>
<td><code>77.88.8.8</code>（Yandex）、<code>94.250.250.250</code>（SkyDNS）</td>
</tr>
<tr>
<td><b>🔐 DOH（推荐）</b></td>
<td><code>https://1.1.1.1/dns-query</code>、<code>https://mozilla.cloudflare-dns.com/dns-query</code></td>
</tr>
</table>

**2. 编辑配置**

- 下载相关的配置文件（`serverless-iran-friendly.json`、`serverless-china-friendly.json` 或 `serverless-russia-friendly.json`）。
- 在文本编辑器中打开它（例如 Notepad++ 或 VS Code）。
- 找到 `"dns"` > `"servers"` 部分。例如：
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
- 用您选择的 DNS 服务器替换列出的服务器。对于 DOH 配置文件，更新 `"servers"` 数组中的 URL。
- 此外，在某些配置中某处有 `8.8.8.8`。您可以更改它以查看会发生什么。（对于阻止 DNS 反欺骗的网络（如 Irancell）很有用）
- 保存文件并将其重新导入到您的 V2Ray 客户端，或在您的 GitHub 仓库上托管它并更新订阅链接。

**3. 测试 DNS**

使用 [dnsleaktest.com](https://dnsleaktest.com) 等网站确保您的 DNS 查询由您选择的服务器解析，并且不会泄漏给您的 ISP。

#### 🚫 替换被封锁的 IP

配置封锁了与伊朗审查基础设施相关的特定 IP（`10.10.34.34`、`10.10.34.35`、`10.10.34.36`）。这些 IP 不太可能适用于其他国家，因此您应该将它们替换为与您所在地区审查系统相关的 IP：

**识别被封锁的 IP**

- 研究您所在国家的审查或监控系统使用的 IP（例如中国的长城防火墙、俄罗斯的 Roskomnadzor）。您可能会在在线论坛、GitHub 问题或反审查社区中找到这些。
- **示例**：在中国，您可能会封锁与 GFW 深度包检测服务器相关的 IP。在俄罗斯，检查与 Roskomnadzor 相关的 IP。
- 如果不确定，您可以删除这些 IP 以避免意外封锁，但这可能会降低对本地审查的有效性。

**编辑配置**

- 在文本编辑器中打开配置文件。
- 找到带有被封锁 IP 的 `"routing"` > `"rules"` 部分：
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
- 用与您所在国家相关的 IP 替换这些 IP，或者如果不需要封锁特定 IP，则删除该规则。
- 保存文件并将其重新导入到您的 V2Ray 客户端或更新您在 GitHub 上托管的文件。

**测试更改**

- 连接到更新的配置并尝试访问被封锁的网站。如果问题仍然存在，请仔细检查 IP 或咨询您所在国家的社区资源。

#### 📝 特定地区的示例

**对于中国 🇨🇳**
- **DNS**：替换为 `114.114.114.114` 和 `223.5.5.5`，或使用 DOH（`https://1.1.1.1/dns-query`）。
- **被封锁的 IP**：将 `10.10.34.34` 等替换为已知的与 GFW 相关的 IP（需要研究，因为它们各不相同）。

**对于俄罗斯 🇷🇺**
- **DNS**：使用 `77.88.8.8`（Yandex）或 `94.250.250.250`（SkyDNS），或坚持使用 DOH 服务器。
- **被封锁的 IP**：替换为与 Roskomnadzor 或被封锁服务相关的 IP（查看社区列表）。

#### 🔄 更新您的仓库

- 编辑后，将修改后的配置上传到您的 GitHub 仓库（`GFW-slayer`）并在您的 V2Ray 客户端中更新订阅链接。
- 通过 pull request 与社区分享您的自定义配置，以帮助您所在地区的其他人！

> **通过为您的国家定制 DNS 和被封锁的 IP，您可以针对您的特定审查环境优化 GFW-Slayer。如果您需要帮助查找 DNS 服务器或被封锁的 IP，请查看您所在地区的 GitHub 问题或反审查论坛。**

---

## ❓ 故障排除

常见问题和解决方案：

| 🔴 问题 | ✅ 解决方案 |
|---------|----------|
| **连接被拒绝/无法导入** | 确保您的客户端支持 JSON 订阅，并且原始 GitHub URL 可访问 |
| **DNS 泄漏** | 使用启用 DOH 的配置文件或调整 JSON 中的 `dns.servers` |
| **连接缓慢或不可靠** | 尝试不同的配置文件；分片和 DOH 可提高可靠性但可能增加延迟 |
| **配置文件未显示** | 在您的客户端中更新订阅并检查网络连接 |
| **被封锁的网站仍然无法访问** | 尝试不同的配置文件或在客户端设置中启用分片 |

如需更多帮助，请在 GitHub 上开一个问题，并包含：
- 📱 您的客户端（V2RayNG、V2RayN 等）
- 🌍 您的地区
- 📋 错误日志（如果可用）

---

## ⚠️ 免责声明

- ⚖️ 此工具仅用于**信息自由目的**。请负责任地使用它并遵守当地法律 :)。
- 📊 性能可能因您的网络和位置而异——审查不断演变，因此配置可能需要更新。
- 🚫 **不提供任何保证**；在依赖这些配置之前请彻底测试。
- 🔐 如果您处于高风险地区，请与 Tor 等其他隐私工具结合使用以获得额外的安全性。
- © **版权声明**：此项目和所有配置由 **void**（@voidr3aper-anon）创建。请尊重知识产权。

---

## 🤝 贡献

欢迎贡献！如果您有改进、新配置或修复：

1. 🍴 Fork 仓库
2. 🔧 进行更改
3. ✅ 彻底测试
4. 📝 提交带有明确描述的 pull request

有问题和功能请求？[在这里开一个问题](https://github.com/voidr3aper-anon/GFW-slayer/issues)。

---

## 📞 联系方式

<div align="center">

由 **void**（[@voidr3aper-anon](https://github.com/voidr3aper-anon)）打造

如有问题或支持，请通过以下方式联系：
- 📱 [Telegram 频道](https://t.me/VoidVerge)
- 🐛 [GitHub Issues](https://github.com/voidr3aper-anon/GFW-slayer/issues)

---

⭐ **如果仓库对您有帮助，请给它加星——让我们一起击败 GFW！** 🌐🚀

</div>
