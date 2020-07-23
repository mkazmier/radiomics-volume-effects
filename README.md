# Machine learning helps identifying volume-confounding effects in radiomics
Authors: **Alberto Traverso**, **Michal Kazmierski**, Ivan Zhovannik, Mattea Welch, Leonard Wee, David Jaffray, Andre Dekker, Andrew Hope
DOI: [https://doi.org/10.1016/j.ejmp.2020.02.010]()

This repository contains the analysis code for the 2020 *Physica Medica* publication. Refer to the manuscript for more information.

## Setup
1. Install the required packages:
```
pip install -r requirements.txt
```
2. Launch Jupyter in the project directory:
```
jupyter notebook
```
3. Open the notebook file in the browser window.

## Notes
The original Lung1 and HN1 data, including the images and contours can be found at [https://xnat.bmia.nl](). This repository only includes the clinical data and the extracted image features. The HeadNeckMR dataset is not yet available publically. The features were extracted using [PyRadiomics](https://pyradiomics.readthedocs.io) with the [PyRex](https://github.com/zhenweishi/Py-rex) extension to handle DICOM inputs. The extraction parameters can be found in the [PyRadiomics params file](pyradiomics_params.yaml). The code was tested under Python 3.6.
