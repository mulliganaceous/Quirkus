# Quantum-AI-for-Climate
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 4
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with NNL. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1yoY_venPkNStjcDu0Na0HYhgO6CvVYdM/view?usp=sharing) to view the project description.
  - YouTube recording of project description - [link](https://youtu.be/ka2RgUYo83c?si=MUb_dwTVfP1FV_47)

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):

Team Member 2:
 - Full Name: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):


Team Member 3:
 - Full Name: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):


Team Member 4:
 - Full Name: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):


### Project Solution:
Implementing Physics Informed Neural Networks For Modelling Environmental Variables Through Quantum Circuits : An Assessment of Refined Techniques, Strategies, Circuits and Sustainability Machine Learning Methods

The impacts of anthropogenic activities on environmental domains as well as connected areas of the biosphere have been studied heavily in relation to effects to weather, temperatures, topography and peripheral climate sectors. Such methods and impacts have resulted in renewed interpretations of modeling parameters in meteorology, climate dynamics, policy development, carbon finance, climate finance and atmospheric modeling. A greater academic consensus with such models places them at a less significant position due to the general simulated nature of such environmental designs as well as a lack of heuristic variables and equations that closely relate to Physics. These variables and equations concern areas of fluid dynamics, atmospheric physics, energy exchanges, transport phenomena and heat dynamics. Due to the limitations that are manifest in typical machine learning models, accounting for such extraneous yet crucial variables becomes a cumbersome and arduous process. The primary of this Paper is to propose applications that have been applied to resolve such modeling issues and providing a set of strategies for developing more salient Physics Informed Neural Networks that leverage the intensity of Quantum Circuits. To accomplish this with respect to the study of implementing models toward climate research and sustainability metrics, a series of models have been developed using climate data and Quantum neural networks equipped with defined physical components. The end result is a set of models that are more robust, more aligned to heuristic components and less vulnerable to noise as well as variances. The models have been generated using open source coding frameworks and implementation architectures from established neural network designs. A greater objective with this paper is to augment the results and testing of climate centered models with amplified physical metrics that account for intricacies which are not covered by conventional models. The generated models can be used for numerous research, testing and metaheuristic process mapping for climate related variables which are associated with important issues such as global warming, pollutant modeling(puff-plume models), atmospheric gasses, fluid viscosity effects, shear deformation, atmospheric heat exchange, rainfall patterns and inclement weather patterns. The Paper further delves into steps and processes implemented to derive general purpose circuits built with open source Quantum Computing resources which can be used alongside neural network architectures with the aim of providing replicable components for other researchers.  


#### 1	Introduction

Machine learning methods have recently shown promise in solving partial differential equations (PDEs). They can be classified into two broad categories: solution function approximation and operator learning. The Physics-Informed Neural Network (PINN) is an example of the former while the Fourier neural operator (FNO) is an example of the latter. Both these approaches have shortcomings. The optimization in PINN is challenging and prone to failure, especially on multi-scale dynamic systems. FNO does not suffer from this optimization issue since it carries out supervised learning on a given dataset, but obtaining such data may be too expensive or infeasible. In this work, we propose the physics-informed neural operator (PINO), where we combine the operating-learning and function-optimization frameworks, and this improves convergence rates and accuracy over both PINN and FNO models. In the operator-learning phase, PINO learns the solution operator over multiple instances of the parametric PDE family. In the test-time optimization phase, PINO optimizes the pre-trained operator ansatz for the querying instance of the PDE. Experiments show PINO outperforms previous ML methods on many popular PDE families while retaining the extraordinary speed-up of FNO compared to solvers. In particular, PINO accurately solves long temporal transient flows and Kolmogorov flows, while PINN and other methods fail to converge.

