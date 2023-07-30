# Gradient-Descent-Versions
<h2>1- Batch gradient descent (BGD)</h2>
It updates the weights after calculating gradient according to all training examples.<br>
<b>Pros:</b> It is stable, there is no overshooting (except if the learning rate is high) as it uses all the training examples this leads to stability and accurate convergence to minimum. <br>
<b>Cons:</b> It is computationally expensive for large dataset, get stuck easily to local minimum.<br>
<h2>2- Stochastic gradient descent (SGD)</h2>
It updates the weights after calculating gradient for each training example.<br>
<b>Pros:</b> It is faster than <b>BGD</b>, used when dealing with large dataset.<br>
<b>Cons:</b> not very stable as it updates weights for each training example, less likely to stuck to local minimum compared to <b>BGD</b>, it is better to use very small learning rate with <b>SGD</b> as it is naturally tends to overshoot because it depends on single training example to update weights which mighnt not be the true direction of gradient, and can be very noisy, so, to overcome this issue several variants of <b>SGD</b> have been developed, such as mini-batch gradient descent, AdaGrad, RMSprop, and Adam, which adapt the learning rate or the step size based on the past gradients to improve convergence and reduce overshooting, that will be explained ان شاء الله.
