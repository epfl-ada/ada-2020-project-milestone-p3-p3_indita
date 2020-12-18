# Languages influence social network patterns: a case study


### Abstract

In this project, we would like to play with the language feature from the original dataset. There has always been a stereotype that western people are more active on social media than eastern people. To verify such trends, we propose to analyze the features’ distribution of different language users. We can decide a user's activeness from some features such as tweet counts, friend numbers etc. Moreover, we would like to know if users in different cultures (western and eastern) have different using behaviors. In order to do so, we reproduce two propositions, 80-20 laws, and cycardian laws. Besides, we check the following preference of different culture users.In the end, we apply machine learning to see if we can predict the culture of a user based on the features of his/her own Twitter profile and that of the follower-followee network.


### Research Questions

- Do different language users have different characteristic on statistical results? ( i.e. number of tweets, number of followers, number of followees, years of subscription)
- Do different culture (western and eastern) users have different using behaviors on Twitter?
- Can we predict the culture of a user based on the features of his/her own Twitter profile and that of the follower-followee network?


### Proposed dataset

`EgoAlterProfile`: The dataset is from the original paper. The dataset contains tweets counts, language, number of friends… of over 1,000,000 users on Twitter. There are at least 20 languages which have more than 1000 users in the dataset. It is large enough for us to analyze our first research question. From this dataset, we could get the distribution of features such as number of tweets, number of followers, number of friends, and years of subscription among different languages.

`EgoNetwork`: The dataset is from the original paper. The dataset contains more than 3,000,000 following relations of users in EgoAlterProfile dataset. Combining it with the EgoAlterProfile dataset, we can construct a network with language features and solve our second research question. It could help even in the third research question.

`EgoTimeline`: The dataset is from the original paper. EgoTimelines dataset contains information of tweets that generated by egos during a certain period. The information of tweets include create time, hashtag usage, mentioned ID etc.


### Methods

- Group the users by languages or cultures
- Compute the distributions of the main features of each Ego for each subset, comparing the results
- Reproduce one or more propositions analysed in the original paper for each subset of Egos and compare the results
- Build a multi-class classifier to predict the language of a user based on the features of his/her own Twitter profile and that of the follower-followee network, evaluating the performance of the model.


### Proposed timeline

- **Week1** 28.11.20 ~ 04.12.20: Do data analysis looking for language trends, focused on the first two research questions.
- **Week2** 05.12.20 ~ 11.12.20: Work on the machine learning model, focused on the third research question.
- **Week3** 12.12.20 ~ 18.12.20: Understand and improve the results, iterate if necessary. Finally, organize the code and write the report.


### Organization within the team

- In week1, Po-Jui and Kushagra will plot the features' distribution figure of different languages and construct the directed network by networkx modules with language attribute. At the same time, Riccardo will do the feature preprocessing of the third task.
- In week2, we collectively try to train the model to predict the language of a user based on other features.
- In week3, we collectively focus on improving the results, iterating if necessary. Finally, we will write the report in parts and make a short video together.


### Questions for TAs (optional)

Is this too much work for the given deadline? Should we try to focus on a subset of the research questions?

### Contribution

- Po-Jui Chang: data preprocessing, using behavior analysis, build data story webpage, write data story
- Riccardo Cadei:
- Kushagra Shah:

