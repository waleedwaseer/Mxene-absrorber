# Predictive Modeling of MXene-Based Solar Absorbers Using Deep Neural Network

Welcome to the **Predictive Modeling of MXene-Based Solar Absorbers** repository! This project presents a deformable convolutional neural network (CNN) approach to accurately predict the absorption spectra of MXene-based solar absorbers, significantly reducing the need for time-consuming electromagnetic (EM) simulations such as FDTD or FEM.

---

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#Dataset)
3. [Citation](#citation)


---

## Overview

**Paper Title:**  
*Predictive Modeling of MXene-Based Solar Absorbers Using Deep Neural Network*

**Authors:**  
Waleed Iqbal Waseer, Muhammad Abuzar Baqir, Muhammad Saqlain, Muhammad Junaid Mughal, and Shujaat Khan.

**Abstract (Brief):**  
- This work leverages a **deformable convolutional neural network** for predicting absorption spectra of **MXene-SiO<sub>2</sub>-Ag (MIM)** metasurface absorbers.  
- **Traditional EM simulations** (FDTD/FEM) are often time-consuming. Our **deep learning** approach accelerates this process while maintaining high accuracy.  
- **Grad-CAM** explainability provides insights into which regions of the metasurface design are most influential for absorption.  
- This method has strong potential for rapid, high-throughput design of solar absorbers, photodetectors, and other nanophotonic devices.

---

## Dataset

The dataset used in this study comprises **501 images** and their corresponding absorption spectra.  
- The images are stored in the **`images/`** folder.  
- The absorption spectra are provided in **`absorbtion spectra.xlsx`**.  

For more details on how these data were generated or used, please refer to the manuscript.

---

## Citation
If you find this repository helpful in your research or work, please cite our paper:

@article{waseer2025predictive,
  title={Predictive modeling of MXene-based solar absorbers using a deep neural network},
  author={Waseer, Waleed Iqbal and Baqir, Muhammad Abuzar and Saqlain, Muhammad and Mughal, Muhammad Junaid and Khan, Shujaat},
  journal={Journal of the Optical Society of America B},
  volume={42},
  number={4},
  pages={763--772},
  year={2025},
  publisher={Optica Publishing Group}
}
