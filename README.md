
# 🧠 Tiny Agents — An Agent for Every Purpose

Tiny Agents is a lightweight framework that brings specialized AI agents directly into your development **environment**.
Each agent is built for a distinct task — from refactoring code to writing documentation or generating commit messages — all accessible from within VS Code or your CLI.

# 🚀 Features

⚙️ Plug-and-play Agents — Easily install and use purpose-built agents.

💬 Context-aware — Works directly with your current codebase, detecting language and framework.

🧩 Customizable — Extend or create your own agents for specialized workflows.

🔍 VS Code Integration — Run, configure, and view agent results seamlessly.

⚡ Lightweight — No server setup or heavyweight dependencies.


# 🧩 Installation

You can install Tiny Agents as a dev dependency:

```
npm install -D tiny-agents
```


Note: Make sure you have Node.js v18+ and npm v9+ installed.

# ⚙️ Configuration

Tiny Agents integrates smoothly with your existing VS Code workspace through a simple JSON-based configuration. This setup allows you to register and load your agents automatically whenever your project opens — no additional tooling required.

### 🧰 Configure the Workspace Settings

To enable Tiny Agents in VS Code, you need to update your workspace settings file (.vscode/settings.json).
This tells VS Code where to locate and activate the available agent definitions.

```
{
  "chat.modeFilesLocations": {
    "node_modules/tiny-agents/agents": true
  }
}
```

### 🔍 Explanation

chat.modeFilesLocations — This is the setting VS Code uses to locate mode or agent definition files that extend its AI chat capabilities.

node_modules/tiny-agents/agents — The path points to the folder inside your project where Tiny Agents stores its predefined agent scripts.

true — Enables VS Code to load all the .mode or .agent files from that directory automatically.

Once this is configured, VS Code can discover all Tiny Agents and make them accessible directly within the Command Palette, Chat sidebar, or inline chat panels.

# ▶️ Running an Agent



# 📜 List of Agents


