# Portable Log Analysis System (Offline SOC Project)

## Description

The Portable Log Analysis System is an offline SOC (Security Operations Center) project designed for isolated environments where internet access is not available.

It helps users upload system log files, parse unstructured logs, analyze security events, detect anomalies using Isolation Forest, and visualize results through interactive charts.

## 🎯 Features

Works completely offline

Upload .log, .txt, and .csv files

Log parsing using Python and Regex

Structured log analysis

Anomaly detection using Isolation Forest algorithm

Detection of critical logs and suspicious IPs

Interactive charts and dashboards

Log filtering and search

Report generation and export

## 🏗️ System Architecture

User → Web Dashboard → Log Upload → Log Parser → Analysis Engine → Isolation Forest → Charts & Reports

Standalone application

No internet dependency

## 🛠️ Technology Stack

Frontend: HTML, CSS, JavaScript

Backend: Python

Anomaly Detection: Isolation Forest

Log Parsing: Regular Expressions (Regex)

Data Storage: Local files / SQLite

Visualization: JavaScript charts (offline supported)

## Anomaly Detection

The system uses the Isolation Forest algorithm to detect abnormal patterns such as:

Multiple failed login attempts

Repeated access from the same IP

Sudden spikes in error or critical logs

### screenshots 

<img width="1341" height="614" alt="Screenshot 2026-02-03 191731" src="https://github.com/user-attachments/assets/378187a9-a9ef-4bb9-abef-b3b5bf5a5f16" />

# log message

<img width="1007" height="542" alt="Screenshot 2026-02-03 210252" src="https://github.com/user-attachments/assets/a0a0d644-b5ba-4451-9535-9c84cd006864" />

# Anomaly charts
<img width="1071" height="440" alt="Screenshot 2026-02-18 224200" src="https://github.com/user-attachments/assets/6f390209-a34b-45fb-8b0e-52c2827848a9" />



## Use Cases

SOC monitoring in isolated networks

Offline system log analysis

Security incident detection

Educational SOC and cybersecurity projects

## Conclusion

The Portable Log Analysis System provides a secure, portable, and offline solution for log analysis and anomaly detection. By combining Python-based analysis with Isolation Forest and visual dashboards, it helps identify security threats effectively in isolated environments.


