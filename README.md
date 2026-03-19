# Explainable Federated Learning for Secure Telemedicine

**Protecting Patient Identity through Privacy-Preserving Deepfake Detection in Digital Health Platforms**

> Extended Abstract presentato al CIDE 2025

**Autori:** Raimondo Fanale, Fabio Liberti, Vittorio Stile
**Affiliazione:** University of the Italian Chambers of Commerce (Universitas Mercatorum)

---

## Obiettivi

La telemedicina europea, cresciuta da 45 a 380 miliardi di euro nel post-pandemia, e' esposta a una vulnerabilita' critica: i **deepfake medici**. I tradizionali controlli via webcam e documenti d'identita' statici sono ormai facilmente aggirabili.

Questo studio propone l'**Explainable Federated Learning (XFL)** come standard di verifica dell'identita' per i sistemi di telemedicina, con tre obiettivi:

1. **Privacy** — Evidenziare le violazioni di privacy nei metodi centralizzati di rilevamento deepfake e dimostrare come il federated learning promuova la sovranita' dei dati
2. **Regolamentazione** — Proporre framework normativi con tempistiche, standard di compliance e sanzioni per l'adozione obbligatoria di XFL
3. **Analisi economica** — Dimostrare che l'implementazione proattiva e' meno costosa delle perdite per frode d'identita' medica

## Metodologia

L'architettura tecnica si basa su una **topologia federata gerarchica a tre livelli**:

| Livello | Componente | Funzione |
|---------|-----------|----------|
| Tier-1 | Grandi reti ospedaliere (>500 posti letto) | Potenza computazionale e dati demografici diversificati |
| Tier-2 | Sistemi di telemedicina | Pattern di attacco dominio-specifici |
| Tier-3 | Dispositivi edge | Verifica in tempo reale |

**Aspetti chiave del design:**

- **Differential privacy** (epsilon = 1.5) per mantenere i dati biometrici entro i confini istituzionali
- Mappatura sugli articoli GDPR 25 (Privacy-by-Design) e 32 (Sicurezza del Trattamento)
- Classificazione dei rilevatori deepfake come software **Classe IIa** sotto il Medical Device Regulation (MDR)
- Conformita' con l'**AI Act** europeo per applicazioni ad alto rischio
- Modellazione economica basata su dati di mercato di 15 piattaforme di telehealth europee

## Risultati Preliminari

- Il **94%** dei sistemi di telemedicina europei non dispone di rilevamento deepfake; il restante 6% utilizza sistemi centralizzati potenzialmente in violazione del GDPR
- Le tecniche federate rilevano i deepfake con un'accuratezza del **97.8%** (vs 99.2% dei sistemi centralizzati), ma garantiscono l'anonimato completo
- Costo di implementazione: **2-3 milioni di euro** per piattaforma chiave (~0.5% del fatturato annuo)
- Un singolo deepfake medico pubblico potrebbe costare oltre **500 milioni di euro** in danni diretti

**Piano di adozione in tre fasi:**

| Fase | Periodo | Azione |
|------|---------|--------|
| 1 | 2025-2026 | Adozione volontaria con incentivi fiscali e riduzione della responsabilita' |
| 2 | 2027 | Obbligo per le nuove piattaforme |
| 3 | 2028+ | Obbligo universale con sanzioni per la non-conformita' |

## Implicazioni

Il sistema offre output interpretabili per tutti gli stakeholder:

- **Pazienti** — Spiegazioni in linguaggio naturale e supporto visivo
- **Medici** — Dashboard con livelli di confidenza tecnica e pattern anomali
- **Regolatori** — Registri tamper-proof per la verifica della compliance

Lo studio evidenzia come l'aggiunta di livelli di verifica federata migliori sicurezza e privacy senza rendere obsoleti gli investimenti infrastrutturali esistenti.

## Keywords

`Explainable AI` `Deepfake Detection` `Federated Learning` `Medical Privacy` `GDPR Compliance` `Digital Health Regulation`

## Riferimenti Principali

- Stile V. et al. — *Analysis of DeepFake Detection through Semi-Supervised Facial Attribute Labeling*, 2024
- Liberti F. et al. — *Federated Learning in Dynamic and Heterogeneous Environments*, Applied Sciences, 2024
- Bergamini M. et al. — *Weak signals in Science and Technologies*, Publications Office of the EU, 2025
- Ali Z. et al. — *Enhancing deepfake content detection through blockchain technology*, SAI Organization, 2025
- Ayorinde A.S. — *Explainable Deep Learning Models for Detecting Sophisticated Cyber-Enabled Financial Fraud*, 2025
- Ndibe O.S. — *AI-Driven Forensic Systems for Real-Time Anomaly Detection and Threat Mitigation*, 2025

## Struttura del Progetto

```
CIDE2/
├── paper/
│   └── P-C2_CIDE2025_FL_XAI_DeepFake.pdf   # Extended abstract completo
└── README.md
```

## Licenza

Per informazioni sulla licenza e sull'utilizzo, contattare gli autori.
