---
Title: "Refinement Commands"
Date: "2025-11-25"
Author: "LL3-13"
Tags: ["refinement","editing","tone","clarity"]
Model: "gpt-4"
Purpose: "Quick, copy-pasteable refinement commands to iteratively improve outputs: tone, clarity, evidence, and format changes."
Complexity: "Low"
ExampleInputs:
  - "Draft email to investor (needs to be shorter and more urgent)"
ExampleOutputs:
  - "3 shortened email variants + one with urgent tone"
Evaluation:
  - "Clarity: yes/no"
  - "Tone-fit: yes/no"
  - "Actionability: yes/no"
---

# Refinement — Quick Edit Commands

Copy any of these short refinement instructions and append them to the original prompt or output. Replace bracketed values.

1) Simplify for non-technical audience  
"Rewrite the text for a non-technical audience. Use analogies, avoid jargon, and explain key terms in one sentence each."

2) Make concise / cut to N words  
"Shorten the text to N words while keeping the main argument and 2 supporting facts."

3) Highlight key takeaways  
"Extract 3–5 key takeaways as bullet points (one sentence each) suitable for an executive."

4) Add metrics or evidence  
"Add 2–3 supporting metrics or public evidence items (with suggested source types) that strengthen the claim."

5) Tone swap  
"Rewrite the text in a [tone] tone (e.g., urgent, empathetic, confident). Keep structure the same."

6) Prioritize next steps  
"List the top 3 next actions in order (who, what, and timeline), each as a single bullet."

7) Make it recruiter-friendly  
"Rewrite this description to highlight outcomes, measurable impacts, and collaboration (for a recruiter or hiring manager). Keep ≤100 words."

8) Expand into a short plan  
"Turn this into a 3-step execution plan with milestones and 1 risk per step."

9) Format as [format]  
"Convert the text into [format] (e.g., numbered steps, table with columns: action/owner/date, JSON with fields: task, owner, due)."

10) Quick bias & safety check  
"Identify potential bias, privacy, or safety issues in the output and suggest 2 mitigations."

---

# Usage tips
- Append one refinement command per request (keeps results focused).  
- Combine a "Make concise" + "Tone swap" step for final recruiter-ready text.  
- After refinement, always run the Evaluation Rubric (Clarity, Usability, Completeness).

# Example (copyable)
Original prompt + appended refinement:
"[Original prompt text here]
Now: Rewrite the above for a non-technical executive, extract 3 key takeaways, and keep the total output under 150 words."
