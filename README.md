# Project-2

The dataset we will be using here contains the physical and chemical properties of thousands of wines from the Minho (northwest) region of Portugal, as well as a quality rating for each determined by a group of sommeliers. The features include acidity levels, both fixed and volatile as well as citric acid in mg/L and pH levels. The dataset also includes chlorides, alcohol percentage, residual sugars, sulphates, and SO2, both free and total. The dataset was compiled for research purposes in *Decision Support Systems*, Elsevier, 2009. As for data visualizations, I started by splitting the wines by color (red and white) and showing counts of each quality rating. Further, I used boxplots to visualize each feature in the dataset; and concluded with a correlation heatmap. The mission of this project is to see if we can essentially create a digital sommelier that can predict quality ratings of wines based on their physical and chemical properties. 

![image](https://user-images.githubusercontent.com/98555801/166616218-df3b1f92-2a4d-479e-b584-638aeda55f7b.png)

![image](https://user-images.githubusercontent.com/98555801/167012221-40197bdf-30e7-41cd-ac41-5e27c8820a48.png)

In the end, our **Optimized Decision Tree** is the most accurate model we have prepared. The important thing to remember is that wine quality is a subjective variable, and sommeliers will often disagree wildly on a wines true quality, if such a thing even exists. Our model is getting close to predicting quality accurately, based on physiochemical properties, but the truth is the correlation between these properties and the enjoyability of a wine is subjective, and therefore difficult for a model to accurately predict. 
