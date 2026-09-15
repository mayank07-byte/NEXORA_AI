# NEXORA_AI
# ⚡ NEXORA AI OS v3.0
> **An Autonomous Desktop AI Operating System & Futuristic HUD Assistant**

NEXORA AI is a production-inspired, local-first AI Operating System built to redefine desktop interaction. Moving beyond conventional chatbots, NEXORA combines real-time multimodal vision, agentic function calling, local RAG vector retrieval, and background system automation inside a 60 FPS sci-fi PySide6 HUD interface.

---

### ✨ Key Engineering Features

- 🎨 **Futuristic 3D Ultron HUD Interface:** 60 FPS PySide6 radial orb with 3D parallax mouse tracking, honeycomb aura grid, 28-bar reactive audio visualizer, and telemetry sparklines.
- 🤖 **Agentic Tool Router & Function Calling:** Autonomous multi-step command chaining using Gemini 3.6 Flash Automatic Function Calling (AFC).
- 📚 **Local-First RAG Engine:** Dense vector storage and semantic retrieval using ChromaDB, SentenceTransformers (`all-MiniLM-L6-v2`), and PyPDF.
- 👁️ **Multimodal Screen Perception:** Sub-1-second desktop display analysis powered by PIL downscaling pipelines and Gemini Vision.
- 💾 **Persistent Long-Term Memory:** Thread-safe SQLite database storing user facts, context, and multi-turn conversation logs across sessions.
- 🎙️ **Neural Voice & Ambient Wake-Word:** Hands-free continuous listening with `SpeechRecognition` and natural Edge-TTS speech synthesis.
- 💻 **Desktop & Process Automation:** System application launching, media master controls, voice notes scratchpad, and workstation power controls.
- 🎭 **Dynamic Persona Engine:** On-the-fly switching between Ultron, JARVIS, and Cyberpunk HUD themes and AI system prompts.

---

### 🛠️ Architecture & Tech Stack

- **UI Framework:** PySide6 (Qt for Python), Custom QPainter Vector Math
- **AI / LLM Orchestration:** `google-genai` SDK (Gemini 3.6 Flash), Ollama (Open-Source Local LLMs)
- **Embeddings & Vector DB:** ChromaDB, `SentenceTransformers`
- **Voice & Audio:** `SpeechRecognition`, `edge-tts`, `QMediaPlayer`
- **Data & Telemetry:** SQLite3, `psutil`, `pynput`, `Pillow`
- **Concurrency & Threading:** Non-blocking Qt `QThread` workers, `asyncio`
