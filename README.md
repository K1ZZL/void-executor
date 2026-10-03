# Void Executor v3.2 Ultimate

> Premium dark-themed Roblox script executor with AI script generation, ScriptBlox integration, and a built-in script hub.

![Version](https://img.shields.io/badge/version-3.2%20Ultimate-8a2be2)
![Platform](https://img.shields.io/badge/platform-Roblox-blue)
![Language](https://img.shields.io/badge/language-Luau-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## ✨ Features

- **Premium Dark UI** — deep black + neon purple accents, fully draggable and resizable
- **Key System** — simple license gate with session persistence
- **Executor Tab** — multi-line Luau editor with Execute, Clear, Save, and Load
- **ScriptBlox Integration** — search scripts via the public ScriptBlox API with preview
- **AI Script Generator** — powered by DeepSeek / Pollinations with local fallback templates
- **AI Chat / Fix / Explain** — ask questions, fix broken code, or get explanations
- **Script Hub** — one-click launch for Infinite Yield, Dark Dex, Rayfield and more, with local caching
- **Tools Tab** — FPS Booster, Rejoin, Server Hop, Admin Detector, Player Spy
- **Settings Tab** — 8 color themes, window transparency, AI provider selection
- **Script Roulette** — random script from ScriptBlox (Russian roulette for the brave)
- **Infinity Yield Button** — one click to load the official IY
- **Minimize / Restore** — collapse the window into a small draggable bar
- **Auto-Execute** — run saved scripts automatically after each respawn
- **Global Error Handler** — catches game errors and logs them to the built-in console
- **Config Persistence** — settings saved to `void_executor_config.json` in the executor folder
- **Notifications** — toast-style popups in the top-right corner
- **Stop All Scripts** — emergency button to disconnect all active script threads

---

## 🚀 Quick Start

### 1. Launch Roblox

Open any game. Make sure Roblox is running before injecting.

### 2. Open your executor

Use a supported Luau executor such as **Xeno**, **Wave**, **Solara**, or **Synapse**.

### 3. Attach and execute

Paste this one-liner into your executor and press **Execute**:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/K1ZZL/void-executor/main/VoidExecutor.lua"))()
