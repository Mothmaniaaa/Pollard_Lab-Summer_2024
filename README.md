# Pollard_Lab-Summer_2024
Machine learning model for optimizing PAM site selection and predicting change in gene expression after editing with CRISPR technology.

As of 2024, the causality of up to 98% of the human genome. This is because this percentage is non-coding, meaning it doesn't directly encode protein creation but rather environment the proteins were created in. With the creation of gene editing techniques like CRISPR, researchers can edit non-coding genes and measure their gene expression to understand what they affect. However, researcher need to make sure that the gene expression we are looking for doesn't signifcantly change in the process of gene editing.

This project is focused on comparing gene expression predictions produced with Deepmind's Enformer model. Particularly It finds the most viable genes for genetic editing and calculates the statistical difference in predictions between it and it an edited version of itself. This is meant to be an in silico model of CRISPR-Cas9 editing. If the nonedited gene variant and the edit variant have significant correlation, the gene would then be considered for in vitro testing to find causality. 
