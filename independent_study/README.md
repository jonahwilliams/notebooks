<h2>Data Mining Independent Study</h2>


<h3>Support Vector Machines</h3>
<p>For the first part of the independent study I concentrated my efforts on understanding the math behind the support vector classifier. What is a kernel function?  It turns out they are much more universal - allowing us to implicitly represent higher dimensional objects for support vector machines - but also allowing us to bring our assumptions about the structure of our data (periodic, smooth) into different modeling approaches.  Finally, I researched some extremely basic methods of setting the hyperparameters of the kernel functions using a grid search.
</p>

1. [Linear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/SupportVectorMachines.ipynb)
2. [Nonlinear SVM](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/KernelMethodsII.ipynb)
3. [Interactive SVM](http://bl.ocks.org/jonahwilliams/e3eef13a85774df70e18)
4. [Hyperparameter Selection](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/HyperParameterSelection.ipynb)


<h3>Gaussian Processes</h3>
Grid search works okay for a low number of dimensions, but it scales extremely poorly.  I took some inspiration from [this paper](http://arxiv.org/pdf/1206.2944.pdf) and developed a small prototype optimizer using Thompson Sampling.  Because Gaussian Processes also use kernel functions, I found this particularly enlightning because it introduced a larger variety of kernel functions - periodic kernels seemed especially interesting.

1. [Bayesian Optimization](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/BayesianOptimization.ipynb)


<h3>Artificial Neural Networks</h3>
The prerequisite knowledge for setting up ANN models is an understanding of the backpropagation algorithm and gradient based optimization ( and a ton of linear algebra).  I made use of Theano, as well as the Keras library which wraps theano into a nice interface for faster prototyping.  There is still a lot to do here, I will most likely continue developing more complicated models with theano in hopes of catching up to current RNN and NTM performance.

1. [Gradient Optimization](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/GradientBasedOptimization.ipynb)
2. [Backpropagation](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/Backpropagation.ipynb)
3. [Linear Classification](https://github.com/jonahwilliams/notebooks/blob/master/networks/LinearClassification.ipynb)
3. [Theano Basics](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/TheanoBasics.ipynb)
4. [Keras Basics](https://github.com/jonahwilliams/notebooks/blob/master/networks/KerasNet.ipynb)

<h3>Case Studies</h3>
1. [Predicting Forest Cover](https://github.com/jonahwilliams/notebooks/blob/master/independent_study/ForestCover.ipynb)
