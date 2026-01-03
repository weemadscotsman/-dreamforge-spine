# DREAMFORGE SPINE // v0.95 [CANDIDATE]

> **"Truth is not found; it is forged in the collapse of contradictions."**

![Status](https://img.shields.io/badge/STATUS-CANDIDATE_RELEASE-00f0ff?style=for-the-badge)
![Architecture](https://img.shields.io/badge/ARCH-6_ORGAN_BIOMECH-ff00ff?style=for-the-badge)
![Inference](https://img.shields.io/badge/INFERENCE-WEB_GPU_LOCAL-00ff9d?style=for-the-badge)

---

## 💀 SYSTEM IDENTITY

**Dreamforge Spine** is a recursive, multi-modal AI operating system designed for **autonomous reasoning**.

Unlike standard chat interfaces that optimize for speed or politeness, Spine optimizes for **epistemic rigor**. It wraps any LLM (Gemini, Llama, Claude, WebLLM) in a biological architecture that forces it to argue against itself, validate assumptions, and rewrite its own operating rules based on survival.

It features a **"Fever" Mechanic**: As the system encounters contradictions or adversarial pressure, the interface visually distorts (chromatic aberration, tremors), reflecting the cognitive load.

---

## 🚀 NEW IN v0.95

*   **BROWSER-NATIVE INFERENCE**: Run **Llama-3 8B** or **Phi-3.5** locally in your browser via WebGPU. No API keys required. Privacy preserved.
*   **AUTONOMOUS JOB LOOPS**: Give the system a goal ("Research X", "Write Code Y"). It enters a self-governed loop, creating artifacts until the job is done.
*   **VISION & BIO-LINK**: The system can see your screen and read your webcam to detect frustration or intent, adapting its strategy in real-time.
*   **SELF-HEALING MEMORY**: Beliefs (Axioms) decay over time if not reinforced. Dead beliefs are tracked in a "Lesion Map" to prevent repeating mistakes.
*   **NERVOUS SYSTEM**: The UI reacts to "System Heat" (Entropy). High heat = Visual Glitching.

---

## ⚡ QUICK START

### Prerequisites
*   **Node.js** (v18+)
*   **WebGPU Browser** (Chrome 113+, Edge) for Local Mode
*   **API Key** (Gemini/OpenAI) OR **Ollama** installed (Optional for Local Mode)

### Installation

1.  **Clone & Install**
    ```bash
    npm install
    ```

2.  **Ignition**
    ```bash
    npm run dev
    ```

3.  **Access Cortex**
    *   Open `http://localhost:3000`
    *   *Note:* If using WebLLM, the first load will download model weights (~4GB) to your browser cache.

---

## 🕹️ OPERATIONAL MODES

### 1. MANUAL (The Command Deck)
Standard interface. You prompt, the system thinks, fights, and responds.
*   *Best for:* Specific questions, debugging, creative writing.
*   *Features:* Real-time "Typewriter" streaming, manual attachment ingest.

### 2. AUTO (The Job Runner)
Click **INITIATE AUTO THINK** or use the **Job Runner**.
*   *Best for:* "Refactor this file", "Research this topic", "Generate a test suite".
*   *Governor:* The **Autonomy Governor** restricts execution based on user presence.
    *   `FREE`: Full execution allowed.
    *   `ASSIST`: Requires human confirmation.
    *   `PAUSE`: Read-only.

### 3. DREAM (Idle Protocol)
When idle, the system samples its **Belief Ledger**.
*   *Behavior:* It connects random concepts to generate new axioms.
*   *Output:* New beliefs appear in the "Belief Fire" telemetry panel.
*   *Purpose:* To prevent "Model Collapse" by injecting controlled entropy.

---

## 🧬 KEY CAPABILITIES

### Universal Neural Link (Multi-Provider)
Switch instantly between backends without restarting:
*   **Google Gemini** (1.5 Flash/Pro, 2.0 Flash) - High speed, massive context.
*   **WebLLM (WebGPU)** - Run Llama-3 directly in Chrome/Edge. Zero server cost.
*   **Ollama (Local)** - Air-gapped local inference.
*   **OpenAI / Anthropic** - Legacy support via API.

### Fight Topologies (The Arena)
Configure how the internal agents collaborate or compete:
*   **DUEL (1v1)**: Prime vs. Nemesis. Surgical stress testing.
*   **TAG TEAM (2v2)**: (Prime + Lateral) vs. (Nemesis + Reductionist).
*   **BOSS RUSH (3v1)**: Three variants of a solution vs. One super-powered Critic.
*   **SWARM (4-WAY)**: Maximum entropy. Four distinct personas competing for the Truth.

### Evolutionary Learning (Distillation)
The system learns from its wins.
*   **Heuristic Extraction**: Successful reasoning patterns are extracted as rules.
*   **Self-Ratchet**: Weights for these rules are adjusted based on victory margins.
*   **Graveyard**: Failed strategies are buried. If the system tries to use a dead strategy, it feels "pressure" and diverges.

---

## 🖥️ INTERFACE GUIDE

*   **CORTEX (Center)**: The command deck. Displays the conversation and fight logs.
*   **TELEMETRY (Left)**:
    *   **Latent Map**: Force-directed graph of thoughts. Green=Candidate, Red=Attacker.
    *   **Distillation Feed**: Real-time log of heuristic evolution.
*   **SENSORY (Right)**:
    *   **Optic/Bio Feeds**: Live screen and webcam analysis.
    *   **Evolution Ring**: Visualization of dominant heuristics.
    *   **VFS**: Virtual File System for autonomous artifacts.

---

## 📂 PROJECT STRUCTURE

```
dreamforge-spine/
├── src/
│   ├── autonomous/       # Job Runner & Autonomy Governor
│   ├── bridge/           # Event Bus & Orchestrator
│   ├── components/       # React UI Components (Surgical/Cyberpunk)
│   ├── config/           # System JSON Configurations
│   ├── core/             # The 6-Organ Engines (Judge, Agents)
│   ├── distillation/     # Evolutionary Learning & Heuristics
│   ├── engine/           # Beliefs, Pressure, & Dynamics
│   ├── memory/           # Self-Healing Memory Vector Store
│   ├── model/            # Adapters (Gemini, WebLLM, Ollama)
│   └── tools/            # VFS & Sandbox Tools
├── public/
└── index.html            # Entry point with Fever shaders
```

---

## 🧪 DIAGNOSTICS

Run **RUN DIAGNOSTIC SPIN** in Settings to verify the 6-organ pipeline.
*   Checks WebGPU availability.
*   Verifies Vector Math engine.
*   Tests Memory persistence.

> System Status: **ONLINE**

