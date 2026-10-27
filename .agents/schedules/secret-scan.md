---
name: Secret scan
schedule: 0 6 * * *
---

Scan commits pushed to any branch in the last 24 hours for committed secrets: API keys, tokens, private keys, passwords, connection strings, and .env files. Report the commit, file, line, author, and secret type, and say which credential needs rotating. Never print the secret value.
