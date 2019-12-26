# Gradient-Descent-code-from-scratch


Implementation flow:

   ![ScreenShot](https://github.com/saikarthikcheedella/Gradient-Descent-code-from-scratch/blob/master/GD%20Table%20Of%20Contents.PNG)

Gradient descent is a very simple optimization algorithm. It makes iterative movements in the direction opposite to the gradient of a function at a point.

It is easy to understand if we visualize the procedure, refer to the visualization step in implementation.

Irrespective of the algorithm, we use these common steps.
   1) Initialize weights (randomly)
   2) Converge to local minima(i.e. point where our Loss is minimal, through out the feature space)
   3) Calculate partial derivatives of "Loss function" with respect to weights and Intercept(if considered).
      
      W = W - d(Loss)/dW
      
      C = C - d(Loss)/dC , where W=weights, C=Intercept.  
      
For instance, Here I solved Gradient Descent for linear regresion by taking Loss function as:

Loss = argmin Σ(y_actual - y_pred)^2 , 
      
       where y_pred= W^T.X + C,  C=Interecept, W=weights

Update by calculating d(loss)/dW and d(Loss)/dC, 

untill these values are not changing anymore. This indicates that we reached Local Minima.


In similar fashion,

Logistic Regression has Logloss/ CrossEntrophy.

SVM's have Hinge loss, etc.











