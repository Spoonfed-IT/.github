# Spoonfed IT Solutions

Welcome to the engineering organization for **Spoonfed IT Solutions**.

## Engineering Principles
- **Strict Tenant & Repository Isolation:** Dedicated private repositories for every client project under formal SOW milestones.
- **Branch Isolation:** No direct commits to main. All work happens in isolated feature branches matching eat/{CUST_ID}/{TASK_ID}-{slug}.
- **Automated Verification Harness:** Pre-merge linting, unit/contract testing, Gitleaks secret scanning, and CVE audits.
- **Zero Secret Spills:** DevContainer environment isolation with 1Password (op run) secret injection.