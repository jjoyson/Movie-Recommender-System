# Project Proposal

I will not assign a specific problem to work on; rather, you will propose what you would like to work on.

Requirements:

1. The class project **_has_** **to** be a machine learning project and it **_has_** to include both *interaction* and *transparency* components.
1. It has to be approved by the course instructor.

Recommended:

1. Pick a problem that you are passionate about.
1. Do not simply use existing data; collect data.

**Interaction**

1. Active learning: http://active-learning.net/ The pdf of the book should be accessible through university network.
1. Tandem learning: examples: https://aclanthology.info/pdf/D/D09/D09-1009.pdf http://prem-melville.com/publications/pooling-multinomials-kdd09.pdf
1. Learning with rationales: examples: http://www.aclweb.org/anthology/N07-1033 http://www.aclweb.org/anthology/N15-1047

**Transparency**

Your model should generate explanations regarding
1. The data and important features,
1. The model overview,
1. The individual predictions.

Write a project proposal that explains the task, the domain, existing datasets and your additional data collection strategies, the machine lerning model, why it is an interactive machine leanrning project, how you are planning to provide transparency, and related work and references.

Please do not edit above this line.

---

# TASK AND MOTIVATION

[Explain the problem you are interested in working and why it is an important problem.]

I would be interested in working on a movie or tv show recommendation system. It seems straightforward and a problem that I often deal with. Even though Netflix has a good recommendation system, it is respective to the realm of shows and movie they release. Furthermore, I often find the recommendation system often fall short of what I would like to watch with random recommendations. If I were to create my own system, I can customize the model and make it transparent such that I understand those weird results. Furthermore, making it interactive can help my model become better at what it does for a specific person and might be scalable to future users.

# DATASETS

[Which existing datasets will you use, if any? Will you collect additional datasets and if so how? What is the data format? Text? Images? Table?]

The IMDB dataset introduced in class would be a good starting point dataset in the creation of the model. MovieLens, Yahoo, Jester and Cornell University dataset will also be investigated since it contains rating from multiple rating platforms. Since this is a recommendation system, it would need additional data in terms of the user likes and dislikes to be collected. Data would be usually in csv (text) format but sometimes covers of movies/shows can impact the user's choice (even though you shouldn't judge a movie by its cover) and this data will be images; a closer look needs to be done on the datasets to see if this information is given.

# MODEL

[Is this a supervised learning, unsupervised learning, or reinforcement learning problem? What models/algorithms will you use?]

This is definitely a supervised learning problem since it is a recommendation system. The model is learning from the data and predicts concrete outputs. So far we have covered Decision Tress so that is the model I am considering but as we get exposed to more models, I would like to consider neural networks (SVMS and such).

# INTERACTION

[How do you plan to utilize interactive ML approaches for this problem? Are you sure they are suitable to your task and data format?]

Having the user confirming recommendations or having the user initially input their likes and dislikes can be ways for the user to interact with the model (Active Learning). Since most if not all of the features are in text format, adjusting for the right features should be doable based on the interaction sessions with the user.


# TRANSPARENCY

[How are you planning to generate and display explanations?]

After prediction(s) or recommendation(s) are made, the model will output how recommendations are made in a user friendly update. Interaction can be tied into this point of time so that the user understands why the ouput was made and can ammend future results through interactions. Furthermore, the model will output an overview of features selection.



# REFERENCES

[Please list the relevant papers and URLs]

https://satwikkottur.github.io/reports/F14-ML-Report.pdf

https://ksiresearchorg.ipage.com/seke/dms14paper/paper18.pdf

https://arxiv.org/pdf/1802.09841.pdf
