# deep-learning-challenge

This project seeks to develop a model to predict the success or failure of ventures funded by Alphabet Soup. Identifying patterns in successful or unsuccessful ventures will allow for wiser allocation of funds and greater impact.

## Data Preprocessing
 - The target variable for the model is the success of the campaign, expressed as a 1, or its failure, expressed as a 0.
 - The features of the model are the following:
    - Alphabet Soup application type
    - Affiliated sector of industry
    - Government organization classification
    - Use case for funding
    - Organization type
    - Active status
    - Income classification
    - Special considerations for application (yes or no)
    - Funding amount requested
 - The original dataset also included name and id number. These were removed for analysis.

 ## Compilation, Training, and Evaluation
 Four neural network models were attempted.
  - One with two hidden layers of 80 and 30 perceptrons using the rectified linear unit activation function
  - One with two hidden layers of 5 and 3 perceptrons using the rectified linear unit activation function
  - One with three hidden layers of 16, 8, and 4 perceptrons using the rectified linear unit activation function
  - One with three hidden layers of 80, 40, and 20 perceptrons, using a linear activation function
This included variance in several aspects of the nerual network.

The best performing model was the first, which achieved 73% accuracy, a precision of 0.73, and a recall of 0.79. This fails to meet the target accuracy of 75%.

The model fails to acheive the target accuracy. This could reveal that the target variable is insufficiently determined by the available data. Before we conclude thus, there are more techniques available. The next step would be to try varying activation functions within the model. The models attempted used the same activation function throughout. It is possible that a combination of multiple activation functions would achieve better results than one with the same activation function throughout.