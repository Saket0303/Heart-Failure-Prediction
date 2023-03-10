# Heart-Failure-Prediction

- HeatMap : Heatmap is defined as a graphical representation of data using colors to visualize the value of the matrix. In this, to represent more common values or                   higher activities brighter colors basically reddish colors are used and to represent less common or activity values, darker colors are preferred. Heatmap is             also defined by the name of the shading matrix. Heatmaps in Seaborn can be plotted by using the seaborn.heatmap() function.
  - Anchoring the colormap : If we set the vmin value to 30 and the vmax value to 70, then only the cells with values between 30 and 70 will be displayed. This is called anchoring the colormap.
  - Choosing the colormap : Matplotlib provides us with multiple colormaps. Reference : https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html
  - Centering the colormap : Centering the cmap to 0 by passing the center parameter as 0.
  - Displaying the cell values : If we want to display the value of the cells, then we pass the parameter annot as True. fmt is used to select the datatype of the contents of the cells displayed. 
  - Customizing the separating line : We can change the thickness and the color of the lines separating the cells using the linewidths and linecolor parameters respectively.
  - Hiding the colorbar : We can disable the colorbar by setting the cbar parameter to False.
  - Removing the labels : We can disable the x-label and the y-label by passing False in the xticklabels and yticklabels parameters respectively.
  - Reference : https://seaborn.pydata.org/generated/seaborn.heatmap.html

- Label Encoder : Label Encoding refers to converting the labels into a numeric form so as to convert them into the machine-readable form. Machine learning algorithms can then decide in a better way how those labels must be operated. It is an important pre-processing step for the structured dataset in supervised learning.
- Distplot
- Displot
- Histplot
- Countplot
- Stripplot
- Scatterplot

- Chi-Square Test
- Anova Test
- MinMax Scaler
- Standard Scaler
- Confusion Matrix
- Roc_Auc_Score
- Cross_Val_Score
- GridSearchCV
- Classification Report
- Accuracy_Score
- RepeatedStratifiedKFold
- precision_recall_curve
- Logistic Regression
- Support Vector Machine
- Decision Tree Classifier
- Random Forest Classifier
- K Neighbours Classifier
- 
