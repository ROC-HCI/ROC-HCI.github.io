## Paper link

https://arxiv.org/pdf/2601.02813


## Title

HAL: Inducing Human-likeness in LLMs with Alignment


## Authors
Masum Hasan Junjie Zhao Ehsan Hoque
University of Rochester
{m.hasan@, jzhao58@u., mehoque@cs.}rochester.edu


## Abstract

Conversational human-likeness plays a central role in human-AI interaction, yet it has
remained difficult to define, measure, and optimize. As a result, improvements in human-like
behavior are largely driven by scale or broad
supervised training, rather than targeted alignment. We introduce Human Aligning LLMs
(HAL), a framework for aligning language
models to conversational human-likeness using an interpretable, data-driven reward. HAL
derives explicit conversational traits from contrastive dialogue data, combines them into a
compact scalar score, and uses this score as a
transparent reward signal for alignment with
standard preference optimization methods. Using this approach, we align models of varying sizes without affecting their overall performance. In large-scale human evaluations, a
model aligned with HAL is more frequently
perceived as human-like in conversation. Because HAL operates over explicit, interpretable
traits, it enables inspection of alignment behavior and diagnosis of unintended effects. More
broadly, HAL demonstrates how soft, qualitative properties of language–previously outside
the scope for alignment–can be made measurable and aligned in an interpretable and explainable way.


## Main figure

./static/images/main-figure.jpg

Caption: The HAL pipeline: (a) identifying human-likeness traits from contrastive dialogues (e.g. Turing tests), (b)
learning trait weights via a proxy classification task, and (c) computing a human-likeness score for alignment.

## Poster

./static/pdfs/HAL--poster.pdf


## Github

Training and inference code
https://github.com/ROC-HCI/hal


## Model Weights
https://huggingface.co/collections/roc-hci/hal-qwen14b

## Ollama
https://ollama.com/urochci/hal


## Interactive demo (Colab)
https://colab.research.google.com/drive/1Xh3hdXlZJoXjFuDsfB1daFk-T8YjML3w?usp=sharing


## Citation

```
@misc{hasan2026hal,
      title={HAL: Inducing Human-likeness in LLMs with Alignment}, 
      author={Masum Hasan and Junjie Zhao and Ehsan Hoque},
      year={2026},
      url={https://arxiv.org/abs/2601.02813}, 
}
```