# Machine Learning in 6 weeks
Following is a weekly plan of learning machine learning for beginners. Resoruces and tasks have been mentioned under each week.

## Week 0
For starting with python : see starting 9 lectures of https://www.youtube.com/playlist?list=PL-osiE80TeTskrapNbzXhwoFUiLCjGgY7
And start with pset 6 of https://cs50.harvard.edu/x/2020/psets/6/

## Week 1
Numpy task and Resources: task 01 available at https://github.com/MananSoni42/ML-SIG-2019

## Week 2
Linear Regression for single variable from scratch using numpy 
Resources : 
The tutorials at : https://pythonprogramming.net/machine-learning-tutorial-python-introduction/
All parts From “Practical Machine Learning tutorial with python - Introduction” to 
“ Regression - How to program R squared”
Dataset : https://github.com/ashryaagr/acm_task_dataset . Download this and start working. Use regression and train using the data in train.csv and then compute accuracy using data in test.csv

## Week 3
Use sklearn SVM on NASA asteroid dataset and train it to predict the property “hazardous” (last column of data ) of asteroids. You have to only use the data available in nasa.csv file.
Resources :
The tutorials at : https://pythonprogramming.net/machine-learning-python-sklearn-intro/
Some knowledge of Pandas will be required ..so go through these tutorials : 
https://pythonprogramming.net/introduction-python3-pandas-data-analysis/

Challenges that you will face :
Some columns are strings. You need to convert them to some integer. ( Try to think of some way to do that )
Dates are given in various formats. Find some way to convert them to integers to feed them to model.
Some fields ( columns ) are useless ( standard term for this is feature selection ). It might be possible that a field (column ) which contains strings is also useless.
Dataset : https://www.kaggle.com/shrutimehta/nasa-asteroids-classification

## Week 4
https://github.com/ashryaagr/ML_Recruitment
You have to fill the Todos of neural_net.py. Resources are provided in Readme. You can skip the task 1.
After completing the Todos, use this Neural Network on MNIST dataset to predict the digit in images

## Week 5
Now You have to make a Generative Adverserial Network using the Neural network you just made

This time you yourself will have to search for resources... But some suggestions are Research papers, lecture on GAN in the series CS231N, tutorial by lan goodfellow ( who is the creator/father of Generative adverserial networks)..you guys can also use the tutoial he presented in NIPS.. Or there are a number of videos on youtube.. Or on tensorflow website in tutorials, they make GAN using tensorflow (but you guys have to make it using the Neural network you wrote)

Btw you might have to rewrite cost function and prepare 2 separate cost functions.. One for generator and one for discriminator

## Deep Learning and cool stuff
- DeepMind Computer Vision : https://www.youtube.com/playlist?list=PLqYmG7hTraZCDxZ44o4p3N5Anz3lLRVZF
This one is very comprehensive and covers most of major recent developments. Btw this playlist was updated very recently updated.

- NYU Course: https://www.youtube.com/playlist?list=PLLHTzKZzVU9eaEyErdV26ikyolxOsz6mq
This guy will parallely teach you coding in pytorch unlike most others which don't focus on coding or teach in tensorflow (But pytorch is better)

- Reinforcement Learning: https://spinningup.openai.com/

- Natural Language Processing using Deep Learning : http://web.stanford.edu/class/cs224n/

# Machine Learning Resource List

- [BITSACM - A Simple Machine Learning Classifier](https://blog.bitsacm.in/a-simple-machine-learning-classifier/): Tutorial for building a simple machine learning classifier on [BITSACM Blog](https://blog.bitsacm.in).
- [ML ALgorithms Overview](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) for a basic understanding of the various ml algorithms
- [Awesome List](https://github.com/ChristosChristofidis/awesome-deep-learning)
- [Adversarial Examples and Adversarial Training](https://www.youtube.com/watch?v=CIfsB_EYsVI&feature=youtu.be) - Lecture Video
- [Network Morphism](https://www.microsoft.com/en-us/research/publication/network-morphism/) - research paper
- [Audio Data Analysis Resource](https://www.analyticsvidhya.com/blog/2017/08/audio-voice-processing-deep-learning/)
- [Probably Caliberation](https://scikit-learn.org/stable/modules/calibration.html) - interesting read
- [Hinton's Capsule Network Series](https://medium.com/ai%C2%B3-theory-practice-business/understanding-hintons-capsule-networks-part-i-intuition-b4b559d1159b)
- [General Topics to know](http://www.cs.yale.edu/homes/radev/posts/thingstoknow.txt)
- [Deep Learning Theory](https://stats385.github.io/readings)
- [Visualizing DeepNets](http://yosinski.com/deepvis)
- [DeepNet Recommendations](https://arxiv.org/pdf/1206.5533v2.pdf) - research paper
- [Deep RL Lecture Series](https://sites.google.com/view/deep-rl-bootcamp/lectures)
- [Genetic Algorithm](https://blog.sicara.com/getting-started-genetic-algorithms-python-tutorial-81ffa1dd72f9) - article for beginners
- [Youtube Recommending system Paper](https://dl.acm.org/doi/10.1145/3298689.3346997)
- [FastAI's Tutorials](https://course.fast.ai/)
- [Deep Double Descent](https://openai.com/blog/deep-double-descent/)
- [NLP Datasets](https://datasets.quantumstat.com/)

## ML Winter SIGs
- [Beginner Projects](https://github.com/MananSoni42/ML-SIG-2019/)
