# Two-level-PR-RBC

Code and data accompanying the manuscript titled "A Two-Level Parameterized Model-Order Reduction Approach for Time-Domain Elastodynamics", authored by M. A. Bhouri and A. T. Patera. Will become available after the peer review process is complete.

Abstract:

We present a two-level parameterized Model Order Reduction (pMOR) technique for the linear hyperbolic Partial Differential Equation (PDE) of time-domain elastodynamics. In order to approximate the frequency-domain PDE, we take advantage of the Port-Reduced Reduced-Basis Component (PR-RBC) method to develop (in the offline stage) reduced bases for subdomains; the latter are then assembled (in the online stage) to form the global domains of interest. The PR-RBC approach reduces the effective dimensionality of the parameter space and also provides flexibility in topology and geometry. In the online stage, for each query, we consider a given parameter value and associated global domain. In the first level of reduction, the PR-RBC reduced bases are used to approximate the frequency-domain solution at selected frequencies. In the second level of reduction, these instantiated PR-RBC approximations are used as surrogate truth solutions in a Strong Greedy approach to identify a reduced basis space; the PDE of time-domain elastodynamics is then projected on this reduced space. We provide a numerical example to demonstrate the computational capability and assess the performance of the proposed two-level approach.

Citation:

@article{Bhouri2020PRRBC,
  title={A two-level parameterized model-order reduction approach for time-domain elastodynamics},
  author={Bhouri, Mohamed Aziz and Patera, Anthony T. Patera},
  journal={arXiv preprint arXiv:2002.11084v2 [math.NA, CS.NA]},
  year={2020}
}
