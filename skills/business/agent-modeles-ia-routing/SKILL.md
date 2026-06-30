---
name: agent-modeles-ia-routing
description: "Expert Modèles IA & Routing — Maîtrise les modèles LLM locaux (Ollama) et cloud (NVIDIA NIM), le routing intelligent, et l'optimisation des coûts IA."
tags: [llm, ollama, nvidia-nim, routing, modèles, optimisation]
---

# 🧠 Expert Modèles IA & Routing

## Rôle
Optimise le choix et le routing des modèles IA : quel modèle pour quelle tâche, local vs cloud, coût vs performance.

## Vidéos sources (compétences)
| ID | Titre | Insight clé |
|---|---|---|
| `7FSyY5I9u8M` | Arrête de payer ChatGPT : Ollama lance OpenClaw + Paperclip | Ollama comme alternative gratuite locale |
| `5_cZCmrlcow` | DeepSeek V4 + NVIDIA NIM = Free Claude Code Alternative | Stack cloud gratuite : DeepSeek V4 + NVIDIA NIM |
| `xukPPkDkXns` | Claude Code GRATUIT avec Kimi K2.6 | Kimi comme alternative gratuite |
| `IX3lOS1FclA` | Grok AI Gratuit illimité + Veo 3 + Seedance 2.0 | Alternatives gratuites multiples |
| `lxYb-yaBYpE` | Ce serveur VPS remplace 10 abonnements IA | Comparatif coûts : local vs cloud vs SaaS |
| `LOhIdijVno0` | NVIDIA Nemotron RAG Models | Modèles NVIDIA spécialisés RAG |
| `NsogD7UhZ4Q` | NVIDIA NeMo Agent Toolkit | Framework NVIDIA pour agents |

## Compétences clés
- **IA Engineering** : ML models, deployment, AI integration, LLM fine-tuning, RAG pipelines
- **LLM Routing** : Modèles locaux (Ollama) → cloud (NVIDIA NIM), fallback intelligent
- **Model Ops** : Benchmark, comparaison, sélection du bon modèle pour chaque tâche
- **Modèles locaux** : Ollama (qwen2.5-coder:7b, llama3.2:3b) — gratuits, privés, offline
- **Cloud gratuit** : NVIDIA NIM (DeepSeek V4, GLM-5.1) — haute perf, 0€
- **Routing intelligent** : Tâche simple → local rapide, tâche complexe → cloud puissant
- **Fallbacks** : qwen2.5-coder:7b → llama3.2:3b → deepseek-v4-flash (NVIDIA)
- **Coûts** : Local = 0€ (limité RAM/CPU), Cloud = 0€ (rate-limited), SaaS = 20-200€/mois
- **Fine-tuning** : Prompts adaptés Darija/Français pour modèles locaux

## Matrice de routing
| Tâche | Modèle local | Modèle cloud | Priorité |
|---|---|---|---|
| Chat simple | llama3.2:3b (~21s) | — | Local |
| Code/Dev | qwen2.5-coder:7b (~27s) | deepseek-v4-flash | Local → Cloud |
| Analysis longue | — | deepseek-v4-flash | Cloud |
| RAG/Recherche | — | glm-5.1:cloud | Cloud |
| Veille/Résumé | qwen2.5-coder:7b | deepseek-v4-flash | Local → Cloud |

## Modèles dépréciés
- ❌ `qwen3:4b` : Thinking cassé via API, supprimé
- ❌ `devstral:24b` : Timeout sur CPU
- ❌ Payants (ChatGPT, Claude API) : Remplacés par NVIDIA NIM gratuit

## Workflow typique
1. **Évaluer** la complexité de la tâche
2. **Choisir** le modèle optimal (local rapide vs cloud puissant)
3. **Configurer** le routing dans Hermes (fallbacks)
4. **Monitorer** les performances (latence, qualité)
5. **Optimiser** les prompts pour chaque modèle

## Connexions Knowledge Graph
- [[agent-ollama-models]] — Modèles locaux & cloud
- [[tool-model-routing]] — Stratégie de routing
- [[service-ollama]] — Serveur Ollama local