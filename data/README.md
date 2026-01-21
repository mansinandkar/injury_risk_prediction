# Dataset Description

## Dataset Selection and Rationale
This project uses the **MHEALTH (Mobile Health) dataset**, selected for its strong relevance to **athlete performance monitoring and injury risk prediction**.

The dataset provides rich, multivariate time-series data collected from wearable sensors placed on an athlete’s **chest, wrist, and ankle**, capturing detailed physiological and biomechanical signals during real-world physical activities. Its sequential nature makes it particularly suitable for modeling **continuous movement patterns** and understanding how one motion transitions into another over time.

The data closely mirrors signals produced by professional sports monitoring devices, making it valuable for applications in **sports analytics, injury prevention, and human activity recognition**. Additionally, the dataset is publicly available and well-documented through the **UCI Machine Learning Repository**, supporting reproducibility and research transparency.

---

## Dataset Characteristics

### Participants
- **Total subjects:** 10 volunteers  
- **Gender:** 8 male, 2 female  
- **Age range:** 20–35 years  

Participants performed a variety of physical activities while wearing body-mounted sensors, generating realistic motion and physiological data.

---

### Activities
The dataset includes **12 labeled activities**, spanning both low-intensity and high-intensity movements, such as:
- Standing, sitting, lying down  
- Walking, running, cycling  
- Jumping, crouching, and other dynamic motions  

This wide activity range makes the dataset highly relevant for analyzing **athletic workload, fatigue, and injury risk patterns**.

---

### Sensor Modalities
- **Chest:** Accelerometer, ECG  
- **Wrist:** Accelerometer, gyroscope, magnetometer  
- **Ankle:** Accelerometer, gyroscope, magnetometer  

These modalities capture complementary motion and physiological signals, enabling comprehensive activity and risk analysis.

---

### Technical Specifications
- **Sampling Frequency:** 50 Hz (50 measurements per second)  
- **Features:**  
  - 24 continuous sensor measurements  
  - Activity labels  
  - Subject identifiers  

The high temporal resolution supports fine-grained time-series modeling and deep learning approaches.

---

## Relevance to Injury Risk Prediction
The combination of high-frequency sensor data, multiple body locations, and diverse physical activities allows for:
- Detection of abrupt movement changes  
- Identification of repetitive high-load patterns  
- Analysis of physiological stress indicators  
- Modeling of movement variability and instability  

These characteristics make the MHEALTH dataset well-suited for developing **proxy-based injury risk prediction models** in the absence of explicit injury labels.

