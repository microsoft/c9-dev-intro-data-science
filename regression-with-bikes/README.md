# Using Regression Algorithms to Predict Bike Share Rentals
This folder contains the code for the [Developer's Intro to Data Science course](https://www.youtube.com/playlist?list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE). 

## Setup
In this course we walk you through a hybrid development environment to introduce you to Azure Machine Learning both in Visual Studio Code and in Azure Machine Learning Studio. You will start by running the code in a local developer environment using Visual Studio Code and then move to running the code in Azure Machine Learning Studio. This is the same process shown in the course.

Below you will find high level instructions for setting up your local and cloud environments, with links to the videos that walk you through them. 

NOTE:  
If you want to run everything in your Azure Machine Learning environment in the browser, you can skip the Visual Studio Code setup. You will have to modify the code provided in this repo to combine the Visual Studio Code notebook and Azure Machine Learning notebook.

### Azure Machine Learning
This course requires an active Azure subscription and an Azure Machine Learning resource at Enterprise level. Here are some high level steps with references for more information on how to get started:
1. [Create an Azure Account](https://docs.microsoft.com/en-us/learn/modules/create-an-azure-account/): This Microsoft Learn module will walk you through creatin and Azure account using the free subscription. 
  - If you are a student, you might also qualify for the [Azure for Students offer](https://azure.microsoft.com/en-us/free/students/).
2. [Create an Azure Machine Learning resource](https://www.youtube.com/watch?v=c1MIP4zbdto&list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE&index=8&t=0s): This is a video from the course that walks you through creating an Enterprise Azure Machine Learning resource.
  - For more information on Azure Machine Learning, you can find additional resources on the [Azure Machine Learning developer resource page](http://aka.ms/AzureMLGettingStarted)

### Visual Studio Code Local Environment
This course demonstrates how to write Python code in Visual Studio Code and connect that to Azure Machine Learning. 

1. Download and install software:
  - [Visual Studio Code](https://code.visualstudio.com/Download)
  - [Python](https://www.python.org/downloads/)
  - [Anaconda](https://www.anaconda.com/products/individual)
2. Create an Anaconda environment with Python
3. Install the [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python), [Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account), and [Azure Machine Learning](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-ai) Visual Studio Extensions.
4. Sign in to Azure using the Visual Studio Code command palette.
5. Create an `.ipynb` file, open it, and verify that it opens in notebook form.
6. Import the following packages in the notebook file you just created:
  - `azureml.core`
  - `pandas as pd`
  - `numpy as np`
  - `logging`
7. Verify that the Azure Machine Learning SDK is working by running the following code in your notebook file:
  - `print('AzureML SDK Version:", azureml.core.VERSION)`

Note:  
The [setting started with Python in Visual Studio Code](www.aka.ms/PythonInVSCode) docs have extensive steps for setting up your local environment. And you can watch the videos from this course on [setting up your local environment](https://www.youtube.com/watch?v=5E3WMb8_T3s&list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE&index=8), [getting Jupyter notebooks and AzureML SDK working in Visual Studio Code](https://www.youtube.com/watch?v=ilFYqD2SR4k&list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE&index=9) and [making sure your specific Azure Machine Learning resource is connected to your local environment](https://www.youtube.com/watch?v=tgz3uxxbj4I&list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE&index=10).
 
## Visual Studio Code Development
At the beginning of this course we write and run our code locally in Visual Studio Code. Before you can started in Visual Studio Code, you need to have already completed all of the setup steps above. 

Additionally, you should downdload:
- Your `config.json` file from your specific Azure Machine Learning resource, [as seen in the course video 10](https://www.youtube.com/watch?v=tgz3uxxbj4I&list=PLlrxD0HtieHjDop2DtiCmwTTcrlwKAVHE&index=10).
- The [dataset bike-no.csv](bike-no.csv)
  - This dataset comes from the [Forecast demand with automated machine learning tutorial](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-automated-ml-forecast) on Microsoft Automated ML docs.

If you want the completed code for this course to run in Visual Studio Code you can find it in the [Bike Share in Visual Studio Code notebook](bike-share-vscode.ipynb) in this repo.

## Azure Machine Learning Studio
When it's time to migrate over to Azure Machine Learning Studio, you will need to upload a few things to a Notebook folder in the studio:
- The [scripts from the forecast](forecast/) folder.
- The [dataset bike-no-horizon.csv](bike-no-horizon.csv).

If you want the completed code for this course to run in Azure Machine Learning Studio you can find it in the [Bike Share in Azure Machine Learning notebook](bike-share-aml.ipynb) in this repo.
