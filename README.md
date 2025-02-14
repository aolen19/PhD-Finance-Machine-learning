# PhD-Finance-Machine-learning

# Introduction
This project tries to include almost all necessary knowledge about doing a PhD in Finance using Machine learning. 

As machine learning rapidly merged with traditional social science, it's very attractive to apply Machine learning to finance field, especially prediction related problem.

Currently, it includes:
  1. The machine learning algorithm and intuitive applications
  1. Related mathematics algorithm. 
  1. Trading strategies
      1. Momentum Strategies
      1. Pair Trading Strategies
  1. Asset pricing 
      1. Retrieve data from WRDS
      1. Common risk factors and firm characteristics
 
# About me
 
Third-year PhD. candidate in finance at Durham University.
 
5 years of data analysing and 2-year quant experience specializing in machine learning and equity prediction.Interested in fancy technologies and equipment. Familiar with many kinds of derivatives, stocks and bonds, and devoted to more accurate asset pricing and forecasting methods. 
 
A cat lover and a good chef (Chinese Cuisine and Sichuan hotpot). If you find me, I would very like to treat you a special dinner with my menu.


# How to find related reference

Each research field has a trend. Traditional research area can directly search the published resources such as the web of science  (www.webofknowledge.com) to create the personal library. While for some newly established intersection research such as machine learning in finance filed,  papers tend to be in different areas. Publishing papers require a long time. Researchers would be more willing to published their working paper in some public database such as SSRN and arXiv before it's too late. 

Normally the machine learning in fiance papers can be mostly (not all) found in the following places:

1. Working papers in public database: SSRN(more finance and social science papers), arXiv(more computer science paper) and some university-owned database(MIT, Chicago booth)

2. Journal paper:
    1. Expert System with Applications (3)
    1. Management Science (4*)
    1. Journal of Financial Economics (4*)
    1. Journal of Emperical Finance (3)
    

As papers are not published in the same journal, I would highly recommend using google scholar as the main reference management website. Of course, you may use the EndNote (if your university offers the free student version), Melody(Free) or other software. But google scholar for me is good enough to support every function required. 

Some functions are extremely useful in google scholar after you sign in your google account.
1. 'Labels': A tag-like button just below the search box. You may category your papers with this tool. Can help you manage the big amount of literature.
1. 'Related Articles': A button under the title of the paper. It may automatically research all related articles to this topic. The result may include all possible working papers, conference papers and journal papers from many fields in the most popular order. It can make one quickly grasp the recent trend and result of one topic.
1. 'Cite': A double-quotation-mark-like button. Generate multiple format citations for Bibtex, EndNote, et al. One can export multiple citations for selected papers by using the 'Export' button below the search box. As I don't use EndNote, the Bibtex format is the most used. 
1. 'Anytime': Some years listed in the left-hand side. We would have more cared about the recently 2 years papers or sometimes the latest published paper. This function filters papers by years. Normally papers within 5 years are comparably new and some working papers within one year are great to learn the hot topics and the most popular issues.



# Choose an editor to write the essay

The most frequently used editor in normal life would be the Word from Microsoft Office. While it's not the best choice for academic writing. For my point of view, the only option for researchers is LaTex which offered the high-quality formatting system and makes your papers more professional. You may write your CV, cover letter and even apologies letter to make them proper and formal. The advantage of LaTex is:
1. Easy to manage Bibliography using the bib file. The bib file can reuse in the next paper
1. Once get on the board, you will forget about the fear of adjusting the linewidth and font style. 
1. Abundant of templates and easy to use with one mouse click.

