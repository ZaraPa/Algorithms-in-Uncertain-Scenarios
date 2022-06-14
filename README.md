# Effucient Regret Minimization in Non-Convex Games Project
###### Algorithms in Uncertain Scenarios (097280, Technion) - Final Project

<p align="justify">
In the project my partner and I review the paper of Hazan et al. (from 2017) and in particular the approach of local regret,
which generalizes the concept of regret to online non-convex problems (assuming a static best model). We briefly analyze the
algorithms, the assumptions and the theoretical results and in the end, we propose to switch the regular Newton method to
Quasi-Newton and present the pros and cons of it.
</p>

<p align="justify"> The paper of Hazan et al. introduces us a new notion of local regret for online non-convex problems. It proves convergence to a
local equilibrium or a local minima. From a mathematical point of view - It would be interesting to investigate under which
conditions does one converge to the global optimum (but that is for the future). </p>

<p><p> We can also observe that the main novelty of the paper is the use of time smoothing(by t) of the objective function.
