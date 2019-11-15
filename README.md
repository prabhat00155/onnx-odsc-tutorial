# Performant cross-platform ML/DNN model inferencing on cloud and edge with ONNX Runtime
In this workshop, we will demonstrate how to train PyTorch and Scikit-Learn machine learning models, convert them to the [ONNX](onnx.ai/) format, and inference the converted model with [ONNX Runtime](https://github.com/microsoft/onnxruntime). Finally, we will deploy the models to Azure as a hosted service. 

## Pre-Requisites
You will need an Azure subscription for this workshop. When you [sign up for a new account](https://azure.microsoft.com/en-us/free/), you can get $200 free credit for the first 30 days. You **will not** be automatically charged after the credits are used up and/or the trial period ends. You must explicitly upgrade your free account to a pay-as-you-go plan to continue using Azure after the 30-day trial. Credit card information is only used for identity validation. For more questions about the free trial period, please check the [FAQ](https://azure.microsoft.com/en-us/free/free-account-faq/).

## Getting Started
1. Log into your [Azure Portal](http://portal.azure.com/) and create a new [AzureML workspace](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace). 
  * Create a Resource
  * AI and Machine Learning
  * Machine Learning
    * name = choose a name for your workspace...e.g. "odsc-[yourname]"
    * subscription = your subscription name
    * resource group -> create a new resource group, you can name it something like "my-rg"
3. Open your workspace. Now we will create a NotebookVM. The NotebookVM has the AzureML SDK, Python, and Jupyter Notebooks preinstalled to make it an easy ready-to-use workspace.
  * Select a name for your Notebook VM
  * Select the VM type: we suggest using **STANDARD_DS3_V2 --- 4 vCPUs, 14 GB memory, 28 GB storage**
4. Open Jupyter on the Notebook VM
5. From Jupyter, click on "New" -> "Terminal" and then clone this repository by typing `git clone https://github.com/prabhat00155/onnx-odsc-tutorial.git'
6. Open up pytorch experiment.ipynb and let's begin!
