## Welcome to STATS 315 / DATA SCI 315

This is an introductory deep learning course using the Python programming language and the TensorFlow deep learning library.

- **Textbook**: We will not follow any one textbook too closely. Here are a few references we might use:
  - _Introduction to Deep Learning_ by Charniak. This undergraduate level textbook is perhaps the closest to this course in terms of prerequisites and the level at which deep learning is presented. It is available from [MIT Press](https://mitpress.mit.edu/books/introduction-deep-learning). Unfortunately this uses TensorFlow version 1 whereas we will use the more user friendly version 2.
  - _Deep Learning with Python (2nd edition)_ by Chollet. A solid hands-on guide oriented towards programmers from the creator of the Keras deep learning library. Ebook and print versions are available from [Manning Publications](https://www.manning.com/books/deep-learning-with-python-second-edition).
  - _Deep Learning_ by Goodfellow, Bengio and Courville. Written by three top deep learning researchers, this comprehensive book is required reading if you want to pursue your study of deep learning at a more advanced level. Print version is available from [MIT Press](https://mitpress.mit.edu/books/deep-learning) and an online version is [here](https://www.deeplearningbook.org/).
  - _Neural Networks and Deep Learning_ by Nielsen. Uses the Theano library which is no longer popular. However, most of this [free online textbook](http://neuralnetworksanddeeplearning.com/) is focused on conceptual issues that will not become out-of-date anytime soon.
  - _Dive into Deep Learning_ by Zhang, Lipton, Li and Smola. An advanced text from research scientists at Amazon. It weaves together math, figures, and code in an interactive online resource available [here](https://d2l.ai/). Code examples are provided in three frameworks: MXNet, PyTorch and TensorFlow. 
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

**Name**: Yash Patel    
**Email**: [yppatel@umich.edu](mailto:yppatel@umich.edu)

**Name**: Vinod Raman  
**Email**: [vkraman@umich.edu](mailto:vkraman@umich.edu)

**Lab webpage** (also has GSI office hours info): [https://yashpatel5400.github.io/stats315-winter2022lab/](https://yashpatel5400.github.io/stats315-winter2022lab/)

## Grading

- Weekly quizzes (60%): We will only use your top 10 scores
- Homeworks (40%): Four homeworks with a substantial coding component

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
01     | Jan 06 | Course logistics <br/> Introduction <br/> [slides](https://docs.google.com/presentation/d/1i2g3yoxzL_sciLtKmJrb2EWFRnaFm1vzmzvMSg9oSeo/edit?usp=sharing) | DLPy, Ch. 1 <br/> DL, Ch. 1 <br/> D2L, Ch. 1
02     | Jan 11 <br/> V | Basic Elements of Linear Regression <br/> [slides](https://docs.google.com/presentation/d/1mlwk7Y89Jmxzn-f22lSIWVZdXLBcaDPBx7VJfLrxLvw/edit?usp=sharing) | D2L, Sec. 3.1.1
03     | Jan 13 <br/> V | Regression <br/> Classification <br/> [slides](https://docs.google.com/presentation/d/1oSQes_xa7JhJ7kfsrGuD7RhLnm7tw75AlnNdkCyynL0/edit?usp=sharing) | D2L, Sec. 3.1.3-4 <br/> D2L, Sec. 3.4.1-3
04     | Jan 18 | Softmax Operation <br/> Loss Function <br/> Information Theory Basics <br/> [slides](https://docs.google.com/presentation/d/1MyEGh1iCxWssAIAoI9-XCU-HB2-UBj0mkv-UEv-IY3o/edit?usp=sharing)|  D2L, Sec. 3.4.4 <br/> D2L, Sec. 3.4. <br/> D2L, Sec. 3.4.7 
05     | Jan 20 |  | TBD
&nbsp; |       | **TensorFlow/Keras** |
06     | Jan 25 | TensorFlow, Keras, Google Colab | DLPy, Sec. 3.1-3.4
07     | Jan 27 | First steps with Tensorflow | DLPy, Sec. 3.5 
08     | Feb 01 | Keras Layers | DLPy, Sec. 3.6
09     | Feb 03 | Machine learning fundamentals | DLPy, Ch. 5 
&nbsp; |        | **Multilayer Perceptrons** |
--     |        | Perceptrons and activation functions | --
--     |        | Multilayer perceptrons, Backprop | --
--     |        | Universal Approximation | --
--     |        | Depth | --
&nbsp; |        | **Convolutional Neural Networks and Vision** |
--     |        | Convolutions and Pooling | --
--     |        | Multilayer convolutions | --
&nbsp; |        | **Sequence Models and Language** |
--     |        | -- | --