There are plenty of LaTex editors and what I use is [**OverLeaf**](https://www.overleaf.com/) which is a web browser-based online editor. Since all data are uploaded and saved on the cloud. As long as you can find a computer with Wifi, you can start to work. Almost all necessary packages are installed already and you will never be worried about the computer crash as it will automatically save the documents from time to time.  Some beautiful templetes can be found in [**here**](https://www.overleaf.com/gallery)


# Python - A free language 

## Introduction of Python
Python has become the top programming language recently. Not like traditional C or C++, Python is a very high-level language where almost all usually used functions are provided by either company like google or individual contributors. So we have to bear in mind that packages may get wrong, especially for some rarely used packages. It's always good to check carefully to make sure the results are correct. 

Python is very popular in the industry because it's free. Matlab is better in terms of efficiency and well-designed packages. But the expense is just too high for some start-up companies. Learning python also improve competitiveness in the job market.


## Choose python version 3.X 
Python mainly has three versions. The old version is 2.7 and the two new version are 3.6 and 3.7. I would recommend using at least python 3.6. If you would like to risk some unstable issue (very rare to happen), the 3.7 version may be a better choice. My current version is 3.7 as I believe normally most packages will try to compatible with the newest version python. The 2.X version is significantly different from 3.X version and it's very out of date as many latest version of packages like pandas and Numpy doesn't officially support the python 2.X. Also, the codes from python 2.X may not run successfully on 3.X for the code grammar changes (such as: 'print'). 


## The choice of Python IDE

Mycommendations are using jupyter notebook for making report or tutorial and using PyCharm for real programming.

IDE provides comprehensive facilities to computer programmers for software development, and a proper IDE can make your coding much easier and faster. The most popular IDEs are PyCharm and Jupyter notebook. Jupyter notebook comes from iPython, creating the documents that contain live code, equations, visualizations and narrative text. It's a perfect solution for presenting the project and making the report. 

When it comes to real programming project which more than a hundred functions and .py files, the jupyter notebook becomes not that friendly. PyCharm is a gem in Python Community. I used Visual Studio for C++ programming before, and PyCharm even excels in many perspectives. The professional version of PyCharm is free for all students and it offers the historical tracking records, code duplicates check, time-consuming check et al... It also supports jupyter notebook so that you can create and edit jupyter file inside. The virtual environment is also easy to switch. 

All in all, why not to use PyCharm and make life easier? The JupyterLab may be an alternative, but currently if not for some specific reason, PyCharm is still the best choice. 

# Machine learning with Python

## Introduction of the Machine learning algorithm
Machine learning represents huge groups of algorithms and methodology. We can give three categories in terms of Learning Style which are supervised learning, unsupervised learning and reinforcement learning. The key difference between supervised and unsupervised is if we label the samples. If samples are labelled with a target value and fed into a machine learning model. It must be a supervised learning model. Reinforcement learning reverses the idea of traditional machine learning. Without minimizing the loss function, it carefully designs a reward function and the model aims to maximize the reward function to get the best performance. 

The most commonly used algorithms are:

- Supervised learning
  - Logistic Regression (Supervised learning – Classification)
  - Naïve Bayes Classifier Algorithm (Supervised Learning - Classification)
  - Support Vector Machine Algorithm (Supervised Learning - Classification)
  - Decision Trees (Supervised Learning – Classification/Regression)
  - Random Forests (Supervised Learning – Classification/Regression)
  - Artificial Neural Networks (Supervised Learning – Classification)
- Unsupervised learning
  - K Means Clustering Algorithm (Unsupervised Learning - Clustering)
- Reinforcement learning
  - Artificial Neural Networks (Reinforcement Learning)

Our research mainly focuses on Supervised and Unsupervised learning as there are still many potential topics. The Reinforcement learning is leading by UC Berkley and we are still waiting for a mature tool so that no computer science background researchers can more easily get involved in this powerful tool. 

## Scikit-learn and TensorFlow
We are lucky that most algorithms are provided by [**scikit-learn**](https://scikit-learn.org/) and [**TensorFlow**](https://www.tensorflow.org/). It's not easy to implement machine learning algorithms like neural network and random forest as well as taking the efficiency and user-friendly into consideration. These tools are tested by hundreds and thousands of users and survive from the time. The scikit-learn package offers not only the models but also many data preprocessing and data visualizations tools. It's also a good place to initially start learning the framework of machine learning. 

I would recommend using TensorFlow as the primary development tool for Depp Learning. Deep learning has become the most significant model with a great contribution to NLP and Image Recognization. It's a group of special Artificial Neural Network which has more than one hidden layers. Because of the huge amount of computational ability requirement and difficult to implement, much open-source deep-learning library comes up. The top three platforms are TensorFlow (from Google), PyTorch and Theano. Apparently, with top research and development ability, google keep developing and enhancing the TensorFlow and make it as one of the most convenient tools. In 2019, the TensorFlow 2.0 perfectly merged with Keras which is a straightforward machine learning model packages. Now even a beginner with some basic computer science knowledge can set up his LSTM network in minutes. That lowers the entry barrier and make Machine learning convenient to more developers.


# Setting up machine learning environment in Windows and Ubuntu

Now it's time to set up the machine learning platform on your machine now. Depending on the Operation system, the instlalling process may changes. But the softwares and packages are identical. 

We need to install Anaconda firstly and set up the virtual environment. Then install the PyCharm and select the virtual environment as the interpreter for all project. The virtual environment will include all must-have packages like tensorflow, scikit-learn, pandas, cuDnn, CudaToolkit et al...

The guide to install anaconda and pycharm in Windows can refer to [**Guide_to_install_pycharm_and_anaconda**](Install_pycharm_anaconda_windows.md)

The guide to install anaconda and pycharm in Ubuntu 18.04 can refer to [**How To Install Anaconda on Ubuntu 18.04**](https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart)

The guide to set up virtual environment in Ubuntu can refer to [**Guide_to_set_up_anaconda**](TensorFlow_2_0_gpu_installation_guide_ubuntu.md). 

The Windows version will come soon. 

