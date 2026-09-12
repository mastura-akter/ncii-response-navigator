# NCII Response Navigator

A research-based LegalTech prototype implementing a victim-centred digital response workflow for Non-Consensual Intimate Image (NCII) abuse in Bangladesh.

---

## Research Foundation

This prototype implements the framework developed in the research project:

**"A Victim-Centred Legal Response Framework for Non-Consensual Intimate Image Abuse in Bangladesh"**

The research identifies that Bangladesh's legal and institutional response to NCII abuse is fragmented — survivors must navigate reporting, evidence documentation and integrity recording, platform response, and institutional processes separately.

---

## What This Prototype Does (Implemented & Working)

1. **Situation Assessment** — structured intake questions about what has happened
2. **Evidence Record & Integrity** — logs evidence entries and generates a real SHA-256 hash for each entry, computed client-side in the browser
3. **Incident Timeline** — generates a recommended response pathway based on the assessment and evidence log, referencing applicable Bangladesh channels (Police Cyber Support for Women & Children, Legal Aid, the Cyber Security Act 2026)
4. **Case Brief Generation** — compiles the above into one structured, downloadable record
5. **Selective Disclosure** — lets the user choose which information is included in packages prepared for Police/PCSW, a lawyer, or a platform report

---

## What This Prototype Does NOT Do

• No backend server or database — everything runs client-side; no data is uploaded or stored anywhere  
• No AI-generated legal advice — logic is rule-based, not AI  
• No integration with police, courts, or platforms — it structures information; it does not submit it anywhere  
• SHA-256 provides an integrity record only, not a certificate of legal admissibility  
• No pilot testing or real case data — this is a demonstration prototype  

---

## Author

**Mastura Akter**

Department of Law,
Uttara University

Sole author of the underlying research and framework. The research, framework, and design decisions are the author's own. The prototype's code was built with AI-assisted development.

---

## Project Status

✓ Submitted as part of a research poster to Uttara University for the Bangladesh Innovation Fair 2026  
✓ Selected to represent the university at the national round (September 2026)  
✓ This prototype is an implementation layer built after the original poster submission, to demonstrate the framework in practice

---

## Technologies Used

• HTML, CSS, and vanilla JavaScript (no frameworks)  
• Web Crypto API (browser-native) for SHA-256 hash generation  
• Hosted via GitHub Pages — fully client-side, no backend or database

---

## Citation

If referencing this prototype in academic work, please cite:

Akter, M. (2026). *NCII Response Navigator: A Victim-Centred LegalTech Prototype for Non-Consensual Intimate Image Abuse in Bangladesh* [Software prototype]. Uttara University. 

Project URL:
<https://mastura-akter.github.io/ncii-response-navigator/>

---

## Disclaimer

⚠️ **This is a research and demonstration prototype only.** It does not replace legal advice, police reporting, or platform reporting mechanisms.

If you are a survivor of NCII abuse in Bangladesh, you may find these official channels helpful:

• National Helpline for Violence Against Women & Children: 109 (toll-free, 24/7, all operators)  
• Police Cyber Support for Women (PCSW): 01320-000888, or call the national emergency number 999  
• National Legal Aid Services Organization (NLASO): www.nlaso.gov.bd

---

## License

MIT License

---

**A Research-Based LegalTech Prototype**

*Developed to demonstrate a victim-centred digital response workflow.*

