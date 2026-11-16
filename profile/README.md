<p align="center">
  <img src="https://raw.githubusercontent.com/pixie-agent/pixie/main/src-tauri/icons/icon.png" width="112" alt="Pixie Agent logo" />
</p>

<h1 align="center">Pixie Agent</h1>

<p align="center">
  <b>An ecosystem of autonomous AI agents.</b><br/>
  <i>A pluggable desktop workspace · an Android workspace · a single-binary Rust coding agent · an AI app generator.</i>
</p>

<p align="center">
  <img alt="Public repositories" src="https://img.shields.io/badge/repositories-4-6c63ff?style=for-the-badge&logo=github" />
  <img alt="Primary language" src="https://img.shields.io/badge/Rust_%2B_TypeScript-Tauri_v2-6c63ff?style=for-the-badge" />
  <img alt="Focus" src="https://img.shields.io/badge/focus-autonomous_agents-6c63ff?style=for-the-badge" />
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT%20%E2%80%A2%20PolyForm-6c63ff?style=flat-square" />
  <img alt="Status" src="https://img.shields.io/badge/status-actively%20developed-6c63ff?style=flat-square" />
</p>

---

## ✨ The projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/pixie-agent/pixie">🪄 pixie</a></h3>
      <p>A <b>native desktop workspace for pluggable AI agents</b>. Run Claude Code, Cursor Agent or CodeBuddy against any folder, swap engines per session, and watch them work in real time — with a built-in knowledge base and scheduled tasks.</p>
      <p>
        <img alt="Stars" src="https://img.shields.io/github/stars/pixie-agent/pixie?style=flat-square&color=6c63ff" />
        <img alt="License" src="https://img.shields.io/github/license/pixie-agent/pixie?style=flat-square" />
        <img alt="Language" src="https://img.shields.io/github/languages/top/pixie-agent/pixie?style=flat-square&color=9a93ff" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/pixie-agent/pixie-app">📱 pixie-app</a></h3>
      <p><b>Pixie for Android</b> — a native AI agent workspace with a built-in engine, knowledge base and scheduled tasks, shipped as an Android app.</p>
      <p>
        <img alt="Stars" src="https://img.shields.io/github/stars/pixie-agent/pixie-app?style=flat-square&color=6c63ff" />
        <img alt="License" src="https://img.shields.io/github/license/pixie-agent/pixie-app?style=flat-square" />
        <img alt="Language" src="https://img.shields.io/github/languages/top/pixie-agent/pixie-app?style=flat-square&color=9a93ff" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/pixie-agent/pixie-pi">⚡ pixie-pi</a></h3>
      <p>An <b>autonomous, tool-using AI coding agent in a single static Rust binary</b> — one-shot CLI and interactive REPL, no runtime dependencies. The agent core that powers the Pixie apps.</p>
      <p>
        <img alt="Stars" src="https://img.shields.io/github/stars/pixie-agent/pixie-pi?style=flat-square&color=6c63ff" />
        <img alt="License" src="https://img.shields.io/github/license/pixie-agent/pixie-pi?style=flat-square" />
        <img alt="Language" src="https://img.shields.io/github/languages/top/pixie-agent/pixie-pi?style=flat-square&color=9a93ff" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/pixie-agent/forge">🏗️ forge</a></h3>
      <p>An <b>open-source AI app generator</b> — describe an app in natural language and Forge plans, writes and builds a multi-file React app with a real backend (D1/KV/R2/DO). <a href="https://app.1forgen.site">Live instance →</a></p>
      <p>
        <img alt="Stars" src="https://img.shields.io/github/stars/pixie-agent/forge?style=flat-square&color=6c63ff" />
        <img alt="License" src="https://img.shields.io/badge/license-PolyForm%20Noncommercial-9a93ff?style=flat-square" />
        <img alt="Language" src="https://img.shields.io/github/languages/top/pixie-agent/forge?style=flat-square&color=9a93ff" />
      </p>
    </td>
  </tr>
</table>

## 🧭 How they fit together

| | What it is | Runs on |
|---|---|---|
| **pixie-pi** | The agent engine — an autonomous, tool-using agent loop in one Rust binary | CLI · REPL · embedded |
| **pixie** | Desktop shell that drives *pluggable* agent CLIs (Claude Code / Cursor / CodeBuddy) | macOS · Windows · Linux |
| **pixie-app** | The same workspace with a *built-in* engine, in your pocket | Android |
| **forge** | Uses the agent to build and host full AI apps from a prompt | Cloudflare + Cloud Run |

## 🚀 Quick start

```bash
# The desktop workspace
git clone https://github.com/pixie-agent/pixie

# The single-binary agent
git clone https://github.com/pixie-agent/pixie-pi

# The Android workspace
git clone https://github.com/pixie-agent/pixie-app

# The AI app generator
git clone https://github.com/pixie-agent/forge
```

## 🤝 Contributing

We welcome issues, PRs and ideas. Every repository has its own `CONTRIBUTING.md` — start there, and please read the [Code of Conduct](https://github.com/pixie-agent/forge/blob/main/CODE_OF_CONDUCT.md).

<hr/>

<p align="center">
  <sub>🧚 Built with <b>Rust</b>, <b>TypeScript</b> and <b>Tauri v2</b> · Autonomous agents, real tools, real files.</sub>
</p>

<p align="center">
  <sub>✨ Pixie Agent —— 自主 AI 智能体生态：桌面工作台、安卓工作台、单文件 Rust 编程智能体，以及 AI 应用生成器。欢迎 Star、Fork 和贡献！</sub>
</p>
