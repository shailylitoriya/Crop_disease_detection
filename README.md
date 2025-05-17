#  Crop Disease Detection using CNN

A Deep Learning-based image classification model to detect crop diseases from leaf images using Convolutional Neural Networks.

---

## Problem Statement
Plant diseases affect crop yield and quality. Early detection can prevent large-scale crop loss. This model helps in identifying 15 types of crop diseases using images.

---

## Dataset
Used the **PlantVillage** dataset available on Kaggle. It includes 15 classes:
- Pepper__bell___Bacterial_spot
- Pepper__bell___healthy
- Potato___Early_blight
- Potato___Late_blight
- Tomato_Bacterial_spot
- Tomato_Early_blight
- Tomato_Late_blight
- Tomato_Leaf_Mold
- Tomato_Septoria_leaf_spot
- Tomato_Spider_mites_Two_spotted_spider_mite
- Tomato__Target_Spot
- Tomato__Tomato_YellowLeaf__Curl_Virus
- Tomato__Tomato_mosaic_virus
- Tomato_healthy

---

##  Model Architecture
Built a CNN model using Keras:
- 3 Conv2D + MaxPooling layers
- Dropout
- Flatten + Dense layers
- Activation: ReLU, Softmax
- Loss: Categorical Crossentropy
- Optimizer: Adam

---

## Results

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | 93%       |
| Loss          | 0.30      |
| Epochs        | 15        |
| Model Size    | 12.61 MB  |

---

## Evaluation
- Confusion Matrix
- Classification Report
- Custom Image Prediction

---

## Sample Prediction

<img src="https://raw.githubusercontent.com/shailylitoriya/Crop_disease_detection/main/download%20(1).jpeg" width="200"/>

  
Prediction: **Tomato__Tomato_YellowLeaf__Curl_Virus**

---

##  How to Run

1. Clone repo
2. Install requirements

bash
pip install -r requirements.txt

3. Open crop_disease_detection.ipynb
4. Run all cells

## Contact
For any queries, reach out on [LinkedIn](www.linkedin.com/in/shailylitoriya)

