# **🌱 Plant Disease Detection System using Deep Learning**  

Welcome to the **Plant Disease Detection System**, an AI-powered solution that uses **deep learning** to detect plant diseases from leaf images. This system is trained on **38 different plant diseases** and is deployed via a **Streamlit web application** for real-time disease recognition.  



##  Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Guide](#installation-guide)
- [Usage Guide](#usage-guide)
- [License](#license) 



##  Features 
✅ **Deep Learning-Based Disease Detection** – Uses a CNN model for classification.  
✅ **Web Interface for Easy Use** – Built using **Streamlit**.  
✅ **High Accuracy Model** – **83.6% Training Accuracy, 90.0% Validation Accuracy**.  
✅ **Confusion Matrix & Performance Metrics** – Evaluate classification results.  
✅ **Real-Time Image Upload & Prediction** – Users can upload images for instant disease identification.  



##  Technologies Used  
- **Python** – Core programming language.  
- **TensorFlow/Keras** – Deep learning framework for training the CNN model.  
- **OpenCV** – Used for image preprocessing and manipulation.  
- **NumPy & Pandas** – Data handling and numerical operations.  
- **Matplotlib & Seaborn** – For visualizing accuracy trends and confusion matrices.  
- **Streamlit** – Web-based application framework for user interaction.  



##  Installation Guide  

### **🔹 Prerequisites**  
- Install **Python (version 3.8 or above)** from the [official website](https://www.python.org/).  
- Install **VS Code or Jupyter Notebook** for code execution.  

###  Setup Steps  

#### **1. Clone the Repository**  
```bash
git clone https://github.com/shantaveer21/Plant-Disease-Detection.git
cd Plant-Disease-Detection
```

#### **2. Set Up Virtual Environment**  
Launch the terminal and run the following commands:  
```bash
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # macOS/Linux
```

#### **3. Install Dependencies**  
```bash
pip install -r requirements.txt
```



##  Usage Guide  

###  Launch the Web Application
Run the following command to start the Streamlit app:  
```bash
streamlit run app.py
```

###  Application Workflow  

#### **1. Upload Image**  
- Users upload a plant leaf image for disease detection.  

#### **2. Model Prediction**  
- The CNN model processes the image and predicts the disease.  

#### **3. Display Results**  
- The system displays the **disease name** with confidence scores.  


### **4. Closing the Application**  
- The app supports safe exit via the **Close Window** button.  



##  📊 Results & Snapshots  

| **Figure**  | **Description**  |  
|-------------|----------------|  
| **Home Page** | Web interface where users can upload an image for disease detection. |  
| **Disease Recognition Page** | Displays an uploaded image before classification. |  
| **Prediction Result Page** | Shows the detected disease name with model confidence. |  



##  License  
This project is licensed under the **MIT License**. You are free to **use, modify, and distribute** the project under its terms.  

---

 **If you found this project useful, give it a ⭐ on GitHub!** 😊  

 
