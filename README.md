# Missing Data

The purpose of this repository is to explore methods useful for handling missing data. Many types of analysis do not work with missing data. Even models that "support" missing data often only perform simple mean imputation. Otherwise, the default is to delete any records with missing data (listwise deletion) and continue the analysis. However, if the missing data is not randomly distributed, then by deleting rows with missing data you could introduce bias. And even if the data is randomly distributed, after listwise deletion you could end up with a very small sample. Fortunately, there are several methods developed to overcome missing data.

[_Missing Data_](Missing_Data_Document.md)    
This notebook is adapted from multiple presentations I gave at meetup groups in 2016 and 2017. I show how missing data can erode a dataset. Then I compare naïve methods to more advanced methods. However most importantly, I hope to impart a way of thinking about missing data that will serve in most situations. I use R and share a few of the packages that have been developed to handle missing data.
