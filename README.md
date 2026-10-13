# ISMS-Risikoanalyse – Noventis Group GmbH

![Status](https://img.shields.io/badge/Status-in%20Arbeit-yellow)
![Standard](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-blue)
![Autor](https://img.shields.io/badge/Autor-Ilker%20Acikg%C3%B6z-red)
![Jahr](https://img.shields.io/badge/Jahr-2026-lightgrey)
![Sprache](https://img.shields.io/badge/Sprache-Deutsch-brown)

Eine praxisorientierte Fallstudie zur **systematischen Identifikation, Bewertung und Behandlung von Informationssicherheitsrisiken** nach ISO/IEC 27001:2022 – durchgeführt anhand des fiktiven Unternehmens *Noventis Group GmbH*.

> **Hinweis:** Dies ist eine reine Lern- und Demonstrationsarbeit. Es handelt sich weder um ein Audit noch um eine Zertifizierung. Alle Unternehmensdaten sind fiktiv.

---

## Ziel des Projekts

Ziel ist es, den vollständigen Risikomanagement-Prozess eines ISMS exemplarisch durchzuführen:

1. Risiken identifizieren
2. Risiken bewerten (Eintrittswahrscheinlichkeit × Auswirkung)
3. Maßnahmen vorschlagen
4. Restrisiken betrachten
5. Ergebnisse dokumentieren

---

## Unternehmensprofil 

| Merkmal | Beschreibung |
|---|---|
| Name | Noventis Group GmbH (fiktiv) |
| Hauptsitz | Nürnberg, Deutschland |
| Mitarbeitende | ca. 4.800 |
| Standorte | 12 weitere in Europa |
| Geschäftsfeld | B2B-Technologie, IT-Dienstleistungen, Beratung |
| IT-Landschaft | Hybride Cloud- & Rechenzentrumsumgebung |

→ [Vollständiges Unternehmensprofil](docs/01_unternehmensprofil.md)

---

## Methodik & Scope

- **Standard:** ISO/IEC 27001:2022, ergänzend ISO/IEC 27005
- **Bewertungsmodell:** 5×5-Matrix (Wahrscheinlichkeit × Auswirkung)
- **Risikowert:** 1–25, priorisiert in vier Stufen (niedrig / mittel / hoch / kritisch)
- **Scope:** Zentrale IT-Dienste, Cloud, Entwicklungsumgebungen, vertrauliche Kundendaten, Backup, Zugriffsverwaltung

---

isms-risikoanalyse-noventis/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── 01_unternehmensprofil.md
│   ├── 02_scope.md
│   ├── 03_methodik.md
│   ├── 04_bewertungsskalen.md
│   └── 05_annahmen_und_grenzen.md
│
├── datenschutz/
│   ├── README.md
│   └── VVT_Noventis.xlsx
│
├── risikoregister/
│   ├── README.md
│   └── Risikoregister_Noventis.xlsx
│
├── massnahmen/
│   ├── README.md
│   └── Risikobehandlungsplan.md
│
├── berichte/
│   ├── README.md
│   └── Risikobericht_Noventis.md
│
└── assets/
    ├── risikomatrix.png
    ├── organigramm.png
    └── it-landschaft.png
