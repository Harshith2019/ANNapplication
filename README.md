# ANNapplication
ANN application for finding the customers who may leave the bank in future 
<p>This artificial neural network(ANN) model is build to find the customers of a bank with high possibility of leaving the bank.</p>
<p>Those customers were found based on some factors like CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary</p>
<p>Geography represents their locality (country) and NumOfProducts is the number of facilities he is having from bank like debit card, credit card, loans ect.</p>
<p>The model is having 3 layers(excluding input layer) with 2 hidden layers and 1 output layer with 6,6,1 units respectively in each layer.</p>
<p>The optimizer used is adam optimizer and metric to track improvement is accuracy and the loss is 'binary cross entropy' since we have only 2 categories in output.</p>
