# ISPOR Metamodeling Short Course

This is the repository for the short course on "Metamodeling for Simulation-Based Optimization of Strategies in Healthcare", which is presented by Hendrik Koffijberg (University of Twente, the Netherlands) and Koen Degeling (Lumen Value & Access, Netherlands/United States) for the Professional Society for Health Economic and Outcomes Research.

The repository contains three important files:

* `code.R`: the script containing the R code
* `objects.RDA`: the object containing the health economic model (HEM) and runHEM() function to run the HEM
* `ISPOR_Metamodeling.Rproj`: the R Studio project file that can be loaded to set up R Studio session

The code illustrates the use of metamodels to address run time issues (i.e., the computational burden) of a health economic
simulation models to enable optimization. More details on the case study are provided in the `code.R` script.

We recommend to save all these files, or simply the whole repository, in a single folder, and use the `ISPOR_Metamodeling.Rproj` to open R Studio, which ensures the working directly is set automatically. We also recommend to ensure you can run at least the INITIALIZATION section of the code before the live short course session.