# IEEEBHI2019
Materials for paper titled 'You're Making Me Depressed: Leveraging Text From Contact Subsets to Predict Depression'
(https://ieeexplore.ieee.org/document/8834481)

This repository contains 5 Jupyter Notebooks:
1. FeatureEngineeringForIEEEBHI2019.ipynb contains the code that takes original text and extracts Part of Speech and sentiment features for each participant-contact combination. 
2. FeatureSetsForIEEEBHI2019.ipynb contains code to extract volume features not calculated in the prior Notebook, generates features for each participant from a user defined subset of contacts, and attaches PHQ-9 scores.
3. MachineLearningForIEEEBHI2019.ipynb contains the machine learning code inputs the output of the prior Jupyter Notebook and outputs prediction evaluation metrics.
4. BoxPlotsForIEEEBHI2019.ipynb creates boxplots as seen in the paper for each method from the outputs of the prior Jupyter Notebook.
5. PlotsForIEEEBHI2019.ipynb creates the other results based plots seen in the paper. 


Citation:

M. Tlachac, E. Toto and E. Rundensteiner, "You're Making Me Depressed: Leveraging Texts from Contact Subsets to Predict Depression," 2019 IEEE EMBS International Conference on Biomedical & Health Informatics (BHI), Chicago, IL, USA, 2019, pp. 1-4. doi: 10.1109/BHI.2019.8834481

@INPROCEEDINGS{Depressed,
author={M. {Tlachac} and E. {Toto} and E. {Rundensteiner}},
booktitle={2019 IEEE EMBS International Conference on Biomedical Health Informatics (BHI)},
title={You're Making Me Depressed: Leveraging Texts from Contact Subsets to Predict Depression},
year={2019},
pages={1-4},
doi={10.1109/BHI.2019.8834481},
month={May},}
