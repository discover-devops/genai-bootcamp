# Codex + GitHub Copilot + VS Code

# Beginner Hands-On Lab Guide

---

# 1. Introduction

Today we learned how modern AI-assisted software engineering works using:

* Visual Studio Code
* GitHub Copilot
* OpenAI Codex
* AI-generated website development
* Localhost deployment

This is not just “autocomplete”.

This is:

# Conversational Software Engineering

Meaning:

```text id="doc1"
Human describes intent
↓
AI generates implementation
↓
Human validates
↓
Application runs locally
```

---

# 2. Important Concepts

# Traditional Development

```text id="doc2"
Human writes every line manually
```

---

# AI-Assisted Development

```text id="doc3"
Human gives instruction
↓
AI generates code
↓
Human reviews
↓
Application runs
```

---

# Copilot vs Codex

| Tool           | Purpose                          |
| -------------- | -------------------------------- |
| GitHub Copilot | AI code suggestions/autocomplete |
| OpenAI Codex   | AI engineering agent             |

---

# GitHub Copilot

Used for:

* inline suggestions
* autocomplete
* small code generation
* coding assistance

---

# OpenAI Codex

Used for:

* multi-file generation
* reasoning across project
* modifying applications
* AI engineering workflows
* conversational coding

---

# 3. Prerequisites

Before starting, install:

| Tool                | Purpose          |
| ------------------- | ---------------- |
| VS Code             | Development IDE  |
| Git                 | Version control  |
| Python              | Runtime          |
| GitHub Account      | Copilot login    |
| Internet Connection | AI communication |

---

# 4. Install VS Code

Download:

[VS Code Official Website](https://code.visualstudio.com?utm_source=chatgpt.com)

Install normally.

---

# 5. Install Git

Download:

[Git Official Website](https://git-scm.com/downloads?utm_source=chatgpt.com)

Verify:

```bash id="doc4"
git --version
```

---

# 6. Install Python

Download:

[Python Official Website](https://www.python.org/downloads/?utm_source=chatgpt.com)

IMPORTANT:
Enable:

```text id="doc5"
Add Python to PATH
```

Verify:

```bash id="doc6"
python --version
```

---

# 7. Create GitHub Account

Create account:

[GitHub Signup](https://github.com/signup?utm_source=chatgpt.com)

This is needed for:

* GitHub Copilot
* authentication
* AI workflows

---

# 8. Install GitHub Copilot

## Step 1

Open VS Code.

---

## Step 2

Open Extensions:

```text id="doc7"
Ctrl + Shift + X
```

---

## Step 3

Search:

```text id="doc8"
GitHub Copilot Chat
```

Install extension from:
GitHub

---

## Step 4

Enable AI features.

---

## Step 5

Login using GitHub account.

Browser opens automatically.

Authorize access.

---

# 9. Install OpenAI Codex

## Step 1

Open Extensions again.

---

## Step 2

Search:

```text id="doc9"
Codex
```

Install:

# Codex – OpenAI’s coding agent

from:
OpenAI

---

## Step 3

Open Codex Sidebar

Press:

```text id="doc10"
Ctrl + Shift + P
```

Search:

```text id="doc11"
Codex: Open Codex Sidebar
```

---

# 10. Install Live Server

Live Server is used to run websites locally.

Install extension:

```text id="doc12"
Live Server
```

from:
Ritwick Dey

---

# 11. LAB — AI Website Generation

# Goal

Create website using AI:

* red background
* centered content
* localhost deployment

Then modify:

* red → orange

using ONLY prompts.

---

# Step 1 — Create Folder

Inside VS Code:

Create folder:

```text id="doc13"
ai-website-demo
```

Open folder.

---

# Step 2 — Open Codex Sidebar

Press:

```text id="doc14"
Ctrl + Shift + P
```

Search:

```text id="doc15"
Codex: Open Codex Sidebar
```

---

# Step 3 — Generate Website Using AI

Paste this prompt into Codex:

```text id="doc16"
Create a simple modern website using HTML and CSS.

Requirements:
- red background
- centered heading
- centered button
- responsive layout

Create:
- index.html
- style.css

Add proper comments.
```

Press ENTER.

---

# Step 4 — Keep Changes

Codex creates:

* index.html
* style.css

Click:

```text id="doc17"
Keep
```

VERY important.

---

# Step 5 — Run Website

Right-click:

```text id="doc18"
index.html
```

Click:

```text id="doc19"
Open with Live Server
```

Browser opens:

```text id="doc20"
http://127.0.0.1:5500
```

Website appears with:

# RED BACKGROUND

---

# 12. LAB — Modify Website Using AI

Now modify website WITHOUT touching CSS manually.

Ask Codex:

```text id="doc21"
Change the website background color from red to orange.
```

Press ENTER.

---

# What Happens

Codex:

* opens style.css
* changes color
* modifies application

Click:

```text id="doc22"
Keep
```

Browser auto-refreshes.

Background changes:

# RED → ORANGE

---

# 13. What Students Learn

This single lab teaches:

| Concept                    | Learning                     |
| -------------------------- | ---------------------------- |
| AI-assisted coding         | AI generates implementation  |
| Conversational engineering | Modify app using English     |
| Frontend basics            | HTML + CSS                   |
| Live reload                | Localhost workflow           |
| Multi-file generation      | AI creates project structure |
| Human-AI collaboration     | Real engineering workflow    |

---

# 14. Important Teaching Point

AI does NOT replace engineers.

AI accelerates:

* repetitive coding
* syntax generation
* boilerplate
* scaffolding

Engineers still provide:

* architecture
* creativity
* validation
* security
* debugging

---

# 15. Final Understanding

Today we moved from:

```text id="doc23"
AI chatbot usage
```

to:

```text id="doc24"
AI-assisted software engineering
```

and experienced:

# Conversational Development Workflow

using:

* VS Code
* GitHub Copilot
* OpenAI Codex
* Live Server
* Localhost execution

---

# 16. Next Labs (Future)

Possible next hands-on labs:

| Lab             | Topic                         |
| --------------- | ----------------------------- |
| Flask API       | AI-generated backend          |
| Dockerfile      | AI-generated containerization |
| Kubernetes YAML | AI-generated manifests        |
| Terraform EKS   | AI-generated cloud infra      |
| Jenkinsfile     | AI-generated CI/CD            |
| Debugging       | AI fixes broken code          |

---


