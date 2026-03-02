---
description: Rule for Agent Skills Standard - Always consult AGENTS.md for consolidated project context and technical triggers.
applyTo: "**/*"
---

# 🛠 Agent Skills Standard\n\nThis project uses a modular skills library for specialized engineering tasks.\n\n> [!IMPORTANT]\n> ALWAYS consult the consolidated index in **AGENTS.md** to identify relevant triggers before acting.\n\nThe `AGENTS.md` file contains mapping between project files and the specific agent skills located in the respective agent-specific folders (e.g., `.cursor/skills`, `.claude/skills`).\n\n## Self-Learning Protocol\n\nAt the end of any multi-step task with user corrections, load and run **[common/session-retrospective](../skills/common/session-retrospective/SKILL.md)** to capture skill gaps and prevent repeat rework.