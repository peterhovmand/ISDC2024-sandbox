# Characterizing Loop Dominance Patterns with Application to a Developmental Theory of the Dynamics of Adolescence Suicide

Eyvind Hovmand Warner and Peter Hovmand

August 6, 2024

Presented at the 2024 International System Dynamics Conference, Bergen, Norway

## Model
The Developmental Transitions model of dynamics of cognitive vulnerability and family support is a “proof of concept” model where the primary purpose is to demonstrate the feasibility of using system dynamics to develop feedback theories in developmental psychology. Details of the model and documentation are described in [Hovmand et al (2022)](https://doi.org/10.1007/s10567-022-00395-3) and [the CCFP22 release on GitHub](https://github.com/CBSDLab/Developmental_Transitions/tree/CCFP22).

## Results

Figure 1 is the model with loop labels assigned based on the loop dominance analysis (Schoenberg, Davidsen, and Eberlein, 2020) implemented in Stella Simulator. B and R prefixes refer to loops that were always behaving as balancing and reinforcing loops. Loops labeled with U prefix behaved at least once as a balancing loop and also a reinforcing loop across the initial conditions and parameter spaces simulated. When there is a prevailing behavior across the simulations, the prevailing behavior is labeled in parentheses (e.g., "U1 (B3)").  

![image](https://github.com/user-attachments/assets/8e0ed502-67f4-46b1-8a4f-ace437dfc5b2)

**Figure 1** Model with loop labels corresponding to loop dominance analysis

Figure 2 shows the results for a transition from case 1 to case 3. The dominant loops correspond to the diagram in Figure 1. To interact and explore the diagram, [click here to interact with the plot](https://tinyurl.com/5n7ewd2w). 

![image](https://github.com/user-attachments/assets/74ea33cb-1405-48a1-9e0f-bc0355d39f2a)

**Figure 2** Results of loop dominance analysis for transition from case 1 to case 3 [Click here to interact with the plot](https://cbsdlab.github.io/ISDC2024-loop-dominance-patterns/Results/p3.html).

Figure 3 summarizes the results from simulating and analyzing transition across six cases where "1-2" refers to a transition from case 1 to case 2. To explore this graph in more detail, click [here to interact with the plot (may take a few seconds to load)](https://tinyurl.com/5n7ewd2w). 

![image](https://github.com/user-attachments/assets/c495405b-3ff6-4588-bf03-d766a6eb9a97)

**Figure 3** Results from simulating and analyzing transitions across six cases. [Click here to interact with the plot (may take a few seconds to load)](https://tinyurl.com/5n7ewd2w)

Figure 3 provides a global view to identify and characterize potential patterns of loop dominance for additional analysis. For example, 1-4, 1-5, and 1-6 appear to have a pattern of brifrucations in loop dominance. To further explore this, we can look at Figure 4.

Figure 4 shows the patterns of loop dominance across transitions between 4 cases (1-6, 1-5, and 1-4) organized by the "age" of tipping points in loop dominance. 

![image](https://github.com/user-attachments/assets/1b28d16f-0bf7-4a3d-aaa6-51680abc7317)

**Figure 4** Patterns of loop dominance across transitions between four cases organized by the "age" of tipping points in loop dominance. [Click here to interact with the plot](https://cbsdlab.github.io/ISDC2024-loop-dominance-patterns/Results/p2.html)

## References 
Hovmand, P. S., Calzada, E. J., Gulbas, L. E., Kim, S. Y., Chung, S., Kuhlberg, J., Hausmann-Stabile, C., & Zayas, L. H. (2022). System dynamics of cognitive vulnerabilities and family support among Latina children and adolescents. *Clinical Child and Family Psychology Review, 25*(1), 131–149. [https://doi.org/10.1007/s10567-022-00395-3](https://doi.org/10.1007/s10567-022-00395-3)

Schoenberg, W., Davidsen, P., & Eberlein, R. (2020). Understanding model behavior using the Loops that Matter method. *System Dynamics Review, 36*, 148-190. [https://onlinelibrary.wiley.com/doi/full/10.1002/sdr.1658](https://onlinelibrary.wiley.com/doi/full/10.1002/sdr.1658)

## Acknowledgements
The original model development was partially supported by NIMH grant R01MH070689 (PI: Zayas), the Dean of the Steve Hicks School of Social Work, University of Texas, Austin, TX, the Provost’s Think Big Early Investment Funding, Case Western Reserve University, Cleveland, OH, and the Brown School Social System Design Lab, Washington University in St. Louis.

isee Systems for including export feature of Loops That Matter in Stella Simulator and Billy Schoenberg for helpful feedback and guidance on implementation and interpretation of results. 

This work made use of the High Performance Computing Resource in the Core Facility for Advanced Research Computing at Case Western Reserve University.



