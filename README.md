# 🌱 Crop Recommendation System

A Machine Learning-based Crop Recommendation System that recommends the most suitable crop based on soil and environmental conditions such as **Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall**.

The system uses a **Random Forest Classifier** to analyze the input conditions and predict a suitable crop. It also provides a graphical user interface using **Tkinter** and stores recommendation activity using **SQLite**.

## 📌 Features

* 🌾 Crop recommendation using Machine Learning
* 🤖 Random Forest Classification algorithm
* 🧪 Soil parameter analysis
* 🌡️ Temperature and humidity analysis
* 💧 Rainfall-based recommendation
* 🧑‍💻 User-friendly Tkinter GUI
* 🖼️ Displays the recommended crop image
* 🗄️ SQLite database for activity logging
* 👨‍💼 Admin dashboard
* 📊 User activity and recommendation logs
* 🔄 Clear and reset input functionality

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* Random Forest Classifier
* Pandas
* NumPy

### GUI

* Tkinter
* Pillow (PIL)

### Database

* SQLite

### Dataset

* `crop_recommendation.csv`

## 🧠 Machine Learning Model

The system uses the following input features:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH
* Rainfall

The target variable is the **crop label**.

The dataset is divided into training and testing sets, and a Random Forest Classifier is trained to predict the most suitable crop.

## 📂 Project Structure

```text
Crop-Recommendation-System/
│
├── Crop Recommendtion.py
├── admin_dashboard (1).py
├── Crop_Recommendation_Model.ipynb
├── crop_recommendation.csv
├── database.db
│
├── result/
│   └── Crop Images
│
├── images/
│   └── Application Images
│
└── README.md
```

> Note: The Python virtual environment (`env/`) should not normally be uploaded to GitHub. It is better to add it to `.gitignore` and let users install the required packages separately.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Crop-Recommendation-System
```

### 2. Create a virtual environment

```bash
python -m venv env
```

### 3. Activate the virtual environment

**Windows:**

```bash
env\Scripts\activate
```

### 4. Install required libraries

```bash
pip install pandas numpy scikit-learn pillow
```

Tkinter is normally included with standard Python installations on Windows.

## ▶️ How to Run

Run the main application:

```bash
python "Crop Recommendtion.py"
```

The application will open the Crop Recommendation window.

Enter:

```text
Nitrogen
Phosphorus
Potassium
Temperature
Humidity
pH
Rainfall
```

Then click **Predict**.

The system will display the recommended crop.

## 👨‍💼 Admin Dashboard

The project also contains an admin dashboard that provides access to:

* Registered users
* Email and phone information
* Login count
* User activity logs
* Crop recommendation history
* Recommended crop information

Run the admin dashboard using:

```bash
python "admin_dashboard (1).py"
```

### Default Admin Account

For the current development version:

```text
Username: admin
Password: admin123
```

⚠️ Change these credentials before using the application in a real production environment. Passwords should also be securely hashed rather than stored as plain text.

## 📊 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Random Forest Training
   ↓
Model Prediction
   ↓
Accuracy Evaluation
   ↓
Crop Recommendation
```

## 🎯 Project Objective

The main objective of this project is to assist farmers and agricultural users in selecting a suitable crop based on soil nutrients and environmental conditions.

The system demonstrates how Machine Learning can be applied to agriculture to support data-driven crop selection.

## 🔮 Future Enhancements

* 🌦️ Real-time weather API integration
* 📱 Android mobile application
* ☁️ Cloud deployment
* 🌾 Fertilizer recommendation
* 💧 Irrigation recommendation
* 📈 Crop yield prediction
* 🌐 Web-based interface
* 🔐 Secure user authentication
* 🧠 Improved Machine Learning models
* 📊 Advanced analytics dashboard

## 👨‍💻 Author

**Pavan**

MCA Student
Interested in Software Development, Machine Learning, Data Science and Web Technologies.

## 📄 License

This project is created for educational and academic purposes.

---

⭐ If you find this project useful, consider giving the repository a star.
