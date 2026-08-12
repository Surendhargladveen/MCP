# 🚀 MCP

> Hey buddy, I'm just building an MCP server 🛠️

---

## ⚡ Why `uv`?

`uv` is a **blazing-fast Python package manager**, used here to spin up an isolated, temporary environment for running things — no clutter, no hassle.

🔗 **Official Docs:** [docs.astral.sh/uv](https://docs.astral.sh/uv/#highlights)

---

## 📦 Installation

**Windows (PowerShell):**

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

---

## 🐍 Setup

**1. Install Python via `uv`:**

```bash
uv python install
```

**2. Initialize the project:**

```bash
uv init
```

**3. Creating virtual environment:**

```bash
uv venv
```

**4. Activate it:**

```bash
.venv\Scripts\activate
```

**5. Install fastmcp:**

```bash
uv add fastmcp
```

**6. Install MCP CLI:**

```bash
uv add "mcp[cli]"
```
**7. Check fastmcp is working:**

```bash
fastmcp
```
**8. Run the mcp inspector:**

```bash
mcp dev <filename.py>
```
---
