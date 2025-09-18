
# Automated Labour Detection Framework using Deep CNN

## 📌 Introduction

This project presents a **Deep Convolutional Neural Network (CNN) framework** for the early detection of labour in pregnant women. The system analyzes **Electrohysterography (EHG) signals** to identify uterine contractions, enabling timely medical intervention to mitigate the risks of **premature birth**.

Premature birth (before 37 weeks of gestation) is a leading cause of neonatal complications and mortality. Early and accurate detection of labour is crucial for improving maternal and fetal health outcomes.


## 🎯 Motivation

* Globally, **15 million babies** are born prematurely every year.
* In India, \~**3.5 million premature births** occur annually.
* Preterm birth is the **leading cause of newborn deaths worldwide**.
* Detecting labour early helps provide necessary medical support and reduces complications.

## 🧪 Methodology

Designed a **10-layer CNN model**:

* **6 Convolutional Layers**
* **4 Fully Connected Layers**

### Key Steps:

1. **Data Pre-processing** – Extract and prepare 30-minute uterine EHG signal records.
2. **Model Training** – Apply CNN for automatic feature extraction and classification.
3. **Activation Functions** – ReLU for hidden layers, Sigmoid for binary classification.
4. **Regularization** – Dropout layers to prevent overfitting.

### Dataset

* **Term-Preterm EHG Database (TPEHG DB)**
* 300 uterine EMG records (1997–2005)
* Includes both term (>37 weeks) and preterm (≤37 weeks) pregnancies

## ⚙️ System Requirements

**Hardware**

* CPU: Intel Core i5 / 4+ cores
* GPU: NVIDIA GTX 1050+ (or AMD RX 5000+)
* RAM: 16 GB+
* Storage: 1 TB+

**Software**

* OS: Windows 10
* Python 3.6+
* Jupyter Notebook / Google Colab

**Libraries**

* NumPy
* Pandas
* Matplotlib, Seaborn
* Scikit-learn
* SciPy

## 📊 Results

* Achieved **99.93% accuracy** in detecting labour from EHG signals.
* High recall and precision values confirm the model’s reliability.
* Demonstrated effective binary classification (labour vs. no labour).

## 🚀 Future Scope

* Develop a **mobile/IoT application** for real-time monitoring.
* Generate **synthetic EHG signals** to improve dataset size and model accuracy.
* Extend system to include **labour stage detection** and **automated alerts** for timely intervention.

## 📝 Conclusion

This framework successfully demonstrates the use of **Deep CNN** in **premature birth detection**. By leveraging EHG signals, the system enables early detection of labour, potentially reducing neonatal mortality and improving healthcare outcomes for mothers and babies.
