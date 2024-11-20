# Last-iterate-Convergence-of-Constrained-Reinforcement-Learning

Copyright (c) [2023] 
[Dongsheng Ding, Chen-Yu Wei, Kaiqing Zhang, and Alejandro Ribeiro]
All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
    
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

=================================================================================================

Acknowledgment

The code of generating random MDP transition dynamics 
https://github.com/jb3618columbia/Optimality-Guarantees-for-Policy-Gradient-Methods
The reference: Global Optimality Guarantees For Policy Gradient Methods, J. Bhandari and D. Russo

=================================================================================================

# Description
# 
# Our proposed methods in the NeurIPS 2023 paper: 
#
#     Last-Iterate Convergent Policy Gradient Primal-Dual Methods for Constrained MDPs 
#
# can be referred as follows:
#
# (1) RPG-PD (Regularized Policy Gradient Primal-Dual) -----------------------> Equation (6)
# (2) OPG-PD (Optimistic Policy Gradient Primal-Dual) ------------------------> Equation (9)
# (3) OMWU-PD (Optimistic Multiplicative Weights Update Primal-Dual) ---------> Equation (41)
# 
# All of our computational results in the paper can be reproduced by, 
# executing our Jupyter Notebook documents, accordingly. The requirements are: 
#
#            		 Jupyter Notebook
#    		Python 3, NumPy, Matplotlib, and SciPy.
#
# =================================================================================================
# 
#    	 Convergence performance of RPG-PD, OPG-PD, and primal-dual methods
#
# (1) NPG_primal_dual_comparison.ipynb -----------------------------------> Figure 1
# (2) NPG_primal_dual_comparison_conservative.ipynb ----------------------> Figure 6
#
#
# =================================================================================================
# 
#     	Convergence performance of RPG-PD, OPG-PD, and dual methods
#
# (1) NPG_dual_comparison.ipynb ------------------------------------------> Figure 4
# (2) NPG_dual_comparison_conservative.ipynb -----------------------------> Figure 7
#
#
# =================================================================================================
#
#     	Convergence performance of RPG-PD, OPG-PD, and primal methods
# 
# (1) NPG_primal_comparison.ipynb ----------------------------------------> Figure 5
# (2) NPG_primal_comparison_conservative.ipynb ---------------------------> Figure 8
#
#
# =================================================================================================
#
#     	Convergence performance of RPG-PD with different regularization parameters and stepsizes
# 
# (1) Regularized_NPG_primal_dual_sensitivity_tau.ipynb ------------------> Figures 9-12
#
#
# =================================================================================================
#
#     	Convergence performance of OPG-PD/OMWU-PD with different stepsizes
# 
# (1) Optimistic_NPG_primal-dual_ODGA_OMWU_sensitivity.ipynb -------------> Figure 2 and Figure 13
# (2) Optimistic_NPG_primal-dual_ReLOAD_OMWU_sensitivity.ipynb -----------> Figures 14-17


