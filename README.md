# Bank Customer Churn
 Bank Customer Churn Machine Learning project. Dataset was taken from [Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset/data)

## Goal
Goal is to create classification model using ML logistic regression which could help **Bank** to identify potential customers that might **churn**.

Models like this can help to invest a bit more time into customers and avoid losing high paying clients. Identifying churning customers can lead for precise marketing/product suggestion campaigns to retain them.


## Key Takeaways:
- Highest chance of churned customer (definition):
    - Female
    - Not active customer
    - From Germany
    - Elder person
- Model recalls 77% of churned customers in test split.

## Improvement Areas:
- Test different models to check if better performance can be found.
- Bring more features (product/service usage, credit limits, account type, etc.)

## Clone the project:

1. Clone the repository

```
git clone https://github.com/ArvydasKacinas/Bank-Customer-Churn.git
cd Bank-Customer-Churn.git
```

2. Create a virtual environment

```
python -m venv .venv
```
3. Activate the virtual environment:

```
On Windows:
venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate
```

4. Install the required dependencies

```
pip install -r requirements.txt
```