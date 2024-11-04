# **Diabetes Prediction Model Using SVM with Streamlit Deployment**

This project aims to develop a Diabetes Prediction Web Application that uses a Support Vector Machine (SVM) model to predict the likelihood of an individual having diabetes based on their health data. The model leverages clinical data, including Blood Pressure, Glucose Level, BMI, Age, and other relevant parameters, to classify a person as diabetic or non-diabetic. The prediction model is trained using the Scikit-Learn library, and the web application interface is built using Streamlit for easy deployment and accessibility.

# **Key Features:**

1. *Data Preprocessing:* Cleans and normalizes input health data to ensure accuracy in predictions.
2. *Machine Learning Model:* Uses Support Vector Machine (SVM), a robust classification model suitable for high-dimensional data, trained on a diabetes dataset.
3. *Interactive Web Interface:* Streamlit provides a simple yet interactive interface where users can input their health details.
4. *Real-Time Prediction:* Displays the prediction result instantly after the user inputs their data.
5. *User-Friendly Design:* The application is easy to use, with clear instructions and an intuitive layout for inputting health parameters.

# **Tech Stack:**

- *Python:* For data processing, model development, and backend logic.
- *Scikit-Learn:* To build, train, and test the SVM classification model.
- *Streamlit:* For deploying the web app and creating a clean, user-friendly interface.


# **Output**

![deploy1](https://github.com/user-attachments/assets/d7ca1214-99ba-462f-8954-c87d72bb8b8f)
![deploy2](https://github.com/user-attachments/assets/dc6e1705-0b01-4624-a522-74a988e48685)

### **To Run**

- Clone the repo
- Set Up Your Environment: Make sure you have Python 3.x installed on your system. It's a good practice to create a virtual environment for this project.
-   python3 -m venv env
-   source env/bin/activate  # On Windows: env\Scripts\activate
- Install the Required Dependencies: Use pip to install all the necessary packages for the project.
-   pip install streamlit scikit-learn pandas numpy
-   Run the Streamlit App: Launch the Streamlit app using the following command:
-     streamlit run diabetes_web_app.py

### **Requirements**
- Python 3.x
- Streamlit
- Scikit-learn
- Pandas
- Numpy
