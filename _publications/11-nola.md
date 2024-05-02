---
title: 'NOLA: Compressing LoRA using Linear Combination of Random Basis'
collection: publications
teaser: publications/11-nola
excerpt: 'NOLA is a novel method for parameter-efficient fine-tuning of LLMs and
vision models. In NOLA, we re-parameterize the low-rank matrices of LoRA using linear
combinations of randomly generated matrices (basis) and optimizing the linear
mixture coefficients only. This approach allows us to decouple the number of
trainable parameters from both the choice of rank and the network architecture and helps
overcome the rank one lower bound for number of parameters present in LoRA.
We present adaptation results using GPT-2 and ViT in natural language and
computer vision tasks. NOLA performs as well as, or better than models with
equivalent parameter counts. We can halve the
parameters in larger models compared to LoRA with rank one, without sacrificing
performance.'
date: 2023-12-14
venue: ''
paperurl: '/files/11-nola.pdf'
link: 'https://arxiv.org/abs/2310.02556'
github: 'https://github.com/UCDvision/NOLA'
width: 600
citation: 'Koohpayegani, S.A.*, <strong>Navaneet K L</strong>*, Nooralinejad, P., Kolouri, S., Pirsiavash, H., (2024). &quot;NOLA: Compressing LoRA using Linear Combination of Random Basis&quot; <i> International Conference on Learning Representations (ICLR)</i>.'
---
