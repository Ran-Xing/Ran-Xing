<div align="center">

![Banner](2022-07-06%2023.52.23.png)

### Hi there, I'm 星冉 (Ran-Xing / XRSec) 👋

**AI Agent Infrastructure Builder · Security Engineer · Cross-Platform Developer**

![Ran-Xing](https://img.shields.io/badge/Ran--Xing-XRSec-da282a?style=flat-square&logo=github)
![Motto](https:[REDACTED_PASSWORD]@XRSec-0f172a?style=flat-square&logo=github)](https://github.com/XRSec)
[![Email](https:[REDACTED_PASSWORD]@outlook.com-da282a?style=flat-square&logo=minutemailer&logoColor=white)](mailto:Jalapeno1868@outlook.com)
[![Blog](https://img.shields.io/badge/Blog-xrsec.vercel.app-da282a?style=flat-square&logo=vercel)](https://xrsec.vercel.app)

</div>

---

### 🧠 近期焦点与工程方向 (What I'm Working On)

- 🔭 **多 Agent 运行时与上下文工程**：深度打磨 **Claude Code / Pi / Antigravity (`agy`) / Codex / Paseo / Cindy** 跨工具协同生态，专注于 **System Prompt 压缩优化**（[`pi-prompt-diet`](https://github.com/XRSec/pi-prompt-diet)）、**长会话 Prompt Cache 命中率治理**、**跨 Runtime 统一记忆层**以及**原生 Plugin/Skill 标准化**。
- 🤖 **Local-First 个人数字分身与桌面智能体基建**：构建基于 **MCP (Model Context Protocol)** 的多平台身份图谱与受控回复引擎（[`Yance`](https://github.com/XRSec/Yance)）、跨平台 AI 进程守护管理器（[`AI-Agent-Launcher`](https://github.com/XRSec/AI-Agent-Launcher)）以及桌面安全桥接器（[`Aura`](https://github.com/XRSec/Aura)）。
- ⚡ **LLM 高性能网关与跨端远控/网络隧道**：使用 **Rust / Go / Swift / Tauri v2 / Kotlin** 打造纯 Go Gemini REST 网关（[`antigravity-gemini-gateway`](https://github.com/XRSec/antigravity-gemini-gateway)）、SSH 隧道编排工具（[`TunnelFlow`](https://github.com/XRSec/TunnelFlow)）以及移动端跨设备远控套件（[`Screen-Remote`](https://github.com/XRSec/Screen-Remote) `★206`、[`wifi-adb`](https://github.com/XRSec/wifi-adb)）。
- 🛡️ **安全与隐私工程**：坚持最小权限与默认零污染原则，构建运行于 Cloudflare Workers 的自托管密码服务（[`nodewarden`](https://github.com/Ran-Xing/nodewarden)）、防误删工具（[`SAFE_DELETE`](https://github.com/XRSec/SAFE_DELETE)）与零成本防盗刷全球混合图床架构。

---

### 🔥 近期核心开源项目 (Recent & Featured Projects @ [XRSec](https://github.com/XRSec) & [Ran-Xing](https://github.com/Ran-Xing))

- **[XRSec/AI-Agent-Launcher](https://github.com/XRSec/AI-Agent-Launcher)** — 基于 `Tauri v2` + `Vue 3` + `Rust` 的跨平台 AI Agent 与本地服务进程管理器 (macOS · Windows · Linux)。
- **[XRSec/Yance](https://github.com/XRSec/Yance)** `★12` — Local-first 个人关系与通信 AI 大脑（`Swift` + `MCP`），涵盖多平台身份图谱、关系记忆与受控自动回复。
- **[XRSec/TunnelFlow](https://github.com/XRSec/TunnelFlow)** `★8` — 下一代跨平台 SSH 隧道与端口转发可视化管理器 (macOS · Windows · Linux)。
- **[XRSec/antigravity-gemini-gateway](https://github.com/XRSec/antigravity-gemini-gateway)** — 纯 `Go` 高性能 Gemini REST 网关，支持 Session Sticky 粘性调度保障 Prompt Caching、CPA 代理池隔离与一键 OAuth。
- **[XRSec/pi-prompt-diet](https://github.com/XRSec/pi-prompt-diet)** `★5` & **[paseo-session-ids](https://github.com/XRSec/paseo-session-ids)** — Pi Coding Agent 提示词瘦身（削减 60%+ 基线 Token）与跨 CLI (`agy`/`claude`/`pi`/`codex`) 会话 ID 透视插件。
- **[XRSec/Screen-Remote](https://github.com/XRSec/Screen-Remote)** `★206` & **[wifi-adb](https://github.com/XRSec/wifi-adb)** `★3` — 移动端 `scrcpy` 跨设备远控及独立无线 ADB 调试工具（`Kotlin`，支持无障碍自动授权）。
- **[XRSec/DFU-Tools](https://github.com/XRSec/DFU-Tools)** `★53` & **[AWVS-Update](https://github.com/XRSec/AWVS-Update)** `★226` — macOS 原生 Apple Silicon/T2 设备 DFU 维护工具与安全扫描器容器化维护套件。
- **[Ran-Xing/nodewarden](https://github.com/Ran-Xing/nodewarden)** & **[XRSec/SAFE_DELETE](https://github.com/XRSec/SAFE_DELETE)** `★3` — Cloudflare Workers 轻量级 Bitwarden 服务端与 `Rust` 安全防误删命令行工具。

---

### 🌐 近一个月社区共建与架构提案 (Past Month Highlights)

活跃于 AI Coding Agent、桌面自动化与网络工具社区，近一个月深度参与以下开源项目的 PR 贡献、Bug 诊断与 RFC 架构探讨：

- **AI Agent 运行时与多端协同**：
  - [`makecindy/cindy`](https://github.com/makecindy/cindy)：定位动态上下文破坏 Prompt Cache 前缀导致命中率锁死问题（`#7349`）、提出跨 Runtime 统一记忆层与 `~/.pi` 继承 RFC（`#7379`）、守护进程化常驻架构（`#7347`）、安卓端插件化瘦身（`#7378`）、局域网直连发现（`#7216`）及 `ego-lite` 浏览器适配（`#7217`）。
  - [`getpaseo/paseo`](https://github.com/getpaseo/paseo) & [`getpaseo/plugins`](https://github.com/getpaseo/plugins)：贡献 `paseo-session-ids` 插件（`#1201`），反馈动态模型发现（`#6837`）与 Antigravity 会话重载/导入修复（`#6838`）。
  - [`lbjlaq/Antigravity-Manager`](https://github.com/lbjlaq/Antigravity-Manager) & [`google-antigravity/antigravity-cli`](https://github.com/google-antigravity/antigravity-cli)：撰写 `agy` CLI 深度指南（`#3686`），排查 Headless 模式配置热更新（`#3730`）、Gemini URL Query 鉴权拦截（`#3729`）、Beta 切换异常（`#3754`），并推动 API Key 与 OAuth 模式能力对齐（`#1322`）。
- **记忆网络与跨 CLI 原生插件标准化**：
  - [`nowledge-co/nowledge-mem`](https://github.com/nowledge-co/nowledge-mem) & [`community`](https://github.com/nowledge-co/community)：修复 `.claude-plugin/marketplace.json` 导致 Claude Desktop 插件被排除的问题（`#764`），定位子智能体会话导入（`#153`）与 PreToolUse Hook 兼容性问题（`#181`）。
  - 推动 `claude` / `codex` / `pi` / `agy` 原生插件安装体系与「前置消息整理与意图软路由」RFC：[`jnMetaCode/superpowers-zh#135`](https://github.com/jnMetaCode/superpowers-zh/issues/135)、[`trycua/cua#5736`](https://github.com/trycua/cua/issues/5736)、[`moeru-ai/auv#407`](https://github.com/moeru-ai/auv/issues/407)、[`citrolabs/ego-lite#538`](https://github.com/citrolabs/ego-lite/issues/538)、[`yetone/magpie#3304`](https://github.com/yetone/magpie/issues/3304)、[`farion1231/cc-switch#8714`](https://github.com/farion1231/cc-switch/issues/8714)。
- **跨平台桌面工具与开源生态贡献**：
  - [`luckjiawei/frpc-desktop#150`](https://github.com/luckjiawei/frpc-desktop/pull/150) & [`MoonProxyHQ/moonproxy-desktop#20`](https://github.com/MoonProxyHQ/moonproxy-desktop/issues/20)：提交从 Electron 重构至 Tauri v2 的轻量化 PR 与 macOS 托盘/热重载体验升级提案。
  - [`jaywcjlove/awesome-mac`](https://github.com/jaywcjlove/awesome-mac)：向多语言目录贡献 `AI-Agent-Launcher`（`#3116`）与 `TunnelFlow`（`#3226`）。

---

### 📊 GitHub 统计 (Statistical Data)

<div align="center">

![XRSec's GitHub top-langs](https://github-stats-extended.vercel.app/api/top-langs/?username=RAN-XING&layout=compact&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR&show_icons=true)
![XRSec's GitHub stats](https://github-stats-extended.vercel.app/api?username=RAN-XING&count_private=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR)

</div>
