# Complex_Time_Integrators

This repository contains code to accompany the paper "Walking into the complex plane to 'order' better time integrators" by Jithin D. George, Samuel Y. Jung and Niall M. Mangan. This is a work in progress.

Some of the notebooks contain code that generate the figures in the paper. Those notebooks have the section number of the figures in their title. Some of the notebooks use the package Nodepy[1]. The code written in these notebooks have used Nodepy[1] in the process of experimentation and as inpsiration.

For a reader that wants a slow introduction to the code, this is the reccomended order based on ease of code readability.

1. 2_step_3_order_paths.ipynb : Shows the derivation of 2 step 3rd order paths for particular odes. Try changing the ode to get the new path.
2. (Sec_3.4)2_step_3_order_convergence_plot.ipynb : This uses the paths derived in the previous notebook and shows the convergence results on those particular odes.
3. (Sec_2)Paths_and_ODEs.ipynb : Uses the complex paths to simulate a variety of different odes.
4.  (Sec_2)Burgers_equation.ipynb : The complex paths are used to simulate the Burgers equation.
5. Barrier_breakingRK2-3_integrator_derivation.ipynb : This notebook derives the complex coefficients of the rk2/rk3 integrator that has 5th order accuracy with 5 function evaluations. The order conditions in theses notebooks were obtained using a separate mathematica notebook.
6. (Sec_5)Barrier_breakingRK2-3_integrator.ipynb : This uses the integrator derived in the previous notebook and verifies the 5th order accuracy on non-autonomous scalar odes.


[1]Ketcheson, D. I.  NodePy software version 1.0.1
http://github.com/ketch/nodepy/.
