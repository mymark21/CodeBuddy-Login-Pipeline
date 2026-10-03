# CodeBuddy Login Pipeline

Headless-captured WeChat login QR for CodeBuddy / WorkBuddy account onboarding.

- `current/` — the newest QR (overwritten on every capture)
- `archive/<timestamp>/` — every previous QR, kept for auditing

Published at: https://mymark21.github.io/CodeBuddy-Login-Pipeline/

**The QR expires ~10 minutes after capture.** Credentials (`state`) are never published.
