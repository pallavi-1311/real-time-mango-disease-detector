#  Real-Time Detection of Mango Leaf Diseases

This project focuses on identifying diseases in mango leaves using a deep learning approach built with EfficientNetB0. It’s designed to help farmers and agricultural researchers detect issues early, reduce crop loss, and improve yield.

We’ve trained the model on both Kaggle datasets and real-time field images. It performs well in classifying diseases like anthracnose, rust, and also healthy leaves — even under real-world conditions like poor lighting and noisy backgrounds.

---

##  Project Goals

- Detect mango leaf diseases **automatically and accurately**
- Build a lightweight and real-time system using **transfer learning**
- Make the solution practical for use in **real agricultural environments**

---

##  What’s Inside

- A **CNN model based on EfficientNetB0**
- **Preprocessing techniques** like brightness, contrast adjustment
- **Data augmentation** to make the model more robust
- A clean and readable **Jupyter Notebook** with all the steps

---

##  Model Highlights

| Phase           | Accuracy     |
|----------------|--------------|
| Training       | 92.70%       |
| Validation     | 89.04%       |
| Real-time Test | 84.76%       |

Compared with other models:
- **EfficientNetB0**: Balanced and reliable
- **Decision Tree** & **Random Forest**: High accuracy but may overfit
- **MobileNet**: Lightweight but less accurate in our case

---

##  Dataset Used

- **Kaggle Mango Leaf Disease Dataset**
- **Real-time images** taken in natural farm environments

---

##  Technologies

- Python 
- TensorFlow & Keras
- Google Colab
- OpenCV
- Matplotlib

---


## Why This Matters

Early detection of plant diseases can save crops and reduce pesticide usage. Our model can act as a quick and effective diagnostic tool for farmers — especially in resource-constrained areas.

We’ve focused on making the system:
- Accurate 
- Easy to use 

---

## Future Plans

- Add more disease classes
- Improve real-time performance with more diverse datasets
- Try attention mechanisms to boost classification on challenging images