We propose a generalized space-time domain decomposition approach for the physics-informed neural networks (PINNs) to solve nonlinear partial differential equations (PDEs) on arbitrary complex-geometry domains. The proposed framework, named eXtended PINNs (XPINNs), further pushes the boundaries of both PINNs as well as conservative PINNs (cPINNs), which is a recently proposed domain decomposition approach in the PINN framework tailored to conservation laws. Compared to PINN, the XPINN method has large representation and parallelization capacity due to the inherent property of deployment of multiple neural networks in the smaller subdomains. Unlike cPINN, XPINN can be extended to any type of PDEs. Moreover, the domain can be decomposed in any arbitrary way (in space and time), which is not possible in cPINN. Thus, XPINN offers both space and time parallelization, thereby reducing the training cost more effectively. In each subdomain, a separate neural network is employed with optimally selected hyperparameters, e.g., depth/width of the network, number and location of residual points, activation function, optimization method, etc. A deep network can be employed in a subdomain with complex solution, whereas a shallow neural network can be used in a subdomain with relatively simple and smooth solutions. We demonstrate the versatility of XPINN by solving both forward and inverse PDE problems, ranging from one-dimensional to three-dimensional problems, from time-dependent to time-independent problems, and from continuous to discontinuous problems, which clearly shows that the XPINN method is promising in many practical problems. The proposed XPINN method is the generalization of PINN and cPINN methods, both in terms of applicability as well as domain decomposition approach, which efficiently lends itself to parallelized computation.



#### 2   Research

While physics-informed neural networks have been shown to accurately solve a wide range of fluid dynamics problems, their effectivity on highly compressible flows is so far limited. In particular, they struggle with transonic and supersonic problems that involve discontinuities such as shocks. While there have been multiple efforts to alleviate the nonphysical phenomena that arise on such problems, current work does not identify and address the underlying failure modes sufficiently. This thesis shows that physics-informed neural networks struggle with highly compressible problems for two independent reasons. Firstly, the differential Euler equations conserve entropy along streamlines, so that physics-informed neural networks try to find an isentropic solution to a non-isentropic problem. Secondly, conventional slip boundary conditions form strong local minima that result in fictive objects that simplify the flow. In response to these failure modes, two new adaptations are introduced, namely a local viscosity method and a streamline output representation. The local viscosity method includes viscosity as an additional network output and adds a viscous loss term to the loss function, resulting in localized viscosity that facilitates the entropy change at shocks. Furthermore, the streamline output representation provides a more natural formulation of the slip boundary conditions, which prevents zero-velocity regions while promoting shock attachment. To the author's best knowledge, this thesis provides the first inviscid steady solutions of curved and detached shocks by physics-informed neural network.


Stochastic differential equations (SDEs) are used to describe a wide variety of complex stochastic dynamical systems. Learning the hidden physics within SDEs is crucial for unraveling fundamental understanding of these systems’ stochastic and nonlinear behavior. We propose a flexible and scalable framework for training deep neural networks to learn constitutive equations that represent hidden physics within SDEs. The proposed stochastic physics-informed neural network framework (SPINN) relies on uncertainty propagation and moment-matching techniques along with state-of-the-art deep learning strategies. SPINN first propagates stochasticity through the known structure of the SDE (i.e., the known physics) to predict the time evolution of statistical moments of the stochastic states. SPINN learns (deep) neural network representations of the hidden physics by matching the predicted moments to those estimated from data. Recent advances in automatic differentiation and mini-batch gradient descent are leveraged to establish the unknown parameters of the neural networks. SPINN provides a promising new direction for systematically unraveling the hidden physics of multivariate stochastic dynamical systems with multiplicative noise.


#### 3   Available tooling

Approaching quantum-related SDEs has it’s track record among several research groups across the world. One of them is the Crunch Group, which proposed tooling called PINNs-TF2, bilt on top of TensorFLow framework. In their work, they propose uniformed framework for tackling quantum physics PDEs. Following equations were implemented with the use of proposed framework: Continuous Forward 3D Navier-Stokes Equation (widely utilzed for weather forecasting problem), Discrete Inverse Korteweg–de Vries Equation, Continuous Forward Burgers' Equation, as well as Continuous Forward Schrodinger Equation. The goal of this study was to implement Poisson-Schroedinger equations (also knows as Newton-Schroedinger), for measuring quantization problem in the context of weather forecasting. As there is no direct connection between those two, but Poisson-Schrodinger equation could potentially be utilized in the development of sensors or other instruments for weather modeling, it can be therefore useful for this purpose. 


### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://drive.google.com/file/d/1wJx-rdZCiX-i_p5HH3xFt-nrLRslsWyA/view?usp=sharing)

