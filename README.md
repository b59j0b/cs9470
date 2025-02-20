java cMIME 473 – Winter 2025 Assignment #5 Due: 11:59pm, Feb 19
NOTE: This assignment requires you to write Lammps scripts and conduct molecular statics (MS) simulations. For questions requiring you to submit Lammps scripts, you will ONLY GET POINTS when the Lammps script. can run correctly and produce the numerical results you stated.
Question 1 [ET.1]: [6pts] Consult tutorials on cohesive energy and vacancy formation. Based on the example on Ni, please do the following:
(a) Similar to what’s done in the tutorial, construct a fully periodic, rectangular simulation box, but with ,  and  (see Figure 1) being along [110],    [-112]   and [1 -11]   directions respectively. Conduct MS simulations to

i) obtain the equilibrium cohesive energy E0 [1 pts].
ii) then create a single vacancy and obtain the vacancy formation energy  [2 pts].
Please submit your Lammps script, named as YourMcGillID_Q1a.txt.
(b) [2pts] Similar to question (a) above, but instead of removing a single atom to create a single vacancy, add an atom at an octahedral interstitial site to create a self-interstitial defect. Please conduct a MS simulation to obtain the formation energy of a self-interstitial defect, denoted as . Please submit your Lammps script, named as YourMcGillID_Q1b.txt.
(c) [1pt] Based on your  and  values (and assume that they are not temperature dependent), if we know that, at T = 800 a single crystal Ni sample has a total of 1.5 × 1020 vacancies, please determine the number of self-interstitial defects in this sample.
NOTE: assuming that both vacancies and self-interstitials are thermally activated, and there is no interaction between individual defects. You may check Self-exercise #1 if needed.
For (a) and (b) above, please briefly explain what you did and discuss the simulation results you obtained. The explanation can weight as much as 1.5 pts).   Also please ensure that you use the appropriate simulaiton dimensions for each direction.
SPECIAL NOTE: Please ensure that you use CORRECT crystalline directions. Using wrong crystalline directions will automatically result in -50% penalty.
Question 2 [DE.1]: [4pts] Consult tutorials, develop a LAMMPS script. and design a simulation process to
i) construct a fully periodic rectangular simulati代 写MIME 473 – Winter 2025 Assignment #5Haskell
代做程序编程语言on box with two corner points located at  and  (see Figure 2 for illustration);
ii) within this simulation box, please create two atoms respectively located at (x, y, z) =  and ;
iii) the interaction between them is described by a LJ potential (please use parameters
“pair_coeff   1 1 0.012 3.5 7.5”).
Make use of the script. you created. Perform. MS simulations and answer the following questions.
a) [3pts] Run for a sinlge step to obtain the potential energy Ep of this two-atom system from your simulation. Please submit your Lammps script, named as YourMcGillID_Q2a.txt;
(Here briefly explain what you did and discuss the simulation results you obtained).
b) [1pts] Perform. a “pencil-and-paper” calculation of the potential energy (please ignore the influence of tail function). Check to see if your hand calculation result matches with the simulation result.
SPECIAL NOTE: Please ensure that you use CORRECT LJ parameters. Using wrong parameters will automatically result in -50% penalty.
Solution:   (NOTE: In your answers, please provide some necessary details, which can weight as much as 1.5 pts).

Self-exercise #1: Calculate the number of vacancies per cubic meter in iron at 850°C. The energy for vacancy formation is 1.08 eV. Furthermore, the density and atomic weight for Fe are 7.65 g/cm3 and 55.85 g/mol, respectively.
Self-exercise #2: Practice the following variations of Question 1 above.
(i) Change the orientation ,  and  to be ,    [111]   and . How would the cohesive energy and vacancy formation energy change?
(ii) Instead of putting the self-interstitial at the octahedral site, how about the tetrahedral site? How do we determine which one is the preferred site for the self-interstitial atom?
(iii) Food for thought: what about a divacancy? For creation of a divacancy, it is similar to question 1(a) above, but instead of removing a single atom to create a single vacancy, remove two adjacent atoms to create a divacancy. Please conduct a MS simulation to obtain the formation energy of a divacancy, denoted as .  is defined as , where Etot denotes the energy of the divacancy containing system and N denotes the number of atoms before creation of the divacancy.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
