<h2>Data Mining Independent Study</h2>


<h3>Support Vector Machines</h3>
<p>For the first part of the independent study I concentrated my efforts on understanding the math behind the support vector classifier. What is a kernel function?  It turns out they are much more universal - allowing us to implicitly represent higher dimensional objects for support vector machines - but also allowing us to bring our assumptions about the structure of our data (periodic, smooth) into different modeling approaches.  Finally, I researched some extremely basic methods of setting the hyperparameters of the kernel functions using a grid search.
</p>

1. [Linear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/SupportVectorMachines.ipynb)
2. [Nonlinear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/KernelMethodsII.ipynb)
3. [Interactive SVM](http://bl.ocks.org/jonahwilliams/e3eef13a85774df70e18)
4. [Hyperparameter Selection](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/HyperParameterSelection.ipynb)


<h3>Gaussian Processes</h3>
Grid search works okay for a low number of dimensions, but it scales extremely poorly.  I took some inspiration from [this paper](http://arxiv.org/pdf/1206.2944.pdf) and developed a small prototype optimizer using Thompson Sampling.

https://github.com/jonahwilliams/notebooks/blob/master/independent_study/BayesianOptimization.ipynb


<h3>Artificial Neural Networks</h3>
<li>
