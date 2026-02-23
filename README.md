## Mourya Reddy Udumula

**Final-year CSE student at Indrashil University** — building security systems that hold up under adversarial conditions, and measuring precisely how much they don't.

I work at the intersection of adversarial machine learning, distributed systems, and applied cryptography. My research question is consistent across projects: *what happens when the system faces something the designer didn't test for?*

---

### Current Work

**SOC Implementation & Threat Detection Intern — CyberSpear Technologies** *(Jan 2026 – present)*  
Security operations centre infrastructure and threat detection pipelines, under Dr. Maulik Shah.

---

### Research Projects

#### 🔒 [SentinEL](https://github.com/Maze-6/SentinEL-Adversarial-ML) — Adversarial Robustness in ML Phishing Detection

ML phishing detectors achieve 97% accuracy on benchmark datasets. SentinEL measures what happens when an adversary uses Cyrillic homoglyphs — a zero-cost, visually undetectable character-encoding attack documented in real phishing toolkits.

```
97.2% → 81.4% accuracy under attack   (15.8 pp robustness gap)
< 2 ms explainability latency         (vs 50–80 ms for SHAP/LIME — 25–40× faster)
70-page technical report · Random Forest · 17-feature engineered URL space
```

#### 🗄️ [VaultZero](https://github.com/Maze-6/VaultZero-Core) — Fault-Tolerant Distributed Storage

Standard distributed key-value stores centralise cryptographic key management — a single crashed node takes the system offline; a single compromised node exposes everything. VaultZero eliminates both failure modes using Shamir's Secret Sharing and AsyncIO orchestration.

```
85% crash reduction    (37% → <5% failure rate at 1,000 concurrent requests)
+35% throughput        (2,300 → 3,100 ops/sec — side effect of removing lock contention)
Shamir SSS (k=2, n=3) · AES-256-GCM · PBKDF2 (100k iterations)
Presented at Indrashil University Research Symposium (Jan 2026)
```

---

### Professional Experience

**CyberSpear Technologies** — SOC Implementation & Threat Detection *(Jan 2026 – present)*

**Ekaantik** — Backend & Security Engineering *(Jul – Oct 2025)*
- Identified OWASP ASVS violation: plaintext authentication token logging in production; implemented sanitisation middleware fix
- Built input validation middleware — 15,000+ req/sec at < 20 ms latency for marketing APIs
- Contributed to stateful-session → JWT (RS256) migration across 12 microservices

---

### Education

**B.Tech Computer Science Engineering — Indrashil University**  
CGPA: 8.15 / 10.0 · Top 10% of cohort  
*Applying for MSc Computer Science — University College Dublin (September 2026)*

---

### Research Interests

`Adversarial Machine Learning` · `AI Security Architecture` · `Threshold Cryptography` · `Explainable AI for Security Operations` · `Distributed Systems Fault Tolerance`

---

### Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

*The interesting security problems are the ones nobody thought to test for.*

📧 [mouryaudumula@gmail.com](mailto:mouryaudumula@gmail.com)
