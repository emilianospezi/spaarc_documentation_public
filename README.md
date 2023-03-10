# Spaarc documentation


<img src="attachments/spaarc_logo_landscape_rgb.jpg" width="500">


## Overview

SPAARC-Radiomics is a tool for multimodal quantitative image analysis developed at Cardiff University School of 
Engineering. SPAARC-Radiomics includes a total of 164 features: 23 Morphology, 
18 Intensity-based Statistics, 23 Intensity Histogram (IH), 7 Intensity-Volume Histogram (IVH),
25 Gray Level Co-occurrence Matrix (GLCM), 16 Gray Level Run Length Matrix (GLRLM), 
16 Gray Level Size Zone Matrix (GLSZM), 16 Gray Level Distance Zone Matrix (GLDZM), 
5 Neighboring Gray Tone Difference Matrix (NGTLDM), and 15 Neighborhood Gray Level 
Dependence Matrix (NGLDM). SPAARC-Radiomics features comply with the definitions provided 
by the Image Biomarker Standardization Initiative (IBSI) and are standardized following the 
IBSI guidelines (https://theibsi.github.io). The official SPAARC-Radiomics website is: https://spaarc-radiomics.io/.


## Purpose
This repository contains text and video instructions for the use of SPAARC across different platforms.


- [MICE Toolkit](https://micetoolkit.com) / [Hero Imaging](http://heroimaging.com/spaarc) 
- Matlab (Matlab 2021a Recommended)
- Python (3.9.10)


SPAARC has been implemented from scratch in both Python and Matlab to allowed integration with APIs of
different software. Note that the two versions are standalone, though both rigorously match IBSI benchmarks.

## Contents 

### 1. Installation and configuration of SPAARC
 
- a. SPAARC in MICE Toolkit: Installation & Setup ([link](1_a_SPAARC_MICE_installation_and_setup.md))
- b. SPAARC in Matlab: Installation & Setup  ([link](1_b_SPAARC_MATLAB_installation_and_setup.md))
- c. SPAARC in Python: Installation & Setup ([link](1_c_SPAARC_run_python_from_command_line.md))

### 2. Running radiomics analysis with SPAARC

- a. Structure of json file ([link](2_a_SPAARC_json_config.md))
- b. Running radiomics analysis in MICE Toolkit  ([link](2_b_SPAARC_MICE_Demo.md))
  - i. NIfTI example (single and batch) ([link](2_b_SPAARC_MICE_Demo.md))
  - ii. DICOM RTSTRUCT example ([link](2_b_SPAARC_MICE_Demo.md))
- c. Running radiomics analysis in MATLAB ([link](2_c_Running_radiomics_analysis_in_MATLAB.md))
- d. Running radiomics analysis in a Pure Python environment ([link](1_c_SPAARC_run_python_from_command_line.md))


### 3. Advanced 

- a. Checking IBSI compliance ([link](3_a_ibsi_benchmark_check.md))
- b. Additional notes on batch filtering options for Matlab version of spaarc. ([link](3_b_more_on_filters.md))



### 4. Other utilities

- a. Using the Conformity Index plugin ([link](conformity_index_plugin.md))



<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



