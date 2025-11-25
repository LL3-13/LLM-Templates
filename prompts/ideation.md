---
Title: "Ideation Templates"
Date: "2025-11-25"
Author: "LL3-13"
Tags: ["ideation","brainstorming","mvp","competitive"]
Model: "gpt-4"
Purpose: "Short, copy-pasteable ideation templates: brainstorming, competitive analysis, problem statements, MVP scoping, and assumption mapping."
Complexity: "Low"
ExampleInputs:
  - "Industry: fintech; Niche: SMB invoicing"
ExampleOutputs:
  - "Top 3 problems + 5 short solutions + one quick validation idea"
Evaluation:
  - "Clarity: yes/no"
  - "Relevance: yes/no"
  - "Actionability: yes/no"
---

# Ideation — Prompt Templates

Use these by replacing [BRACKETS] with your specifics and pasting into ChatGPT.

## 1) Brainstorming (fast founder ideation)
ROLE: Act as a market expert in [INDUSTRY] with experience in [NICHE].  
TONE: Practical, focused.  
TASK: List the top 3 problems or trends in [NICHE] (≤50 words each). For the #1 problem, propose 5 potential solutions (≤50 words each). For each solution add one quick validation check (e.g., search volume, competitor gap, simple user interview). Rank solutions by impact × feasibility.  
OUTPUT FORMAT: Numbered lists: Problems, Solutions (with validation).  
CONSTRAINTS: ≤50 words per item.

## 2) Competitive Analysis
ROLE: Act as a competitive intelligence analyst.  
TONE: Analytical, concise.  
TASK: For idea [SHORT DESCRIPTION], list 3 public competitors and 3 direct differentiators you could own. For each differentiator, give one concrete go-to-market or product tactic to exploit it. Conclude with one short risk (what could stop you).  
OUTPUT FORMAT: Bulleted sections (Competitors → Differentiators → Tactics → Risk).  
CONSTRAINTS: ≤50 words per bullet.

## 3) Problem Statement (3 concise statements)
ROLE: Act as a problem-definition expert.  
TONE: Clear, strategic.  
TASK: Given context [INSERT CONTEXT], produce 3 problem statements (<50 words each). Each should include: context, core issue, why it matters, and one metric you’d use to measure it.  
OUTPUT FORMAT: 3 numbered problem statements.

## 4) MVP Scoping
ROLE: Act as a product strategy lead.  
TONE: Practical, prioritized.  
TASK: For product idea [INSERT IDEA], identify: (A) Core user and need, (B) 5 essential features for MVP ranked by priority, (C) 3 success metrics for the MVP, (D) One quick experiment to validate the core assumption. Keep each item short.  
OUTPUT FORMAT: Short sections (User, Features, Metrics, Experiment).  
CONSTRAINTS: Each feature ≤25 words; metrics must be measurable.

## 5) Assumption Mapping
ROLE: Act as a risk/prioritization expert.  
TONE: Systematic, concise.  
TASK: For idea [INSERT IDEA], list 6 key assumptions (customer, technical, market, ops). For each assumption assign Risk (High/Med/Low) and propose one cheap experiment to validate. Output as a table or numbered list.  
OUTPUT FORMAT: Assumption — Risk — Validation experiment (1 line each).

---

# Quick example (copyable)
Prompt to paste into an LLM:
"ROLE: Market expert in fintech for SMBs. TASK: List top 3 problems in SMB invoicing (≤50 words each). For the top problem propose 5 solutions (≤50 words each) and one quick validation idea per solution. Rank solutions by impact × feasibility. OUTPUT: Numbered lists."

---

Save and commit the file, then reply exactly: Done — ideation added
