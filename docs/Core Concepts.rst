.. _Core Concepts:
 

Core Concepts
=============
-------
K Type
-------
Kinetic law type (K type) including ten types:

- "ZERO" (Zeroth order);
- "UNDR" (Uni-directional mass action);
- "UNMO" (Uni-term with moderator);
- "BIDR" (Bi-directional mass action);
- "BIMO" (Bi-terms with moderator);
- "MM" (Michaelis-Menten kinetics without explicit enzyme);
- "MMCAT" (Michaelis-Menten kinetics with explicit enzyme);
- "HILL" (Hill equations);
- "FR" (Kinetics in the format of fraction other than MM, MMCAT or HILL);
- "NA" (not classified kinetics). 

Example: K_type = SBMLKinetics.types.K_type("NA").


-------
M Type
-------
Mass transfer type (M type) is quantitatively represented by the number of reactants 
(r = 0, 1, 2, 3 (representing>2)) and products (p= 0, 1, 2, 3 (representing>2)).

Example: M_type = SBMLKinetics.types.M_type(1,1).
