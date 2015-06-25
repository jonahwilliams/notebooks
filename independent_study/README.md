<h2>Data Mining Independent Study</h2>


<h3>Support Vector Machines</h3>
<p>For the first part of the independent study I concentrated my efforts on understanding the math behind the support vector classifier. What is a kernel function?  It turns out they are much more universal - allowing us to implicitly represent higher dimensional objects for support vector machines - but also allowing us to bring our assumptions about the structure of our data (periodic, smooth) into different modeling approaches.
</p>

1. [Linear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/SupportVectorMachines.ipynb)
2. [Nonlinear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/KernelMethodsII.ipynb)
3. [Interactive SVM](http://bl.ocks.org/jonahwilliams/e3eef13a85774df70e18)

Here I go through kernel functions with specific applications to SVM with some of the more common kernels
[Nonlinear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/KernelMethodsII.ipynb)

Next, I tried grid search methods for picking hyper-parameter settings

[Hyperparameter Selection](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/HyperParameterSelection.ipynb)

Finally, I produced a small interactive visual for SVMs, including an implementation of the SMO algorithm in javascript.  I'd like to expand this to nonlinear kernels, but I have yet to think of a way to make it look nice.

[Interactive SVM](http://bl.ocks.org/jonahwilliams/e3eef13a85774df70e18)


<h3>Gaussian Processes</h3>
Grid search works okay for a low number of dimensions, but it scales extremely poorly.  I took some inspiration from [this paper](http://arxiv.org/pdf/1206.2944.pdf) and developed a small prototype optimizer using Thompson Sampling.

https://github.com/jonahwilliams/notebooks/blob/master/independent_study/BayesianOptimization.ipynb


<h3>Artificial Neural Networks</h3>
<li>
