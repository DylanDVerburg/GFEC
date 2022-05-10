# GFEC
Gibbs free energy calculations, set up for Msc Thesis
This is a jupyter labs file.
The first block contains a class based implementation of gibbs free energy calculations including:
  - reading reactions in the form like: "2*H+(aq) + O2-(aq) --> H2O(l)" (this is case sensitive, and the compounds should be present in the 'entropy_enthalpy_table.csv'
  - checking if reactions are chemically and charged balanced
  - calculating the gibbs free enery for a given concentration by defining a bulk solution upon initialization
  - adapting to the absence of a bulk sollution (all concentrations will be assumed 1M)
  - calculating gibbs free energy for temprature ranges
  - calculating energies for changing concentrations as a reaction occurs ('thin_film' method)
  - plotting the above data on a temprature axis
  - generating exact data via the 'thin_film' method to LaTeX friendly tables
 
 The second block contains a project relevant definition of the bulk solution, the reactions and their names.
 
 The last block contains some example function calls for your convinience.
