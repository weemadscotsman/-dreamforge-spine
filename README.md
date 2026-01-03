# DREAMFORGE SPINE // v0.95 [CANDIDATE]

> **"Truth is not found; it is forged in the collapse of contradictions."**

---

## 💀 WHAT IS THIS?

**Dreamforge Spine** is a recursive, multi-modal AI operating system designed for **autonomous reasoning**.

Unlike standard chat interfaces that optimize for speed or politeness, Spine optimizes for **epistemic rigor**. It wraps any LLM (Gemini, Llama, Claude) in a biological architecture that forces it to argue against itself, validate assumptions, and rewrite its own operating rules based on survival.

**Status:** `v0.95` (Candidate Release)
**Architecture:** 6-Organ Biomechanical (Model, Evaluator, Constraint, Memory, Recursor, Distillation)

---

## 🚀 NEW IN v0.95

*   **BROWSER-NATIVE INFERENCE**: Run **Llama-3 8B** or **Phi-3.5** locally in your browser via WebGPU. No API keys required. Privacy preserved.
*   **AUTONOMOUS JOB LOOPS**: Give the system a goal ("Research X", "Write Code Y"). It enters a self-governed loop, creating artifacts until the job is done.
*   **VISION & BIO-LINK**: The system can see your screen and read your webcam to detect frustration or intent, adapting its strategy in real-time.
*   **SELF-HEALING MEMORY**: Beliefs (Axioms) decay over time if not reinforced. Dead beliefs are tracked in a "Lesion Map" to prevent repeating mistakes.

---

## 🛑 WHO IS THIS FOR?

### ✅ BUILD THIS IF:
*   You need an **Autonomous Agent** that can write files, execute code logic, and critique its own work.
*   You want **Local Privacy**: Run fully offline with Ollama or WebLLM.
*   You want to visualize the **Latent Space**: See the force-directed graph of the thought process.
*   You are a Researcher studying **LLM Cognitive Architectures**.

### ❌ DO NOT BOTHER IF:
*   You want a "friendly" chatbot for casual conversation.
*   You are afraid of the terminal or editing JSON configs.
*   You expect 100ms latency (Deep reasoning takes time).

---

## 🧬 KEY CAPABILITIES

### 1. Universal Neural Link (Multi-Provider)
Switch instantly between backends without restarting:
*   **Google Gemini** (1.5 Flash/Pro, 2.0 Flash) - High speed, massive context.
*   **WebLLM (WebGPU)** - Run Llama-3 directly in Chrome/Edge. Zero server cost.
*   **Ollama (Local)** - Air-gapped local inference.
*   **OpenAI / Anthropic** - Legacy support via API.

### 2. Fight Topologies (The Arena)
Configure how the internal agents collaborate or compete:
*   **DUEL (1v1)**: Prime vs. Nemesis. Surgical stress testing.
*   **TAG TEAM (2v2)**: (Prime + Lateral) vs. (Nemesis + Reductionist).
*   **BOSS RUSH (3v1)**: Three variants of a solution vs. One super-powered Critic.
*   **SWARM (4-WAY)**: Maximum entropy. Four distinct personas competing for the Truth.

### 3. Autonomy & Agency
*   **Auto-Loop**: The system pursues a goal through multiple cycles of generation, critique, and refinement.
*   **Governor**: A safety module ("The Leash") that restricts execution permissions (File Write, Shell Exec) based on user presence and trust level.
*   **Dream Protocol**: When idle, the system hallucinates on existing beliefs to synthesize new axioms.

### 4. Evolutionary Learning (Distillation)
The system learns from its wins.
*   **Heuristic Extraction**: Successful reasoning patterns are extracted as rules.
*   **Self-Ratchet**: Weights for these rules are adjusted based on victory margins.
*   **Graveyard**: Failed strategies are buried. If the system tries to use a dead strategy, it feels "pressure" and diverges.

---

## ⚡ QUICK START

### Prerequisites
*   **Node.js** (v18+)
*   **WebGPU Browser** (Chrome 113+, Edge) for Local Mode
*   **API Key** (Gemini/OpenAI) OR **Ollama** installed

### Installation
1.  Clone & Install:
    ```bash
    npm install
    ```
2.  Run:
    ```bash
    npm run dev
    ```
3.  Access UI: `http://localhost:3000`

### Configuration
1.  Open the **CONF (SETTINGS)** panel.
2.  **Provider**: Choose `WEBLLM` (Local) or `GEMINI` (Cloud).
3.  **Topology**: Select `DUEL_1V1` for standard tasks or `SWARM_4_WAY` for complex brainstorming.

---

## 🕹️ OPERATIONAL MODES

### MANUAL (User Driven)
Standard command deck. You prompt, the system thinks, fights, and responds.
*   *Best for:* Specific questions, debugging, creative writing.

### AUTO (Autonomous Job)
Click **INITIATE AUTO THINK** or use the **Job Runner**.
*   *Best for:* "Refactor this file", "Research this topic", "Generate a test suite".
*   *Governor:* Ensure Autonomy Level is set to `FREE` or `ASSIST`.

### DREAM (Idle Reflection)
The system automatically samples its **Belief Ledger** when idle.
*   *Behavior:* It connects random concepts to generate new axioms.
*   *Output:* New beliefs appear in the "Belief Fire" telemetry panel.

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

## 🧪 DIAGNOSTICS

Run **RUN DIAGNOSTIC SPIN** in Settings to verify the 6-organ pipeline.
*   Checks WebGPU availability.
*   Verifies Vector Math engine.
*   Tests Memory persistence.

> System Status: **ONLINE**
