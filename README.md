## Approach
A practical, top-down approach, starting with high-level frameworks with a focus on Deep Learning.

---

Language versions: [Korean](https://github.com/emilwallner/How-to-learn-Deep-Learning/blob/master/README_kr.md) | [English](https://github.com/emilwallner/How-to-learn-Deep-Learning/blob/master/README.md)

## Getting started [2 months]

There are three main goals to get up to speed with deep learning: 
1) Get familiar to the tools you will be working with, e.g. Python, the command line and Jupyter notebooks
2) Get used to the workflow, everything from finding the data to deploying a trained model
3) Building a deep learning mindset, an intuition for how deep learning models behave and how to improve them

- Spend a week on codecademy.com and learn the python syntax, command line and git. If you don't have any previous programming experience, it's good to spend a few months learning how to program. Otherwise, it's easy to become overwhelmed. 
- Spend one to two weeks using [Pandas](https://www.youtube.com/watch?v=yzIMircGU5I&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) and [Scikit-learn](http://scikit-learn.org/stable/) on [Kaggle problems](https://www.kaggle.com/competitions?sortBy=grouped&group=general&page=1&pageSize=20&category=gettingStarted) using [Jupyter Notebook on Colab](https://colab.research.google.com/notebooks/welcome.ipynb), e.g. [Titanic](https://www.kaggle.com/c/titanic), [House prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques), and [Iris](https://www.kaggle.com/uciml/iris). This gives you an overview of the machine learning mindset and workflow. 
- Spend one month implementing models on cloud GPUs. Start with [FastAI and PyTorch](http://course.fast.ai/). The FastAI community is the go-to place for people wanting to apply deep learning and share the state of the art techniques.

Once you have done this, you will know how to add value with ML. 


## Portfolio [3 - 12 months]

Think of your portfolio as evidence to a potential employer that you can provide value for them.

When you are looking for your first job, there are four main roles you can apply for 
1. Machine Learning Engineering, 
1. Applied Machine Learning Researcher, 
1. Machine Learning Research Scientist, and 
1. Software Engineering. 

A lot of the work related to machine learning is pure software engineering roles (category 4), e.g. scaling infrastructure, but that's out of scope for this article. 

Here are rough guidelines to self-assess the strength of your portfolio:

#### Machine learning engineering:

Project Type | Base score | 
-------------| -----------|
Common project | -1 p ||
Unique project | 10 p |

Multiplier Type | Factor
-----------------|-----------------
Readme | 5x
Write-up | 5x
Kaggle Medal | 10x
Employer relevancy | 20x
 
* __Hireable:__ 5,250 p
* __Competative:__ 15,000 p



#### Applied research/ research assistant/ residencies:

Projects type | Base score
--------------| -----------
Common project | -1 p
Unique project | 1 p
SOTA paper implementation | 20 p

Multiplier type | Factor
----------------| --------------- 
Readme | 5x
Write-up | 5x
SOTA performance | 5x
Employer relevancy | 20x

* __Hireable:__  52,500 p
* __Competitive:__ 150,000 p


#### Research:

Project type | Base score
-------------| ----------------
An unpublished paper | 5 p
ICML/ICLR/NeurIPS publication | 500p
All other publications | 50 p

Multiplier type | Factor
------------------| ------------------
First author paper | 10x
Employer relevancy | 20x

* __Hireable:__ 20,000 p
* __Competitive roles and elite PhD positions:__ 200,000 p

### Context

You'll have a mix of  5 - 10 technical and non-technical people looking at your portfolio, regardless of their background, you want to spark the following reactions: 
* the applicant has experience tackling our type of problems,
* the applicant's work is easy to understand and well organised, and
* the work was without a doubt 100% made by the applicant.

Common projects include things as MOOC participation, dog/cat classifiers, the titanic and iris datasets. They are often more distracting than useful. They also indicate that you activly avoid real-world problem-solving.

A unique portfolio item implies that you have tackled a unique problem without a solution, and thus have to engage in the type of problem-solving an employee does daily. A good starting point is to look for portfolio ideas on [active Kaggle competitions](https://www.kaggle.com/competitions), and [machine learning consulting projects](https://www.upwork.com/freelance-jobs/machine-learning/), and demo versions of [common prodution pipelines](https://github.com/chiphuyen/machine-learning-systems-design/blob/master/build/build1/consolidated.pdf). Here's a Twitter thread on [how to come up with portfolio ideas](https://twitter.com/EmilWallner/status/1184723538810413056).

__Examples:__
* My first portfolio item (after 2 months of learning): [Code](https://github.com/emilwallner/Coloring-greyscale-images) | [Write-up](https://blog.floydhub.com/colorizing-b-w-photos-with-neural-networks/)
* My second portfolio item (after 4 months of learning): [Code](https://github.com/emilwallner/Screenshot-to-code) | [Write-up](https://blog.floydhub.com/turning-design-mockups-into-code-with-deep-learning/)
* [Dylan Djian's](https://github.com/dylandjian) first portfolio item: [Code](https://github.com/dylandjian/retro-contest-sonic) | [Write-up](https://dylandjian.github.io/world-models/)
* [Dylan Djian's](https://github.com/dylandjian) second portfolio item: [Code](https://github.com/dylandjian/SuperGo) | [Write-up](https://dylandjian.github.io/alphago-zero/)
* [Reiichiro Nakano's](https://github.com/reiinakano) first portfolio item: [Code](https://github.com/reiinakano/arbitrary-image-stylization-tfjs) | [Write-up](https://magenta.tensorflow.org/blog/2018/12/20/style-transfer-js/)
* [Reiichiro Nakano's](https://github.com/reiinakano) second portfolio item: [Write-up](https://reiinakano.com/2019/01/27/world-painters.html)

Most recruiters will spend 10-20 seconds on each of your portfolio items. Unless they can understand the value in that time frame, the value of the project is close to zero. Thus, writing and documentation are key. Here's another thread on how to [write about portfolio items](https://twitter.com/EmilWallner/status/1162289417140264960). 

The last key point is relevancy. It's more fun to make a wide range of projects, but if you want to optimize for breaking into the industry, you want to do all projects in one niche, thus making your skillset **super** relevant for a specific pool of employers.

__Further Inspiration:__
* [FastAI student projects](https://forums.fast.ai/t/share-you-work-here-highlights/57140)
* [Stanford NLP student projects](https://nlp.stanford.edu/courses/cs224n/)
* [Stanford CNN student projects](http://cs231n.stanford.edu/index.html)


## Theory 101 [1-3 months]

Learning how to read papers is a great source to improve your projects, and critical if you want to get into research. There are three key areas to feel comfortable reading papers:
1) Understanding the details of the most frequent algorithms, gradient descent, linear regression, and MLPs, etc
2) Learning how to translate the 50 most frequent math notations
3) Learn the basics of algebra, calculus, statistics, and machine learning

- Spend one month [recoding the core concepts](https://github.com/emilwallner/Deep-Learning-From-Scratch) in python numpy, including least squares, gradient descent, linear regression, and a vanilla neural network. Andrew Trask's [book](https://www.manning.com/books/grokking-deep-learning) and [blog](https://iamtrask.github.io/) are great for this. This will help you reduce a lot of cognitive load down the line. 
-  I believe the best deep learning theory curriculum is the [Deep Learning Book](http://www.deeplearningbook.org/) by Ian Goodfellow and Yoshua Bengio and Aaron Courville. I use it as a curriculum, and the use the internet to learn the details about each concept. Although, it's good to have six months of practical experience or a math/statistic background before you start with the theory. 
- Most of the value comes from memorizing the math notations on the first few pages. Learning that notations are compact logic and how to translate it into code will make you feel less anxious about the theory. If you have a week spare, I'd spend it on 3Blue1Brown's [Essence of linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), [the Essence of Calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr), and StatQuests' [the Basics (of statistics)](https://www.youtube.com/watch?v=qBigTkBLU6g&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) and [Machine Learning](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF). Use a spaced repetition app like Anki and memorize all the key concepts. Use images as much as possible, they are easier to memorize. 
- If you have 2-3 months, spend it on part 1 of the Deep learning book. The MachineLearningGod shows a [great way to study the book.](https://www.youtube.com/watch?v=bzp5bQY7XmE&list=PLh6SAYydrIpc8uCGc_KxjLSDRV6tfT10u&index=2) Use lectures and videos to understand the concepts, and then use Anki and Khan academy exercises to learn them. 



## Forums
- [FastAI](http://forums.fast.ai/)
- [Keras Slack](https://keras-slack-autojoin.herokuapp.com/)
- [Distill Slack](https://join.slack.com/t/distillpub/shared_invite/enQtMzg1NzU3MzEzMTg3LWJkNmQ4Y2JlNjJkNDlhYTU2ZmQxMGFkM2NiMTI2NGVjNzJkOTdjNTFiOGZmNDBjNTEzZGUwM2U0Mzg4NDAyN2E)
- [Pytorch](https://discuss.pytorch.org/)
- Twitter


## Write-up of my process
- [Implementing Keras models (I started with TFlearn, but I'd highly recommend using Keras instead)](https://blog.floydhub.com/my-first-weekend-of-deep-learning/) (I mistakenly thought TFlearn was the official frontend. They have now made Keras the official front-end to Tensorflow.)
- [Recoding the core concepts in python](https://blog.floydhub.com/coding-the-history-of-deep-learning/)
- [My first paper using CNN](https://blog.floydhub.com/colorizing-b&w-photos-with-neural-networks/)
- [My first paper using LSTM](https://blog.floydhub.com/turning-design-mockups-into-code-with-deep-learning/)
- [My first paper using a GAN](http://www.aiartonline.com/design/emil-wallner/)
- [My first paper using RL/evolution](https://github.com/corewarai/open_project)
- [On going via my twitter feed](https://twitter.com/EmilWallner)

## Other good learning strategies:
- [S. Zayd Enam](http://ai.stanford.edu/~zayd/why-is-machine-learning-hard.html)
- [Catherine Olsson](https://80000hours.org/articles/ml-engineering-career-transition-guide/)
- [Greg Brockman V2](https://blog.gregbrockman.com/how-i-became-a-machine-learning-practitioner)
- [Greg Brockman V1](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer)
- [Andrew Ng](https://www.youtube.com/watch?v=F1ka6a13S9I)
- [Amid Fish](http://amid.fish/reproducing-deep-rl)
- [Spinning Up by OpenAI](https://spinningup.openai.com/en/latest/spinningup/spinningup.html)
- [Confession as an AI researcher](https://www.reddit.com/r/MachineLearning/comments/73n9pm/d_confession_as_an_ai_researcher_seeking_advice/)
- YC Threads: [One](https://news.ycombinator.com/item?id=20765553) and [Two](https://news.ycombinator.com/item?id=18421422)

If you have suggestions/questions create an issue or [ping me on Twitter.](https://twitter.com/EmilWallner)
