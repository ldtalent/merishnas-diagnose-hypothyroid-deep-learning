# Diagnosing Hypothyroid disease using Deep Learning

Hypothyroid disease or Hypothyroidism is one of the most difficult diseases to diagnose. It is a condition which causes your thyroid gland to not produce enough of certain crucial hormones. It usually may not cause noticeable symptoms in the early stages and hence becomes extremely difficult to diagnose. Applying deep learning algorithms can help assist healthcare workers in identifying signs and symptoms based on patterns shown in past cases of patients' data.

In this tutorial, we will be learning the code and workflow for diagnosing whether or not a person is suffering from Hypothyroid disease based on various metrics.

1. Start by creating a virtual environment for installing the libraries.
```virtualenv venv```

2. Activate the environment
```
cd venv/Scripts
activate
```

3. Go back to the root directory and install the requirements.txt
```pip install -r requirements.txt```

4. The `diagnose_hypothyroid.ipynb` file contains the code for Diagnosing Hypothyroid disease using Deep Learning. The code itself contains the necessary instructions and comments for running it.

### Results

Upon implementing an artificial neural network with a sequential model with an input and output layer, the model gave fairly good results in classifying if a patient is diagnosed with hypothyroid or not.

### Citations

- The dataset for training our model was derived from [here](https://www.kaggle.com/nguyenthilua/hypothyroidcsv).