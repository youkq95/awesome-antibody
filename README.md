
# Awesome antibody WIP🚧 <!-- omit in toc -->
- A curated list of machine learning(ML) & artificial intelligence(AI) methods for antibody. Inspired by [Machine-learning-for-proteins](https://github.com/yangkky/Machine-learning-for-proteins).
- Warning⚠️: this list only covers a little part of computational antibody literature and heavily depends on my personal reading. CONTRIBUTIONS WELCOMED!
## Categories <!-- omit in toc -->
- [Data](#data)
- [Antibody structure prediction](#antibody-structure-prediction)
- [Antibody optimization and design](#antibody-optimization-and-design)
- [Pretrained language model](#pretrained-language-model)
## Data
- **Absolut!**
- **Observed Antibody Space(2022)**
	- Olsen, Tobias H., Fergus Boyles, and Charlotte M. Deane. 2022. “**Observed Antibody Space: A Diverse Database of Cleaned, Annotated, and Translated Unpaired and Paired Antibody Sequences.**” *Protein Science* 31 (1): 141–46. [https://doi.org/10.1002/pro.4205](https://doi.org/10.1002/pro.4205).
	- The Observed Antibody Space (OAS) database was created in 2018 to offer clean, annotated, and translated repertoire data. The database is accessible at http://opig.stats.ox.ac.uk/webapps/oas/, and all data are freely available for download.
- **Biophysical properties of the clinical-stage antibody landscape(2017)**
	- Jain, Tushar, Tingwan Sun, Stéphanie Durand, Amy Hall, Nga Rewa Houston, Juergen H. Nett, Beth Sharkey, et al. 2017. “**Biophysical Properties of the Clinical-Stage Antibody Landscape.**” *Proceedings of the National Academy of Sciences* 114 (5): 944–49. [https://doi.org/10.1073/pnas.1616408114](https://doi.org/10.1073/pnas.1616408114).
	- A comprehensive analysis of these properties for essentially the full set of antibody drugs that have been tested in phase-2 or -3 clinical trials, or are approved by the FDA (as of 2017).
## Antibody structure prediction
- **IgFold**
## Antibody optimization and design
- **Fragment-based antibody de novo design(2022)**
	- Aguilar Rangel, Mauricio, Alice Bedwell, Elisa Costanzi, Ross J. Taylor, Rosaria Russo, Gonçalo J. L. Bernardes, Stefano Ricagno, Judith Frydman, Michele Vendruscolo, and Pietro Sormanni. 2022. “**Fragment-Based Computational Design of Antibodies Targeting Structured Epitopes.**” *Science Advances* 8 (45): eabp9540. [https://doi.org/10.1126/sciadv.abp9540](https://doi.org/10.1126/sciadv.abp9540).
	- Work form Pietro Sormanni. They grafted (antibody loop-like) fragments from known antibody structures and combined together to created a novel antibody binding to specific epitope on antigen, using crystal/predicted antigen structure. The experiment results shows fair binding affinity (nanomolar-level).
- **Absci's works on antibody optimization(2022&2023)**
	- Shanehsazzadeh, Amir, Sharrol Bachas, George Kasun, John M. Sutton, Andrea K. Steiger, Richard Shuai, Christa Kohnert, et al. 2023. “**Unlocking de Novo Antibody Design with Generative Artificial Intelligence.**” bioRxiv. [https://doi.org/10.1101/2023.01.08.523187](https://doi.org/10.1101/2023.01.08.523187).
	- This work (by AI+antibody biotech company [Absci](https://www.absci.com/)) demonstrates that the approach of combining high-throughput affinity measurements and generative AI can accelerate drug(antibody) discovery. The data was made [open-sourced](https://github.com/AbsciBio/unlocking-de-novo-antibody-design).
	- A previous work of Absci on the same topic:
	   Bachas, Sharrol, Goran Rakocevic, David Spencer, Anand V. Sastry, Robel Haile, John M. Sutton, George Kasun, et al. 2022. “**Antibody Optimization Enabled by Artificial Intelligence Predictions of Binding Affinity and Naturalness**.” bioRxiv. [https://doi.org/10.1101/2022.08.16.504181](https://doi.org/10.1101/2022.08.16.504181).
## Pretrained language model
- **AntiBERTy(2021)**
	- Ruffolo, Jeffrey A., Jeffrey J. Gray, and Jeremias Sulam. 2021. “**Deciphering Antibody Affinity Maturation with Language Models and Weakly Supervised Learning.**” arXiv. [https://doi.org/10.48550/arXiv.2112.07782](https://doi.org/10.48550/arXiv.2112.07782).
	- This work introduces **AntiBERTy**, a language model trained on **558M** natural antibody sequences that finds that within repertoires, the model clusters antibodies into trajectories resembling affinity maturation, and shows that models trained to predict highly redundant sequences under a multiple instance learning framework identify key binding residues in the process.
- **Antibody Benchmark(2022)**
	- Anonymous. 2022. “**On Pre-Training Language Model for Antibody.**” In . [https://openreview.net/forum?id=zaq4LV55xHl](https://openreview.net/forum?id=zaq4LV55xHl).
	- This work (currently under peer review) developes the first comprehensive antibody benchmark, including tasks with varying antibody specificity: antigen-binding discrimination, antibody paratope prediction, B cell maturation analysis and antibody dicovery. The authors observed that including biological mechanism of antibody maturation in the training process improve the language model's performance on highly antibody-specific question.
	- {{embed ((63bf74e9-cef9-4640-9984-487374658b21))}}
- ## Properties prediction
- **solPredict by Eli Lilly(2022)**
	- Feng, Jiangyan, Min Jiang, James Shih, and Qing Chai. 2022. “Antibody Apparent Solubility Prediction from Sequence by Transfer Learning.” *IScience* 25 (10): 105173. [https://doi.org/10.1016/j.isci.2022.105173](https://doi.org/10.1016/j.isci.2022.105173).
	- Eli Lilly publish a research paper on *iScience* about constructing model `solPredict` for antibody apparent solubility prediction using protein pretrained model combined with transfer learning using in-house antibody solubility dataset. The [code](https://github.com/JiangyanFeng-Lilly/solPredict_manuscript_codes_2022) is open without dataset.
- ## Online platform for antibody resarch
- **BioPhi by Merck(2022)**
	- Prihoda, David, Jad Maamary, Andrew Waight, Veronica Juan, Laurence Fayadat-Dilman, Daniel Svozil, and Danny A. Bitton. 2022. “**BioPhi: A Platform for Antibody Design, Humanization, and Humanness Evaluation Based on Natural Antibody Repertoires and Deep Learning.**” *MAbs* 14 (1): 2020203. [https://doi.org/10.1080/19420862.2021.2020203](https://doi.org/10.1080/19420862.2021.2020203).
	- An open-sourced platform named BioPhi by Merck and researchers from academia. BioPhi is consist of two models: **Sapiens** is a deep learning humanization method trained on the OAS using language modeling; **OASis** is a granular, interpretable and diverse humanness score based on 9-mer peptide search in the OAS. BioPhi thus offers an antibody design interface with automated methods that capture the richness of natural antibody repertoires to produce therapeutics with desired properties and accelerate antibody discovery campaigns. The BioPhi platform is accessible at https://biophi.dichlab.org and https://github.com/Merck/BioPhi.
-
-