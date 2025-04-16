
# 🧠 Fetal Anomaly Detection System (FADS)

**Healthier Moms and Babies – AI-Driven Prenatal Care**

Fetal Anomaly Detection System (FADS) is a machine learning-powered platform designed to support obstetricians and patients by classifying fetal health conditions from cardiotocography (CTG) data. This application aids in identifying **normal**, **suspect**, and **pathological** fetal states, enabling data-informed clinical decisions and reducing human error in prenatal diagnosis.

---

## 🚀 Features

- 📊 **ML-Based Classification**: Uses models like Random Forest, XGBoost, and KNN to classify fetal health with high accuracy.
- 📥 **User Interfaces**: Dual interfaces for both healthcare providers and patients to input data and review results.
- 🔒 **Secure & Scalable Backend**: Built with Node.js, Express, MongoDB, and Mongoose for reliability and medical-grade data protection.
- 📈 **Data Visualization**: Clear presentation of results with performance metrics like precision, recall, and specificity.
- 📢 **Notification System**: Alerts and updates for timely action in clinical settings.

---

## 🛠️ Tech Stack

**Frontend**
- HTML, CSS, Bootstrap
- Responsive design with MVC architecture

**Backend**
- Node.js, Express.js
- MongoDB, Mongoose (NoSQL + ODM)
- RESTful API integration

**Machine Learning**
- Python (scikit-learn)
- Algorithms used: Random Forest, XGBoost, KNN, AdaBoost
- Feature selection via correlation heatmaps
- Data scaling using RobustScaler

---

## 📊 ML Model Performance (Random Forest)

| Class        | Precision | Recall | F1-Score | Specificity |
|--------------|-----------|--------|----------|-------------|
| Normal       | 0.976     | 0.988  | 0.982    | 0.908       |
| Suspect      | 0.938     | 0.835  | 0.884    | 0.991       |
| Pathological | 0.923     | 1.00   | 0.960    | 0.994       |

---

## 🧪 Dataset

We used a publicly available **Cardiotocography (CTG)** dataset containing vital fetal health indicators. Features were selected via correlation heatmaps and normalized using `RobustScaler`.

---

## 📷 UI Preview

- Landing Page  
- Patient Data Entry Page  
- Doctor Dashboard  
- Report View with Fetal Health Status  

(*Include screenshots or links to GIFs/screenshots if available*)

---

## 👩‍⚕️ Use Cases

- Medical diagnostics and prenatal decision support  
- Real-time fetal health analysis for hospitals or clinics  
- Low-resource healthcare settings with scalable deployment

---

## 📌 Future Scope

- Integration with ultrasound & maternal health data  
- Real-time CTG streaming & analysis  
- Deep learning model integration  
- Localization for global deployment  
- Clinical trials and real-world testing

---

## 👨‍💻 Contributors

| Name            | Role                  | Contribution                                  |
|-----------------|-----------------------|-----------------------------------------------|
| Shivani Kotian  | Machine Learning      | Model design, training, evaluation             |
| Jay Bambhroliya | Backend               | Server-side logic, ML integration             |
| Jay Patel       | Backend               | API, database, and infrastructure             |
| Safal Rijal     | Machine Learning      | Optimization, testing, metrics tuning         |
| Pooja Shekhar   | Frontend              | UI design for patient and doctor portals      |
| Yash Sohagia    | Frontend              | UX enhancement and responsive design          |

---

## 📄 License

This project is developed for educational and research purposes under the guidance of California State University, Los Angeles. For usage beyond research or academic scope, please contact the contributors.

---

## 🔗 Live Demo or Repository

🔗 [GitHub Repository](https://github.com/poojashekar987/FAD)  
