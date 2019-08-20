# Project Objective :   
## This project aims to achieve [federated learning](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html) training of model and then testing on [encrypted dataset and model](https://iamtrask.github.io/2017/03/17/safe-ai/) using [pytorch](https://pytorch.org/) and [pysyft](https://github.com/OpenMined/PySyft).

## Dataset : MNIST 
> (Intent behind using the simple dataset is the main motive which is to combine privacy preserving techniques using pysyft)

![](pics/google.gif)   

## Basic overview of federated learning :   

Have you ever wondered how Google keyboard predicts the probability of the words you will type after you just start typing ?
Or how the Apple iOS detects the most correct emoji you want to use in a conversation.

![](pics/ios.png)   

There are similar other things where we can see the use of federated learning like :
* wearable medical devices
* predictive maintenance (automobiles / industrial engines)
* ad blockers / autotomplete in browsers (Firefox/Brave)
* app company (Texting prediction app)
* so what exactly is federated learning ?

**Federated Learning is a collaborative form of machine learning where the training process is distributed among many users and not based totally on a single server. Here , the server is the main control for coordinating everything but most of the work for training process is done by federation of users.**  

Normally , one would send all the data to a central server for training the model created on the server and then the model is trained but for some security reasons we might not want to send all of the data in the hands of some other organisations like all the things we type in daily on the phone.
So, federated learning is one of the solution , though not the only one.
In the context of federated learning process, we call the devices or a remote machine ‘workers’.
You might understand in terms like this say , you have a boss and that boss in your organisation has the main role of supervising things there but since he is the busiest due to other stuff like meetings and all , he keeps some persons who are employees working there.
These employees work for different dept. and also share some of the data with the Boss and organisation and therefore making contribution towards overall development of the company / organisation.   

![](pics/fed1.png)   
