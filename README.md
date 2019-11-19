# Performant cross-platform ML/DNN model inferencing on cloud and edge with ONNX Runtime
In this workshop, we will train Machine Learning models using popular frameworks and convert them to the interoperable [ONNX](onnx.ai/) format, then inference the converted model using the open sourced [ONNX Runtime](https://aka.ms/onnxruntime). We'll then demonstrate how to deploy the ONNX model as a hosted webservice using [Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/).

## Pre-Requisites
You will need an Azure subscription for this workshop. For attendees of ODSC Europe 2019, we have provided complimentary $50 Azure passes. Go to [www.microsoftazurepass.com](https://www.microsoftazurepass.com) to redeem your Azure credit. The value is good for 30 days or until all credit has been used up. You will need a Microsoft Account to redeem your Azure credit. You can use your existing Microsoft Account or create a new one. Please follow the instructions on the page, and refer to [this page](https://www.microsoftazurepass.com/Home/HowTo) for full details on how to redeem your pass.

*Note: the credit cannot be redeemed for existing Azure subscriptions*

Alternatively, when you [sign up for a new Azure trial](https://azure.microsoft.com/en-us/free/), you can get $200 free credit for the first 30 days. Credit card information is required for identity validation, and you **will not** be automatically charged after the credits are used up and/or the trial period ends. You must explicitly upgrade your free account to a pay-as-you-go plan to continue using Azure after the 30-day trial. For more questions about the free trial, please check the [Azure Free Account FAQ](https://azure.microsoft.com/en-us/free/free-account-faq/).

## Getting Started
1. Log into the [Azure Portal](http://portal.azure.com/) and create a new [AzureML workspace](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace). 
  * Create a Resource
  * AI and Machine Learning
  * Machine Learning
    * name = choose a name for your workspace...e.g. "odsc-[yourname]"
    * subscription = your subscription name
    * resource group -> create a new resource group, you can name it something like "my-rg"
2. Open your workspace. Now we will create a NotebookVM. The NotebookVM has Python and Jupyter Notebooks pre-installed to make it an easy ready-to-use workspace.
  * Select a name for your Notebook VM
  * Select the VM type: we suggest using **STANDARD_D3_V2 --- 4 vCPUs, 14 GB memory, 200 GB storage**
3. Open Jupyter on the Notebook VM
4. From Jupyter, click on "New" -> "Terminal" and then clone this repository by copy/pasting or typing `git clone https://github.com/prabhat00155/onnx-odsc-tutorial.git'
5. Open up [pytorch experiment-exercise.ipynb](./pytorch%20experiment-exercise.ipynb) and let's begin!

## Additional Resources	
See [additional resources](./additional-resources.md). The slides shared today are available under [ODSC Europe 2019 - Slides.pdf](./ODSC%20Europe%202019%20-%20Slides.pdf)
