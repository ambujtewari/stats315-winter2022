## Welcome to STATS 315 / DATA SCI 315

This is an introductory deep learning course using the Python programming language and the TensorFlow deep learning library.

- **Textbook**: We will not follow any one textbook too closely. Here are a few references we might use:
  - _Dive into Deep Learning_ by Zhang, Lipton, Li and Smola. An advanced text from research scientists at Amazon. It weaves together math, figures, and code in an interactive online resource available [here](https://d2l.ai/). Code examples are provided in three frameworks: MXNet, PyTorch and TensorFlow. 
  - _Deep Learning with Python (2nd edition)_ by Chollet. A solid hands-on guide oriented towards programmers from the creator of the Keras deep learning library. Ebook and print versions are available from [Manning Publications](https://www.manning.com/books/deep-learning-with-python-second-edition)  
  - _Introduction to Deep Learning_ by Charniak. This undergraduate level textbook is perhaps the closest to this course in terms of prerequisites and the level at which deep learning is presented. It is available from [MIT Press](https://mitpress.mit.edu/books/introduction-deep-learning). Unfortunately this uses TensorFlow version 1 whereas we will use the more user friendly version 2.
  - _Deep Learning_ by Goodfellow, Bengio and Courville. Written by three top deep learning researchers, this comprehensive book is required reading if you want to pursue your study of deep learning at a more advanced level. Print version is available from [MIT Press](https://mitpress.mit.edu/books/deep-learning) and an online version is [here](https://www.deeplearningbook.org/).
  - _Neural Networks and Deep Learning_ by Nielsen. Uses the Theano library which is no longer popular. However, most of this [free online textbook](http://neuralnetworksanddeeplearning.com/) is focused on conceptual issues that will not become out-of-date anytime soon.
  
- **Undergraduate Courses on Deep Learning**: Many universities now offer an introductory deep learning course, e.g., [Berkeley](https://c.d2l.ai/berkeley-stat-157/), [CMU](https://deeplearning.cs.cmu.edu/), [MIT](http://introtodeeplearning.com/), [Stanford](https://cs230.stanford.edu/)
- **Canvas**: You should access the [Canvas class page](https://umich.instructure.com/courses/516592) for this course frequently. It will let you access important announcements and track course deliverables. (requires UM login)
- **Slack**: The course slack workspace is at [um-wn22-stats315.slack.com](https://um-wn22-stats315.slack.com) (requires UM login)
- **Days and Times**: Tuesdays and Thursdays, 10-11:30
- **Location**: [B1580 BUS](https://maps.studentlife.umich.edu/building/jeff-t-blau-hall) (for virtual lectures, you can find zoom link in canvas or slack)

## Instructor Information

_Note: Due to the omicron surge, all office hours will be held via zoom until further notice._

**Name**: Ambuj Tewari  
**Office Hours**: Tue and Thu, 11:30-1 ([zoom link](https://umich.zoom.us/j/93781998446))    
**Email**: [tewaria@umich.edu](mailto:tewaria@umich.edu)

## GSI Information

**Name**: Vinod Raman (Lab 002 Th 8:30-10)  
**Email**: [vkraman@umich.edu](mailto:vkraman@umich.edu)

**Name**: Yash Patel (Lab 003 Th 2:30-4)    
**Email**: [yppatel@umich.edu](mailto:yppatel@umich.edu)

**Lab webpage** (also has GSI office hours info): [https://yashpatel5400.github.io/stats315-winter2022lab/](https://yashpatel5400.github.io/stats315-winter2022lab/)

## Grading

- Weekly quizzes (60%): We will only use your top 10 scores
- Homeworks (40%): Four homework assignments with a substantial coding component

## Academic Integrity

The University of Michigan community functions best when its members treat one another with honesty, fairness, respect, and trust. The college promotes the assumption of personal responsibility and integrity, and prohibits all forms of academic dishonesty and misconduct. All cases of academic misconduct will be referred to the LSA Office of the Assistant Dean for Undergraduate Education. Being found responsible for academic misconduct will usually result in a grade sanction, in addition to any sanction from the college. For more information, including examples of behaviors that are considered academic misconduct and potential sanctions, please see [https://lsa.umich.edu/lsa/academics/academic-integrity.html](https://lsa.umich.edu/lsa/academics/academic-integrity.html)

## Accommodation for Students with Disabilities

If you think you need accommodation for a disability, please let me know at your earliest convenience. Some aspects of this course, the assignments, the in-class activities, and the way the course is usually taught may be modified to facilitate your participation and progress. As soon as you make me aware of your needs, we can work with the Office of Services for Students with Disabilities (SSD) to help us determine appropriate academic accommodations. SSD (734-763-3000; [http://ssd.umich.edu/](http://ssd.umich.edu/)) typically recommends accommodations through a Verified Individualized Services and Accommodations (VISA) form. Any information you provide is private and confidential and will be treated as such.

## Mental Health and Well-Being

Students may experience stressors that can impact both their academic experience and their personal well-being. These may include academic pressures and challenges associated with relationships, mental health, alcohol or other drugs, identities, finances, etc. If you are experiencing concerns, seeking help is a courageous thing to do for yourself and those who care about you. If the source of your stressors is academic, please contact me so that we can find solutions together. For personal concerns, U-M offers a variety of resources, many which are listed on the [Resources for Student Well-being](https://wellbeing.studentlife.umich.edu/resources-list) webpage. You can also search for additional well-being resources [here](https://wellbeing.studentlife.umich.edu/well-being-resources). 

## Schedule

IDL = _Introduction to Deep Learning_ by Charniak    
DLPy = _Deep Learning with Python (2nd edition)_ by Chollet    
DL = _Deep Learning_ by Goodfellow, Bengio and Courville    
NNDL = _Neural Networks and Deep Learning_ by Nielsen    
D2L = _Dive into Deep Learning_ by Zhang, Lipton, Li and Smola    

_Note_: A "V" in the date column denotes a virtual lecture.

Lecture No. | Date | Topic | Reading Assignment 
---         | ---  | ---   | ---               
&nbsp; |       | **Basics** |
01     | Jan 06 | Course logistics <br/> Introduction <br/> [slides](https://docs.google.com/presentation/d/1i2g3yoxzL_sciLtKmJrb2EWFRnaFm1vzmzvMSg9oSeo/edit?usp=sharing) | DLPy, Chap. 1 <br/> DL, Chap. 1 <br/> D2L, Chap. 1
02     | Jan 11 <br/> V | Basic Elements of Linear Regression <br/> [slides](https://docs.google.com/presentation/d/1mlwk7Y89Jmxzn-f22lSIWVZdXLBcaDPBx7VJfLrxLvw/edit?usp=sharing) | D2L, Sec. 3.1.1
03     | Jan 13 <br/> V | Regression <br/> Loss functions and gradient descent <br/> [slides](https://docs.google.com/presentation/d/1oSQes_xa7JhJ7kfsrGuD7RhLnm7tw75AlnNdkCyynL0/edit?usp=sharing) | D2L, Sec. 3.1.1
04     | Jan 18 <br/> V | Regression wrap-up <br/> Classification <br/> [slides](https://docs.google.com/presentation/d/1MyEGh1iCxWssAIAoI9-XCU-HB2-UBj0mkv-UEv-IY3o/edit?usp=sharing) | D2L, Sec. 3.1.3-4 <br/> D2L, Sec. 3.4.1
05     | Jan 20 <br/> V | Softmax Operation <br/> Cross Entropy Loss Function <br/> [slides](https://docs.google.com/presentation/d/1dJNBtz4V2_fw_pDOK63Ka9igZpLALI2icdvLZi8n4UQ/edit?usp=sharing)|  D2L, Sec. 3.4.2-4 <br/> D2L, Sec. 3.4.6.1 
06     | Jan 25 | Softmax Derivatives <br/> Information Theory Basics <br/> [slides](https://docs.google.com/presentation/d/1P4VMvq1TboRZSDMHXc2HopTlSFC28kxw5Sm7BjFgnvI/edit?usp=sharing)|  D2L, Sec. 3.4.6.2-3 <br/> D2L, Sec. 3.4.7
&nbsp; |        | **TensorFlow/Keras** |
07     | Jan 27 | TensorFlow, Keras, Google Colab <br/> [notebook](https://colab.research.google.com/drive/158clJ-gSasbyIFB4Cg8tSj_sXq_W2zbR?usp=sharing) | DLPy, Sec. 3.1-4
08     | Feb 01 | First steps with TensorFlow <br/> [notebook](https://colab.research.google.com/drive/158clJ-gSasbyIFB4Cg8tSj_sXq_W2zbR?usp=sharing) | DLPy, Sec. 3.5.1-2 <br/> DLPy, Sec. 2.4.4 
--     | Feb 03 | CANCELLED | 
--     | Feb 06 | <span style="color:red">HW 1 due</span>
09     | Feb 08 | First steps with TensorFlow (continued) <br/> [notebook](https://colab.research.google.com/drive/158clJ-gSasbyIFB4Cg8tSj_sXq_W2zbR?usp=sharing) | DLPy, Sec. 3.5.3-4
10     | Feb 10 | Getting started with NNs: Classification MNIST <br/> [notebook](https://colab.research.google.com/drive/1S5zTo1gkfhkcKCXTicIlmGq8WPmYo3pZ?usp=sharing) | DLPy, Sec. 2.1
11     | Feb 15 | Getting started with NNs: Classification IMDB <br/> [notebook](https://colab.research.google.com/drive/1iXR9tg32xqCo0tu3USKGGMCV9EXF3lKF?usp=sharing) | DLPy, Sec. 4.1
12     | Feb 17 | Getting started with NNs: Regression Boston Housing Price <br/> [notebook](https://colab.research.google.com/drive/1RWw-WaszqBGazJe81NQ1-ezn0FxbSCgF?usp=sharing) | DLPy, Sec. 4.3
13     | Feb 22 | Generalization <br/> Evaluating ML models <br/> [notebook](https://colab.research.google.com/drive/1PWo49STp9ITm_uV-AtET-FsnzUExKcwt?usp=sharing) | DLPy, Sec. 5.1-2
14     | Feb 24 | Improving model fit <br/> Regularizing your model <br/> [notebook](https://colab.research.google.com/drive/1zLs_U_gwYu6cJVjHmCOaA0wsV-CgKaDH?usp=sharing) | DLPy, Sec. 5.3 <br/> DLPy, Sec. 5.4.4
--     | Mar 01 | SPRING BREAK |
--     | Mar 03 | SPRING BREAK |
&nbsp; |        | **Linear Algebra Boot Camp** |
15     | Mar 08 | Linear Algebra <br/> [notebook](https://colab.research.google.com/drive/1Jff1QTe9LKAa9B4bIVk-ItnHIT8FBzqH?usp=sharing) | D2L, Sec. 18.1.1-2
16     | Mar 10 | Linear Algebra (continued) <br/> [notebook](https://colab.research.google.com/drive/1Jff1QTe9LKAa9B4bIVk-ItnHIT8FBzqH?usp=sharing) <br/> <span style="color:red">HW 2 due</span> | D2L, Sec. 18.1.3-5 
17     | Mar 15 | Linear Algebra (continued) <br/> [notebook](https://colab.research.google.com/drive/1Jff1QTe9LKAa9B4bIVk-ItnHIT8FBzqH?usp=sharing) | D2L, Sec. 18.1.6-7 <br/> D2L, Sec. 18.1.9
&nbsp; |        | **Convolutional Neural Networks** |
18     | Mar 17 |  From Fully-Connected Layers to Convolutions <br/> [notebook](https://colab.research.google.com/drive/1qq6NaNSZEbt3sjqX4cCAYEUjHn1nEo25?usp=sharing) | D2L, Sec. 6.1
19     | Mar 22 | Convolutions for Images <br/> [notebook](https://colab.research.google.com/drive/1YYVG1swme5zom6aajkwCPPbLuZZ6WY5J?usp=sharing) <br/> Padding and Stride <br/> [notebook](https://colab.research.google.com/drive/1pCxggO1hhW6nodWTPlvmAA-99FJXzyzE?usp=sharing) <br/> Multiple Input and Multiple Output Channels <br/> [notebook](https://colab.research.google.com/drive/1wDPtqbjSFEnW8ebjB5z4r7twL93y2OFY?usp=sharing) | D2L, Sec. 6.2 <br/> D2L, Sec. 6.3-4
--    | Mar 24 | CANCELLED | 
20     | Mar 29 | Pooling <br/> [notebook](https://colab.research.google.com/drive/1x4strUhdYnER0NWBXl9JE1DK4XtdH_rq?usp=sharing) <br/> LeNet <br/> [notebook](https://colab.research.google.com/drive/1zKtu7pH2qPb_5DCCMNJ5BhlpfzY7-9I5?usp=sharing) | D2L, Sec. 6.5-6
&nbsp; |        | **Deep Learning for Time Series** |
--     | Mar 31 | CANCELLED <br/> <span style="color:red">HW 3 due</span> |
21     | Apr 05 <br/> V | A temperature-forecasting example <br/> [notebook](https://colab.research.google.com/drive/1UFfFz2M79i8H2Ug2CDeP6OART73UG975?usp=sharing) | DLPy, Sec. 10.2
22     | Apr 07 | A temperature-forecasting example (continued) <br/> [notebook](https://colab.research.google.com/drive/1UFfFz2M79i8H2Ug2CDeP6OART73UG975?usp=sharing) | DLPy, Sec. 10.2
23     | Apr 12 | Understanding recurrent neural networks <br/> Advanced use of recurrent neural networks <br/> [notebook](https://colab.research.google.com/drive/1UFfFz2M79i8H2Ug2CDeP6OART73UG975?usp=sharing) | DLPy, Sec. 10.3 <br/> DLPy, Sec. 10.4
24     | Apr 14 | Recurrent Neural Networks <br/> [notebook](https://colab.research.google.com/drive/1nVyijPFe9fJOt9mBdUa1qKqNos8JWGcg?usp=sharing) <br/> Backpropagation Through Time <br/> [notebook](https://colab.research.google.com/drive/1i4dxYyKWzGZHU9T1S4Wi3sH1-zhjLL3Z?usp=sharing) <br/> V |  D2L, Sec. 8.4 <br/> D2L, Sec. 8.7.1
25     | Apr 19 | Course Conclusion <br/> Ask Me Anything! <br/> [slides](https://docs.google.com/presentation/d/1sav3giUY_WhkjzZjQ_b3EKDJ06ERa-seH2TwDs1KAyk/edit?usp=sharing) |
&nbsp; | Apr 25 | <span style="color:red">HW 4 due</span> 
&nbsp; |        | **Multivariable Calculus Boot Camp** |
&nbsp; |        | Multivariable Calculus <br/> [notebook](https://colab.research.google.com/drive/1u-MlftcLbH7xMGielwGxUQ9XAQDXiQKD?usp=sharing) | D2L, Sec. 18.4

