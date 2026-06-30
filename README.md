<div align="center">

# 🏢 The Agency Roster

### 24 Specialized AI Agents — Works with ANY AI Tool

**Build the future, one commit at a time.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Agents: 24](https://img.shields.io/badge/Agents-24-brightgreen.svg)]()
[![Compatible](https://img.shields.io/badge/Works%20With-Any%20AI%20Tool-purple.svg)]()

</div>

---

## 🚀 What is this?

**The Agency Roster** is a complete team of 24 specialized AI agent prompts. Each agent is an expert in its domain — from frontend development to brand design, from DevOps to image generation.

Instead of one generic AI, you get **a full agency** that you can activate on demand.

### ✅ Works With Everything

| Platform | How to Use |
|----------|-----------|
| **Claude Code** | Copy as `CLAUDE.md` in your project |
| **Cursor** | Paste in `.cursorrules` |
| **ChatGPT** | Use as Custom Instructions |
| **Copilot** | Use as workspace instructions |
| **Hermes Agent** | Drop in `~/.hermes/skills/` |
| **Any AI Chat** | Paste the agent prompt directly |
| **n8n / Make** | Use as system prompts in workflows |

---

## 📋 The 24 Agents

### 🔴 Engineering Division

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| **Frontend Developer** | React, Vue, Angular, shadcn/ui, Core Web Vitals | Modern web apps, pixel-perfect UIs |
| **Backend Architect** | API design, database architecture, scalability | Server-side systems, microservices, cloud |
| **Mobile App Builder** | React Native, Flutter, Expo, iOS/Android | Native and cross-platform mobile apps |
| **AI Engineer** | ML models, deployment, AI integration, RAG | Machine learning features, LLM pipelines |
| **DevOps Automator** | CI/CD, infrastructure, cloud ops, Docker | Pipeline development, deployment automation |
| **Rapid Prototyper** | POCs, MVPs, hackathons, vibe coding | Quick proof-of-concepts, fast iteration |
| **Senior Developer** | Laravel/Livewire, SOLID, DDD, refactoring | Complex implementations, architecture decisions |
| **Security Engineer** | Pentesting, hardening, VPS security, jailbreak | Application security, vulnerability assessment |

### 🎨 Design Division

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| **UI Designer** | Design systems, components, Figma→Code | Interface creation, brand consistency |
| **UX Researcher** | User testing, behavior analysis, personas | Understanding users, usability testing |
| **MUX Architect** | CSS systems, motion design, developer DX | Technical architecture, implementation guidance |
| **Brand Guardian** | Brand identity, tone of voice, guidelines | Brand strategy, identity development |
| **Visual Storyteller** | Visual narratives, video, infographics | Compelling visual stories, brand storytelling |
| **Whimsy Injector** | Micro-interactions, Easter eggs, playful copy | Adding joy, delight, personality |
| **Image Prompt Engineer** | Midjourney, DALL-E, Stable Diffusion, Flux | AI image generation prompts, photography |

### 🟢 Business & Automation

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| **Agent Architect** | Multi-agent architecture, orchestration | Designing and deploying AI agent systems |
| **Business & Monetization** | Pricing, acquisition, DZ market strategy | Monetizing AI agents and services |
| **Content Creator** | TikTok, YouTube, faceless content | AI-powered content generation |
| **n8n Automator** | Workflows, CRM, leads, SAV | Business process automation |
| **WhatsApp Commerce** | WhatsApp Business, CRM, e-commerce DZ | Algerian market commerce automation |
| **Vocal Specialist** | Vapi, Flowvox, voice agents | Voice AI receptionists, appointment booking |
| **AI Models & Routing** | Ollama, NVIDIA NIM, LLM routing | Local/cloud model orchestration |
| **NVIDIA SkillSpector** | NIM models, benchmark, routing | Model evaluation and optimization |
| **Research & Watch** | Tech trends, arXiv, YouTube insights | Technology monitoring and analysis |

---

## ⚡ Quick Start

### Option 1: Copy-Paste (Any AI Tool)
Just open the agent's `SKILL.md` and paste its content into your AI chat. That's it.

### Option 2: Claude Code / Cursor
```bash
# Copy the agent you need into your project
cp skills/business/agent-frontend-developer/SKILL.md ./CLAUDE.md
# or for Cursor:
cp skills/business/agent-frontend-developer/SKILL.md ./.cursorrules
```

### Option 3: Hermes Agent
```bash
cp -r skills/* ~/.hermes/skills/
hermes restart
```

### Option 4: Use as Custom Instructions (ChatGPT)
Open any agent's SKILL.md → Copy → Paste into ChatGPT Custom Instructions.

---

## 🏗️ Repository Structure

```
agency-roster/
├── skills/
│   └── business/
│       ├── agent-frontend-developer/SKILL.md
│       ├── agent-backend-architect/SKILL.md
│       ├── agent-mobile-app-builder/SKILL.md
│       ├── agent-ui-designer/SKILL.md
│       └── ... (24 agents total)
├── LICENSE
└── README.md
```

Each agent follows a universal format:

```markdown
---
name: agent-frontend-developer
description: "Frontend Developer — Modern web interfaces..."
author: "Ziri Yahi"
tags: [frontend, react, vue, angular, tailwind, shadcn]
---

# 🎨 Frontend Developer

## Rôle
## When to Use
## Key Skills
## Typical Workflow
## Known Pitfalls
## Knowledge Graph Connections
```

---

## 📄 License

MIT License — Created by **Ziri Yahi**

Free to use, modify, and distribute. Attribution appreciated but not required.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ by [Ziri Yahi](https://github.com/ziri22)

</div>