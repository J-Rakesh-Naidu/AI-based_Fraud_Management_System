# AI-based Fraud Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is an **AI-based Fraud Management System** designed to verify the authenticity of UID Aadhar Cards. It was developed as part of an Infosys Springboard Internship.

## 📜 Description

The primary goal of this project is to leverage Artificial Intelligence to validate Aadhar cards, thereby detecting and preventing potential fraud. The system uses a multi-stage pipeline of machine learning models to analyze and verify the submitted card. This includes:

* **Classification Model**: To initially identify if the uploaded image is a valid type of Aadhar card.
* **Detection Model**: To locate and isolate key features and security elements on the card, such as the photograph, QR code, and official emblems.
* **OCR (Optical Character Recognition) Model**: To extract textual information from the card, which can then be cross-verified against a database or official records.

A **Flask** backend serves as the core of the application, integrating these models and exposing them through a web-based interface.

## ✨ Features

* **End-to-End Verification**: A complete pipeline to validate Aadhar cards using AI.
* **Modular Architecture**: The system is composed of distinct models for classification, detection, and OCR, allowing for independent updates and improvements.
* **Web Interface**: A simple and user-friendly web interface built with Flask for easy interaction.
* **Fraud Prevention**: Helps in identifying forged or tampered Aadhar cards.

##  flowchart

Here is a visual representation of the system's architecture and workflow.


![flowchart of applicaton](https://github.com/J-Rakesh-Naidu/AI-based_Fraud_Management_System/blob/main/flowchart.jpeg)


## 🛠️ Technologies Used

* **Backend**: Python, Flask
* **Machine Learning**: Jupyter Notebook, Scikit-learn, TensorFlow/PyTorch (specify as appropriate)
* **Frontend**: HTML, CSS, JavaScript

## 🚀 Getting Started

To get a local copy of the project up and running, follow these steps.

### Prerequisites

Ensure you have Python 3.x and pip installed on your system.

* **Python 3**
* **pip**

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/J-Rakesh-Naidu/AI-based_Fraud_Management_System.git](https://github.com/J-Rakesh-Naidu/AI-based_Fraud_Management_System.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd AI-based_Fraud_Management_System
    ```
3.  **Install the required packages:**
    (You may need to create a `requirements.txt` file first)
    ```sh
    pip install -r requirements.txt
    ```
4.  **Run the Flask application:**
    ```sh
    python app.py
    ```

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.

---
*This README was generated with assistance from an AI.*
