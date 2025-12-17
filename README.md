# Power cable and Tower Detection with Deep Learning: Training and Evaluation Pipeline of a Mask R-CNN

#### Keywords

`Computer Vision`, `Object Detection`, `Deep Learning`, `Data Augmentation`, `COCO Format`, `Model Training`, `Model Evaluation`, `Performance Metrics`, `Python`, `Jupyter Notebook`.

This project focuses on the **development, training, and evaluation of an object detection model** using deep learning techniques. The objective is to build a complete pipeline that starts from **dataset preprocessing and augmentation**, proceeds through **model training and testing**, and concludes with **quantitative performance evaluation** using standard metrics

The workflow is entirely implemented in **Python** and **Jupyter Notebooks**, enabling reproducibility and transparent experimentation. Dataset annotations and evaluation results follow the **COCO format**, ensuring compatibility with widely used benchmarking tools

---

### Key Features

* **End-to-End Pipeline**: From data preprocessing to final evaluation
* **Data Augmentation**: Techniques applied to improve model robustness and generalization
* **Standardized Evaluation**: Results stored and analyzed in COCO-compliant format
* **Training & Testing Separation**: Clear distinction between learning and inference phases
* **Reproducible Experiments**: Notebook-based workflow with saved metrics and outputs

---

### Project Structure

* **preprocessing_data_augmentation.zip**
  Contains scripts and resources for **dataset preprocessing and data augmentation**, including image transformations and annotation handling

* **training&testing.ipynb**
  Main notebook implementing:

  * Dataset loading and preprocessing
  * Model configuration and training
  * Testing and inference on unseen data

* **outputTesting.ipynb**
  Notebook dedicated to **visualizing inference results**, including predicted bounding boxes and qualitative model performance analysis

* **results_COCO_format.json**
  Stores **model predictions** formatted according to the COCO standard, enabling automated evaluation

* **metrics.json**
  Contains **quantitative evaluation metrics** such as precision, recall, and average precision (AP)

---

### Training and Evaluation Workflow

* Dataset preparation and augmentation to increase variability and reduce overfitting
* Model training with configurable hyperparameters
* Testing on held-out data and generation of predictions
* Evaluation using COCO metrics and structured result storage
* Visualization of detection outputs for qualitative assessment

---

### Results and Analysis

* Quantitative evaluation of detection performance using standard metrics
* Qualitative analysis through visual inspection of detected objects
* Discussion on the impact of data augmentation and training choices on results
