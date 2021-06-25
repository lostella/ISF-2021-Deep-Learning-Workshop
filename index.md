---
layout: default
---

**Sunday, June 27th, 2021** <br>
**19:00–23:00 GMT** <br>
**Chime ID: 6064 72 4824** -- [Download Amazon Chime](https://aws.amazon.com/chime/download)

In this virtual workshop, we aim at covering neural forecasting methods from the ground up, starting from the very basics of deep learning up to recent forecasting model improvements. 

Given that the workshop is fully virtual, we will primarily rely on lectures.
In these, we will focus on the fundamentals of deep learning such as the various architecture types (e.g. feed-forward, convolutional and recurrent neural networks) and the most important breakthroughs that established the strength of neural networks.
Then, we will see how deep learning can be applied to forecasting by reviewing several state-of-the-art neural forecasting models (e.g., WaveNet, DeepAR, NBEATS and the sequence-to-sequence model family).
Furthermore, we will dive into recent work that combines neural networks with probabilistic models such as deep state space and deep factor models, and bayesian techniques.
Finally, we will introduce [GluonTS](https://github.com/awslabs/gluon-ts), a time series modelling toolkit primarily aimed at forecasting which is available as open source.
To complement the lectures, we will provide notebooks for the workshop participants to interactively explore some of these ideas themselves.
Given that the workshop is virtual, this will be self-study largely.
Notebooks will rely on GluonTS.

In contrast to its 2020 edition, we will have a longer practical session and cover an advanced topic in the theoretical part, probabilistic, multi-variate, neural forecasting models.

## Presenters

<p><img align="left" src="./assets/img/januschowski.jpeg" style="padding-right: 15px; padding-top: 5px;"/>
<b>Tim Januschowski</b> is a Machine Learning Science Manager in Amazon AI Labs. He has worked on forecasting since starting his professional career. At Amazon, he has produced end-to-end solutions for a wide variety of time series analysis applications ranging from anomaly detection to forecasting problems. Tim's personal interests in forecasting span applications, system, algorithm and modeling aspects and the downstream mathematical programming problems. He studied Mathematics at TU Berlin, IMPA, Rio de Janeiro, and Zuse-Institute Berlin and holds a PhD from University College Cork. He serves as a director at the International Institute of Forecasters.
</p>

<p><img align="left" src="./assets/img/stella.jpeg" style="padding-right: 15px; padding-top: 5px;"/>
<b>Lorenzo Stella</b> is an Applied Scientist at Amazon AI Labs, where he works on deep learning architectures for forecasting models, and their application to a variety of business problems. He is one of the core developers of GluonTS. Besides machine learning and forecasting, his scientific interests include mathematical programming problems and numerical optimization algorithms. He studied Computer Science at the University of Florence, and holds a PhD from IMT School for Advanced Studies Lucca (Italy) and KU Leuven (Belgium).
</p>

## Schedule

Lecture: Deep Learning (45 mins). Start: 6pm
* Gentle Intro: from linear methods to deep learning
* Optimization challenges
* Different architectures for different problem types
* Probabilistic prediction 
* Q&A and/or break (~5 mins)

Lecture: Deep Learning for forecasting (45 mins). Start: 6:45pm
* Discriminative vs Generative Models
* Deep dive into a couple of models
* Categorization of state-of-the-art
* Results

Lecture: Multivariate Forecasting (20 mins). Start: 7:20pm

Practical Session: Deep Learning for forecasting in action (1:40h). Start: 8pm

## Material

* to be added after the workshop

## Prerequisites

This workshop is appropriate for anyone with a solid programming background and a general interest in neural networks. Prior knowledge in neural networks is recommended but not necessary.
Knowledge of forecasting, basic statistical and machine learning knowledge are a pre-requistite.
For the practical material, Python programming knowledge is essential.

The hands-on session will require Python 3.6 or 3.7, with Jupyter installed.
The required packages are installed with the following commands (*note: these may vary depending on your OS and Python distribution*).

```
pip install --upgrade mxnet==1.7.0 torch==1.7.0
pip install git+https://github.com/awslabs/gluon-ts.git
```

## Dial-in instructions 

We will be using Amazon Chime, not Zoom for this workshop. Unfortunately, we cannot make a recording available. Below are details.

You can use chime via a browser or download Amazon Chime at [https://aws.amazon.com/chime/download](https://aws.amazon.com/chime/download)

For information about creating an Amazon Chime account, see [https://aws.amazon.com/chime/getting-started](https://aws.amazon.com/chime/getting-started)

Click to join the meeting: [https://chime.aws/6064724824](https://chime.aws/6064724824)
Meeting ID: 6064 72 4824

A headset is recommended or you may use your computer’s microphone and speakers.

Call in using your phone: [https://aws.amazon.com/chime/dial-in-numbers/](https://aws.amazon.com/chime/dial-in-numbers/)
Dial-in attendees must enter `*7` to mute or unmute themselves. <br>

Some dial in numbers:
United States Toll-Free (1): +1 855-552-4463
Meeting ID: 6064 72 4824
One-click Mobile Dial-in (United States (1)): +1 206-462-5569,,,6064724824#
United States (1): +1 206-462-5569
United States (2): +1 929-432-4463
Australia (1): +61 2 8311 0237
Austria Toll-Free (1): +43 800 0706266
Austria Toll-Free (2): +43 800 802724
Belgium Toll-Free (1): +32 800 81 753
Belgium Toll-Free (2): +32 800 26 143
Belgium (1): +32 784 84 496
Germany Toll-Free (1): +49 800 7238486
Germany (1): +49 89 220 61384
Poland (1): +48 22 307 41 80
International: https://chime.aws/dialinnumbers/
Dial-in attendees must enter *7 to mute or unmute themselves.

To connect from an in-room video system, use one of the following Amazon Chime bridges:
SIP video system: 6064724824@meet.chime.in or meet.chime.in
H.323 system: 13.248.147.139 or 76.223.18.152
If prompted enter the Meeting PIN: 6064724824#

To connect from an in-room video system, use one of the following Amazon Chime bridges:
SIP video system: 6064724824@meet.chime.in or meet.chime.in
H.323 system: 13.248.147.139 or 76.223.18.152
If prompted enter the Meeting PIN: 6064724824#

