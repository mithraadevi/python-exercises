## Phishing URL Detector

Analyzes suspicious URLs and assigns a risk score based on common phishing patterns.

Checks:
- Protocol security (HTTPS vs HTTP)
- Suspicious keywords (login, verify, paypal, etc.)
- IP addresses instead of domain names

The detector scans for multiple red flags and provides a verdict:
- 0 = Safe
- 1-2 = Caution
- 3+ = High Risk / Avoid

Built as part of cybersecurity education to understand phishing tactics.
