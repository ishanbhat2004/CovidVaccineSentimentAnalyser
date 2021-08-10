# CovidVaccineSentimentAnalyser
In this supervised ML project, we aim to help hospitals create a model that can gather data which relate to the sentiments of the general public regarding the covid-19 vaccine so that apt. steps can be taken to optimize demand and supply rates of specific vaccines to save resources in these unprecedented times. 
During the course of the project, we go into the details of data exploration and nlp processing by analysing the different reviews given by people based on their experience with different Covid-19 vaccines. 
Furthermore, we make use of basic libraries along with a few advances ones, including tfidf vectorizer, to convert our nlp data to numerical representation, Logistic regression, to build our model, Pywebio, to host our application, and many more.
We are able to create a model which gives us an accuracy of, roughly, ninety percent, and uses reviews as the feature data and positivity as the label data. 
In the end, we also host our application using Pywebio, which makes use of the model to discern between the positive and negtive sentiments of the users and takes note of their age and vaccine, which was taken by the user.
