# Happily
An App for Positive Thinking

  The trope "Happy thoughts, Happy life" is not just a cheeky slogan that is written on thift store mugs. 
  According to a study performed in 2019 [1], positive thinking can actually extend the length of your life. 
  Unfortunately, it can be hard to remember to think optimistically, especially for those with clinical depression or anxiety [2]. 
  Currently, there are very few tools available to specifically address having a positive outlook, and those that do exist 
  are either very buggy, or do not deliver the experience users expect.
  
  I propose an application based in natural language processing to encourage a habitually cheerful mindset.
  Users will utilize the application as a journal. Sentiment analysis and topic modeling will then be applied
  to the entries not only to predict the connotation, but to analyze what topics are related to positive or negative thoughts.
  The results will appear to a user in the form of another text box, asking for some positive topics if the entry was negative,
  and as a dashboard with interactive visualizations about their entries over time.  The goal is that this analysis
  will inform a user on what topics they are most negative/positive about, to remind a user to be more positive during their
  day, and show a user how their mood as been changing over time. Hopefully, the user will become more positive the more they 
  use the app. Most of the tools I need are available in the following Python libraries: sklearn, nltk, gensim, and TextBlob. 
  The novel method that I will need to develop is a machine learning model to correctly map certain text and connotation to topics. 
  The gensim package contains an LDA function that is able to decompose corpuses into a linear regression model of prominant words. 
  I plan to code a supervised learning model that will attempt to map the output of the LDA to topics such as family, 
  automobile, pets, friends, school, work, fitness, appearance, and love life. I have begun to code up a prototype of my project
  and it is available in the url below. 

url for jupyter notebook : https://raw.githubusercontent.com/nicolenlama/Happily/master/Positive_App.ipynb

## This user had a two bad days in January and February but overall, this user has been pretty positive!
Inline-style: 
![alt text](https://github.com/nicolenlama/Happily/blob/master/Images/MoodVsTime.png "Mood over Time")

## This user consistently speaks about his love life negatively. I wonder what the user can do to improve it?
Inline-style: 
![alt text](https://github.com/nicolenlama/Happily/blob/master/Images/MoodVsTopic.png "Mood and Topics")

## Mood and Subjectivity Heatmap
Inline-style: 
![alt text](https://github.com/nicolenlama/Happily/blob/master/Images/MoodSubjectivityHeatMap.png "Mood and Subjectivity")

## Tools
* Gensim
* Sklearn
* NLTK
* TextBlob


## References
1. Optimism is associated with exceptional longevity in 2 epidemiologic cohorts of men and women. 
Lewina O. Lee, Peter James, Emily S. Zevon, Eric S. Kim, Claudia Trudel-Fitzgerald, Avron Spiro III, 
Francine Grodstein, and Laura D. Kubzansky. (September 10 2019). PNAS. https://doi.org/10.1073/pnas.1900712116

2. Depression doing the Thinking. Estra Marano. July 1 2001. 
https://www.psychologytoday.com/us/articles/200107/depression-doing-the-thinking

