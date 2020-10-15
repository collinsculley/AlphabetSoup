# AlphabetSoup

Machine Learning And Neural Network Exploration With TensorFlow

## Exploratory Analysis

A custom machine learning and neural network model was implemented to predict the success of a venture paid by Alphabet Soup.  The model was based on existing data for AS's prior charitable contribution outcomes with success/fail details included.

### Model Details and Performance

1. Categorical Variables were trimmed and bucketed to reduce noise of analysis.  **Is Successful** data was converted to categorical float dtypes for use in training/testing split and standardization.

2. Modeling began with a single layer with neurons = input variables x 2.  Performance reached 54% accuracy.

3. Two hidden layers with neurons = input variables (x3 and x2) produced model performance of:  72% accuracy at 57% loss.

4. Further layers or activation functions did not produce an optimized neural network.

5. Additional Epochs did not improve the training regimen and was capped at **50**
