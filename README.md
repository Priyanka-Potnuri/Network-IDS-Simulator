# Flask-Based Security Operations Center (SOC) Dashboard Simulator

## Project Definition: What is this project and what does it do?

The Flask-Based Security Operations Center (SOC) Dashboard Simulator is a web-based cybersecurity monitoring application developed using Python and the Flask framework. It simulates a Security Operations Center (SOC) environment by generating synthetic network intrusion events and presenting them through an interactive dashboard. The application visualizes simulated attack logs, security metrics, and attack distributions using dynamic charts, providing an overview of how security analysts monitor and interpret security events.

---

## Why is this used? / How does it help?

### Security Operations Center (SOC) Simulation
The application demonstrates how a SOC dashboard can present network security events in a structured and visual format, allowing users to understand how security incidents are monitored and analyzed.

### Security Event Visualization
Instead of displaying raw console output, the dashboard converts simulated intrusion events into interactive visualizations, making attack patterns and distributions easier to interpret.

### Security Metrics Demonstration
The dashboard displays commonly used machine learning evaluation metrics such as Accuracy, Precision, Recall, F1-Score, Classification Report, and Confusion Matrix to demonstrate how intrusion detection model performance can be represented in security monitoring systems.

### Educational Cybersecurity Dashboard
The project serves as a learning platform for understanding SOC dashboards, cybersecurity monitoring concepts, Flask web development, and security data visualization.

---

## Core Functional Workflow / Architecture

### Simulated Event Generation
Generates simulated network intrusion events with randomized timestamps, source IP addresses, and predefined attack categories including DDoS, SQL Injection, Port Scanning, and Malware.

### Dashboard Processing Layer
Processes the generated security events and dynamically renders them within a Flask-based web application.

### Data Visualization Engine
Uses Matplotlib to generate attack distribution charts, which are converted into Base64-encoded images and embedded directly into the web dashboard for real-time visualization.

### Security Metrics Module
Utilizes scikit-learn evaluation utilities to display classification reports and confusion matrices, illustrating how detection performance metrics are commonly presented in cybersecurity dashboards.

### User Interface
Presents simulated attack logs, graphical attack distributions, and security evaluation metrics through a centralized web dashboard designed to resemble a simplified Security Operations Center monitoring interface.
