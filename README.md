# -dreamforge-spine
Recursive reasoning engine with evaluator → constraint → memory → recursor → exporter spine.  Not a chatbot. Not a toy. It argues back.
# DREAMFORGE SPINE // ADVERSARIAL REASONING ENGINE v0.9

> "Truth is not found; it is forged in the collapse of contradictions."

## 📚 DOCUMENTATION
**[👉 READ THE FULL SYSTEM MANUAL](./docs/SYSTEM_MANUAL.md)**  
(Covers Architecture, Genetic Distillation, Twin-Loops, and Logic Parsers)

---

## 💀 WHAT IS THIS?

**Dreamforge Spine** is a multi-modal, recursive AI operating system designed for rigorous thought. It rejects the standard "chat" paradigm in favor of an **Adversarial Twin-Loop**: every thought generated is immediately attacked by a nemesis model. Only ideas that survive this collision are output.

It transforms LLMs from passive text generators into **Active Reasoning Agents** with eyes (Vision), ears (Audio), and memory (Vector/Symbolic).

---

## 🧬 KEY CAPABILITIES

### 1. Universal Neural Link (Multi-Provider)
Connect to any intelligence backend. Dreamforge creates a unified cognitive layer over:
*   **Google Gemini** (Flash/Pro/1.5)
*   **Anthropic Claude** (via REST)
*   **OpenAI GPT-4o** (via REST)
*   **Mistral AI** (Le Chat/Large)
*   **HuggingFace Inference** (Llama 3, Mixtral, etc.)
*   **Ollama (Local)** - Run entirely offline/air-gapped.

### 2. Fight Topologies (The Arena)
Configure how the internal agents collaborate or compete to solve your task:
*   **DUEL (1v1)**: Prime vs. Nemesis. Surgical stress testing.
*   **TAG TEAM (2v2)**: (Prime + Lateral Thinker) vs. (Nemesis + Reductionist). Synthesis of complex ideas.
*   **BOSS RUSH (3v1)**: Three variants of a solution vs. One super-powered Critic.
*   **SWARM (4-WAY)**: Maximum entropy. Four distinct personas competing for the Truth.

### 3. Sensory Deck
*   **Optic Nerve (Screen)**: Universal screen capture allows the system to "see" your work, analyze code in VS Code, or watch videos.
*   **Bio-Link (Webcam)**: Reads user presence and emotional context to adjust system pressure.

### 4. Evolutionary Learning (Distillation)
The system rewrites its own instructions based on what works.
*   **Heuristic Extraction**: Successful reasoning patterns are saved as rules.
*   **Competition Ring**: Rules fight for limited "attention weight". Weak rules die.
*   **Lesion Map**: Failed beliefs are entombed. If the system tries to repeat a known mistake, it feels "pain" (Pressure) and corrects course.

### 5. Autonomous Agency
*   **Dream Protocol**: When idle, the system hallucinates on existing beliefs to forge new axioms (cost-controlled).
*   **Auto-Loop**: Give it a job (e.g., "Research X"). It enters a self-governed loop until the job is done.
*   **Governor**: A safety layer that restricts autonomy levels (Free, Assist, Pause) based on human presence.

---

## ⚡ QUICK START

### Prerequisites
*   **Node.js** (v18+)
*   **API Keys** (for Cloud models) OR **Ollama** (for Local)

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
Go to the **SETTINGS (CONF)** panel in the UI.
*   **Provider**: Select your backend (Gemini, Claude, OpenAI, etc.).
*   **Keys**: Enter API keys directly in the secure inputs.
*   **Topology**: Select your Fight Mode (Duel, Swarm, etc.).

---

## 🕹️ OPERATIONAL MODES

### MANUAL (User Driven)
Standard interaction. You prompt, the system thinks, fights, and responds. Use the **Terminal** at the bottom.

### DREAM (Idle Reflection)
The system automatically samples its **Belief Ledger** when idle. It connects random concepts to generate new insights.
*   *Config*: Adjust "Dream Budget" in Settings to control costs.

### AUTO (Autonomous Job)
Autonomous execution loop.
*   **Trigger**: Click "INITIATE AUTO THINK" in Settings.
*   **Behavior**: The system will pursue the current context/goal until convergence or failure.

---

## 🖥️ INTERFACE GUIDE

*   **CORTEX (Center)**: The main command deck. Displays the conversation and fight logs.
*   **TELEMETRY (Left)**:
    *   **Latent Map**: Force-directed graph of the thought process. Green=Candidate, Red=Attacker.
    *   **Pressure Graphs**: Real-time metrics of system load and conflict.
*   **SENSORY (Right)**:
    *   **Optic/Bio Feeds**: Live video inputs.
    *   **Evolution Ring**: Visualization of the dominant heuristics.
    *   **Filesystem**: Virtual File System (VFS) for autonomous artifacts.

---

## 🧪 DIAGNOSTICS

Run the **Diagnostic Spin Test** via the Settings Panel to verify the 6-organ pipeline (Model -> Judge -> Memory -> Constraint -> Recursor -> Distillation) is connected.

> **Status**: `SYSTEM_ONLINE`
