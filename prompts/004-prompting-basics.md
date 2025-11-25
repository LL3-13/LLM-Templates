---
Title: "Prompting Basics — Overview"
Date: "2025-11-25"
Author: "LL3-13"
Tags: ["prompting","overview","prompt-bank"]
Model: "gpt-4"
Purpose: "Short overview, table of contents, and how-to for the full prompt bank. Links to split category files."
Complexity: "Low"
ExampleInputs:
  - "Short prompt that needs improvement"
ExampleOutputs:
  - "Rewritten prompt + structure + suggested tests"
Evaluation:
  - "Clarity: yes/no"
  - "Usability: yes/no"
  - "Completeness: yes/no"
---

# Prompting Basics — Overview

This short file is the entry point for the organized prompt bank. Copy any template file into ChatGPT (chat.openai.com), replace bracketed fields (e.g., [INDUSTRY]) with your specifics, and run. If you want me to auto-fill examples for any template, tell me which one and I’ll generate a filled example.

Table of contents (files you will add next)
- prompts/ideation.md — Ideation templates (brainstorming, competitive analysis, problem statements, MVP)
- prompts/biz-dev.md — Business development templates (cold email, BMC, investor pitch, RFP)
- prompts/research.md — Research & analysis templates (market summary, competitor deep-dive, customer discovery)
- prompts/creative.md — Creative & content templates (one-pager, LinkedIn post, presentation, white paper)
- prompts/refinement.md — Refinement commands (simplify, add metrics, tone swaps)
- prompts/workflow.md — AI-Assisted Career Acceleration Workflow (job-search system)

Quick guidance (one-line each)
- Copy a template file, replace [BRACKETS], paste into ChatGPT, add small context, and run.
- Use the Evaluation checks at the top (Clarity, Usability, Completeness) to mark outputs.
- Keep prompts focused: 1 goal + 3–5 steps + clear output format.

Short example (copyable)
ROLE: Product manager  
TONE: Concise, recruiter-friendly  
AUDIENCE: Hiring manager (non-technical)  
OUTPUT FORMAT: 1-paragraph brief + 3 bullets of success metrics  
TASK: Create a feature brief for "social login" and propose 3 measurable metrics.  
CONSTRAINTS: Brief ≤ 60 words; metrics must include % or numeric targets.

Quick testing notes (for non-coders)
1. Open a prompt file (e.g., prompts/ideation.md after it's added).
2. Copy the template text and paste into chat.openai.com.
3. Replace bracketed items with specifics and add any short input.
4. Send and compare the output to the Evaluation checks.
5. Save good outputs as example runs (you can paste them back into the prompt file under "ExampleOutputs").

What I will do next (one at a time)
- I will prepare prompts/ideation.md now and present it as a single paste-ready block.
- After you commit that, I will give prompts/biz-dev.md, and so on.

If you're ready: copy the entire contents of this file, add a new file in your repo at prompts/004-prompting-basics.md, paste, and commit.

When the file is saved, reply exactly: Done — basics added
