# Ollama Study 🚀

This folder is our workspace for learning **Ollama**, running large language models (LLMs) locally, and building practical AI projects.

## 🎯 Learning Goals

- Understand what Ollama is and how local LLMs work.
- Install Ollama and run models on our own computer.
- Learn essential Ollama CLI commands.
- Use Ollama's local API from Python.
- Build a simple local AI chatbot.

## 📚 Study Roadmap

| Step | Topic | Status |
| --- | --- | --- |
| 1 | Introduction to Ollama and local LLMs | ⬜ Not started |
| 2 | Installing and setting up Ollama | ⬜ Not started |
| 3 | Downloading and running a model | ⬜ Not started |
| 4 | Essential Ollama commands | ⬜ Not started |
| 5 | Calling Ollama with Python | ⬜ Not started |
| 6 | Building a local chatbot | ⬜ Not started |

## 🛠️ Setup

1. Download Ollama from **https://ollama.com/download** and install it.
2. Open your terminal (PowerShell on Windows).
3. Check the installation:

   ```powershell
   ollama --version
   ```

4. Run a model (this downloads it if needed):

   ```powershell
   ollama run llama3.2
   ```

   **Note:** Model size, RAM requirements, and download time vary by model.

## 💻 Basic CLI Commands

```powershell
ollama --help             # Show available commands
ollama list               # List downloaded models
ollama run llama3.2       # Run a model locally
ollama ps                 # Show currently loaded models
ollama stop llama3.2      # Stop a running model
ollama rm llama3.2        # Remove a downloaded model
```

## 📂 Folder Structure

```text
Ollama-Study/
├── README.md          # Introduction, setup, and roadmap
└── study-notes.md     # Notes from each lesson
```

## 🔗 Useful Resources

- Ollama: https://ollama.com/
- Official documentation: https://docs.ollama.com/
- Ollama GitHub repository: https://github.com/ollama/ollama

## ✅ Progress Notes

Update `study-notes.md` after each session and mark finished topics as complete in the roadmap.

---

**Current focus:** Start with Lesson 1 — What is Ollama, and why run LLMs locally?
