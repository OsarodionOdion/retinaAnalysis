# Retina Analysis

**Introduction:** Retinal imaging is the process of taking high-resolution images of the rear inner surface of the eye.  Some of the features captured during this process are; the optic nerve, fovea, surrounding vessels, and the retinal layer (Hoover, n.d.).  Used by ophthalmologists, retinal imaging examines the eyes to detect irregularities that can cause diseases.  Macular degeneration, cancer, diabetic retinopathy, glaucoma, and hypertension are a few diseases that can be detected using retinal imaging (Lazarus, 2021).

**Project Goal:** - This project focuses on predicting the diagnoses of 400 retinal images.

**Dataset(s):** The images and labels were retrieved from [STructured Analysis of the Retina](https://cecas.clemson.edu/~ahoover/stare/) by M. Goldbaum, M.D., Professor of Ophthalmology in Residence, Shiley Eye Institute, and Adam Hoover, Department of Electrical and Computer Engineering, Clemson University. The image transformation was performed in the [convertImages notebook](convertImages/convertImages.ipynb)

**Output:** The `results.csv` file in the `Output` folder contains the prediction for each image while the `pred_actual.csv` file in the same folder includes the label to the predicted results 

**Authors:** The project authors are Osarodion Ogbebor Evans and Sheila Brooks

**Main Notebook:** [retinaAnalysis notebook](retinaAnalysis.ipynb).

**Acknowledgment:** The training materials used in completing the is project has been provided by Professor Vijayan Sugumaran and Professor Mark Isken, SBA, Oakland University. This project was completed under the supervision of Professor Vijayan Sugumaran, SBA, Oakland University.

**References**

[Hoover, A. (n.d). The STARE Project](http://cecas.clemson.edu/%7Eahoover/stare/)

[Lazarus, R. (2021, August 4). What is a digital retinal image? Optometrists.org.](https://www.optometrists.org/general-practice-optometry/guide-to-eye-exams/eye-exams/what-is-a-digital-retinal-image/)