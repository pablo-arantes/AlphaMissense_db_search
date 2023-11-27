# AlphaMissense_db_search

This is a repository where you can find a Jupyter notebook script to search on the AlphaMissense database using the Uniprot ID of your selected protein. 

AlphaMissense is a deep learning model that builds on the protein structure prediction tool AlphaFold2. The model is trained on population frequency data and uses sequence and predicted structural context, all of which contribute to its performance. The authors evaluated the model against related methods using clinical databases not included in the training and demonstrated agreement with multiplexed assays of variant effect. Predictions for all single–amino acid substitutions in the human proteome are provided as a community resource. 

Here, we implemented an easy way to search and find a prediction for a specific variant or residue on your selected protein.

**AlphaMissense** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/AlphaMissense_db_search/blob/main/AlphaMissense_db_search.ipynb)  - `Search on the AlphaMissense database using the Uniprot ID of your selected protein`

For more information about the method, please, read [AlphaMissense 2023 publication](https://www.science.org/doi/10.1126/science.adg7492).
 
## Bugs
- If you encounter any bugs, please report the issue to https://github.com/pablo-arantes/AlphaMissense_db_search/issues

## Acknowledgments
- We would like to thank the [AlphaMissense](https://github.com/google-deepmind/alphamissense) team to pre-computed predictions for all possible human amino acid substitutions and missense variants.
