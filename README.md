# CLASSIFICATION PROJECT
This project involves the development of a deep neural network model for classifying children's anemia levels. The model uses socioeconomic factors as features for the classification. The data used for training and testing the model is stored in the `children anemia.csv` file.

The main code for training the model is in the [`Traning_Anemia.ipynb`](command:_github.copilot.openRelativePath?%5B%22Traning_Anemia.ipynb%22%5D "Traning_Anemia.ipynb") Jupyter notebook. This notebook includes the following steps:

1. Data loading and preprocessing: The data from `children anemia.csv` is loaded and preprocessed. Categorical data and numerical data are handled separately. The categorical data is processed using the `categorical_data` variable, and the numerical data is processed using the `numerical_data` variable.

2. Model creation: A deep neural network model is created using the `Model` class. The model uses a combination of numerical and categorical data.

3. Model training: The model is trained using the training data. The training process involves calculating the loss and updating the model parameters. The mean loss for each epoch is stored in the `mean_epoch_loss` variable.

4. Model testing: The trained model is tested using the test data. The performance of the model is evaluated based on its accuracy in predicting the anemia levels of the children in the test data.

The [`Splitdata.ipynb`](command:_github.copilot.openRelativePath?%5B%22Splitdata.ipynb%22%5D "Splitdata.ipynb") notebook is used for splitting the original data into training and testing datasets. The [`prediction_unseen.csv`](command:_github.copilot.openRelativePath?%5B%22prediction_unseen.csv%22%5D "prediction_unseen.csv") file contains the model's predictions for unseen data.

The project is implemented in Python, using libraries such as pandas for data manipulation, and PyTorch for creating and training the deep learning model.
