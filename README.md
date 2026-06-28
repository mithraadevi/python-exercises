# Python Exercises
Practising Python through samll scripts and projects as I learn.

## Projects
1. **password_checker.ipynb** - checks password based on length, character variety, and common patterns. Built while learning Python Basics during CS50P
2. **caesar_cipher.ipynb** - A simple encoder/decoder implementing the Caesar Cipher — one of the earliest known encryption techniques. Takes a message and a shift key, then encodes or decodes text by shifting each letter's position in the alphabet.
- **hash_checker.ipynb** - Generates SHA256 hashes for text input using Python's hashlib library. Demonstrates how hashing is used to verify data integrity — the same concept used to detect if a file has been altered or tampered with.
- **IPv4_validator.ipynb** - Checks whether a given string is a valid IPv4 address. Validates format (4 segments) and range (0-255 per segment) — a small but practical networking + Python exercise.
- **login_simulator.ipynb** - A basic login system that locks the user out after 3 failed attempts. Demonstrates a simple brute-force protection mechanism — a fundamental security control used in real authentication systems.
- **phishing_url_detector.ipynb** - Analyzes suspicious URLs and assigns a risk score based on common phishing patterns.
  Checks:
      - Protocol security (HTTPS vs HTTP)
      - Suspicious keywords (login, verify, paypal, etc.)
      - IP addresses instead of domain names

   The detector scans for multiple red flags and provides a verdict:
      - 0 = Safe
      - 1-2 = Caution
      - 3+ = High Risk / Avoid
   Built as part of cybersecurity education to understand phishing tactics.
- **xor_encryption_decryption.ipyb** - Encrypts text using XOR encryption with a secret key. How it works: The same key that encrypts also decrypts. This is symmetric encryption. XOR is simple but demonstrates the concept — real systems use stronger algorithms like AES.
- **ping_simulator.ipynb** - Simulates the ping command to test host reachability and latency. Generates realistic response times (10-200ms) and random packet loss to demonstrate how network diagnostics work. Shows min/max/average latency and connection quality.
- **port_scanner.ipynb** - Simulates port scanning, identifies services, detects vulnerabilities, and provides security recommendations. Maps open ports to services (SSH, HTTP, MySQL, etc.) and assigns risk scores based on severity. Shows overall network health and actionable fixes.
