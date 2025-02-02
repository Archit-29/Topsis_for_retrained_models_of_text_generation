# TOPSIS for Text Generation Models Ranking

This repository implements the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to assess and rank pre-trained text generation models based on several criteria. The models are evaluated according to their Performance (BLEU Score), Speed (Response Time), and Memory Usage.

## Overview

This project ranks various pre-trained text generation models by applying the TOPSIS method with a set of criteria. It normalizes the data, constructs a weighted decision matrix, computes both the ideal and negative ideal solutions, and ranks the models based on their proximity to the ideal solution. The results are then presented through various visualizations, such as bar charts, radar charts, and scatter plots.


### Key Features:
TOPSIS Method: A technique used to rank models based on multiple criteria.
Visualizations: Includes bar charts, radar charts, and scatter plots for model comparison and ranking.
Flexibility: The methodology can be easily adapted to rank different models or criteria.
## Requirements

To run the code, make sure the following libraries are installed:

- `numpy`
- `pandas`
- `matplotlib`

<img src="https://github.com/ayu-shiirathore/Topsis-for-pretrained-models-of-text-generation/blob/main/Screenshot%202025-02-02%20212220.png" alt="Sample Image" />
<img src="https://github.com/ayu-shiirathore/Topsis-for-pretrained-models-of-text-generation/blob/main/Screenshot%202025-02-02%20212201.png" alt="Sample Image" />
