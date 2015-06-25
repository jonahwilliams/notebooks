<h2>Data Mining Independent Study</h2>


<h3>Support Vector Machines</h3>
For the first part of the independent study I concentrated my efforts on understanding the math behind the support vector classifier: How do we find an optimal separating hyperplane using the SMO algorithm?

First I go though the basics of Kernel Methods with a linear SVM:
https://github.com/jonahwilliams/notebooks/blob/master/independent_study/SupportVectorMachines.ipynb

What is a kernel function?  It turns out they are much more universal - allowing us to implicitly represent higher dimensional objects for support vector machines - but also allowing us to bring our assumptions about the structure of our data (periodic, smooth) into different modeling approaches.

Here I go through kernel functions with specific applications to SVM with some of the more common kernels
https://github.com/jonahwilliams/notebooks/blob/master/independent_study/KernelMethodsII.ipynb

Next, I tried grid search methods for picking hyper-parameter settings

https://github.com/jonahwilliams/notebooks/blob/master/independent_study/HyperParameterSelection.ipynb

Finally, I produced a small interactive visual for SVMs, including an implementation of the SMO algorithm in javascript.  I'd like to expand this to nonlinear kernels, but I have yet to think of a way to make it look nice.

<link href=http://bl.ocks.org/jonahwilliams/e3eef13a85774df70e18>Interactive SVM</link>


<h3>Gaussian Processes</h3>
Grid search works okay for a low number of dimensions, but it scales extremely poorly.  I took some inspiration from http://arxiv.org/pdf/1206.2944.pdf and developed a small prototype optimizer using Thompson Sampling.

https://github.com/jonahwilliams/notebooks/blob/master/independent_study/BayesianOptimization.ipynb


<h3>Artificial Neural Networks</h3>
<li>
