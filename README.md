# machine_learning_club

### Notebook Options
 * [Jupyter Notebook](http://jupyter.org/): ```pip install jupyter```
 * [Jupyter Lab](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906): ```pip install jupyterlab```
 * [nteract](https://nteract.io/)
 * [google colab](https://colab.research.google.com)

### Reading List

These two sites are great resources 
 * [Machine Learning Mastery](https://machinelearningmastery.com/):      Provides plenty of tutorials with python code that you can experiment with. 
 * [Chris Albon](https://chrisalbon.com/):       Great visualizations of how things work. 

# Meeting agenda and notes

### Next meeting
 * Mike Ritthaler to present on Siamese Networks  
 
### 2019-06-19
 * Michael Smith to present embeddings
   * Code at: https://github.com/DOsinga/deep_learning_cookbook
 * Jason Mauzey to discuss some applications of embeddings 
### 2019-05-30
 * Mark Bastian to show reinforcement learning video
 * Matt Grimm to discuss why nonlinearity in activation functions is important
 * Michael Farnsworth will continue presentation on keras tools. This talk will be on activation functions. 


### 2019-05-16
 * Oriely learning video - TBD
 * Tooling
 * Michael Farnsworth to present neural network layers and uses. 

### 2019-05-02 Meeting
 * Dana Koczur and Travis Heppner to present image classification for mri images.  

### 2019-04-18 Meeting
 * Watch Ada boost video ( for real this time )
 * Mike Ritthaler going to discuss BERT
 * David Rogers to discuss ML project he is working on for his team.  Interested in feedback.  

### 2019-04-04 Meeting

 * Ada boost videos ( Forgot these in last meeting)
 * Michael Farnsworth will present on a personal project he is doing to get familiar with machine learning and python
 * Robert Kennedy is going to present how changing just the data had a dramatic affect on Soda pipeline.  (Data is paramount)


### 2019-03-14 Meeting

 * Watch some Udacity videos including at least AdaBoost
 * Jason Mauzey to demo and discuss results of Uber open source project Ludwig
 * Mark Bastian to share either reinforcement learning for cartpole problem or image classification of x-rays
 * [Mark Bastian's notes on Sebastian Thrun's Presentation](./2019-03-14/README.md)

### 2019-02-28 Meeting

 * Watch some udacity Bayes videos with commentary from Jason Mauzey or Matt Grimm
 * Michael Smith will discuss predicting hall of famers 
 * Mike Ritthaler will discuss data exploration tool he has created

### 2019-02-14 Meeting Notes

Great job Thomas Long and Mark Bastian

### 2019-02-14 Meeting

 * Orange demonstration
 * Thomas Long to present back propagation and gradient descent
 * Mark Bastian to present takaway from udacity machine learning engineer nano degree

### 2019-01-31 Meeting Notes

David Silver course page  http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html
David Silver RL videos    https://www.youtube.com/watch?v=UoPei5o4fps&list=PL7-jPKtc4r78-wCZcQn5IqyuWhBZ8fOxT&index=6
Types of errors           https://www.youtube.com/watch?v=Twf1qnPZeSY
Learning curves           https://www.youtube.com/watch?v=ZNhnNVKl8NM
Thank you Udacity and David Silver!

### 2019-01-31 Meeting

The next meeting is going to consist of the following parts. 

 * Education piece about a TBA machine learning algorithm – may be fulfilled by following talk 
 * Tooling/education about Scikit learn metric tools 
 * 	Application/education of reinforcement learning to blackjack – how to create a table that tells you what the best move is. 
 * Michael Smith will share his results from the sports dataset. 

We would like 1-2 people to also either present their results and experiences with the sports data set or any other problem they are trying to apply machine learning to. 


### 2019-01-17 Meeting Notes
https://github.com/tdpetrou/Learn-Pandas   This is a great resource for learning pandas. 

### 2019-01-17 Meeting 

For this meeting the education component is going to consist of:
 * Matt discussing supervised learning and describe both classification and regression problems. 
 * Jason covering pandas.  Go Pandas!! 
 
For the application part of the meeting we want to see some members work based on the added 
sports data that is described below along with some tasks associated with it. 

There is now a data folder in this project.  The first dataset we are going to work with are some NFL sports data that I
retrieved from https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data/home. There are three files that may need
to be joined to make the data more useful. 

There are two supervised tasks for this dataset. 
 * Predict the spread.
 * Predict the winner.
 
There are two sub-tasks that we could quickly think of for this data. 
 * Identify feature importance for either of the supervised tasks.
 * Enrich the data with rosters at each game or anything else that seems reasonable. 
 
You can access the data by checking out the project or by downloading it from google colab. You could then download a 
copy of the notebook and push that to the project, send it to Jason Mauzey, or remote in to your computer to show what
you have done. Any work is good work.  We look forward to seeing some good efforts.  

If you don't want to checkout the project you can use these links to get the data, or use the above kaggle link. 
https://raw.githubusercontent.com/mauzeyj/machine_learning_club/master/Data/nfl_teams.csv
https://raw.githubusercontent.com/mauzeyj/machine_learning_club/master/Data/nfl_stadiums.csv
https://raw.githubusercontent.com/mauzeyj/machine_learning_club/master/Data/spreadspoke_scores.csv

Importing the data is very easy with pandas. 
pd.read_csv('https://raw.githubusercontent.com/mauzeyj/machine_learning_club/master/Data/spreadspoke_scores.csv')

I haven't started working with these data sets yet so I can't vouch for them yet.  Lets all have a great time!!
