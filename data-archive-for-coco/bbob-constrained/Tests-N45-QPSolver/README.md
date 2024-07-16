# bbob-constrained
Runs done with the development version of Nomad (4.5.dev).
Tests are conducted on 15 instances per problem.
The evaluation budget is 400xDim. If algo stops before reaching the evaluation budget, a new run is started with a new seed.
The version with all default parameters is noted N45_D, it uses Mads to solve quadratic model subproblem during the Search step.
The version noted N45_Q_D uses an Augmented Lagrangian QP solver for this purpose. In N45_QPM_D both QP and Mads solver are used sequentially. 
