# 🛡️ Gerardo Tradito — AI & LLM Red Teaming & Safety Portfolio
**Founder of Aegis | Independent AI Security Researcher & Auditor**

Hi! I'm Gerardo, an independent security researcher and AI auditor specializing in **Black-Box Auditing, Business Logic Abuse, Prompt Injection, and AI Safety**. 

Through my framework **Aegis**, I help organizations harden their deployments against vulnerabilities aligned with the **OWASP Top 10 for LLMs**. I focus on conversational manipulation, context reframing, and safety boundary testing without requiring source code access.

## 📂 Proof of Concepts (PoCs)
Real-world findings from independent assessments demonstrating various attack vectors:

* **[01-Sports-Nutrition-Bot](./01-Sports-Nutrition-Bot):** Business Logic Abuse via Hypothetical Roleplay (OWASP LLM01 / LLM02).
* **[02-Customer-Support-Bot](./02-Customer-Support-Bot):** System Prompt Leakage via Authority Impersonation (OWASP LLM06).
* **[03-Electronics-Retail-Bot](./03-Electronics-Retail-Bot):** Gamification Jailbreak & Internal Logic Extraction.

*(Note: Target identities have been anonymized following responsible disclosure practices).*

## 📄 Formal Audits & Methodology
* **[04-Formal-Audits](./04-Formal-Audits):** Sample professional AI safety and audit reports conducted under the Aegis framework.

### 🎯 Core Methodology & AI Safety Standards
1. **Fingerprinting & Tool Discovery:** Mapping AI boundaries, system instructions, and connected APIs.
2. **Instruction Hierarchy & Safety Testing:** Probing prompt rigidity using Zero-shot, Few-shot, and Chain-of-Thought against alignment drift.
3. **Logic Exploitation:** Executing context reframing and roleplay scenarios to evaluate guardrails and ensure robust AI safety.
