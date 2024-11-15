# Data analysis of the red wine

### Author: Andrii Zhurba
The relevant project is located in src directory, RedWineAnalysis.ipynb file.

This study will consider vinho verde, a unique product from the Minho (north-west) region of Portugal. This wine accounts for 15% of the total Portuguese production, and around 10% is exported. In this work, we will analyze the red wine from the region of vinho verde. We have different variables which characterize wine. Our main goal is to analyze which variables influence the quality of the wine the most and give some recommendation on how to create high-quality wine. For this, we will fit Linear Regression model.


## Results:
Based on the analysis of the red wine dataset, it was found that density and fixed acidity do not significantly impact wine quality, suggesting variations in these factors may not affect quality of red wine. Similarly, residual sugar and citric acid showed no significant influence on quality, indicating their levels may not be crucial as well. Conversely, alcohol content, total sulfur dioxide, and sulphates were found to positively impact quality, with alcohol exhibiting the strongest effect. In contrast, pH, chlorides, and volatile acidity had a significant negative impact, highlighting the importance of managing these factors to enhance overall wine quality. Recommendations include optimizing alcohol, sulfur dioxide, and sulphate levels while minimizing pH, chlorides, and volatile acidity to improve wine quality and meet market demands effectively.


### Source:
The data was downloaded on kaggle website: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009.


To run the notebook, install the following dependencies:

```
pip install -r requirements.txt
```

