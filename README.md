# Awesome-antibody WIP🚧 <!-- omit in toc -->
An curated list of machine learning(ML) &amp; artificial intelligence(AI) methods for antibody. Inspired by [Machine-learning-for-proteins](https://github.com/yangkky/Machine-learning-for-proteins).

## Categories <!-- omit in toc -->
- [Data](#data)
- [Antibody structure prediction](#antibody-structure-prediction)
- [Antibody design and optimization](#antibody-design-and-optimization)
- [Pretrained language model](#pretrained-language-model)


## Data

1. Absolut!

## Antibody structure prediction

- IgFold


## Antibody design and optimization

1. Shanehsazzadeh, Amir, Sharrol Bachas, George Kasun, John M. Sutton, Andrea K. Steiger, Richard Shuai, Christa Kohnert, et al. 2023. “**Unlocking de Novo Antibody Design with Generative Artificial Intelligence.**” bioRxiv. [https://doi.org/10.1101/2023.01.08.523187](https://doi.org/10.1101/2023.01.08.523187).

This work (by AI+antibody biotech company Absci) demonstrates that the approach of combining high-throughput affinity measurements and generative AI can accelerate drug(antibody) discovery. The data was made [open-sourced](https://github.com/AbsciBio/unlocking-de-novo-antibody-design).

A previous work of Absci on the same topic:

Bachas, Sharrol, Goran Rakocevic, David Spencer, Anand V. Sastry, Robel Haile, John M. Sutton, George Kasun, et al. 2022. “**Antibody Optimization Enabled by Artificial Intelligence Predictions of Binding Affinity and Naturalness**.” bioRxiv. [https://doi.org/10.1101/2022.08.16.504181](https://doi.org/10.1101/2022.08.16.504181).

2. Aguilar Rangel, Mauricio, Alice Bedwell, Elisa Costanzi, Ross J. Taylor, Rosaria Russo, Gonçalo J. L. Bernardes, Stefano Ricagno, Judith Frydman, Michele Vendruscolo, and Pietro Sormanni. 2022. “**Fragment-Based Computational Design of Antibodies Targeting Structured Epitopes.**” *Science Advances* 8 (45): eabp9540. [https://doi.org/10.1126/sciadv.abp9540](https://doi.org/10.1126/sciadv.abp9540).


3. 


## Pretrained language model

- Ruffolo, Jeffrey A., Jeffrey J. Gray, and Jeremias Sulam. 2021. “**Deciphering Antibody Affinity Maturation with Language Models and Weakly Supervised Learning.**” arXiv. [https://doi.org/10.48550/arXiv.2112.07782](https://doi.org/10.48550/arXiv.2112.07782).
	- This work introduces **AntiBERTy**, a language model trained on **558M** natural antibody sequences that finds that within repertoires, the model clusters antibodies into trajectories resembling affinity maturation, and shows that models trained to predict highly redundant sequences under a multiple instance learning framework identify key binding residues in the process.


- Anonymous. 2022. “**On Pre-Training Language Model for Antibody.**” In . [https://openreview.net/forum?id=zaq4LV55xHl](https://openreview.net/forum?id=zaq4LV55xHl).
- This work (currently under peer review) developes the first comprehensive antibody benchmark, including tasks with varying antibody specificity: antigen-binding discrimination, antibody paratope prediction, B cell maturation analysis and antibody dicovery. The authors observed that including biological mechanism of antibody maturation in the training process improve the language model's performance on highly antibody-specific question.