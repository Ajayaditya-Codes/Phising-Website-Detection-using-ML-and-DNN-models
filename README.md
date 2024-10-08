# **Phising Website Detection using ML and DNN models**

## **Project Overview**
This project focuses on detecting phishing websites by analyzing various URL features. It implements random forest model using Scikit-Learn and simple neural networks in PyTorch to classify websites as legitimate or phishing. 

## **Dataset**
The dataset is sourced from the UCI Machine Learning Repository. You can find the original dataset and description [here](https://archive.ics.uci.edu/dataset/327/phishing+websites).

## **Fetching the Dataset**
To download the dataset, use the `uci_dataset_fetcher.ipynb` script located in the notebook/fetcher directory. The script will automatically download and save the dataset locally.

```bash
cd notebook
cd fetcher
ipython
%run uci_dataset_fetcher.ipynb
```

## **Installation and Dependencies**
You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## **Usage**
    1. Run the notebook/fetcher/uci_dataset_fetcher.ipynb script to download the dataset.
    2. Follow the workflow by executing the notebooks in the following order:
        a. models/random_forest.ipynb for Random Forest Model
        b. models/deep_learning_model.ipynb for Simple Neural Network Model
    3. Review the results and analysis presented in each notebook.

## **Results**

The project demonstrates the application of machine learning and deep learning models to detect phising websites using the dataset. The models provide valuable insights and predictions, which can be applied in fraud prevention.

## **License**

This project is open-source and available under the MIT License.
