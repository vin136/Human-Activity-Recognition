# Human-Activity-Recognition
This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.

This dataset is collected from 30 persons(referred as subjects in this dataset), performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. This experiment was video recorded to label the data manually.

This repo contains 3 note books each exploring the problem from different directions.

Here's the output from [UMAP:Uniform manifold approximation.](https://umap-learn.readthedocs.io/en/latest/supervised.html)
### As of this writing UMAP is few months old.It gives better or atleast similar results in comparison to state of art techniques like TSNE..and the cool thing about it is it requires almost no parameter tuning(unlike tsne) and can be used in supervised setting.


![UMAP](https://github.com/vin136/Human-Activity-Recognition/blob/master/HAR_UMAP.png)


![TSNE](https://github.com/vin136/Human-Activity-Recognition/blob/master/HAR_TSNE.png)

*OUTPUT FROM TSNE

