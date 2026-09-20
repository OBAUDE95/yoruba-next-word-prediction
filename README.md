# Yorùbá Next-Word Prediction with Deep Learning

> Research showcase for neural next-word prediction in Yorùbá using LSTM-based language models.

This repository documents the research behind my 2026 publication:

**Next Word Prediction in Yorùbá Text: A Long Short Term Memory Approach**  
*INFOCOMP Journal of Computer Science* — published 14 August 2026

[Read the published article](https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651) · [ORCID](https://orcid.org/0009-0008-7831-6255)

---

## Project at a glance

| Area | Details |
|---|---|
| Domain | Natural Language Processing |
| Language | Yorùbá |
| Task | Next-word prediction |
| Approach | LSTM-based neural language modelling |
| Research focus | Low-resource NLP and diacritic-aware text modelling |
| Publication | INFOCOMP Journal of Computer Science, 2026 |
| Source code | Kept private; this repository is the public research showcase |

## Why this project matters

Most modern language technologies are built around high-resource languages. Yorùbá introduces additional challenges because meaning can depend on diacritics, while high-quality training resources are comparatively limited.

This work investigates whether recurrent neural language models can learn useful contextual patterns from Yorùbá text and support next-word prediction for applications such as predictive keyboards, writing assistants, educational tools and other African-language NLP systems.

## Research objective

The study focused on:

- preparing Yorùbá text for neural language modelling;
- preserving language-specific orthographic information;
- generating sequential training examples;
- training and comparing LSTM-based architectures;
- evaluating next-word prediction behaviour; and
- examining challenges specific to low-resource language modelling.

## Modelling pipeline

```text
Yorùbá text
    ↓
Text preparation
    ↓
Tokenisation
    ↓
Sequence generation
    ↓
Vocabulary construction
    ↓
Embedding representation
    ↓
LSTM-based language model
    ↓
Probability distribution over vocabulary
    ↓
Next-word prediction
```

## Architectures investigated

### LSTM
A recurrent neural architecture designed to learn dependencies across word sequences.

### Stacked LSTM
Multiple LSTM layers used to learn deeper sequential representations.

### Attention-enhanced model
A recurrent architecture augmented with attention so that the model can place different emphasis on prior contextual information.

## Key research insight

A central lesson from the study is that **Yorùbá diacritics are not cosmetic preprocessing details**.

Removing them can collapse distinct written forms into ambiguous representations. For low-resource NLP, preprocessing decisions therefore need to respect the structure of the language rather than simply simplify the text.

## What this project demonstrates

For data science and machine-learning roles, this project demonstrates experience with:

- NLP problem formulation;
- sequence modelling and deep learning;
- data preparation for low-resource languages;
- experimental model comparison;
- evaluation of language models;
- research methodology and validation; and
- communicating technical findings through peer-reviewed research.

## Publication

**Obaude, A., Oyekanmi, E., & Tom, J.**  
*Next Word Prediction in Yorùbá Text: A Long Short Term Memory Approach.*  
INFOCOMP Journal of Computer Science, 2026.

**Article:** https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651

## My contribution

My recorded contributions to the publication include:

- Conceptualization
- Methodology
- Data curation
- Validation
- Visualization
- Writing — original draft

Co-authors: **Ezekiel Oyekanmi** and **Joshua Tom**.

## Code availability

The training notebooks, implementation code, model artifacts and experimental working files are **not included in this public repository**.

This repository is intentionally maintained as a public research and portfolio showcase containing only information suitable for public release.

## Research interests

This work sits within my broader interests in:

`Machine Learning` · `Deep Learning` · `NLP` · `Low-Resource Languages` · `Generative AI` · `Applied AI`

## Author

**Obaude Ayodeji Michael**  
Data Scientist · Machine Learning Engineer · Applied AI Researcher

[ORCID](https://orcid.org/0009-0008-7831-6255) · [LinkedIn](https://www.linkedin.com/in/ayodeji-obaude-79b5051b2) · [GitHub](https://github.com/OBAUDE95)
