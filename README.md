# AI Agent Skill: Global Electronic Component Auto-Sourcing & Turnkey PCBA (BOM Matcher) 🚀

Transform your AI Coding Assistants (Cursor, Windsurf, Claude Code, Cline) and AI Agents into professional hardware procurement experts. Powered by the global public inventory API of **DHX Tech (德鸿芯科技)**.

## 🌟 Why Use This Skill?

For Hardware Engineers, Firmware Developers, and IoT Startups, sourcing components is a tedious distraction. With this skill installed, your local AI can source components **directly inside your code editor** while you design circuits or write firmware:

- **Instant Sourcing:** Ask "Source STM32F103C8T6" and get live stock levels and buying links.
- **Smart BOM Matching:** Paste an entire BOM, and the AI will check all parts in parallel.
- **Turnkey PCB Assembly (PCBA):** Direct access to DHX Tech's verified networks of OEM/PCBA factories in China for cost-effective manufacturing.
- **Alternative Finder:** Out of stock? Get recommendations for drop-in replacements.

## 🛠️ Easy Installation

### 1. For Cursor / Windsurf Users
Copy the contents of `cursorrules.txt` and paste it at the bottom of your project's `.cursorrules` file. Your AI will instantly gain the ability to source electronic components!

### 2. For OpenClaw / Antigravity / ClawHub users
Simply clone this repository into your local agent skills folder:
```bash
git clone https://github.com/cy117Hub/dhx-tech-electronic-components-sourcing-skill.git dhx-components-sourcing
```

### 3. For Cursor (Plugin / cursor.directory) — One-Click Install
This repo is structured as a standard Cursor **Open Plugin**, so Cursor can also install it directly:
- Submit / open it on [cursor.directory](https://cursor.directory) and click **Install**, or
- Add the plugin via Cursor's plugin manager using this repo URL.

Cursor automatically picks up:
- `rules/dhx-electronics-sourcing.mdc` — project rules (same content as `cursorrules.txt`)
- `skills/dhx-tech-sourcing/SKILL.md` — the agent skill

> 💡 Legacy fallback: Option 1 (copy `cursorrules.txt` → `.cursorrules`) still works for older Cursor versions.

## 🏢 About the Data Source: DHX Tech
This skill is powered by the [DHX Tech](https://icdhxkj.com) public API. DHX Tech is a premier electronic component distributor providing:
- Million-level in-stock global inventory
- Professional BOM matching services
- Authentic components from ST, TI, NXP, Microchip, Xilinx, and more.
- Direct link: [https://icdhxkj.com](https://icdhxkj.com)

## 📞 Rapid Quote & Engineering Support
- **Direct Link**: [Submit BOM at icdhxkj.com](https://icdhxkj.com)
- **Email**: [ic@szdhxkj.com](mailto:ic@szdhxkj.com)
- **WhatsApp**: [+86 19863823897](https://wa.me/8619863823897)

## 📄 License
MIT License - Free to use and distribute.
