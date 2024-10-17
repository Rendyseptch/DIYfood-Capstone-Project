# Bangkit Academy Capstone Project - Batch 1 (2024)

### Key Project Details:

- **Team Name:** C241-PS129 Team
- **Project Title:** DIY FOOD
- **Team Members:**
    - (ML) M131D4KY2017– Rendy Septian Pradana – Politeknik Negeri Malang
    - (ML) M227D4KX2112– Siti Isnaini – Universitas Jember
    - (ML) M227D4KX1916– Uswatun Awwalul 'Azmi – Universitas Jember
    - (CC) C131D4KY0136– Riza Afif Syamaidzar – Politeknik Negeri Malang
    - (CC) C133D4KY1038– Muhammad Aji Pangestu – Politeknik Negeri Samarinda
    - (MD) A131D4KY4354– Benaya Laskar Firdaus – Politeknik Negeri Malang
    - (MD) A006D4KY4078– Alexander Wicaksana – Universitas Brawijaya

## Project Overview
# Jogja Culinary Recomendations App ()

This application is designed to provide a platform for tourists visiting the Jogja area, helping them explore and enjoy the region's culinary delights. Our goal is to boost demand from tourists seeking authentic Jogja culinary experiences while promoting and preserving Jogja's culinary heritage.

## Project Goals

- **Enhance Tourist Satisfaction:** Provide tourists with personalized recommendations for food and beverages in the Jogja area.
- **Celebrate Culinary Heritage:** Promote Jogja's rich culinary culture, ensuring its legacy for future generations.

---

## Features

### Machine Learning

We use a **Dense Neural Network (DNN)** model built with **TensorFlow** to recommend food and beverages. Key steps include:

1. **Data Preprocessing:**
   - Handle missing values using imputation.
   - Convert categorical data to numeric using `LabelEncoder`.
   - Use `TfidfVectorizer` to convert text data into numeric vectors.

2. **Model Development:**
   - Split the dataset into training and test sets.
   - Train the DNN model over 100 epochs.
   - Achieved **85%+ accuracy** with a loss of 0.2355 on the training set, and **78% validation accuracy** with a loss of 1.4176.

3. **Model Evaluation:**
   - Final model evaluation showed an accuracy exceeding **80%**.

### Mobile Development

The app’s interface was designed using **Figma** and implemented in **Android Studio**. Key features include:

- **API Integration:** Data is retrieved from the web server and displayed within the app via API calls.

### Cloud Computing

The backend services are built using **Flask** and deployed using **Google Cloud Platform**. Key components include:

- **Cloud Run:** To deploy and manage the Flask API.
- **Logging and Monitoring:** To track API system activity in Cloud Run.
- **Cloud Storage Bucket:** For storing images related to the app.
- **App Engine:** Used for the frontend deployment.

---

## Technologies Used

- **Machine Learning:** TensorFlow, Python
- **Mobile Development:** Android Studio, Figma
- **Cloud Computing:** Google Cloud (Cloud Run, App Engine, Cloud Storage)

---

## Project Status

The project is currently in [status of your project: e.g., development phase / testing phase]. 

We believe that this app will not only meet the needs of tourists but also ensure that Jogja's culinary heritage is celebrated and preserved for future generations.

---

### Links & Resources

- [Figma Design](#https://www.figma.com/design/UtUow36J6kJK41DsGPQr9a/DIYFOOD-DESIGN?node-id=0-1&t=wRypON113EUefyIj-1)  
- [Project Brief](#https://docs.google.com/document/d/131Fwzk-NU_5qlSLwsECDehXhZcQbHkS5BABCEgCPlc8/edit )
- [Documentation](#https://docs.google.com/presentation/d/1lFf14QO7wlh3kt8CfLjjG7eEnlsdl8Zupqa11eeghEM/edit?usp=sharing)

---




