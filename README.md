# RAPID_A

### What is RAPID-A? RAPID-A is a deep learning-based framework for rapid post-event damage assessment from satellite imagery, with the main incentive being effective transferability across urban textures and hazards, as real-world scenarios demand.
* We took the opportunity of the recent 2023 Kahramanmaras earthquake, as a rich damage dataset, and the 2023 Maui wildfire incident to build RAPID-A.
* This repo, on its own, is a complete pipeline for such damage assessments. However, this repo mainly serves to reproduce the research article "Rapid Computer-Vision-based Post-Event Assessment Tools for Natural Disasters: Enhancing Generalizability" (DOI), aimed at adding generalizability to rapid post-event damage assessment through satellite imagery.
* Breaking down RAPID-A compartments, this repo step-by-step goes through how our design and taken measures aid the generalizability concerns, with the Lahaina-Maras case as the case study.


## How to use the repo:
* Cloning the repo in your system:
```bash 
cd /path/to/directory
git clone https://github.com/TRG-AI4Good/RAPID_A.git
```
* The Run.ipynb notebook will guide you through the whole repository, building data and making inference step-by-step.
* Still, making sure the requirements.txt libraries are installed is needed.
* Since for the "general-purpose" CD model we are using building on codes by El. Amin et. al. (https://github.com/vbhavank/Unstructured-change-detection-using-CNN), the Tensorflow librray must be at version 2.13.0; as noted in the requirements file (un-installation of a prior TF version might be needed.

* In case you want to give it a try at Google Colab

Open ROC_Curve_Results.ipynb In Colab: 
<a target="_blank" href="https://colab.research.google.com/github/TRG-AI4Good/RAPID_A/blob/main/Run.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

* Otherwise, run Run.ipynb on your local system, guiding you through RAPID-A step by step.

