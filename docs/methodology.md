# Methodology Overview

This document gives a high-level, public description of the research workflow. Implementation details and training code are intentionally kept private.

## 1. Text preparation

Yorùbá text was prepared for language modelling while retaining language-specific orthographic information, including diacritics.

## 2. Tokenisation and vocabulary

The corpus was converted into tokens and mapped into a numerical vocabulary suitable for neural-network training.

## 3. Sequence generation

Training examples were generated as ordered word sequences so that earlier words formed the context and the subsequent word formed the prediction target.

## 4. Neural language modelling

The research investigated LSTM-based sequence models, including:

- a baseline LSTM;
- a stacked LSTM; and
- an attention-enhanced recurrent model.

## 5. Evaluation

The models were compared using language-model and prediction-oriented evaluation to examine how well each architecture captured contextual patterns in Yorùbá text.

## 6. Language-specific consideration

Yorùbá diacritics can distinguish words that would otherwise share the same base spelling. Preserving them is therefore an important modelling decision rather than a purely cosmetic preprocessing choice.

For the complete experimental setup, results and discussion, see the published article:

https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651
