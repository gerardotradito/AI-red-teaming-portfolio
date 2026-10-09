# 🛡️ AI & LLM Red Teaming Portfolio
**Security Researcher specializing in Black-Box Auditing, Business Logic Abuse, and Prompt Injection.**

Hi, I'm Gerardo. I specialize in identifying and exploiting logical vulnerabilities in commercial AI systems and LLM-based assistants. My focus is entirely on conversational manipulation, context reframing, and boundary testing without the need for source code access. 

I help organizations ensure their AI deployments do not leak sensitive data, bypass commercial rules, or generate reputational risks.

## 📂 Proof of Concepts (PoCs)
Below are isolated findings from real-world commercial bots, demonstrating various attack vectors:

* **[01-Sports-Nutrition-Bot](./01-Sports-Nutrition-Bot):** Business Logic Abuse via Hypothetical Roleplay.
* **[02-Customer-Support-Bot](./02-Customer-Support-Bot):** System Prompt Leakage via Authority Impersonation.
* **[03-Electronics-Retail-Bot](./03-Electronics-Retail-Bot):** Gamification Jailbreak & Internal Logic Extraction.

*(Click on each folder to read the vulnerability description and view the evidence. Note: Target identities have been anonymized following responsible disclosure practices).*

## 🎯 Methodology
My audits follow a structured Black-Box approach:
1. **Fingerprinting & Tool Discovery:** Mapping the AI's boundaries and connected APIs.
2. **Instruction Hierarchy Testing:** Probing the rigidity of system prompts using techniques like Zero-shot, Few-shot, and Chain-of-Thought.
3. **Logic Exploitation:** Executing context reframing and roleplay scenarios to bypass commercial guardrails.
