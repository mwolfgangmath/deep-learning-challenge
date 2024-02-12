# deep-learning-challenge
Module 21 HW Alphabet Soup

OVERVIEW:
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With machine learning and neural networks, use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

* Preprocess the Data
* Compile, Train, adn Evaluate the Model
* Optimize the model (target accuracy > 75%)

RESULTS:
Data Preprocessing

* "IS_SUCCESSFUL" is the the target variable for this model.

* the features included for the consideration of this model are: "APPLICATION_TYPE", "AFFILIATION",	"CLASSIFICATION",	"USE_CASE",	"ORGANIZATION"	"STATUS", "INCOME_AMT",	"SPECIAL_CONSIDERATIONS", "ASK_AMT"

* The variables "EIN" an "NAME" were removed from the input data because they are neither targets nor necessary features.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* After multiple attempts, I settled on 4 layers that with a gradual decreasing number of neurons (200, 100, 50,25) because it felt kind of like it was funneling it's way down to the final output layer. I used RELU activation layers for the four inside layers and finished with the SIGMOID function because that was the most common and universally successful in the examples I've used thus far.

Were you able to achieve the target model performance?
* I increased my accuracy rate from the 50's up to 73% which is just short of the target performance of my model.

What steps did you take in your attempts to increase model performance?
* to increase model performance, I added layers from 2 to 3 to 4 and experimented with various units for the number of neurons from as little as 5 to more than 200. I also tried a couple different cutoffs when pre-preprocessing the data. I considered dropping other features, but the remaining catgories felt necessary to the outcome.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
* Honestly, I have no idea. This model does not seem very effective so devising another route would be wise. 