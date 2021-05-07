# AdenosineA2bReceptor

This is a repository for building a "Adenosine A2b Receptor Inhibitors Bioactivity Prediction Model"

**Adenosine A2b Receptor**: Membrane Protein (G-protein Coupled Receptor Family)


**Dataset**: [ChEMBL255](https://www.ebi.ac.uk/chembl/g/#browse/compounds/filter/_metadata.related_targets.all_chembl_ids%3ACHEMBL255)
- Target: Adenosine A2b receptor
- Species: Homo sapiens

**Contents**
* Query of ChEMBL database
* [Lipinski's Rule of Five](https://pubmed.ncbi.nlm.nih.gov/11259830/) : Descriptors of an Orally Active Drug
* PubChem Molecular Fingerprints calculation: PaDEL bashing
* Performance-TrainTime Tradeoff: Dimensionality Reduction
* Stacked Regressor ML model

**Relevance for Future Projects**
* Webapp for target query and customisable ML pipeline 

*(e.g. change the no. of components in PCA, choose regressors for stacked model)*
* Modifications to Bash commands in PaDEL wrapping
* Search of other featurisation methods for ML in molecular activity


**Honourable mention**
* [Data Professor](https://www.youtube.com/channel/UCV8e2g4IWQqK71bbzGDEI4Q) 

  *who regularly creates astonishing tutorials on computational techniques in drug discovery*
