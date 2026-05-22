# Lab 1 RUNBOOK — OpenClaw / Open WebUI

---

# Step 1 — Clone Open WebUI Repository

```bash
git clone https://github.com/open-webui/open-webui.git
````

---

# Step 2 — Navigate to Repository

```bash
cd open-webui
```

---

# Step 3 — Verify Docker Installation

```bash
docker --version
docker ps
```

---

# Step 4 — Run Open WebUI Docker Container

```bash
docker run -d \
-p 5000:8080 \
--add-host=host.docker.internal:host-gateway \
-v open-webui:/app/backend/data \
--name open-webui \
ghcr.io/open-webui/open-webui:main
```

---

# Step 5 — Verify Running Container

```bash
docker ps
```

Expected output should show:

```text
0.0.0.0:5000->8080/tcp
```

---

# Step 6 — Open Security Group / Firewall

Allow inbound TCP traffic on:

* Port 5000

---

# Step 7 — Access Open WebUI

Open browser:

```text
http://<PUBLIC-IP>:5000
```

---

# Step 8 — Create Admin User

Create:

* Email
* Password

---

# Step 9 — Configure OpenAI API

Go to:

Profile Icon
→ Admin Panel
→ Settings
→ Connections
→ OpenAI API

Add:

* OpenAI API Key

---

# Step 10 — Select AI Model

Example:

* gpt-4o

---

# Step 11 — Test Basic Prompt

```text
Explain Artificial Intelligence in simple words.
```

---

# Step 12 — Upload PDF Document

Click:

*

````

Upload:

- PDF
- PPT
- DOC

---

# Step 13 — Ask Questions From Document

```text
Summarize this document.
````

---

# Step 14 — Contextual Question Answering

```text
Generate interview questions from this document.
```

---

# Step 15 — Architecture Understanding

Open WebUI provides:

* UI
* memory
* orchestration
* document handling

OpenAI provides:

* model inference
* token generation

````
