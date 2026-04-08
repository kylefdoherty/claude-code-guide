# Claude Code Presentation Flow

## 1. What is Claude Code?
- Simple definition: "An AI assistant that can read, write, and run code on your computer. You talk to it in plain English, and it does the technical work."
- Proper definition: "An agentic coding harness — the scaffolding that gives an AI agent the ability to do things on your machine: read files, write code, run commands, connect to external tools, and execute multi-step workflows autonomously."
- Quick explainer: LLM (the intelligence) → Agent (LLM + tools + execution) → Harness (the system that wires it all together)

## 2. Quick Desktop App Demo
- Show the familiar chat interface
- Transition: "But I actually work in the terminal. Let me show you why."

## 3. Demystifying the Terminal
- Show Terminal briefly, then iTerm2 (mention customization, link to the getting started guide)
- **Self-serve moment:** Open Claude desktop on one side, ask "How do I navigate the terminal?" — demonstrate you don't memorize commands, you just ask

## 3b. Installing & Launching Claude Code
- Tell them to ask Claude desktop how to install, then show the command (`brew install --cask claude-code`)
- Three launch modes:
  - `claude` — default, asks permission for everything. Safest starting point.
  - `claude --permission-mode auto` — the sweet spot. Runs autonomously but blocks dangerous operations.
  - `claude --dangerously-skip-permissions` — no guardrails. Name is intentionally scary. Only for throwaway environments.

## 4. Why I Use the CLI Over Desktop
- Multiple terminals open — parallel workstreams
- Background agents / sub-agents — kick off a task and keep working
- Piping and chaining — feed output between Claude and other tools (big for data work)
- Already in the project directory — no uploading or context-switching
- Lighter weight / way faster than co-work

## 5. Two Types of Projects I Use Claude Code For

### Type A: Daily Co-pilot — Skills Learning Site
- Show how I use Claude Code as a day-to-day co-pilot
- Demo: creating a skills learning site (similar to the Claude Code getting started guide we built)
- Focus on showing how skills work and how to use them effectively

### Type B: Building Code — Outbound Dashboard
- **Cooking show style:** show the finished outbound dashboard first, then walk through how it was built
- Methodology: spike → plan → break into pieces (front-end first, then data model, then back-end)
- Live element: create a new front-end for the project

---

## Resources Built
- **Getting started guide:** https://kylefdoherty.github.io/claude-code-guide/
- **Repo:** https://github.com/kylefdoherty/claude-code-guide
- **LinkedIn post:** drafted and ready to publish with broken link format

## Key Definitions Developed
- **AI Agent:** What happens when you give an LLM access to tools and the ability to execute
- **Harness:** The system that defines what tools the agent can use, what permissions it has, what integrations it connects to, how it retains memory
- **Harness Engineering:** Configuring and optimizing the harness layer — instructions, tools, permissions, memory, workflows. The evolution of prompt engineering.
