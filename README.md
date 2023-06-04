

<div align="center">
    <h1>Predicting-the-Functionality-of-Water-Pumps-with-XGBoost</h1>
</div>

<div align="center">
    <sub>Let's connect 🤗</sub>
    <br />
    <a href="https://twitter.com/officialsamayo">Twitter</a> •
    <a href="https://www.linkedin.com/in/sam-ayo/">LinkedIn</a> •
<br />
</div>

<br />

<p align="center">
  <img src="" width='600' />
</p>


#### Table of contents
1. [What is this repo about?](#what-is-this-repo-about)
2. [How to run this code](#how-to-run-this-code)
3. [Wannna deploy real-world ML products?](#wannna-deploy-real-world-ml-products)


## What is this repo about?
This repository demonstrates how to train and deploy a machine learning model that predicts whether a water pump is functional, non-functional, or functional but needs repair.

In this project I 
- used of various tools and frameworks
- Data preprocessing and feature engineering are carried out with the Pandas and Scikit learn modules
- Features are stored in a feature store **Hopsworks
    - it is serverless, so we do not need to handle infrastructure
    - it has a very generous free tier, with up to 25GB of free storage.
- Models are built with a combination of Scikit Learn and other machine learning libraries
- MLOps is done through NannyML
- Model is deployed through FastAPI



## How to run this code

1. Create a Python virtual environment with the project dependencies with
    ```
    $ make init
    ```

2. Set your Hopsworks project name and API key as environment variables by running the following script (to generate these head to hopsworks.ai, create a free account, create a project and generate an API key for free)
    ```
    $ . ./set_environment_variables.sh
    ```

3. To run the feature pipeline locally
    ```
    $ make run
    ```
