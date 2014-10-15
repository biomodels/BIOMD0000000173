# BIOMD0000000173: Schmierer_2008_Smad_Tgfb

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000173.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000173.git@20140916`


# Model Notes


This sbml file describes the RECI model from:  
"Mathematical modeling identifies Smad nucleocytoplasmic shuttling as a
dynamic signal-interpreting system" by Bernhard Schmierer, Alexander L.
Tournier, Paul A. Bates and Caroline S. Hill, Proc Natl Acad Sci U S A. 2008
May 6;105(18):6608-13.  
All parameter and species names are as in Figure S3 of the original
publication. The original model was done in copasi.  
SB-431542 addition to a concentration of 10000 nM is set at 2700 sec. The
initial concentration of SB, the time point of addition and the final
concentration can be set by altering the parameters **SB_0** , **t_SB** and
**SB_end** .  
This model file has been used to reproduce Figures 2D and 5A from the research
paper using SBMLodesolver. To get the results for the figures, sum the
corresponding concentrations:  
fig 2D: nuclear EGFP-Smad2 = G_n + pG_n + G2_n + G4_n + 2* GG_n  
fig 5A (either n or c for nucleus or cytosol):  
monomeric Smad2 = S2_n/c + G_n/c  
monomeric P-Smad2 = pS2_n/c + pG_n/c  
Smad2/Smad4 complexes = S24_n/c + G4_n/c  
Smad2/Smad2 complexes = S22_n/c + G2_n/c + GG_n/c  

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


