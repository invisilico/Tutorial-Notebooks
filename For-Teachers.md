## Information for teachers

This digital experiment based on android app activity data tries to show students what real-world neuro-behaviour experiments are like. How, our phone activity, like a mouse wheel, is a noisy method of capturing data that doesn't always tell us the whole truth. And how by manipulating the data and representing it in different ways, it shows us different things about the behaviour of the animal (mouse or man). Beyond different plotting and representation methods, the notebook has one section that deals with inferring a state of the organism from activity data (sleep/wake), and another section where students try to find the relation between weekday sleep-loss and weekend excess sleep. 

I have chosen to keep it really simple and tried to make sure the students do not need to know how to code in order to do the experiment. The entire experiment is within a jupyter notebook and thus does introduce them to python (if they choose to see the code). There are no comparison based "results" here either, and no statsitical analyses, but is rather an all quantitative approach to understanding the inferences one can make from different visualizations of their own data. 

## About Usage Permissions

If you wish to use this to teach your class as a part of curriculum or otherwise, or adapt the notebook in any way to teach, feel free to do so!

However, I would greatly appreciate if **before** using it in any way, you raise an issue in the repository [here.](https://github.com/invisilico/Tutorial-Notebooks/issues) If you do not have a github account and do not wish to create one, just send me a mail at <a href="mailto:nishantjana5@gmail.com">nishantjana5@gmail.com</a>.

Please mention the following details:

Your Name and University (with an e-mail), the course in which you wish to use the tool and a round figure size of the class. If you would like to modify the contents of the experiment (add/remove/change) please add those details as well.

The details will help me keep track of the reach of the project and collect feedback. I would also appreciate any and all feedback from you and your class afterwards. If you choose to collect reports from your students, I would love to see them! (and be a part of the class discussion too, if that's possible!)

Additionally, I would greatly appreciate if you could urge your class to share the data file they used for their experiment with the form linked in the [main page](https://invisilico.github.io/Tutorial-Notebooks). All the details of the data collection protocol and project are detailed there and it would really really help me with my project in studying human rhythms.

## About the Experiment
  
An important pre-requisite is that the students must use android phones, which is not always the case. I suggest three ways to tackle this: 1. ask android using students to share their datafile with friends they trust within the class 2. have students ask a family member that uses android and 3. Use the sample file I have provided. I would suggest for students to find their own data to work with rather than use the sample, but I have provisioned for it so no student is limited.

The experiment is based on Android app activity. Google's My Activity services keep track of each time an app is opened. This data can be downloaded from [takeout.google.com](https://takeout.google.com) using these documented steps: [Android-Takeout-HowTo](https://invisilico.github.io/Tutorial-Notebooks/Android-Takeout-HowTo).

The experiment is simple and goes as follows:

1. Students collect their own data from google takeout, and from it, using the jupyter notebook, generate a dataframe of appnames and timestamps.

2. They observe raster plots for different time frames and identify issues such as background apps or other sources of noise in the data, and then clean the dataset accordingly.

3. They generate different visaulizations from actograms to heatmaps. They look at distributions of sleep time, heatmaps, and various plots to analyse their own behaviour and see if they can infer things about their own habits purely from app activity data. It is also impoortant for them to realise here what they can and can't say from the data. (ex: since timestamps only record app opening and not closing, they have no idea of sleep onset, even if they sleep right after they shut their phones.

4. They then try to build a model that accurately predicts sleep and wake, finding parameters that work for them. It is a good idea for them to discuss here as there can be big differences between individuals. It is also ideal if they can take a sleep log for the week before the experiment or have some kind of sleep tracking data of their own to compare with. The Markov Model concept may be introduced as a latent state is being inferred from an activity readout.

5. Finally, they try to see if there is a relationship between weekday sleep loss and excessive sleeping on weekends, and whether they can predict excess weekend sleep from the data from the week.

At each important stage, it would benefit them to discuss with each other to look at the variance between individuals and how common models don't usually fit. (but clustering does, ergo, chronotypes).

## Link to Notebook
 
Please click on the button below to open the jupyter notebook in google colaboratory:

example for teachers (with plots and data): 

example report: 

student version (empty, for students to run with their own data): 

## For student instruction

I would suggest sending students the following link:

[https://invisilico.github.io/Tutorial-Notebooks/For-Students](https://invisilico.github.io/Tutorial-Notebooks/For-Students)

The page is built to guide students through the process with ease.

## Note

I'd be happy to help in any way possible, feel free to contact me by <a href="mailto:nishantjana5@gmail.com">e-mail</a>./[twitter](twitter.com/In_Visilico)/[github](github.com/invisilico)

I am also an undergrad student, and this is still a learning experience for me. I will appreciate all critical feedback that I can use to learn from myself and use to improve this notebook.
