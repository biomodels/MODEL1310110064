# MODEL1310110064: MODEL1310110064

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1310110064.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1310110064.git@20140916`

## Usage

Importing the model package.

`import MODEL1310110064 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Thiele2013 - Cerebral cortex glial cells

The model of cerebral cortex glial cells metabolism is derived from the
community-driven global reconstruction of human metabolism (version 2.02,
[MODEL1109130000](http://identifiers.org/biomodels.db/MODEL1109130000) ).

This model is described in the article:

[A community-driven global reconstruction of human
metabolism.](http://identifiers.org/doi/10.1038/nbt.2488)

Thiele I, _et al_ .

Nature Biotechnology

Abstract:

Multiple models of human metabolism have been reconstructed, but each
represents only a subset of our knowledge. Here we describe Recon 2, a
community-driven, consensus 'metabolic reconstruction', which is the most
comprehensive representation of human metabolism that is applicable to
computational modeling. Compared with its predecessors, the reconstruction has
improved topological and functional features, including ~2x more reactions and
~1.7x more unique metabolites. Using Recon 2 we predicted changes in
metabolite biomarkers for 49 inborn errors of metabolism with 77% accuracy
when compared to experimental data. Mapping metabolomic data and drug
information onto Recon 2 demonstrates its potential for integrating and
analyzing diverse data types. Using protein expression data, we automatically
generated a compendium of 65 cell type-specific models, providing a basis for
manual curation or investigation of cell-specific metabolic properties. Recon
2 will facilitate many future biomedical studies and is freely available at
http://humanmetabolism.org/.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1310110064](http://identifiers.org/biomodels.db/MODEL1310110064) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


