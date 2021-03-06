# MODEL1006230006: Wierschem2004_PancreaticIslets_ActionPotentials

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230006.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230006.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230006 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Complex bursting in pancreatic islets: a potential glycolytic mechanism.**   
Wierschem K, Bertram R. _J Theor Biol_ 2004 Jun 21;228(4):513-21
[15178199](http://www.ncbi.nlm.nih.gov/pubmed/15178199) ,  
**Abstract:**   
The electrical activity of insulin-secreting pancreatic islets of Langerhans
is characterized by bursts of action potentials. Most often this bursting is
periodic, but in some cases it is modulated by an underlying slower rhythm. We
suggest that the modulatory rhythm for this complex bursting pattern is due to
oscillations in glycolysis, while the bursting itself is generated by some
other slow process. To demonstrate this hypothesis, we couple a minimal model
of glycolytic oscillations to a minimal model for activity-dependent bursting
in islets. We show that the combined model can reproduce several complex
bursting patterns from mouse islets published in the literature, and we
illustrate how these complex oscillations are produced through the use of a
fast/slow analysis.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Wierschem K, Bertram R. () - version=1.0**
](http://models.cellml.org/exposure/8208bdd04deaa0851f1f935b263d6035)  
The original CellML model was created by:  
**Ethan Choi**   
mcho099@aucklanduni.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


