# Privacy & Safety Guidelines

Purpose
This file explains what not to include in this public repository and gives quick steps and resources for handling sensitive data if it appears.

Do NOT commit to this public repo
- Personal Identifiers (PII): full name + DOB, SSNs, personal addresses, phone numbers, personal email addresses.
- Secrets: API keys, private keys, passwords, session tokens, OAuth secrets.
- Confidential content: proprietary corp documents, NDA-protected materials, internal logs with user data.
- Full psychological profiles or private coaching notes — keep those in private storage.

Quick checklist before committing
- Remove or redact any PII from examples or tests.
- Keep profile and style-guide drafts private (local machine, private gist, or encrypted storage).
- Add sensitive files to .gitignore (e.g., secrets.env, profile.txt) before they exist in the repo.

How to scan your repo locally (one-liners)
- Find likely secrets / private keys:
  grep -nE "BEGIN PRIVATE KEY|AKIA|api[_-]?key|secret|password|ssh-rsa" -R .
- Find email addresses:
  grep -nE "[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}" -R .
- Use tools for deeper scans: detect-secrets, truffleHog, git-secrets.

If a secret or sensitive data was committed (immediate steps)
1. Rotate credentials immediately (revoke the key or token).
2. Remove the item from git history (BFG Repo-Cleaner or git-filter-repo). Example:
   - git filter-repo --path secrets.env --invert-paths
3. Force-push cleaned history to remote (only after reviewing organizational policy):
   - git push --force
4. Notify any affected parties and follow your provider’s incident guidance.
5. Contact GitHub Support if you need help or if sensitive keys were exposed publicly.

Safe places to store sensitive prompts & profiles
- Local encrypted file (e.g., encrypted disk or file vault like VeraCrypt).
- Password manager with secure note support.
- Private GitHub Gist (if small and access-controlled) or a private repo.
- Secure team vaults (1Password, HashiCorp Vault, LastPass, etc.)

Short privacy note for prompt authors
- Replace or redact any real personal data before saving example prompts.
- Use placeholders: [FIRST NAME], [EMAIL], [PROFILE TEXT REDACTED].
- Add a short comment near examples stating: "No PII included — placeholders used."

Questions or need help?
If you want, I can:
- Add an explicit privacy warning at the top of workflow.md and relevant prompt files.
- Provide the exact BFG or git-filter-repo commands for a specific file if you find a secret.

Thank you — and good call adding this.
