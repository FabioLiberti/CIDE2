# Explainable Federated Learning for Secure Telemedicine

**Protecting Patient Identity through Privacy-Preserving Deepfake Detection in Digital Health Platforms**

> Extended Abstract presented at CIDE 2025

**Authors:** Raimondo Fanale, Fabio Liberti, Vittorio Stile
**Affiliation:** University of the Italian Chambers of Commerce (Universitas Mercatorum)

---

## Aims

European telemedicine, which grew from €45B to €380B post-pandemic, faces a critical vulnerability: **medical deepfakes**. Traditional webcam checks and static ID images are now easily bypassed by deepfake technology.

This study proposes **Explainable Federated Learning (XFL)** as the identity verification standard for telemedicine systems, with three goals:

1. **Privacy** — Highlight fundamental privacy breaches in centralized deepfake detection methods and demonstrate how federated approaches uniquely promote data sovereignty
2. **Regulation** — Propose real regulatory frameworks with timetables, compliance standards, and penalties to mandate XFL adoption
3. **Economic analysis** — Show that proactive implementation is typically cheaper than medical identity fraud losses

## Methodology

The technical design uses a **three-level hierarchical federated topology**:

| Tier | Component | Function |
|------|-----------|----------|
| Tier-1 | Large hospital networks (>500 beds) | Computational power and diverse patient demographics |
| Tier-2 | Telemedicine systems | Domain-specific attack patterns |
| Tier-3 | Edge devices | Real-time verification |

**Key design aspects:**

- **Differential privacy** (ε = 1.5) to keep biometric data inside institutional boundaries
- Mapping to GDPR Articles 25 (Privacy-by-Design) and 32 (Security-of-Processing)
- Classification of deepfake detectors as **Class IIa** software under the Medical Device Regulation (MDR)
- Compliance with the European **AI Act** for high-risk applications
- Economic modeling based on market data from 15 European telehealth platforms

## Preliminary Results

- **94%** of European telemedicine systems lack deepfake detection; the remaining 6% rely on centralized systems that may violate GDPR data minimization restrictions
- Federated techniques detect deepfakes with **97.8%** accuracy (vs 99.2% for centralized settings), while providing total anonymity
- Implementation cost: **€2–3 million** per key platform (~0.5% of annual revenue)
- A single public medical deepfake could cost over **€500 million** in direct losses

**Three-phase adoption plan:**

| Phase | Period | Action |
|-------|--------|--------|
| 1 | 2025–2026 | Voluntary adoption with tax advantages and reduced liability |
| 2 | 2027 | Mandatory for new platforms |
| 3 | 2028+ | Universal mandate with penalties for non-compliance |

## Implications

The system provides interpretable outputs for all stakeholders:

- **Patients** — Plain-language explanations and visual support
- **Clinicians** — Dashboards showing technical confidence levels and anomalous patterns
- **Regulators** — Tamper-proof records for compliance verification

Adding federated verification levels improves security and privacy without making existing infrastructure investments obsolete. Deepfake detection without explainability could make healthcare access harder for the elderly and tech-illiterate.

## Keywords

`Explainable AI` `Deepfake Detection` `Federated Learning` `Medical Privacy` `GDPR Compliance` `Digital Health Regulation`

## Key References

- Stile V. et al. — *Analysis of DeepFake Detection through Semi-Supervised Facial Attribute Labeling*, 2024
- Liberti F. et al. — *Federated Learning in Dynamic and Heterogeneous Environments*, Applied Sciences, 2024
- Bergamini M. et al. — *Weak signals in Science and Technologies*, Publications Office of the EU, 2025
- Ali Z. et al. — *Enhancing deepfake content detection through blockchain technology*, SAI Organization, 2025
- Ayorinde A.S. — *Explainable Deep Learning Models for Detecting Sophisticated Cyber-Enabled Financial Fraud*, 2025
- Ndibe O.S. — *AI-Driven Forensic Systems for Real-Time Anomaly Detection and Threat Mitigation*, 2025

## Project Structure

```
CIDE2/
├── paper/
│   └── P-C2_CIDE2025_FL_XAI_DeepFake.pdf   # Full extended abstract
└── README.md
```

## License

For licensing and usage information, please contact the authors.
