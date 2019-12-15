# AI & ML made functional
Create AI/ML systems in the cloud through Azure Notebooks, F# & .NET Core with MLOps environments 


FAQ
===================


Why use F# for data science projects?
===================

F# is an excellent programming language that is functional first. It's well-suited for data science projects due to the following: 
* Efficient execution
* Concisness
* Strict type system
* Data access capabilities
* Scalability

In time, F# has shown how powerful a tool it is and now Microsoft is investing more efforts and time to showcase that it's an excellent tool for machine learning.

"Finally, we're also devoting significant time in developing a compelling offering for using F# to do machine learning. In addition to being supported on ML.NET, we're working towards a world-class experience when using F# and TensorFlow," Microsoft said. 

What is the scope of the repository?
===================

The scope of the repository is quite big. It was created for both beginners and intermediate in the following categories:

* Machine Learning
* Functional Programming
* DevOps

The purpose of the repository is to see machine learning from a different kind of lenses. Using skills that some may already have by using the .NET framework (or .NET Core), you will come to get to know enough of data science space such as:

* Feature engineering
* Data normalization
* Setuping your environment
* Using a Jupyter Notebook
* Evaluating your model
* Train your model


What kind of projects can be consulted in the repository?
===================

The repository will use old and current machine learning competitions that are found on [Kaggle](https://www.kaggle.com/). For those who don't know what Kaggle is, in a few words, it is the world's largest community of data scientists. It provides you courses on data science and the chance to compete on machine learning project either for the sake of putting your skills to the test or to get on the podium and win big cash prizes.

Also, you'll also be able to find machine learning notes on courses that I will take online with resources such as [Coursera](https://www.google.com/search?client=firefox-b-d&q=coursera) or [Udacity](https://www.udacity.com/). The vast majority of the courses should be with Python, but I'll make sure, to the best of my abilities, to refactor the code samples to showcase only F#.

Why should we go for automation in data science?
===================
Like in any field of software engineering/development, we want to make sure we get the best value for our buck. In this case, you want to make sure you avoid repetitive tasks and you can spend your time on things that matter, not normalize a portion of your data for the tenth time in the same day **manually**.


How can you get started today for AI/ML projects with F# and Azure?
===================
To get yourself started, you can already get a [Jupyter Notebook](https://jupyter.org/) environment on the cloud with [Azure Notebook](https://notebooks.azure.com/) and use F# as your programming language. Once you've created your first notebook, you can get started with your first machine learning project.

To setup your automation and your pipeline(s), you can go to [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/) to setup your DevOps which we'll use in this repository to set up your MLOps environment.


(As I get more and more familiar with MLOps setups, I will document this readme more and more to reflect what you need to do here for a complete MLOps environment).


What's MLOps and how its vision differs from day-to-day DevOps?
===================

MLOps empowers data scientists and app developers to help bring ML models to production. MLOps enables you to track / version / audit / certify / re-use every asset in your ML lifecycle and provides orchestration services to streamline managing this lifecycle. 


* Data/model versioning != code versioning - how to version data sets as the schema and origin data change
* Digital audit trail requirements change when dealing with code + (potentially customer) data
* Model reuse is different than software reuse, as models must be tuned based on input data / scenario.
* To reuse a model you may need to fine-tune / transfer learn on it (meaning you need the training pipeline)
* Models tend to decay over time & you need the ability to retrain them on demand to ensure they remain useful in a production context.

(This comes from [here](https://github.com/microsoft/MLOps))

Recommended resources
===================

* Microsoft MLOps [repository](https://github.com/microsoft/MLOps)
* Microsoft Python MLOps [repository](https://github.com/microsoft/MLOpsPython)
* Microsoft Recommenders [repository](https://github.com/Microsoft/Recommenders)
* [Machine Learning course](https://www.coursera.org/learn/machine-learning) offered by Standford at Coursera
* [Deep Learning certification](https://www.coursera.org/specializations/deep-learning) offered by deeplearning.ai at Coursera
* [Introduction to machine learning course](https://www.kaggle.com/learn/intro-to-machine-learning) offered by Kaggle
* [Intermediate Machine Learning](https://www.kaggle.com/learn/intermediate-machine-learning) offered by Kaggle
* [Data Visualization](https://www.kaggle.com/learn/data-visualization) offered by Kaggle
* [Feature Engineering](https://www.kaggle.com/learn/feature-engineering) offered by Kaggle
