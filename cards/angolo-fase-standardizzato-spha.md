---
title: "Angolo di Fase Standardizzato (SPhA)"
tags:
  - bia
  - composizione-corporea
  - pha
  - prognosi
  - salute-cellulare
difficulty: 4
language: it
---

L'**Angolo di Fase Standardizzato** (SPhA - Standardized Phase Angle) è l'angolo di fase **convertito in Z-score**, cioè espresso come numero di deviazioni standard dalla media di riferimento per età e sesso. Permette confronti più accurati tra soggetti diversi.

## Formula

```text
SPhA = (PhA osservato - PhA di riferimento) / SD di riferimento
```

Dove:
- **PhA osservato** = Angolo di fase misurato nel soggetto
- **PhA di riferimento** = Media per età e sesso dalla popolazione di riferimento
- **SD** = Deviazione standard della popolazione di riferimento

## Perché Standardizzare il PhA

| Problema del PhA grezzo | Soluzione con SPhA |
|-------------------------|-------------------|
| Varia con età | Corretto per età |
| Varia con sesso | Corretto per sesso |
| Difficile confrontare soggetti | Z-score comparabile |
| Dipende dal dispositivo | Più standardizzato |

## Formula dell'Angolo di Fase

Ricordiamo che il PhA si calcola:

```text
PhA (°) = arctan (Xc / R) × (180° / π)
```

Dove:
- **Xc** = Reattanza (capacitanza delle membrane)
- **R** = Resistenza

## Interpretazione dello SPhA (Z-score)

| SPhA | Interpretazione |
|------|-----------------|
| > 0 | Sopra la media per età/sesso |
| 0 | Nella media |
| -1 a 0 | Leggermente sotto la media |
| -1.65 a -1 | Sotto la media (attenzione) |
| < -1.65 | Significativamente basso (5° percentile) |
| < -2 | Molto basso (rischio aumentato) |

## SPhA come Indicatore Prognostico

Il valore **-1.65** è un cut-off clinicamente significativo:

| SPhA | Rischio | Significato |
|------|---------|-------------|
| ≥ -1.65 | Standard | Nella norma per età/sesso |
| < -1.65 | Aumentato | 5° percentile inferiore |

## Evidenze Cliniche

### Pazienti Oncologici

Uno studio su pazienti con cancro ha dimostrato:

| SPhA | Sopravvivenza |
|------|---------------|
| ≥ -1.65 | Migliore |
| < -1.65 | RR mortalità 3.12 (CI: 2.03-4.79) |

### COVID-19

In pazienti con COVID-19:

| SPhA | Mortalità a 90 giorni |
|------|----------------------|
| ≥ -1.65 | Minore |
| < -1.65 | Significativamente maggiore |

### Infarto Miocardico

In pazienti post-infarto, l'SPhA predice eventi cardiovascolari a breve e lungo termine.

## Vantaggi dello SPhA

| Vantaggio | Descrizione |
|-----------|-------------|
| Standardizzato | Confrontabile tra età e sessi diversi |
| Prognostico | Validato come predittore di mortalità |
| Interpretabile | Z-score facilmente comprensibile |
| Corretto | Tiene conto della variabilità fisiologica |

## Quando Usare SPhA vs PhA

| Situazione | Usare |
|------------|-------|
| Valutazione clinica generale | PhA grezzo |
| Confronto con valori di riferimento | PhA grezzo |
| Studi prognostici | SPhA |
| Confronto tra popolazioni diverse | SPhA |
| Pazienti oncologici | SPhA |
| Predizione outcomes | SPhA |

## Valori di Riferimento PhA (per calcolare SPhA)

### Uomini

| Età | PhA medio | SD |
|-----|-----------|-----|
| 20-29 | 7.5° | 0.8 |
| 30-39 | 7.3° | 0.9 |
| 40-49 | 7.0° | 0.9 |
| 50-59 | 6.7° | 1.0 |
| 60-69 | 6.3° | 1.0 |
| 70-79 | 5.8° | 1.1 |
| > 80 | 5.2° | 1.2 |

### Donne

| Età | PhA medio | SD |
|-----|-----------|-----|
| 20-29 | 6.5° | 0.7 |
| 30-39 | 6.3° | 0.8 |
| 40-49 | 6.0° | 0.8 |
| 50-59 | 5.7° | 0.9 |
| 60-69 | 5.4° | 0.9 |
| 70-79 | 5.0° | 1.0 |
| > 80 | 4.5° | 1.1 |

*Nota: i valori di riferimento variano tra studi e popolazioni*

## Esempio di Calcolo

Donna, 65 anni, PhA misurato = 4.5°

```text
PhA riferimento (60-69, F) = 5.4°
SD = 0.9°

SPhA = (4.5 - 5.4) / 0.9 = -0.9 / 0.9 = -1.0
```

Interpretazione: SPhA = -1.0 → Leggermente sotto la media, ma sopra il cut-off di -1.65

## Limiti dello SPhA

| Limite | Descrizione |
|--------|-------------|
| Riferimenti | Dipende dalla popolazione di riferimento usata |
| Dispositivi | Variazioni tra strumenti BIA |
| Frequenza | Il PhA è misurato a 50 kHz per convenzione |
| Popolazioni speciali | Riferimenti non sempre disponibili |

## Applicazioni Cliniche

Lo SPhA è particolarmente utile in:

- Oncologia (predizione sopravvivenza)
- Terapia intensiva (outcomes)
- Nefrologia (pazienti in dialisi)
- Cardiologia (post-infarto)
- Geriatria (fragilità)
- Nutrizione clinica (malnutrizione)

## In due parole

> "L'angolo di fase standardizzato (SPhA) è il PhA convertito in Z-score, cioè espresso come deviazioni standard dalla media per età e sesso. Un SPhA sotto -1.65 (5° percentile) indica un rischio significativamente aumentato di mortalità e complicanze. È particolarmente utile in oncologia e terapia intensiva per predire gli outcomes dei pazienti."

---

**Fonti**:
- [PubMed - SPhA as prognostic factor in cancer](https://pubmed.ncbi.nlm.nih.gov/20039074/)
- [PMC - Phase angle and COVID-19 mortality](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7886631/)
- [PMC - Bioimpedance basics and phase angle](https://pmc.ncbi.nlm.nih.gov/articles/PMC10140124/)
- [PubMed - SPhA and cardiovascular events](https://pubmed.ncbi.nlm.nih.gov/35872408/)
