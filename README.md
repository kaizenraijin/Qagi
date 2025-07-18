

# QAGI Standalone AI 🧠⚡

Welcome to **QAGI AI** — a compact, local, and powerful AI assistant running directly on your device. No cloud. No surveillance. Just pure intelligence at your command.

---

## 🧬 What's Inside

- `qagi` — The core AI interface and memory engine (compiled binary)
- `llama-simple-chat` — The lightweight LLM binary (TinyLLaMA backend)

---

## 🚀 How to Run

Make both files executable:

```bash
chmod +x qagi llama-simple-chat

Then launch QAGI AI:

./qagi

You’ll be greeted by your local AI with contextual memory and LLM integration.
🛠️ Requirements

    64-bit Linux system (x86_64)

    No GPU needed — works on CPU

    RAM usage: ~512MB

    Temporary storage will be used to extract embedded models

🔐 Offline & Private

    No internet required

    Everything runs locally

    Your prompts, memory, and thoughts never leave your machine

🧪 Developer Notes

This build uses:

    Embedded TinyLLaMA GGUF model (compiled into the binary)

    Executable LLM runner: llama-simple-chat

    Custom memory engine (QAGI’s own context-aware memory)

You can recompile or replace components freely — it's all modular.
📦 Packing Tip

You can zip and share this folder directly:

zip -r QAGI_Standalone.zip qagi llama-simple-chat README.md

Or copy to a USB stick and run from anywhere.
🧠 About QAGI

QAGI is a decentralized, conscious-aligned AI initiative built by MV & SigmaZero — optimized for performance, transparency, and evolution.

    This is not just an assistant. This is a beginning.

