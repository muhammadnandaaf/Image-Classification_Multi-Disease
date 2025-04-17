# Submission Project Multi Disease Image Classification

## Dataset
- **Brain Tumor**
    - glioma
    - meningioma
    - normal
    - pituitary
- **pneumonia**
    - normal
    - pneumonia
- **Skin Cancer**
    - basal_cell_carcinoma
    - melanoma
    - normal
- **Tuberculosis**
    - normal
    - Tuberculosis

## About Dataset 
This dataset contains a comprehensive collection of medical images across four different diseases: brain tumor, pneumonia, tuberculosis, and skin cancer. Each category includes high-quality images intended for training models in medical image analysis and disease diagnosis.

https://www.kaggle.com/datasets/kartik7813/multi-disease-image-classification

## 1. File Sructures
```
Klasifikasi Gambar Multi Disease
├───tfjs_model
|   ├───group1-shard1of1.bin
|   ├───model.json
├───tflite
|   ├───model.tflite
├───saved_model
|   ├───multidisease_model
|       └───assets
|       └───variables
|       └───fingerprint.pb
|       └───saved_model.pb
├───notebook.ipynb
├───README.md
└───requirements.txt
```
## 2. Project Work Cycle
1. Prepare the Library
2. Data Loading
3. Data Preparation
4. Exploratory Data
5. Data Augmentation
6. Merging Dataset (Original & Augmentation)
7. Preprocessing & Splitting Dataset
8. CNN Model
   - Modelling
   - Metrics Evaluation
   - Plotting
   - Confussion Matrix
9. Export Model
   - saved_model
   - tfjs
   - tflite
10. Inference Model

## 3. Getting Started
### `notebook_id.ipynb`
1. Download this project.
2. Open your favorite IDE like Jupyter Notebook or Google Colaboratory.
   - Jupyter lab :
     - Open your terminal
     - Go to the path where you downloaded this file
     - Example : cd D:this/file/to/your/path
     - Type 'jupyter lab .'
   - Google Colaboratory :
     - Create a New Notebook.
     - Upload and select the file with .ipynb extension.
     - Connect to hosted runtime.
     - Lastly, run the code cells.


# Contributor
- Muhammad Nandaarjuna Fadhillah
- muhammadnandaaf@gmail.com