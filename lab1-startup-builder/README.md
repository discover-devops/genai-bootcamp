#  Lab 1 Startup Builder


---

##  Phase 1: Context & Tool Explanation (Before Opening the Tool)
**Time Allocation:**  
**Format:** Talk to the students / Write on the board.

### 1. What is OpenClaw?
* **Explain to Students:** "Before we write a single prompt, let's look at our workspace. We are using **OpenClaw**. OpenClaw is an enterprise-grade AI Assistant interface. It bypasses restrictive consumer-level guardrails and allows us to chat directly with powerful underlying LLM models using advanced system personas."
* **Key Concept:** Explain that a standard AI interaction is "one-shot" (asking a single question and accepting a generic answer). OpenClaw allows us to run **Iterative Prompting Chains**, where we force the AI to maintain a professional persona and build an architecture step-by-step.

### 2. Live Environment Setup Check
* Point the students to the classroom projector. 
* Show them that you are opening the OpenClaw workspace environment via the browser/local environment designated for the boot camp.
* **Instructor Note:** *Ensure your OpenClaw session is logged in and clear before sharing your screen.*

---

##  Phase 2: Live Demo Execution (Step-by-Step)
**Time Allocation:** 
**Format:** Copy-paste the prompts below into your live OpenClaw screen. Explain your actions as you type.

###  Step 1: Prime the System Engine
* **What to tell the students:** "Watch the screen. If I ask the AI to 'give me a business plan', it will give me a boring, generic list. Instead, I am going to run a **System Priming Prompt** to completely overwrite its default behavior and force it to act like a strict Venture Capitalist."
* **Your Live Action:** Copy the text below and hit send in OpenClaw.

```text
Act as an elite Venture Capitalist and Startup Incubator Director. I am going to build a brand new technology startup from scratch using an iterative prompting framework. Do not generate the whole plan at once. First, acknowledge your role and ask me what broad industry or problem domain I want to target today (e.g., EdTech, Sustainability, FinTech, Autonomous Systems, Logistics).
