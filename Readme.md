# Starbucks
## The goal
This analysis of simulated user interaction data in the Starbucks promotion app. The source of the data is Udacity to create the datascience master analysis.

After analyzing the data I ask myself the following questions: 
    - Which customer groups do you convert the most?
    - What kind of offer works best?
    - Which customer profile is most profitable?

## Project motivation
Use real-life data and apply dat science analysis to a business problem.

## Datasets
3 datasets:
 - Portfolio - file describing the types of offers. 
 - Profile - file with the socio-demographic profile data of the users
- Transcript - file with user interactions and offers. It also includes the purchases

## Libraries
> Padas, numpy,  json
> matplotlib, searborn
> sklearn, standarscaler, pca, kmeans, kneed

## Analysis
> Analyze the datasets to define the questions
> Clean up data and create features 
> Apply the techniques and models that help us to answer the questions 

## Insights & summary of results
There are 2 relevant clusters, that convert most, is most profitable and works best
- The users that are in the program since 2015 in the program and received more than 10 offers has better conversion (70%).
- High income ladies, do not receive many offers but those who do receive them has better conversion, 60 %, than young men cluster.

- The users without information about gender convert a 55%.


- The clusters that convert the least , 30%, group the men who have just joined the program. In one cluster are the young men with less income and in another those who are a little older and have a little more income.  

## Post
I wrote a Medium post as well. You can find the post
https://ledaduelo.medium.com/starbucks-capstone-challenge-84e7bd21e883

## Files in the repository
 - Portfolio
 - Profile
- Transcript
- Notebook
- Readme

## Acknowledgements
//stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
//https://towardsdatascience.com/divide-and-conquer-segment-your-customers-using-rfm-analysis-68aee749adf6
//https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html
//https://es.wikipedia.org/wiki/K-medias
//https://datascience.stackexchange.com/questions/22795/do-clustering-algorithms-need-feature-scaling-in-the-pre-processing-stage
// https://medium.com/@dmitriy.kavyazin/principal-component-analysis-and-k-means-clustering-to-visualize-a-high-dimensional-dataset-577b2a7a5fe


