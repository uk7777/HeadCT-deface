This project automatically detects and masks key facial features (Eye, Nose, Ear, Mouth) from DICOM images.  
The demo images below show the process in the order of **Original → Detection (Bounding Box & Label) → Defaced**.

<p align="center">
  <img src="./images/demo_combined.png" alt="Image" width="100%" />
</p>

> **From left to right:**  
> 1. Original DICOM image  
> 2. YOLO-based feature detection with bounding boxes and labels  
> 3. Final masked result (detected areas blacked out)


## Demo Notebook
[View Demo Notebook](./headCT_de_identifciation_demo.ipynb)

## Demo Notebook
[![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-orange)](https://hub.2i2c.mybinder.org/user/uk7777-headct-deface-vz67ezgc/notebooks/head-CT_de_identifciation_demo.ipynb)

## Run the Demo in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uk7777/HeadCT-deface/blob/main/headCT_de_identifciation_demo.ipynb)
