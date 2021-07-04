#
# **Machine Learning and Operations [MLOPS]**

Hello and Welcome to the [MLOps package](https://ai.science/w/mlops?all-materials-tab=week1-mlops&amp;tab=all-materials). This Course package will give you the information regarding Machine Learning packaging requirements, packaging methods and technologies and Serving methods for ML models. You will get an idea about the model contarization using docker hub. We will deploy the dockerize model in the local environment and AWS EC2 instance.

![](RackMultipart20210704-4-1qi90wv_html_237499165a11f2b9.gif)

**What is MLOps?**

MLOps is the process of taking the experimental Machine learning model into the production system to get business values. It includes the word Machine Learning Development and IT operations. This branch is similar to DevOps in which machine learning models are tested and developed in isolated systems. After selection of the best model, it is also considered to deploy the winning model into the production environment.

In more detail, as per the following diagram we can see the typical ML Pipeline. It includes the data pipeline, development stage, and production environment including deploy and monitor. MlOps develop each part with the consideration of the production environment. For more information regarding MLOps please read this [NVIDIA](https://blogs.nvidia.com/blog/2020/09/03/what-is-mlops/)article.

![](https://github.com/vedantdave77/original-handson-packages/blob/main/MLOps/image/MLOPS-process-Gartner-1280.png)

Source: Gartner

**Where does this course stand?**

This course is with assumption that, the model is already developed and we need to deploy it in production. So, in each use case we will take a pre-built model and convert it to deployment compatibility. For that we will use serialization of models, generate mlflow pipeline, model onnx conversation for cross platform deployment and then deploy it to local environment and AWS EC2 linux instance.

**How to Use this Course Package with hands on Code?**

The package has 2 main modules and one optional section of MLOps with Azure centric approach. (in progress) Each video considers one topic at a time and most of the videos have hands- on labs which either use google colab environments or scripting files. Specifically for google colab, you can open jupyter notebook directly from the github page via link. And, for the scripts you should use your local [anaconda](https://www.anaconda.com/products/individual) environment.

### **The package code is distributed in two folders.**

1. Model building and Model packaging | ([Module-1 Codes](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging))
  	- [Common Serialization Methods using Iris model](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging/Common_Serialization_Methods)
  	- [MLflow hands on BERT model and Improvements](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging/MLflow_HandsOn)
  	- [Convert Model in ONNX format for getting cross-platform ML interoperability](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging/ONNX_HandOn)
  	- [Inference Model serving overview](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging/Inference_Model_Serving)
  	- [Flask based Model Serving](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module1-Model_Packaging/Flask_Iris_Model_Serving)
2. Model Serving via Containerization | ([Module-2 Codes](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module2-Model_Serving))
  	- [Containerizing Flask application and Model](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module2-Model_Serving/containerize_flask_and_model)
  	- [Serve Container on AWS-EC2 instance](https://script/)
  	- [MLOps Docker development environmen](https://github.com/Aggregate-Intellect/original-handson-packages/tree/main/MLOps/Module2-Model_Serving/mlops_docker_env)t

**Other Resources:**

-
