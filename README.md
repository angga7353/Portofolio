# 👨‍💻 Angga Fadhlurrahman Prianto – Data Engineer Portfolio

## 📌 About Me
IT professional with 3 years of experience in managing end-user IT support systems and leading projects in data analytics and data science. Skilled in hardware and software troubleshooting, IT asset and storage management, and IT end-user system oversight. Experienced in building data pipelines and implementing best practices in data security and integrity.

## 🧠 Technical Skills
- **Languages & Tools**: Python, SQL
- **Visualization**: Tableau, Kibana
- **Frameworks & Platforms**: Streamlit, Docker, Apache Airflow, Great Expectations

## 📂 Portfolio Projects
### 🔹 [Property Price Trend Analysis – Jakarta, Indonesia (May 2025)](https://github.com/angga7353/Property-Price-Trend-Analysis-as-a-Basis-for-Investment-Strategy.git)
**Objective**: Analyze property price trends to guide investment strategy  
**Role**: Data Engineer  
**Highlights**:
- Designed and implemented DAGs using **Apache Airflow**
- Configured containerized environments with **Docker** for Airflow, PostgreSQL, and Kibana
- Built dashboards in **Kibana** to visualize price trends
- Implemented **data validation** using **Great Expectations** to ensure integrity  
_Tools: Python, Docker, PostgreSQL, Kibana, Airflow_

---

### 🔹 AISeeYou – AI-Powered X-Ray Object Detection (2025)

**Introduction**  
Introducing **"AISeeYou"** – an AI-powered application designed to quickly and accurately detect suspicious objects from X-ray scans. By using AISeeYou, potential smuggling of weapons or hazardous materials can be identified early, significantly reducing crime rates and security threats. This solution strengthens security systems and enhances public safety with high efficiency.

---

**Problem Background**  
Luggage inspection using X-ray scanners has become an essential part of security protocols in many locations, such as airports, government buildings, and major event venues. The primary objective is to ensure that no dangerous or prohibited items are carried into these areas.

However, interpreting X-ray images can be challenging, as items of different materials and shapes may appear similar. To address this, AI-based computer vision technology is now used to assist in automatically identifying potentially hazardous objects. This anomaly detection system accelerates inspections and enhances safety across various public spaces.

---

**Objectives**  
- **X-ray Object Detection**: Recognize and locate objects within an image using bounding boxes and classification. In X-ray baggage scans, this enables automatic identification of dangerous items, improving screening efficiency and reducing reliance on manual inspection.

- **Label Distribution Analysis**:  
  Based on percentage distribution:
  - **Class 4: Swiss Army Knife** – 23.1%  
  - **Class 1: Unidentified Object** – 22.5%  
  - Other classes: **Cutter**, **Scissor**, **Knife**

  Dataset obtained from Kaggle. Note: Class 1 appears to have mislabeling; it is referred to as *Unidentified Object* to reflect uncertainty.

---

**Demo**  
- **YOLOv8 Model**:  
  Visit the deployed application to access real-time predictions. On the Streamlit dashboard, navigate to the **X-ray Detection Prediction** page to view object detection results.

- **Faster R-CNN w/ResNet50**:  
  Download the pre-trained model from the [Google Drive link](#), extract it, and place it in the root folder of the repository. You may also train your own model by following the guide in the TensorFlow `README.md`.

---

**Conclusion**  
The model successfully detects dangerous objects in X-ray images. Using Ultralytics evaluation, it achieved a performance score of **>80% mAP@0.5**, indicating strong predictive accuracy. This provides a solid foundation for continued development.

---

**Further Recommendations**  
- **Increase Dataset Size**: Enhances generalization and reduces overfitting.  
- **Data Augmentation**: Introduce variability via rotation, scaling, flipping, etc., for robustness.  
- **Fine-Tuning**: Adapt pre-trained models to X-ray-specific datasets for better accuracy.  
- **Experiment with Model Architectures**: Consider models like **EfficientDet** or **Faster R-CNN** to optimize for speed, accuracy, and resource usage.

---

**Tools & Technologies**  
- Python, OpenCV, YOLOv8, Streamlit, TensorFlow, Hugging Face Spaces

---

### 🔹 [Problem Category Analysis and Resolution Time – Jakarta, Indonesia (March 2025)](https://github.com/angga7353/Analisis_Tiketing_IT_HELPDESK)
**Objective**: Analyze helpdesk ticket patterns to uncover delay causes  
**Role**: Data Analyst  
**Highlights**:
- Performed descriptive and inferential statistics on ticket resolution times
- Visualized issue status distributions and root causes of pending tickets
- Delivered insights to improve operational efficiency  
_Tools: Python, SQL, Tableau_

---

### 🔹 [Car Price Prediction – USA Market (April 2025)](https://github.com/angga7353/Machine-Learning-for-Car-Price-Prediction)
**Objective**: Predict car prices using supervised machine learning  
**Role**: Data Scientist  
**Highlights**:
- Conducted **EDA**, handled missing values & outliers
- Engineered relevant features
- Built and evaluated multiple regression models
- Deployed model using **Hugging Face** for inference demo  
_Tools: Python, Streamlit, Scikit-learn_

## 📫 Contact Me
- Email: [angga.fpriyanto@gmail.com]
- GitHub: [github.com/angga7353](https://github.com/angga7353)
- LinkedIn: [linkedin.com/in/angga fadhlurrahman prianto](www.linkedin.com/in/angga-fadhlurrahman-prianto-29501b194)
