---
title: 
feature_text: |
  ## Projects
  Summary of the work I did during my undergraduate studies
feature_image: 
  "https://picsum.photos/1300/400?image=989"
---
A list of my research and course projects with the latest first.

### Dynamics of Morphogenesis
  The century-old seminal work of D'Arcy Thompson, On Growth and Form, gave a new dimension to studying growth using mathematical and physical principles to propose mechanisms by which organisms acquire their shapes and sizes. Inspired by this work and more recent developments in the field, we posed the problem of studying how growth factors and surface topology interact during growth. The basic idea is to model this as a process with two parts :  
  - The concentration of growth factors determine stress fields which modify the surface topology. 
  - This change in topology destabilizes the equilibrium concentration field of growth factors and chemical diffusion defines the new concentration field.  
  
  I used [Surface Evolver](https://facstaff.susqu.edu/brakke/evolver/evolver.html) and [FEniCS](https://fenicsproject.org/) to computationally implement the surface mechanics and diffusion respectively.
  [Presentation](https://bighome.iitb.ac.in/index.php/s/w8C7RURfTbh2BhU) and [report](https://bighome.iitb.ac.in/index.php/s/TC0Xl9Ild2l7kfM) for the first phase of the project.  
  
  Important references :  
 - Coen, Enrico, Richard Kennaway, and Christopher Whitewoods (2017). “On genes and form”. In: Development
 - Rees, Wim M. van, Etienne Vouga, and L. Mahadevan (2017). “Growth patterns for shape-shifting elastic bilayers”. In: Proceedings ofthe National Academy ofSciences.
 - Monier, Bruno et al. (2015). “Apico-basal forces exerted by apoptotic cells drive epithelium folding”. In: Nature 
 - Brakke, Kenneth A. (1992). “The Surface Evolver”. In: Experimental Mathematics
  
### Avascular Tumor Growth
  For my course project of Nonlinear Dynamics and Chaos, I studied the different mathematical approaches that are used to model cancer growth specifically growth of avascular tumor. This choice of project was motivated by the *The Emperor of All Maladies* which was a brilliant read.  
  
  Important references :
  - L. Preziosi, Cancer modelling and simulation. Boca Raton, FL: Chapman & Hall/CRC, 2003.
  -  T. Roose, S. J. Chapman, and P. K. Maini, “Mathematical Models of Avascular Tumor Growth,” SIAM Review, vol. 49, no. 2, pp. 179–208, 2007.
  - N. Beerenwinkel, R. F. Schwarz, M. Gerstung, and F. Markowetz, “Cancer Evolution: Mathematical Models and Computational Inference,” Systematic Biology, vol. 64, no. 1, Jul. 2014.
  - It's a Nonlinear World, Richard H. Enns
  
### Multi-scale mechanics of respiration
  I pursued this project as a research intern at the Datta Lab (Soft Materials in Complex Spaces) at Princeton University.  
  Respiratory disorders change mechanical properties of the lungs and the goal of this project was to establish a relationship between these altered properties and respiration dynamics that is quantified by the pressure-volume curve and distribution of avalanches during inspiration.
  We're also preparing a journal submission  : 
  "Dynamic network modeling of the multi-scale mechanics of respiration”, Anvitha Sudakar, Nathanael Ji, and Sujit S. Datta, *in preparation for submission to Journal of Fluid Mechanics*  
  Abstract : 
  Respiratory disorders like Cystic Fibrosis and Asthma are characterized by changes in the mechanical properties of lung tissues and secretions, which in turn lead to difficulties in breathing. However, a quantitative connection between altered lung mechanics and the
spatiotemporal features of lung opening remains lacking. To shed light on this problem, we
develop a statistical model of the lungs as a branched network, with different branches
opening at rates and pressures that are determined by key biomechanical factors: branch
geometry, tissue stiffness, and mucus surface tension and viscosity. We quantify the
evolution of airway pressure and volume during a single breath, and find that these
characteristics depend strongly on both breathing rate and lung biomechanics. In some
cases, respiration is “breathing limited”, with more and more branches opening up as
breathing progress; in other cases, respiration is “opening limited”, with many branches
unable to open during a breath. We find that this behavior is determined by the competition
between the overall breathing rate and the rate at which individual branches open. By
connecting multi-scaled processes - deformations of individual airway branches, flow of the
viscous mucus lining, coupling between different connected airway branches, and overall
changes in pressure and volume - these results enhance our fundamental understanding of
respiration
  
### Mechanics of Euler's disc
  For my course project in *Analytical Mechanics* I studied the mechanics and dynamics of Euler's disc. The mechanics of a rolling Euler's disc toy was analysed to explain the increase in frequency of acoustic signal produced(commonly termed as 'ringing') as it's inclination decreases, the extended duration of time taken to settle down and the abrupt nature with which the motion stops. An approach based on modelling the effect of frictional dissipation on the the disc's rigid body motion is pursued.  
  A youtube [video](https://www.youtube.com/watch?v=rFtYzVJcWyA) showing the toy's characteristic peculiar behaviour.    
  The model in MATLAB showing the trajectory of the toy and its increase in frequency([GitHub repo](https://github.com/anvitha-s/Eulers-Disc)), which was made starting from the [MATLAB code](https://rotations.berkeley.edu/the-rolling-disk/) for an ideal rolling disc.  
  Project report.
### Parallelising numerical computation of 1d wave solutions
  For my course project in *High Performance Scientific Computing* I looked at implementing parallelising the computation of numerical solutions for 1D wave solutions.  
  Project Abstract:  
  The one dimensional wave equation is solved using the finite difference method, after which a convergence study is performed against known analytical solutions of the equation. Two example problems were analyzed to illustrate the procedure and confirm the performance of the proposed method. An excellent agreement of the two sample problems with their known analytical solutions indicates that the proposed method is sufficiently accurate to be reliably used in various applications. The code is then parallelised using MPI and OpenCL. A timing study on CPU computing was conducted to determine the speedup obtained by MPI. The numerical results show that the finite difference method is a robust and accurate procedure for solving linear hyperbolic partial differential equations.
  Project [report](https://bighome.iitb.ac.in/index.php/s/6kgLRfz4SOimuFi).

### Motion of Molecular Motors
  I modeled the motion of molecular motors as a particle whose motion is described by the Langevin equation but with a fluctuating potential fields. The net motion arising from forces in an extended ratchet of two asymmetric sawtooth potentials was simulated.  
  Important references:
  - Jülicher, F., Ajdari, A., & Prost, J. (1997). Modeling molecular motors. *Reviews of Modern Physics, 69(4), 1269–1282. doi:10.1103/revmodphys.69.1269*
  - Parmeggiani, Andrea, Julicher, Frank, Ajdari, Armand & Prost, Jacques (1999). Energy transduction of isothermal ratchets: Generic aspects and specific examples close to and far from equilibrium. *Phys. Rev. E, 60, 2127-2140*. 
  - Grimm, Andrej & Stark, Holger & Maarel, Johan. (2009). Model for a Brownian ratchet with improved characteristics for particle separation. *Physical review. E, Statistical, nonlinear, and soft matter physics. 79. 061102. 10.1103/PhysRevE.79.061102*.
