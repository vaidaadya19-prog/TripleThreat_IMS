# Triple-Threat Inventory Intelligence System

## Overview

The Triple-Threat Inventory Intelligence System is an AI-powered inventory management application that integrates machine learning with a Java-based graphical user interface. The system is designed to perform intelligent inventory analysis, demand forecasting, and stock risk prediction using real-world data. It follows a hybrid architecture where the backend is implemented in Python and the frontend is developed in Java Swing.

The system also includes a RESTful API layer for communication between the frontend and backend, along with a chatbot interface for natural language interaction with the inventory data.


## Objectives

* To develop an intelligent inventory management system using machine learning techniques.
* To automate stock analysis, demand forecasting, and risk prediction.
* To provide a user-friendly graphical interface for interacting with inventory data.
* To enable real-time communication between Python backend and Java frontend.
* To support natural language queries through an integrated chatbot system.


## System Architecture

The system follows a hybrid architecture:

* Python Backend (Machine Learning Engine)
* Flask API Layer (Communication Bridge)
* Java Swing Frontend (User Interface)

Flow of execution:

Java GUI → Flask API → Python ML Engine → Response → Java GUI


## Features
### Machine Learning Module (Python)

* Product clustering using K-Means algorithm
* Demand forecasting using regression models
* Stockout risk prediction using classification models
* Data preprocessing and feature engineering

### Backend API (Flask)

* REST API endpoints for model interaction
* JSON-based communication with frontend
* Real-time query processing

### Frontend Application (Java Swing)

* Multi-tab dashboard interface
* Product clustering visualization
* Forecasting panel for demand trends
* Risk monitoring and alerts
* Add new product feature with live prediction
* Integrated AI chatbot interface

### Chatbot System

* Accepts natural language queries
* Provides inventory insights such as:

  * Stock status
  * Risk analysis
  * Product recommendations
  * Summary reports


## Technologies Used

### Backend
* Python 3.x
* Flask
* Pandas
* NumPy
* Scikit-learn

### Frontend

* Java
* Swing
* JSON Simple Library

### Tools

* Visual Studio Code
* Java Development Kit (JDK)
* Python Interpreter

## Installation and Execution
### Prerequisites

* Python 3.x installed
* Java JDK installed
* Required Python libraries installed:

  ```
  pip install flask pandas numpy scikit-learn
  ```

### Step 1: Start Python Backend

Navigate to the backend directory:

```
cd python_backend
python api_server.py
```

Ensure the server is running at:

```
http://127.0.0.1:5000
```

---

### Step 2: Start Java Frontend

Open a new terminal and navigate to the Java GUI directory:

```
cd java_gui
javac -cp "lib/json-simple-1.1.1.jar" -d out src/gui/*.java
java -cp "out;lib/json-simple-1.1.1.jar" gui.MainFrame
```

---

## Workflow

1. Dataset is loaded and processed in Python.
2. Machine learning models are trained on inventory data.
3. Flask API exposes model outputs to frontend.
4. Java Swing GUI sends requests to backend.
5. Backend returns predictions and analytics.
6. Chatbot processes user queries and returns responses.

---

## Modules

* Data Processing Module
* Clustering Module
* Forecasting Module
* Risk Prediction Module
* API Communication Module
* GUI Module
* Chatbot Module

---

## Output

The system provides:

* Clustered product categories
* Future demand predictions
* Stock risk classification
* Inventory summary reports
* Interactive chatbot responses

---

## Future Enhancements

* Integration with web-based frontend using React
* Database integration for persistent storage
* Deployment on cloud platforms
* Advanced deep learning-based forecasting models
* Voice-enabled chatbot interface

---

## Author
Aadya Vaid

Ananya Alagh

Kanusha Sharma

B.Tech Computer Science and Engineering (AI/ML)

