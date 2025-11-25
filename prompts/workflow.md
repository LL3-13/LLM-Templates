---
Title: "AI-Assisted Career Acceleration Workflow"
Date: "2025-11-25"
Author: "LL3-13"
Tags: ["career","workflow","job-search","ai"]
Model: "gpt-4"
Purpose: "A repeatable, annotated workflow for using LLMs to run a focused, high-volume job search while preserving voice and quality."
Complexity: "Medium"
ExampleInputs:
  - "Profile: 3 years robotics engineering, interests: autonomy, defense, startup"
ExampleOutputs:
  - "Weekly plan + 3 tailored resume variants + 3 cold email templates"
Evaluation:
  - "Alignment: yes/no"
  - "Scalability: yes/no"
  - "Effectiveness: yes/no"
---

# AI-Assisted Career Acceleration Workflow

This system is designed to help an early-career professional run a disciplined, high-quality job search using LLMs. Follow each step in order. Use other prompt templates in this repo to produce deliverables (resumes, emails, pitches).

1) Build an honest psychological profile
- Capture values, dealbreakers, work preferences, failures, strengths, and writing samples. Be brutally specific — the model needs the real you.

2) Create a style guide
- Provide 3–5 writing samples. Ask the model to extract sentence rhythm, pacing, vocabulary, and signature phrases. Save the guide as "style-guide.txt".

3) Treat profile + style guide as operational doctrine
- Always prepend outputs with: "Use profile X and style-guide Y." This keeps voice and alignment consistent across documents.

4) Build a job filter (Fit vs Callback)
- Define scoring: Fit (culture, role, growth) and Callback Probability (likelihood of hearing back).
- Provide thresholds (e.g., score ≥ 7/10 to prioritize).

5) Provide concrete industry lanes
- Give the model 3–6 focused industries or roles (e.g., defense autonomy engineer, robotics firmware, applied AI infra).

6) Sourcing cadence
- Set a daily goal: 3–5 targeted applications on weekdays. Use saved searches and RSS/email alerts. Track progress in a simple spreadsheet.

7) Resume + cover letter templates
- Create a base resume and base cover letter aligned to your profile and style guide.
- For each job: produce (A) light-touch variant and (B) deep rewrite for high-priority roles.

8) Automated role scoring and prioritization
- Ask the model to score scraped roles against your job filter; output a ranked list and one-sentence rationale per role.

9) Outreach system
- For high-priority roles, generate:
  - 3 cold email variants (short, metric-driven, personalized)
  - 1 LinkedIn message variant
  - 1 recruiter-friendly 2-line hook for referrals

10) Interview prep & practice
- Generate role-specific mock interview questions. For each question provide: ideal answer outline, 2 practice prompts to run with the model, and one concise follow-up question to deepen answers.

11) Consistency & batching
- Batch similar roles together to reuse variants. Use 2–3 hour blocks: sourcing, tailoring, sending, follow-ups.

12) Calibration & review
- Weekly review: model summarizes what’s working, false positives, and suggests tweaks to the job filter and outreach scripts.

13) Accountability & metrics
- Track weekly KPIs: roles applied, responses, interviews, offers. Have the model create a one-line weekly status and a 3-item improvement plan.

14) Stress test & vetoes
- Periodically ask the model: "Recommend five roles I should avoid and why." Use to protect from bad fits.

15) Maintenance cadence
- Update profile every 2 weeks, style guide monthly, add new industries quarterly.

16) Final prompt (use to bootstrap the system)
- "Using my profile (paste profile) and my style guide (paste style guide), act as my career ops assistant. Each weekday, find 5 targeted roles, score them by Fit and Callback, produce tailored resume bullets and 3 outreach variants for the top 3 roles, and provide a daily 1-line status and one experiment to improve reply rate."

---

# Quick templates to copy into the workflow process
- Daily sourcing: "Find 5 open roles for [ROLE] in [INDUSTRY], remote/hybrid filter [choice], and score them by Fit/Callback. Output CSV-style: title, company, URL, score, 1-line rationale."
- Apply pack: "For this role [PASTE LINK AND JD], produce a 120-word recruiter-friendly pitch, 3 resume bullet edits prioritized by impact, and 3 cold email variants (≤120 words each)."

# Notes & ethical considerations
- Do not include private PII or sensitive company data in public repos.
- Use interview prep responsibly and do not request non-public proprietary information.

# How to use with this repo
- Use prompts/ideation.md, prompts/biz-dev.md, and prompts/refinement.md alongside this workflow.
- Save high-quality outputs as example runs in each prompt file under "ExampleOutputs".

---

When you commit this file, reply exactly: Done — workflow added
