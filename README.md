# CharityML Neural Network Optimization
# deep-learning-challenge

## Introduction
This project aims to optimize a neural network model to predict the success of charity donations for Alphabet Soup, a fictitious charity organization. The dataset used for training and testing the model contains various features such as application type, classification, and organization affiliation.

## Files Included
- **Starter_Code.ipynb**: Initial attempt to build and train a neural network model using TensorFlow and Keras.
- **AlphabetSoupCharity_Optimization.ipynb**: Optimized version of the neural network model using AdaGrad optimizer.
- **AlphabetSoupCharity_Optimization2.ipynb**: Second optimization attempt with adjustments to the number of units in hidden layers.
- **AlphabetSoupCharity_Optimization3.ipynb**: Final optimization attempt with feature engineering by removing certain columns.

## Instructions
1. **Starter_Code.ipynb**:
   - This notebook contains the initial implementation of the neural network model.
   - The model is trained using the Adam optimizer.
   - It serves as the baseline for subsequent optimization attempts.

2. **AlphabetSoupCharity_Optimization.ipynb**:
   - An optimized version of the model is implemented using AdaGrad optimizer.
   - The notebook demonstrates how changing the optimizer affects model performance.

3. **AlphabetSoupCharity_Optimization2.ipynb**:
   - Further optimization is attempted by adjusting the number of units in hidden layers.
   - The notebook explores the impact of varying the neural network architecture on model accuracy.

4. **AlphabetSoupCharity_Optimization3.ipynb**:
   - Feature engineering is performed by removing certain columns from the dataset.
   - The notebook evaluates the effect of feature selection on model performance.

## Conclusion
- The project showcases the iterative process of optimizing a neural network model for charity donation prediction.
- Various optimization techniques, including changing optimizers, adjusting neural network architecture, and feature engineering, are explored.
- The first optimized model achieves an accuracy of 72.9% on the test dataset.

## Dependencies
- TensorFlow
- Keras
- pandas
- scikit-learn