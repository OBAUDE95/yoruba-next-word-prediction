# Experimental Results

The values below are taken from the final published version of:

**Next Word Prediction in Yorùbá Text: A Long Short Term Memory Approach**  
INFOCOMP Journal of Computer Science, 2026.

## Model comparison

| Model | Top-3 Accuracy | Top-4 Accuracy | Top-5 Accuracy | Perplexity |
|---|---:|---:|---:|---:|
| **Vanilla LSTM** | **48.96%** | **50.95%** | **52.49%** | **165.90** |
| Stacked LSTM | 46.63% | 48.66% | 49.91% | 273.55 |
| Attention LSTM | 45.40% | 47.58% | 48.91% | 286.26 |

Lower perplexity is better. Higher Top-k accuracy is better.

The Vanilla LSTM achieved the strongest reported performance across the main evaluation metrics.

## Statistical significance

Pairwise McNemar tests with Bonferroni correction reported:

| Comparison | Chi-square | p-value | Significant |
|---|---:|---:|---|
| Vanilla vs Stacked | 9.47 | 0.002 | Yes |
| Vanilla vs Attention | 19.37 | <0.001 | Yes |
| Stacked vs Attention | 2.01 | 0.156 | No |

## Dropout ablation

| Metric | With Dropout | Without Dropout |
|---|---:|---:|
| Top-3 Accuracy | 48.96% | 47.78% |
| Top-4 Accuracy | 50.95% | 49.71% |
| Top-5 Accuracy | 52.49% | 51.00% |
| Perplexity | 165.90 | 410.78 |

Removing dropout worsened the main reported metrics, particularly perplexity.

## Diacritic-preservation ablation

| Metric | With Diacritics | Without Diacritics |
|---|---:|---:|
| Vocabulary Size | 3,091 | 2,358 |
| Top-3 Accuracy | 48.96% | 50.77% |
| Top-4 Accuracy | 50.95% | 53.80% |
| Top-5 Accuracy | 52.49% | 56.16% |
| Perplexity | 165.90 | 84.96 |

The apparent numerical improvement after removing diacritics should be interpreted carefully. Removing diacritics reduced the vocabulary and collapsed distinct Yorùbá forms into homographs, making the task easier while losing linguistic distinctions.

## User evaluation

The study also reports a user evaluation with **12 Yorùbá speakers**, with an average overall performance rating of **4.5**.

## Publication

https://infocomp.dcc.ufla.br/index.php/infocomp/article/view/5467/651
