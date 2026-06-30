<div align="center">

# 🏢 The Agency Roster

### 24 AI Agent Skills for Hermes Agent

**Build the future, one commit at a time.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills: 24](https://img.shields.io/badge/Skills-24-brightgreen.svg)]()
[![Hermes Agent](https://img.shields.io/badge/Powered%20by-Hermes%20Agent-purple.svg)](https://hermes-agent.nousresearch.com)

</div>

---

## 🚀 What is this?

**The Agency Roster** is a complete team of 24 specialized AI agent skills for [Hermes Agent](https://hermes-agent.nousresearch.com). Each agent is an expert in its domain — from frontend development to brand design, from DevOps to image generation.

Instead of one generic AI, you get **a full agency** that you can activate on demand.

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
| **Kittle Code Intelligence** | Repo analysis, Mermaid diagrams, multi-model | Code intelligence and architecture |

## ⚡ Quick Start

### Install All Agents

```bash
# Clone the roster
git clone https://github.com/ziri22/agency-roster.git

# Copy all skills to your Hermes skills directory
cp -r agency-roster/skills/* ~/.hermes/skills/

# Restart Hermes to load new skills
hermes restart
```

### Install a Single Agent

```bash
# Just copy the agent you need
cp -r agency-roster/skills/business/agent-frontend-developer ~/.hermes/skills/business/
```

### Use in Hermes

Just mention the agent's specialty in your prompt:

```
"Design a landing page for my SaaS"  → UI Designer activates
"Set up CI/CD for my project"        → DevOps Automator activates
"Create a mobile app for delivery"   → Mobile App Builder activates
```

## 🏗️ Architecture

```
agency-roster/
├── skills/
│   └── business/
│       ├── agent-frontend-developer/SKILL.md
│       ├── agent-backend-architect/SKILL.md
│       ├── agent-mobile-app-builder/SKILL.md
│       ├── agent-ui-designer/SKILL.md
│       ├── ... (24 agents total)
│       └── agent-image-prompt-engineer/SKILL.md
├── LICENSE
└── README.md
```

Each agent follows the standard Hermes SKILL.md format:

```yaml
---
name: agent-frontend-developer
description: "Frontend Developer IA — Expert en interfaces web modernes..."
author: "Ziri Yahi"
tags: [frontend, react, vue, angular, tailwind, shadcn]
---

# 🎨 Frontend Developer IA
## Rôle, Compétences, Workflow, Pièges connus, Connexions
```

## 🛠️ Requirements

- [Hermes Agent](https://hermes-agent.nousresearch.com) installed
- Python 3.10+
- Ollama (for local models) or NVIDIA NIM (for cloud)

## 📄 License

MIT License — Created by **Ziri Yahi**

Free to use, modify, and distribute. Attribution appreciated but not required.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ by [Ziri Yahi](https://github.com/ziri22)

</div>