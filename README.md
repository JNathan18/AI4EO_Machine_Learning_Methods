# Unsupervised Learning Methods - Week 4

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#overview">Overview</a>
    </li>
    <li>
      <a href="#contents">Contents</a>
    </li>
    <li>
      <a href="#requirements">Requirements</a>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li>
      <a href="#results-and-analysis">Results and Analysis</a>
    </li>
    <li>
      <a href="#notes">Notes</a>
    </li>
    <li>
      <a href="#acknowledgements">Acknowledgements</a>
    </li>
  </ol>
</details>


## Overview
This Jupyter Notebook focuses on the classification of sea ice and leads, it does this via an implementation of unsupervised learning methods. We use both K-means Clustering and Gaussian Mixture Models (GMM) and compare our classifiction with the ESA, then compare both models performance. This content is part of a broader study of machine learning and AI and its application to satellite observation.

## Contents
- Introduction and basic implementation of K-means Clustering and GMM (example and image classification).
- Data preprocessing/cleaning and reading in useful functions.
- Rolling out the models for feature classification.
- Plotting mean waveform and standard deviation for both classifications from satellite data.
- Classification comparison across both models.
- Aligning waveforms for both sea ice and leads using correlation.
- Comparison to ESA classification.

## Requirements
Ensure you have the following dependencies installed.
```
!pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
Open the notebook using google colab after downloading 'MachineLearningMethods.ipynb' from the home page of this GitHub. Then link your google drive to the notebook and create a path to the data you'd like classified. Modify parameters as required to obtain the best results.

## Results and Analysis
This notebook finds that GMM performed slightly better than K-means when comparing to the classification provided by the ESA. However both models performed very well, emphasising the power of these models for efficient and accurate classification.

## Notes
- Ensure all libraries are properly installed before running the notebook.
- Ensure that when using the notebook all paths are changed to the data you'd like to classify.
- This notebook was structured for educational purposes.
- Email zcapmcl@ucl.ac.uk regarding any issues/bugs with the notebook.

## Acknowledgments
The base code for this notebook created for UCL’s GEOL0069 module. Special thanks to Dr Michel Tsamados for guidance and support. 
We also acknowledge the use of publicly available datasets and tools.

