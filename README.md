## Installation:

option 1:
* in (base): ```conda install nb_conda```
* `conda env create -f environment.yml` (create environment)
* `conda activate transferLearning` (activate environment)
* in (transferLearning): `conda install ipykernel`
* in (base): `jupyter notebook`, pick correct kernel in browser

option 2:
* `conda env create -f environment.yml` (create environment)
* `conda activate transferLearning` (activate environment)
* in (transferLearning): `conda install jupyter`
* in (transferLearning): `jupyter notebook`, kernel should be correct
