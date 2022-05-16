# Neural_Network_Charity_Analysis
-----------------------------------------------------------
# Overview of the analysis: 
The purpose of this Machine Learning project was to use deep-learning neural networks with TensorFlow to analyze and predict whether applicants will be successful if funded by Alphabet Soup using a dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

# Results: Using bulleted lists and images to support your answers, address the following questions:

------------------------------------------------------------
## Data Preprocessing
### What variable(s) are considered the target(s) for your model?
The column "is_successful" was considered are target.
<img width="121" alt="Screen Shot 2022-05-15 at 10 25 59 PM" src="https://user-images.githubusercontent.com/96555487/168514810-01c7d872-f51e-49d7-88bb-f29057250f2a.png">

### What variable(s) are considered to be the features for your model?
The columns below were are considered features.
<img width="705" alt="Screen Shot 2022-05-15 at 10 27 28 PM" src="https://user-images.githubusercontent.com/96555487/168514936-e5f627e0-f7e0-401f-91be-d5e77d979a1b.png">

### What variable(s) are neither targets nor features, and should be removed from the input data?
The columns below were considered neither targets nor features.
<img width="538" alt="Screen Shot 2022-05-15 at 10 29 24 PM" src="https://user-images.githubusercontent.com/96555487/168515029-11b3886f-8d0b-4802-9a65-2612983da3c1.png">


## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why?
<img width="371" alt="Screen Shot 2022-05-15 at 10 30 47 PM" src="https://user-images.githubusercontent.com/96555487/168515154-212b9d3b-02bf-463d-996f-588d8924ec15.png">
<img width="378" alt="Screen Shot 2022-05-15 at 10 31 18 PM" src="https://user-images.githubusercontent.com/96555487/168515186-c93fced9-308e-4fe0-989a-cb61be765db7.png">
<img width="826" alt="Screen Shot 2022-05-15 at 10 31 40 PM" src="https://user-images.githubusercontent.com/96555487/168515220-3779cfd4-4a5b-49af-a9d6-f9a79c1c6a1b.png">

### Were you able to achieve the target model performance?
No we were targeting at least 75%, but ended up with .718 as our height.

### What steps did you take to try and increase model performance?
Increasing the neurons, used a model with (3) hidden layers and used a different activation function.

---------------------------------------------------------------
# Summary: 
In summary the neural network performed average and did not hit our expected accuracy percentage of 75%. Though I would concluded that adding an extra hidden layer did much better in increasing the accuracy than the other different steps. 
