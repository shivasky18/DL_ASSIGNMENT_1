# DL_ASSIGNMENT_1
REPORT ON OBSERVATIONS


Optimizers:

Adam outperformed other optimizers, providing the fastest convergence and highest accuracy (95-97% validation/test).
SGD showed slower convergence with a slightly lower accuracy (~92-94%) but performed decently when using a deeper network.
RMSprop balanced generalization and convergence, with accuracy around 94-96%.


Hidden Layers:

A network with 128 and 64 neurons performed best, showing good complexity without overfitting.
Using three hidden layers (128, 64, 32) resulted in slower training but decent accuracy.
64 neurons in two layers worked well for generalization and avoided overfitting.


Learning Rate:

0.001 worked best with Adam, enabling fast and stable convergence.
Higher learning rates (0.01) with SGD led to slower convergence and slightly lower performance.
A small learning rate (0.0001) with RMSprop improved generalization but was slower to converge.


Interpretation:


Adam with moderate hidden layer sizes and a learning rate of 0.001 provided the best overall results.
SGD required more epochs and was slower to converge but still performed well with a more complex network.
RMSprop performed similarly to Adam but took longer to converge, emphasizing the importance of balancing speed and generalization.
