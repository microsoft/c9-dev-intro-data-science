# Developers Intro to Data Science

## Overview

This series on [Channel 9](https://channel9.msdn.com/Series/Dev-Intro-to-Data-Science) and [YouTube](https://www.youtube.com/playlist?list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE) are designed to help you, a developer, begin your journey through understanding data science and machine learning concepts, while providing you with a practical guide to your first data steps. Whether you want to learn how to actually apply data science and machine learning to the technical solutions you're building, or just want to be able to have more effective conversations with the data scientists or machine learning experts on your team, this series will give you that initial insight and hopefully spark your interest to learn more.

We do assume you are familiar with software development, however the majority of the code shown in this series is relatively straight-forward Python. So even if you're a novice developer, you will likely learn something for your level. We also assume that you have some familiarity with Azure. 

If you're not familiar with Python, we recommend these video series:
- [Python for beginners](https://aka.ms/pythonbeginnerseries)
- [More Python for beginners](https://aka.ms/morepython)
- [Even more Python for beginners](https://aka.ms/evenmorepython)

If you're not familiar wiht Azure, we recommend checking out this Microsoft Learn modules:
- [Create an Azure Account](https://docs.microsoft.com/en-us/learn/modules/create-an-azure-account/)
- [Azure Fundamentals](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

Remember, Azure offers free trials:
- [Azure free trial for professionals](https://azure.microsoft.com/en-us/free/)
- [Azure free trial for students (no credit card required](https://azure.microsoft.com/en-us/free/students/)

### What you'll learn

- The basic data science lifecycle
- An overview of common machine learning algorithms
- How to setup your local and cloud developer environment to:
  - Write Python in Jupyter notebooks in Visual Studio Code
  - Connect an Azure Machine Learning resource to your local Visual Studio Code environment
  - Write Python in Jupyter notebooks in Azure Machine Learning Studio
- How to import, clean, and manipulate data with Python
- How to split data and test machine learning algorithms in code

## Prerequisites

- Some software development experience
- Light experience with Python
- [An understanding of Git](https://git-scm.com/book/en/v1/Getting-Started)
- [Light experience with Azure](https://docs.microsoft.com/en-us/learn/modules/create-an-azure-account/)

## Next Steps

If you want to follow along with the course without writing out all of the code (or try to find an error in your code), we have created this repository that contains all of the content that we showed in the course. 

### Getting Started with Code

We have created a folder in this repo with all of the code and instructions on how to get started with this completed code both locally in Visual Studio Code and in the clour on Azure Machine Learning Studio. You can find this [code in the project README](https://github.com/microsoft/c9-dev-intro-data-science/blob/main/regression-with-bikes/README.md).


### Course Outline

Here you will find a table for each video, the corresponding resources, and the corresponding slides. Note that some videos only had a title slide, so we did not include the links to the slides for those videos. 

| Video # | Video Title | References | Slides | 
|---------|-------------|------------|--------|
| 1 | Introduction to the Developer's Intro to Data Science Video Series | [Microsoft Learn Collection](www.aka.ms/DevIntroDS_Learn) |  |
| 2 | What is the Data Science Lifecycle? | [The Data Science Lifecycle](www.aka.ms/DataScienceLifecycle) |  |
| 3 | How do you define your business goal and scope your data science solution? | [The Data Science Lifecyle](www.aka.ms/DataScienceLifecycle) |  |
| 4 | What is Machine Learning?	What is Machine Learning? | [Machine Learning Algorithm Cheat Sheet](www.aka.ms/AlgorithmCheatSheet) |  |
| 5 | Which Machine Learning Algorithm Should You Use? | [Machine Learning Algorithm Cheat Sheet](www.aka.ms/AlgorithmCheatSheet) |  |
| 6 | What is AutoML? | [Automated Machine Learning Overview](www.aka.ms/AutomatedML) |  |
| 7 | How do you create a machine learning resource in Azure? | [Automated Machine Learning Overview](www.aka.ms/AutomatedML) [Getting Started with Azure Machine Learning](www.aka.ms/AzureMLGettingStarted) |  |
| 8 | How do you setup your local environment for data exploration? | [Getting Started with Python in Visual Studio Code](www.aka.ms/PythonInVSCode) |  |
| 9 | How do Jupyter notebooks work in Visual Studio Code? | [Setting up Jupyter notebooks in Visual Studio Code](www.aka.ms/DataScienceInVSCode) |  |
| 10 | How do you connect your Azure Machine Learning resources to your local Visual Studio Code environment? | [Getting Started with the Azure Machine Learning SDK](www.aka.ms/IntroToAzureMLSDK) |  |
| 11 | How do you prepare your data for a time series forecast? | [Creating a Datastore with Azure Machine Learning](www.aka.ms/AzureMLDatastore) |  |
| 12 | Why do you split data into testing and training data in data science? | [Getting Started with the Code in this Course](https://github.com/microsoft/c9-dev-intro-data-science/blob/main/regression-with-bikes/README.md) |  |
| 13 | What is an AutoML Config file? | [A usable sample of the Auto Machine Learning Config Class](www.aka.ms/AutoMLConfig-Class) |  |
| 14 | What should your parameters be when creating an AutoML Config file? | [A usable sample of the Auto Machine Learning Config Class](www.aka.ms/AutoMLConfig-Class) |  |
| 15 | How do you create an AutoML Config file and run your data science experiments on the cloud? | [An Auto Machine Learning Tutorial](www.aka.ms/IntroToAutoML) |  |
| 16 | What is Azure Machine Learning? | [Azure Machine Learning Serivce Product Page](www.aka.ms/AMLservice) |  |
| 17 | How can you collaborate on Jupyter Notebooks using Azure Machine Learning studio? | [Azure Machine Learning Studio](ml.azure.com) |  |
| 18 | How do you choose the best model and perform feature engineering? | [Auto Machine Learning Tutorial with Featurization](www.aka.ms/AutoMLfeaturization) |  |
| 19 | How do you use Azure ML for best model selection and featurization? | [Auto Machine Learning Tutorial with Featurization](www.aka.ms/AutoMLfeaturization) |  |
| 20 | How do you evaluate and retrieve a time series forecast from Azure Machine Learning? | [Getting Started with the Code in this Course](https://github.com/microsoft/c9-dev-intro-data-science/blob/main/regression-with-bikes/README.md) |  |
| 21 | How do you score your machine learning model on accuracy? | [Evaluating a Machine Learning Model with Azure](www.aka.ms/EvaluateModel) |  |
| 22 | How do you deploy a machine learning model as a web service within Azure? | [Deploying a Machine Learning Model with Azure](www.aka.ms/DeployModel) |  |
| 23 | What have you learned from deploying a machine learning model as a web service? | [Deploying a Machine Learning Model with Azure](www.aka.ms/DeployModel) |  |
| 24 | What is the importance of model deployment in machine learning? | [Azure Machine Learning Serivce Product Page](www.aka.ms/AMLservice) |  |
| 25 | How do you select the right machine learning algorithm? | [Selecting a Machine Learning Algorithm](www.aka.ms/SelectAlgos) |  |
| 26 | How does ethics play a role in data science? | [Model interpretability in Azure Machine Learning](www.aka.ms/ModelInterpretability) |  |
| 27 | What is model interpretability and how can you incorporate it into your data science solutions? | [Model interpretability in Azure Machine Learning](www.aka.ms/ModelInterpretability) |  |
| 28 | Concluding the Developer's Intro to Data Science Video Series | [Microsoft Learn Collection](www.aka.ms/DevIntroDS_Learn) |  |

## After the Video Series

As the goal of this course is to help get you understand the basics of data science and machine learning, while being able to practically begin to explore those concepts in code. The next step after completing the videos is to start to explore other types of data, algorithms, and approches. One way to do that is to find additional tutorials to guide you through your discovery, a few of our favorites are:

- [Predict flight delays by creating a machine learning model in Python](https://docs.microsoft.com/learn/modules/predict-flight-delays-with-python?WT.mc_id=python-c9-niner)
- [Build AI solutions with Azure Machine Learning service](https://docs.microsoft.com/en-us/learn/paths/build-ai-solutions-with-azure-ml-service/)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
