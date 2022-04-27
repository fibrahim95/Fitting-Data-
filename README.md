# Fitting-Data

Hello, everyone!

In this GitHub, I will you show some examples of fitting curve into data. We will use [scipy](https://scipy.org/) library and using [scipy.optimize](https://docs.scipy.org/doc/scipy/reference/optimize.html) functions for minimizing (or maximizing) objective functions, possibly subject to constraints. It includes solvers for nonlinear problems (with support for both local and global optimization algorithms), linear programing, constrained and nonlinear least-squares, root finding, and curve fitting.

If you used conda environment, just open the terminal and type:
```
conda install -c anaconda scipy
```

There are several fitting functions are used in the examples such as:
- Gaussian Function
- Cosine function
- Lennard-Jones potential
- Least Square

Please take a look this documentation on how to use [curve fitting](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html#scipy.optimize.curve_fit).

In addition to what was already revealed in other answers, it is important to know that the fitting results, specially in real life, are not unique. That is, you don't get one and only one relationship between your x and y. The relationship you obtain depends on the method you choose to fit the data. For example, you may use the method of Linear Least Squares or a Non-Linear Least Square method. If the phenomena is not linear, you will get different relations even thought the input pairs are the same. For this reason and others, you can't always depend on the relationship obtained a 100% nor for the future or even for the current set of data. The relationship obtained in many cases represent a good formula with some compromises.


At the end of this example, I provided the example on how to fitting the data with Y-error bar. Please take a look and enjoy do the hands-on also find the other examples.Cheers!!
