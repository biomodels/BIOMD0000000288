# BIOMD0000000288: BIOMD0000000288

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000288.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000288.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000288 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**PI3K-dependent cross-talk interactions converge with Ras as quantifiable inputs integrated by Erk.**   
Wang CC, Cirit M, Haugh JM _Mol. Syst. Biol._ 2009;5:246.
[19225459](http://www.ncbi.nlm.nih.gov/pubmed/19225459) ,  
**Abstract:**   
Although it is appreciated that canonical signal-transduction pathways
represent dominant modes of regulation embedded in larger interaction
networks, relatively little has been done to quantify pathway cross-talk in
such networks. Through quantitative measurements that systematically canvas an
array of stimulation and molecular perturbation conditions, together with
computational modeling and analysis, we have elucidated cross-talk mechanisms
in the platelet-derived growth factor (PDGF) receptor signaling network, in
which phosphoinositide 3-kinase (PI3K) and Ras/extracellular signal-regulated
kinase (Erk) pathways are prominently activated. We show that, while PI3K
signaling is insulated from cross-talk, PI3K enhances Erk activation at points
both upstream and downstream of Ras. The magnitudes of these effects depend
strongly on the stimulation conditions, subject to saturation effects in the
respective pathways and negative feedback loops. Motivated by those dynamics,
a kinetic model of the network was formulated and used to precisely quantify
the relative contributions of PI3K-dependent and -independent modes of Ras/Erk
activation.

  

This model is parameterized with the median of the estimated parameters given
in the supplementary material of the original publication's (doi:
[10.1038/msb.2009.4](http://dx.doi.org/10.1038/msb.2009.4) )
[supplement](http://www.nature.com/msb/journal/v5/n1/extref/msb20094-s1.pdf)
on pages 8 and 9.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
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


