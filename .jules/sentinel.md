## 2024-08-31 - [Fix Typo in Secret Scanner Regex]
**Vulnerability:** A typo in the `gitleaks` regex (`[x22]?` instead of `[\x22]?`) effectively broke the generic API key scanning for API keys surrounded by double quotes.
**Learning:** Regular expressions for secret scanners are critical and complex. Small typos can lead to widespread failure in catching secrets.
**Prevention:** Always test custom secret scanning regexes using representative positive and negative examples before relying on them to catch secrets in production or repositories.
