## Network Port Scanner Simulator

A security tool that simulates network port scanning, identifies running services, assesses vulnerabilities, and provides actionable security recommendations.

### What It Does

Scans a target host across a user-specified port range and:
- Identifies services running on open ports (SSH, HTTP, MySQL, etc.)
- Detects known vulnerabilities for each service
- Assigns severity levels (Critical, High, Medium, Low)
- Calculates overall network risk score
- Provides specific security recommendations
- Generates a professional security report

### How It Works

The scanner uses weighted randomization (70% closed, 20% open, 10% filtered) to simulate realistic port scan results. Each open port is cross-referenced against a vulnerability database to identify security risks. Results are scored by severity and presented in a detailed report with actionable recommendations.

### Features

- **Service Database** — Maps 13+ common ports to their services and known vulnerabilities
- **Risk Scoring** — Critical=5pts, High=3pts, Medium=1pt, Low=0pts
- **Network Health Assessment** — Rates overall security posture (Secure, Caution, At Risk, Critical)
- **Professional Output** — Formatted tables, detailed vulnerability list, and specific recommendations

### Test Cases

**Test 1:** Host=google.com, Range=20-80 → Shows mixed results with recommendations

**Test 2:** Host=localhost, Range=443-443 → Single port check

**Test 3:** Host=example.com, Range=1-1000 → Large-scale scan with summary

### Note

This is an educational simulator, not a real port scanner. It demonstrates vulnerability assessment concepts without performing actual network connections.
