# BIOMD0000000414: DIIVENUS_reducedmodel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000414.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000414.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000414 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Root gravitropism is regulated by a transient lateral auxin gradient controlled by a tipping-point mechanism. **   
Band LR, Wells DM, Larrieu A, Sun J, Middleton AM, French AP, Brunoud G, Sato
EM, Wilson MH, Péret B, Oliva M, Swarup R, Sairanen I, Parry G, Ljung K,
Beeckman T, Garibaldi JM, Estelle M, Owen MR, Vissenberg K, Hodgman TC,
Pridmore TP, King JR, Vernoux T, Bennett MJ. _Proc Natl Acad Sci U S A._2012
Mar 20;109(12):4668-73
[22393022](http://www.ncbi.nlm.nih.gov/pubmed/22393022),  
**Abstract:**   
Gravity profoundly influences plant growth and development. Plants respond to
changes in orientation by using gravitropic responses to modify their growth.
Cholodny and Went hypothesized over 80 years ago that plants bend in response
to a gravity stimulus by generating a lateral gradient of a growth regulator
at an organ's apex, later found to be auxin. Auxin regulates root growth by
targeting Aux/IAA repressor proteins for degradation. We used an Aux/IAA-based
reporter, domain II (DII)-VENUS, in conjunction with a mathematical model to
quantify auxin redistribution following a gravity stimulus. Our
multidisciplinary approach revealed that auxin is rapidly redistributed to the
lower side of the root within minutes of a 90° gravity stimulus. Unexpectedly,
auxin asymmetry was rapidly lost as bending root tips reached an angle of 40°
to the horizontal. We hypothesize roots use a "tipping point" mechanism that
operates to reverse the asymmetric auxin flow at the midpoint of root bending.
These mechanistic insights illustrate the scientific value of developing
quantitative reporters such as DII-VENUS in conjunction with parameterized
mathematical models to provide high-resolution kinetics of hormone
redistribution.

This model corresponds to the simplified model described in the article. It is
assumed that, on the timescale of DII-VENUS degradation, the concentrations of
auxin, TIR1/AFB, and their complexes can be approximated by quasi-steady-state
expressions. This reduced the full model to a single ODE that describes how
the DII-VENUS dynamics depend on the auxin influx and four parameter
groupings.


