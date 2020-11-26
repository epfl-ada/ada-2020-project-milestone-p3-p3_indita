# Languages influence social network patterns: a case study


### Abstract

In this project, we would like to play with the language feature from the original dataset. There is always a stereotype that western people are more active in social media than eastern people. To check if it is true or not, we propose to analyze the features’ distribution of different language users. We can decide the activeness from some features such as tweet counts, friend numbers .... Moreover, we would like to learn if there exists language or geographical location clusters on Twitter. If so, we also want to learn to what extent they are going to interact with different clusters. To do so, we would run the community algorithm provided by networkx modules and see if we can detect the clusters of different language groups. In the end, we could apply machine learning to see if we can predict the language of a user based on the features of his/her own Twitter profile and that of the follower-followee network.


### Research Questions

- Do different language users have different usage behaviors on Twitter? ( i.e. number of tweets, number of followers, number of followees, years of subscription)
- Is there a follower-followee pattern among users based on the same language or geographical locations?
- Can we predict the language of a user based on the features of his/her own Twitter profile and that of the follower-followee network?


### Proposed dataset

`EgoAlterProfile`: The dataset contains tweets counts, language, number of friends… of over 1,000,000 users on Twitter. There are at least 20 languages which have more than 1000 users in the dataset. It is large enough for us to analyze our first research question. From this dataset, we could get the distribution of features such as number of tweets, number of followers, number of friends, and years of subscription among different languages.

`EgoNetwork`: The dataset contains more than 3,000,000 following relations of users in EgoAlterProfile dataset. Combining it with the EgoAlterProfile dataset, we can construct a network with language features and solve our second research question. It could help even in the third research question.


### Methods

- Reproduce 1.5 Ego Network
- Split the Egos in different subsets according to the language that they use
- Compute the distributions of the main features of each Ego for each subset, comparing the results
- Reproduce 1 or more propositions analysed in the original paper for each subset of Egos and compare the results
- Build a multi-class classifier to predict the language of a user based on the features of his/her own Twitter profile and that of the follower-followee network, evaluating the performance of the model.


### Proposed timeline

- 28.11.20 ~ 04.12.20: focus on the first two research question
- 05.12.20 ~ 11.12.20: focus on the last research question
- 12.12.20 ~ 18.12.20: organize the code and write the report


### Organization within the team


### Questions for TAs (optional)

Is this too much for the given deadline? Should we try to focus on a subset of the research questions?




