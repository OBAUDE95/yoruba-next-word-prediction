\# Yorùbá Next-Word Prediction with Deep Learning



Research showcase for neural next-word prediction in the Yorùbá language using Long Short-Term Memory (LSTM) neural networks.



This repository accompanies my published research:



\*\*Next Word Prediction in Yorùbá Text: A Long Short Term Memory Approach\*\*

\*INFOCOMP Journal of Computer Science\*

Published: \*\*14 August 2026\*\*



📄 \[Read the published article](https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651)



👤 \[ORCID: 0009-0008-7831-6255](https://orcid.org/0009-0008-7831-6255)



\---



\## Overview



Next-word prediction is an important task in Natural Language Processing (NLP) and is used in applications such as:



\* Predictive keyboards

\* Text completion

\* Writing assistance

\* Language modelling

\* Conversational AI



However, many African languages remain underrepresented in modern NLP research and language technologies.



This research investigates the application of deep learning to \*\*next-word prediction for Yorùbá\*\*, a tonal and diacritic-rich language spoken primarily in West Africa.



The work explores how neural sequence models can learn contextual patterns in Yorùbá text and predict likely subsequent words.



\---



\## Research Objective



The primary objective of this research was to investigate the effectiveness of LSTM-based neural networks for modelling sequential patterns in Yorùbá text.



The project focused on:



\* Preparing Yorùbá text for neural language modelling

\* Preserving important Yorùbá orthographic information

\* Training recurrent neural-network architectures

\* Comparing different LSTM-based approaches

\* Evaluating next-word prediction performance

\* Investigating challenges associated with low-resource language modelling



\---



\## Why Yorùbá NLP?



Yorùbá presents several interesting NLP challenges.



The language makes extensive use of diacritics, and removing them can create ambiguity between words that have different meanings.



For example, language technologies developed primarily for English cannot simply be transferred to Yorùbá without accounting for its linguistic characteristics.



This makes Yorùbá an important case study in \*\*low-resource and language-specific NLP\*\*.



\---



\## Machine Learning Pipeline



```text

Yorùbá Text

&#x20;    ↓

Text Cleaning

&#x20;    ↓

Tokenisation

&#x20;    ↓

Sequence Generation

&#x20;    ↓

Vocabulary Construction

&#x20;    ↓

Embedding Layer

&#x20;    ↓

LSTM-based Neural Network

&#x20;    ↓

Probability Distribution

&#x20;    ↓

Next-Word Prediction

```



\---



\## Models Investigated



The research explored LSTM-based architectures for sequential language modelling.



\### LSTM



A Long Short-Term Memory network learns relationships between words across sequences while reducing some of the limitations associated with traditional recurrent neural networks.



\### Stacked LSTM



Multiple LSTM layers can be combined to allow the network to learn increasingly complex sequential representations.



\### Attention-Enhanced Modelling



Attention mechanisms can help a model assign different levels of importance to previous contextual information when making predictions.



The experiments were designed not only to identify model performance but also to better understand the behaviour of different neural architectures when applied to Yorùbá.



\---



\## Evaluation



Model performance was evaluated using language-modelling and prediction-oriented evaluation methods.



Evaluation considered the ability of each model to predict contextually appropriate subsequent words rather than relying solely on training loss.



Detailed experimental results are documented in the published paper.



\---



\## Key Research Insight



One important observation from this work is the importance of preserving \*\*Yorùbá diacritics\*\*.



Removing diacritics can introduce homographs and semantic ambiguity, which can negatively affect the quality of language modelling.



This highlights an important principle in low-resource NLP:



> Language-specific characteristics should be treated as part of the modelling problem rather than removed simply to make preprocessing easier.



\---



\## Applications



Research in Yorùbá next-word prediction can contribute to the development of:



\* Yorùbá predictive keyboards

\* Intelligent text-completion systems

\* Writing assistants

\* Educational applications

\* Speech and language technologies

\* African-language Large Language Models

\* Accessibility technologies



\---



\## Research Contribution



My contributions to the published research included:



\* Conceptualization

\* Methodology

\* Data curation

\* Validation

\* Visualization

\* Writing – original draft



The research was conducted with:



\*\*Ayodeji Obaude\*\*

\*\*Ezekiel Oyekanmi\*\*

\*\*Joshua Tom\*\*



\---



\## Publication



\*\*Obaude, A., Oyekanmi, E., \& Tom, J.\*\*



\*Next Word Prediction in Yorùbá Text: A Long Short Term Memory Approach.\*



INFOCOMP Journal of Computer Science, 2026.



🔗 https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651



\---



\## Source Code



The research implementation, training notebooks, model artifacts and experimental source code are maintained privately.



This public repository is intended to document:



\* The research problem

\* Machine-learning methodology

\* Experimental approach

\* Key findings

\* Research impact



The absence of source code does not affect access to the published research, which is available through the journal link above.



\---



\## Current Research Direction



This work forms part of my broader interest in:



\* Low-resource NLP

\* African-language AI

\* Neural language modelling

\* Diacritic-aware NLP

\* Deep learning

\* Efficient language models

\* Human-centred language technology



Future work includes exploring stronger neural architectures and practical Yorùbá language technologies.



\---



\## Author



\*\*Obaude Ayodeji Michael\*\*



Data Scientist | Machine Learning Engineer | Applied AI Researcher



Research interests:



`Machine Learning` • `Deep Learning` • `NLP` • `Generative AI` • `Low-Resource Languages`



\* ORCID: https://orcid.org/0009-0008-7831-6255

\* LinkedIn: https://www.linkedin.com/in/ayodeji-obaude-79b5051b2

\* GitHub: https://github.com/OBAUDE95



\---



\## Note



This repository is a research showcase. Proprietary or private implementation artifacts are intentionally not included.



