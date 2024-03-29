# PCNtoolkit braincharts

[![Gitter](https://badges.gitter.im/predictive-clinical-neuroscience/community.svg)](https://gitter.im/predictive-clinical-neuroscience/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Documentation Status](https://readthedocs.org/projects/pcntoolkit/badge/?version=latest)](https://pcntoolkit.readthedocs.io/en/latest/?badge=latest) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5207839.svg)](https://doi.org/10.5281/zenodo.5207839)

## Pre-trained models, code, documentation, and supporting files for: 
### 1.) Charting Brain Growth and Aging at High Spatial Precision
In press at [eLife](https://elifesciences.org/articles/72904).

### 2.) Evidence for Embracing Normative Modeling
In press at [eLife](https://elifesciences.org/articles/85082).


**Training the reference cohort (cortical thickness and subcortical volume)** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/braincharts/blob/master/scripts/fit_normative_models_ct.ipynb)

**Fit pre-trained model (cortical thickness and subcortical volume) to new (transfer) data** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/braincharts/blob/master/scripts/apply_normative_models_ct.ipynb)

**Fit pre-trained model (surface area) to new (transfer) data** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/braincharts/blob/master/scripts/apply_normative_models_sa.ipynb)

**Fit pre-trained model (resting-state functional connectivity - Yeo17 brain networks) to new (transfer) data** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/braincharts/blob/master/scripts/apply_normative_models_yeo17.ipynb)

![](docs/elife_press_release_photo.jpg)

## **Interactive visualizations of evaluation metrics:**

[Heroku app for exploring explained variance - temporarily offline due to Heroku policy changes](https://brainviz-app.herokuapp.com/).

Click on the 'open in colab' button below to launch the interactive visualization and explore the evaluation metrics yourself. There is a separate visualization for each test set and evaluation metric. 

![](docs/eLife_interactive_viz.gif)

### **1. Full test set (including 10 randomized split halfs)**

Explained Variance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/10foldCV_EVviz.ipynb)

MSLL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/10foldCV_MSLLviz.ipynb)

Kurtosis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/10foldCV_Kurtosisviz.ipynb)

Skew [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/10foldCV_Skewviz.ipynb)

### **2. mQC test set**

Explained Variance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/mQC_EVviz.ipynb)

MSLL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/mQC_MSLLviz.ipynb)

Kurtosis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/mQC_Kurtosisviz.ipynb)

Skew [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/mQC_Skewviz.ipynb)

### **3. Patients test set**

Explained Variance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/patient_EVviz.ipynb)

MSLL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/patient_MSLLviz.ipynb)

Kurtosis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/patient_Kurtosisviz.ipynb)

Skew [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/patient_Skewviz.ipynb)

### **4. Transfer test set**

Explained Variance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/transfer_EVviz.ipynb)

MSLL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/transfer_MSLLviz.ipynb)

Kurtosis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/transfer_Kurtosisviz.ipynb)

Skew [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saigerutherford/brainviz-app/blob/main/transfer_Skewviz.ipynb)
