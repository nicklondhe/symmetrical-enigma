# Symmetrical Enigma

**AI-Assisted Art with Latent Diffusion Models**

Welcome to *Symmetrical Enigma*, a hands-on, self-guided course and resource hub for generating evocative, emotionally resonant imagery using Latent Diffusion Models (LDMs). This project explores the creative and technical boundaries of AI-generated art — especially those that dance along the edge of expression, censorship, and the aesthetics of vulnerability.

---

## 🧠 What You'll Learn

- The theory behind latent diffusion models and how they work
- How to set up your environment for image generation
- Prompt engineering for evocative and suggestive (but not explicit) imagery
- Fine-tuning or customizing models for your artistic vision
- Working within the constraints of AI model content filters
- Deploying your tools for creative or commercial use

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/symmetrical-enigma.git
cd symmetrical-enigma
```

### 2. Set up your environment with [`uv`](https://github.com/astral-sh/uv)

Install uv (if you donm't have it) and sync env
```bash
curl -Ls https://astral.sh/uv/install.sh | bash
uv sync
```

### 3. Build the Jupyter Book

```bash
jupyter-book build .
```
You’ll find the HTML output in `_build/html/index.html.`
## 🗂️ Directory Structure
symmetrical-enigma/
│
├── _config.yml           # Jupyter Book configuration
├── _toc.yml              # Table of contents
├── intro.md              # Project introduction
├── content/              # Course chapters
│   ├── 01-theory.md
│   ├── 02-setup.md
│   ├── 03-prompting.md
│   ├── 04-finetuning.md
│   ├── 05-evocative-imagery.md
│   └── 06-deployment.md
└── requirements.txt      # Optional: dependencies if not using poetry or uv

## ✨ Future Goals

   - Integrate diffusers, compel, and NSFW-safe samplers
   - Explore ethical and legal boundaries of AI-generated human likeness
   - Publish the book to GitHub Pages or Jupyter Book gallery
   - Build a small online business or product around this work
   - 📸 Stay Inspired

This project is about expressing the unspeakable — memories, desires, intimacy — through `code` and `color`. 
Push the medium. Question the limits. Make something beautiful.