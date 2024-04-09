# GenModeling Paper Study : Consistency models

This project provides an analysis, codes and experiments concerning the paper
> Song, Yang and Dhariwal, Prafulla and Chen, Mark and Sutskever, Ilya. Consistency models. arXiv preprint arXiv:2303.01469, 2023

Diffusion models, best-in-class generative models for image synthesis, can output
high fidelity images but it entails with a trade-off in generation time. Consistency
models, explored in this paper study, are a novel class of image generative models
strongly inspired from diffusion models which try to address the challenge of
generating high fidelity images faster. We first provide a brief recap on diffusion
models and introduce the theory behind consistency models. Then, we propose a
comparison of a diffusion model, a consistency model distilled from a diffusion
model and a consistency model trained from scratch on low dimensional data.
Lastly, we explore how consistency models can be used for zero-shot image editing
on an inpainting task and compare our results with those obtained with concurrent
works on diffusion models.
