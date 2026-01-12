# Netflix-movies-recommendation
We have clustered Netflix Movies And TV Shows Data with K-Means Clustring and built a recommender system in Google Colab which recommends 5 movies based on input movie using cosin similarity.

Project Files Description

This Project includes 1 colab notebook, 1 technical documentation as well as 1 presentation:

Executable Files:

Netflix movie clustering.ipynb - Includes all functions required for classification operations.
Output:

Google Colab - All the outputs are visible in the provided colab notebook.
Data Source:

Dataset - https://drive.google.com/file/d/1qL5TOac80aA5dI62Kea9lYEJEaJwG_pl/view?usp=sharing
rainbow

K-Means Clustering

k=8 is found to be an optimal value for clusters with highest silhouette score of 0.909 using which we grouped our data into 8 distinct clusters.
Using dendograms and comparing various distance thresholds, a distance of 20 produced the highest silhouette score of 0.90 with 8 clusters produced the highest silhouette score of 0.90 with 8 clusters
rainbow

Execution Instruction The order of execution of the colab notebook is as follows:

TEAM_REALITY_ANDRIOD_AUTHENTICITY_PREDICTION.ipynb

First, click on the open in colab button present on the top center of the notebook.
Kaggle Dataset

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.
Cell Path

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.
