<div align="center">
  <img src="assets/logo.png" width="150" alt="Asuswrt-Merlin logo">
  <h3>Custom firmware for Asus routers</h3>
  <p><em>Everything you like about the stock firmware — with the fixes, hardening, and fine-tuning it deserves.</em></p>

  <p>
    <a href="https://www.asuswrt-merlin.net/download"><img alt="Latest firmware" src="https://img.shields.io/github/v/tag/Asuswrt-Merlin/asuswrt-merlin.ng?sort=semver&style=flat-square&label=firmware&color=0b6bcb"></a>
    <a href="https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/Asuswrt-Merlin/asuswrt-merlin.ng?style=flat-square&label=stars&color=0b6bcb"></a>
    <a href="https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/Supported-Devices"><img alt="Supported models" src="https://img.shields.io/badge/supported_models-19+-0b6bcb?style=flat-square"></a>
    <a href="https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/blob/main/License"><img alt="License" src="https://img.shields.io/badge/license-GPL--2.0_+_proprietary-0b6bcb?style=flat-square"></a>
  </p>
</div>

---

**Asuswrt-Merlin** is a third-party alternative firmware for Asus routers, built on top of Asuswrt — the firmware that ships with every Asus router. We don't set out to reinvent the wheel. We fix bugs, harden security, improve performance, and add the small, well-chosen features that power users actually use, while keeping the look, feel, and feature set of the original firmware intact.

The guiding principle is simple: **stability over performance, and performance over features.**

## Highlights

| 🧰 Familiar by design | 🔐 Hardened and private | 🧩 Made to be extended |
| :--- | :--- | :--- |
| The Asuswrt interface you already know, with AiMesh, Adaptive QoS, and the stock setup flow. No learning curve, no radical redesign. | Updated third-party components, DNSSEC validation, DNS-over-TLS, per-client [DNS Director](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/DNS-Director), and advanced OpenVPN with policy-based routing and VPN Director. | [User scripts](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/User-scripts) and cron jobs, customizable config files, [Entware](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/Entware) packages, and [AMTM](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/AMTM) for installing community add-ons. |

## Repositories

| Repository | What it's for |
| :--- | :--- |
| [**asuswrt-merlin.ng**](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng) | The main development tree — enhanced Asuswrt firmware for current Asus routers. |
| [**asuswrt-merlin.ng-gnuton**](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng-gnuton) | A companion branch that extends Merlin support to more models, such as the DSL-AX82U, RT-AX82U, TUF-AX3000, and GT-BE98. |
| [**am-toolchains**](https://github.com/Asuswrt-Merlin/am-toolchains) | Cross-compilation toolchains used to build the firmware. |
| [**am-buildtools**](https://github.com/Asuswrt-Merlin/am-buildtools) | Helper scripts for setting up and running a build environment. |
| [**asuswrt-merlin.legacy**](https://github.com/Asuswrt-Merlin/asuswrt-merlin.legacy) | Archived legacy tree for older models (380.xx branch). |
| [**wsdd2**](https://github.com/Asuswrt-Merlin/wsdd2) · [**miniupnp**](https://github.com/Asuswrt-Merlin/miniupnp) | Forked components used by the firmware for network discovery and UPnP. |

## Install in three steps

1. **Check your model** — see the [supported devices list](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/Supported-Devices).
2. **Download the build** for your router from [asuswrt-merlin.net/download](https://www.asuswrt-merlin.net/download).
3. **Flash it** like a regular Asus firmware update. Your existing settings are preserved.

> Before upgrading, read the changelog for model-specific notes. A factory reset is recommended when moving across major firmware branches.

<details>
<summary><b>Supported models</b> (current builds)</summary>

**3006.102.x**
GT-BE19000AI · GT-BE98 Pro · RT-BE96U · RT-BE92U · RT-BE88U · RT-BE86U · RT-BE58 Go · ZenWiFi Pro XT12 · GT-AXE16000 · GT-AX11000 Pro · GT-AX6000 · RT-AX88U Pro · RT-AX86U Pro

**3004.388.x**
GT-AXE11000 · GT-AX11000 · RT-AX88U · RT-AX86U · RT-AX68U · RT-AX58U

Support varies by model and firmware branch. The [wiki](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki/Supported-Devices) is the authoritative list.

</details>

## Community & support

| | |
| :--- | :--- |
| 🌐 **Website** | [asuswrt-merlin.net](https://www.asuswrt-merlin.net) — news, downloads, and changelogs |
| 📖 **Documentation** | [Project wiki](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/wiki) — setup guides, features, and how-tos |
| 💬 **Community** | [SNBForums](https://www.snbforums.com/forums/asuswrt-merlin.42/) — support and discussion |
| 🐛 **Issues** | [GitHub Issues](https://github.com/Asuswrt-Merlin/asuswrt-merlin.ng/issues) — bug reports for the main tree |
| 📣 **Updates** | [Mastodon](https://fosstodon.org/@RMerlin) · [Bluesky](https://bsky.app/profile/asuswrt-merlin.net) · [X](https://x.com/RMerlinDev) |

---

<sub>Asuswrt-Merlin is an independent community project, not affiliated with or endorsed by Asus. Asus and Asuswrt are trademarks of ASUSTeK Computer Inc. Firmware is provided "as is", without warranty of any kind — flash at your own risk. Open-source components are distributed under the GNU GPL v2; some bundled components remain proprietary to Asus.</sub>
