#  JWT Security Analyzer

Analyze JSON Web Tokens (JWT) for common security risks instantly.

A lightweight developer tool that decodes JWTs and highlights potential vulnerabilities such as weak algorithms, expired tokens, and missing claims.

---

##  Features

-  Decode JWT header & payload
-  Detect expired tokens
-  Identify insecure algorithms (e.g. `alg: none`)
-  Flag long-lived tokens (security risk)
-  Detect missing claims (`iss`, `aud`)
-  Risk summary (Safe / Moderate / High)
-  Copy-to-clipboard support
-  Clean dark developer-friendly UI

---

##  Why This Matters

JWTs are widely used in authentication systems. Poor implementation can lead to serious vulnerabilities such as:

- Token forgery
- Unauthorized access
- Session hijacking

This tool helps developers quickly identify these issues.

---

##  Demo

> (Add your deployed link here later — GitHub Pages or Netlify)

---

## 📸 Screenshot

> (Add a screenshot here)

---

##  Tech Stack

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- JWT Decode Library

---

##  How It Works

1. Paste a JWT token  
2. The app decodes header & payload  
3. Security checks are applied:
   - Expiration validation
   - Algorithm safety check
   - Claim presence verification  
4. A risk level is generated  

---

##  Test Cases

Try pasting:
- Valid token
- Expired token
- `alg: none` token
- Malformed token

---

##  Installation

```bash
git clone https://github.com/your-username/jwt-security-analyzer.git
cd jwt-security-analyzer
open index.html
