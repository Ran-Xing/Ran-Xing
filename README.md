<div align="center">

![Banner](2022-07-06%2023.52.23.png)

### Hi there, I'm 星冉 (Ran-Xing / XRSec) 👋

**AI Agent Infrastructure Builder · Security Engineer · Cross-Platform Developer**

![Ran-Xing](https://img.shields.io/badge/Ran--Xing-XRSec-da282a?style=flat-square&logo=github)
![Motto](https://img.shields.io/badge/低调求发展-潜心习安全-da282a?style=flat-square)
[![Org](https://img.shields.io/badge/Lab-@XRSec-0f172a?style=flat-square&logo=github)](https://github.com/XRSec)
[![Email](https://img.shields.io/badge/Email-Jalapeno1868@outlook.com-da282a?style=flat-square&logo=minutemailer&logoColor=white)](mailto:Jalapeno1868@outlook.com)
[![Blog](https://img.shields.io/badge/Blog-xrsec.vercel.app-da282a?style=flat-square&logo=vercel)](https://xrsec.vercel.app)

</div>

---

### 🧠 近期焦点与工程方向 (What I'm Working On)

- 🔭 **多 Agent 运行时与上下文工程**：深度打磨 **Claude Code / Pi / Antigravity (`agy`) / Codex / Paseo / Cindy** 跨工具协同生态，专注于 **System Prompt 压缩优化**（[`pi-prompt-diet`](https://github.com/XRSec/pi-prompt-diet)）、**长会话 Prompt Cache 命中率治理**、**跨 Runtime 统一记忆层**以及**原生 Plugin/Skill 标准化**。
- 🤖 **Local-First 个人数字分身与通信智能体**：构建基于 **MCP (Model Context Protocol)** 的多平台身份图谱、会话记忆与受控回复引擎（[`Yance`](https://github.com/XRSec/Yance)、[`wx-cli`](https://github.com/Ran-Xing/wx-cli)），推动 IM/社交通信工具与 AI Agent 的安全契约定义。
- ⚡ **LLM 网关与桌面/移动底层基建**：使用 **Rust / Go / Swift / Tauri v2 / Kotlin** 打造高性能 API 网关（[`antigravity-gemini-gateway`](https://github.com/XRSec/antigravity-gemini-gateway)）、AI 进程守护管理器（[`AI-Agent-Launcher`](https://github.com/XRSec/AI-Agent-Launcher)）、桌面 MCP 桥接器（[`Aura`](https://github.com/XRSec/Aura)）以及移动端跨设备控制（[`Screen-Remote`](https://github.com/XRSec/Screen-Remote) `★206`、[`DFU-Tools`](https://github.com/XRSec/DFU-Tools) `★53`）。
- 🛡️ **安全与隐私工程**：坚持最小权限与默认零污染原则，构建自托管密码服务（[`nodewarden`](https://github.com/Ran-Xing/nodewarden)）、防误删工具（[`SAFE_DELETE`](https://github.com/XRSec/SAFE_DELETE)）与多 Profile 强隔离网络环境。

---

### 🔥 代表性开源项目 (Selected Projects @ [XRSec](https://github.com/XRSec) & [Ran-Xing](https://github.com/Ran-Xing))

- **[XRSec/Screen-Remote](https://github.com/XRSec/Screen-Remote)** `★206` — 将 `scrcpy` 移植至移动端，支持在 Android 手机上远程控制其他 Android 设备，配套 [`adbd-auth-gateway`](https://github.com/XRSec/adbd-auth-gateway) (Rust) 与 [`wifi-adb`](https://github.com/XRSec/wifi-adb) (Kotlin)。
- **[XRSec/AWVS-Update](https://github.com/XRSec/AWVS-Update)** `★226` — 安全扫描器容器化维护与规则更新套件。
- **[XRSec/DFU-Tools](https://github.com/XRSec/DFU-Tools)** `★53` — macOS 原生 (`Swift`) 硬件辅助工具，支持 Apple Silicon、T2 与 iOS/iPadOS 设备的 DFU、恢复与修复。
- **[XRSec/Yance](https://github.com/XRSec/Yance)** `★12` — Local-first 个人关系与通信 AI 大脑（Swift + MCP），涵盖多平台身份图谱、关系记忆与受控自动回复。
- **[XRSec/TunnelFlow](https://github.com/XRSec/TunnelFlow)** `★8` — 下一代跨平台 SSH 隧道与端口转发可视化管理器 (macOS · Windows · Linux)。
- **[XRSec/AI-Agent-Launcher](https://github.com/XRSec/AI-Agent-Launcher)** — 基于 Tauri v2 + Vue 3 + Rust 的跨平台 AI Agent 与本地服务进程管理器。
- **[XRSec/antigravity-gemini-gateway](https://github.com/XRSec/antigravity-gemini-gateway)** — 纯 Go 高性能 Gemini REST 网关，支持 Session Sticky 保障 Prompt Caching 与多账号代理池隔离。
- **[XRSec/pi-prompt-diet](https://github.com/XRSec/pi-prompt-diet)** `★5` & **[pi-session-distill](https://github.com/XRSec/pi-session-distill)** — Pi Coding Agent 提示词瘦身（削减 60%+ 基础 Token）与会话状态蒸馏交接套件。
- **[Ran-Xing/nodewarden](https://github.com/Ran-Xing/nodewarden)** & **[wx-cli](https://github.com/Ran-Xing/wx-cli)** — 运行于 Cloudflare Workers 的 Bitwarden 兼容服务端，以及 macOS 本地数据库解密与检索 CLI。

---

### 🌐 开源社区共建与架构提案 (Recent Community Contributions)

活跃于 AI Coding Agent、桌面自动化与记忆网络社区，近期深度参与以下开源项目的 Issue 诊断、PR 贡献与 RFC 架构探讨：

- **AI Agent 运行时与多端协同**：[`makecindy/cindy`](https://github.com/makecindy/cindy)（Prompt Cache 前缀保护、跨 Runtime 记忆继承、守护进程化常驻、移动端插件化瘦身）、[`getpaseo/plugins`](https://github.com/getpaseo/plugins)（贡献 `paseo-session-ids` 插件）、[`lbjlaq/Antigravity-Manager`](https://github.com/lbjlaq/Antigravity-Manager)（Headless 热更新修复、Gemini 鉴权与 `agy` CLI 指南）。
- **记忆网络与原生插件生态**：[`nowledge-co/nowledge-mem`](https://github.com/nowledge-co/nowledge-mem)（子智能体会话导入与 Hook 兼容性排查）、[`jnMetaCode/superpowers-zh`](https://github.com/jnMetaCode/superpowers-zh)、[`trycua/cua`](https://github.com/trycua/cua)、[`moeru-ai/auv`](https://github.com/moeru-ai/auv)、[`citrolabs/ego-lite`](https://github.com/citrolabs/ego-lite)。
- **Agent 通信契约与安全边界**：与 [`pandorafuture/wx-cli`](https://github.com/pandorafuture/wx-cli)、[`WecomTeam/wecom-cli`](https://github.com/WecomTeam/wecom-cli)、[`fancyboi999/goofish-cli`](https://github.com/fancyboi999/goofish-cli) 等项目共同探讨面向 Agent 的即时通讯会话契约与确认发送边界。

---

### 📊 GitHub 统计 (Statistical Data)

<div align="center">

![XRSec's GitHub top-langs](https://github-stats-extended.vercel.app/api/top-langs/?username=RAN-XING&layout=compact&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR&show_icons=true)
![XRSec's GitHub stats](https://github-stats-extended.vercel.app/api?username=RAN-XING&count_private=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR)

</div>
