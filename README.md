# MLCon Berlin 2026 — Hands‑On GenAI Development Bootcamp

Teaching code for the **MLCon Berlin 2026 "Hands‑On GenAI Development
Bootcamp"** by John Davies ([Incept5](https://incept5.com)).

Every script here is a **standalone program** — there is no build system and no
test suite. Run any file directly with `python <script>.py`; it pulls in only the
libraries that one demo needs. Demos talk to either a local model server (Ollama,
LM Studio, MLX, llama.cpp) or a cloud provider via an API key.

## Getting started

See **[PYTHON_SETUP.md](PYTHON_SETUP.md)** to create a virtual environment and
install the dependencies, then copy `.env.example` to `.env` for your cloud keys.

```bash
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

`requirements.txt` is a convenience superset that lets every script run; you don't
need all of it for any single demo.

## Contents

- **[day-1/](day-1/)** — AI fundamentals: classic neural networks, what an LLM
  really is (tokenisation → embeddings → attention → decoding), and running
  models locally, remotely and in the cloud. See the
  [Day‑1 README](day-1/README.md) for a guided tour of every script.

---
John Davies · [john.davies@incept5.com](mailto:john.davies@incept5.com)
