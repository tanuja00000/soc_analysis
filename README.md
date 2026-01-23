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

## Use Cases

SOC monitoring in isolated networks

Offline system log analysis

Security incident detection

Educational SOC and cybersecurity projects

## Conclusion

The Portable Log Analysis System provides a secure, portable, and offline solution for log analysis and anomaly detection. By combining Python-based analysis with Isolation Forest and visual dashboards, it helps identify security threats effectively in isolated environments.
