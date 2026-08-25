🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎉 Soc Ops

### The Social Bingo Game That Breaks the Ice

_Find people who match the prompts. Score a bingo. Make new friends._

[![Play Now](https://img.shields.io/badge/▶%20Play%20Now-0a7cff?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Lab Guide](https://img.shields.io/badge/📖%20Lab%20Guide-6c47ff?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![.NET 10](https://img.shields.io/badge/.NET-10-512bd4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WASM](https://img.shields.io/badge/Blazor-WASM-512bd4?style=for-the-badge&logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

</div>

---

## What Is Soc Ops?

**Soc Ops** is a browser-based social bingo game designed for in-person meetups, workshops, and team events. Each player gets a unique 5×5 bingo card filled with conversation prompts — _"Has lived in another country"_, _"Speaks more than two languages"_, _"Can code in three or more languages"_. Walk the room, find matches, and race to bingo.

> No app to install. No account required. Just open the link and play.

---

## ✨ Highlights

| | |
|---|---|
| 🃏 **Unique cards** | Every player gets a randomised bingo board |
| 💬 **Inclusive prompts** | Low-stakes, conversation-starting questions |
| 📱 **Mobile-friendly** | Runs in any browser, on any device |
| ⚡ **Instant deploy** | GitHub Pages CI/CD out of the box |
| 🧩 **Fully customisable** | Swap in your own questions in minutes |

---

## 🚀 Quick Start

**Option A — GitHub Codespaces (zero setup)**

1. Click **Use this template** → **Create a new repository**
2. Open your new repo → **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the devcontainer to finish, then:
   ```bash
   cd SocOps && dotnet run
   ```

**Option B — Local**

```bash
# Prerequisites: .NET 10 SDK
git clone <your-repo-url>
cd SocOps
dotnet run
```

Open [http://localhost:5000](http://localhost:5000) and start playing. 🎊

---

## 🛠 Build & Test

```bash
cd SocOps
dotnet build          # Compile
dotnet test           # Run tests
dotnet format         # Lint / format check
```

Pushes to `main` automatically deploy to **GitHub Pages**.

---

## 🧪 This Is Also a Copilot Lab

Soc Ops doubles as a hands-on lab for **GitHub Copilot agent-mode** in VS Code. Work through the parts below to experience context engineering, design-first development, custom agents, and multi-agent workflows — all on a real Blazor app.

| Part | Title | What you'll do |
|:----:|-------|----------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | Understand the lab structure |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | Wire up AGENTS.md and instructions |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | Redesign the UI with Copilot |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master Agent | Build a specialised Copilot agent |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Orchestrate multiple agents together |

> 📝 Offline versions of all guides live in [`workshop/`](workshop/).

---

## 🤝 Contributing

Contributions are welcome! Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR, and please follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

<div align="center">
Made with ☕ and Blazor · Deploys to GitHub Pages · <a href="LICENSE">MIT License</a>
</div>
