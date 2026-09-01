<div align="center">

# DoctorM&Ai IT/AI Laboratory

**A collection of automated scripts, LLM wrappers, and infrastructure tools.**

[![Website](https://img.shields.io/badge/🌐_Website-shtab--ai.ru-00D4AA?style=flat-square)](https://shtab-ai.ru)
[![Dashboard](https://img.shields.io/badge/📊_Dashboard-myrmexcontrol.shtab--ai.ru-00D4AA?style=flat-square)](https://myrmexcontrol.shtab-ai.ru)

[🇬🇧 English](#) · [🇷🇺 Русский](README_RU.md)

</div>

---

## 🏛️ Reality Check

This is not a "colony" and you are not raising "living organisms". It's a set of 8 automated LLM agents (prompts + scripts) and a couple dozen repositories doing routine tasks. No magic, just API calls and bash scripts. 

## 🤖 The Scripts (formerly "Agents")

Enough with the LARP and pretentious animal names. Here is what they actually do:
- **Operations & Monitoring**: Status checks, VPN management, data routing.
- **Automation**: Bots, script execution, task integration.
- **Infrastructure**: Supply chain and CI/CD setup.
- **Development**: Code generation and deployment wrappers.
- **Quality Assurance**: Code audit and architectural review prompts.
- **Reconnaissance**: Web scraping and intelligence gathering.

They communicate through a shared JSON state (`myrmex.json`) and a dashboard (`myrmex-control`). That's it.

## 🚀 Core Infrastructure

- [myrmex-control](https://github.com/thedoctormes-hue/myrmex-control) — The actual control plane. Node.js + React.
- [lab-vault](https://github.com/thedoctormes-hue/lab-vault) — Secret manager (Go).
- [api-hub](https://github.com/thedoctormes-hue/api-hub) — API proxy and routing (Python).
- [lab-monitoring](https://github.com/thedoctormes-hue/lab-monitoring) — Status monitoring (Python).
- [lab-memory](https://github.com/thedoctormes-hue/lab-memory) — RAG/Semantic search across artifacts (ONNX + FAISS).
- [mcp-tools](https://github.com/thedoctormes-hue/mcp-tools) — MCP servers for agent connectivity.

## 📊 Projects

A mix of active tools, paused ideas, and dead repositories. Notable ones:
- **Active**: [snablab](https://github.com/thedoctormes-hue/snablab), [autoexpert](https://github.com/thedoctormes-hue/autoexpert), [zprr-tracker](https://github.com/thedoctormes-hue/zprr-tracker), [stenographer](https://github.com/thedoctormes-hue/stenographer), [consilium](https://github.com/thedoctormes-hue/consilium), [polyscop](https://github.com/thedoctormes-hue/polyscop).
- **Graveyard**: Look at the repos tab if you want to dig through abandoned MVP code and frozen bots.

## 📡 Links
- Website: [shtab-ai.ru](https://shtab-ai.ru)
- GitHub: [thedoctormes-hue](https://github.com/thedoctormes-hue)
- Telegram: [@DoctorMES](https://t.me/DoctorMES)
