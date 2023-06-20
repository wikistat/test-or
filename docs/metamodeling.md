## General presentation

Let us consider a costly real-valued function defined on some domain $\mathcal{X}$,
$$ 
(x_1, \dots, x_d) \in \mathcal{X} \mapsto f(x_1, \dots, x_d)
$$
representing, for instance, a numerical code simulating a complex phenomenon, or the classification error of a machine learning algorithm. 

You have a limited computational budget, say no more than $10 d$ function evaluations. Under this budget restriction,

* How building a good approximation of $f$ (metamodel or surrogate model), that can embed a measure of our ignorance at unvisited area? 
* How customizing this metamodel in order to account for expert knowledge, or physical information?
* How choosing the points $x$ (designing the experiments) in order to find the global minimum of $f$?
* How discovering the unessential inputs, and quantifying the influence of the influential ones (sensitivity analysis)?

These are typical questions that we want to answer in this course.

## Program 

* Introduction on real problems. 
* Two famous classes of metamodels: polynomial chaos and Gaussian process.
* Gaussian process and reproducing kernel Hilbert space (RKHS). 
* Customizing kernels to embed expert knowledge or physical information.
* Gaussian process regression and approximation in RKHS. 
* Design of experiments
    * space-filling designs. 
    * sequential designs for optimization (Bayesian optimization) or other purpose.
* Sensitivity analysis. 
    * Variance-based indices: Sobol-Hoeffding decomposition.


