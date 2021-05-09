# Black-Scholes with a k-neighbours regression and simple local weights

The task is to predict the value of vanilla European call options, as priced by the Black-Scholes formula, using a given set of prices and values of corresponding dependent variables of those prices to train a model. Further details and background on this specific exercise can be found here:

https://github.com/robbieculkin/black-scholes-NN

in the paper:

https://github.com/robbieculkin/black-scholes-NN/blob/master/blackscholesNN.pdf

and in the work here:

https://samuellee19.github.io/CSCI145_Option_Pricing

where it is shown how approach this task using neural networks. Here, we have used a local linear regression instead. For ease of comparison, the 'CheckAccuracy' function in our notebook is essentially the same as that in the notebook in the first link above.
