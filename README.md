Detecting Cyber Attacks through Measurements: Learnings from a Cyber Range

Project Overview
This project focuses on detecting cyber attacks using network and host-based monitoring techniques within a Security Operations Center (SOC) environment. It leverages the ELK Stack (Elasticsearch, Logstash, Kibana) for log aggregation, analysis, and visualization to identify malicious activities like brute-force attacks, unauthorized access, and lateral movement.

Key Features
Real-time Threat Detection: Monitors network traffic and host logs for Indicators of Compromise (IoCs).

ELK Stack Integration:
Elasticsearch: Stores and indexes logs.
Logstash: Processes and normalizes log data.
Kibana: Visualizes security events via dashboards.

Machine Learning Algorithms:
K-Nearest Neighbors (KNN) for attack classification.
Naive Bayes for probabilistic threat detection.
Random Forest for ensemble-based anomaly detection.

Multi-Module System:
Admin Panel: Authorizes users and views attack analytics.
Remote User Portal: Submits data for attack prediction.



Software:
Frontend: Python, HTML/CSS/JavaScript
Backend: Django-ORM
Database: MySQL (WAMP Server)

Modules
Service Provider:
Login, train/test datasets, view accuracy metrics, and download predictions.

Admin:
Authorize users and monitor registered user details.

Remote User:
Register/login, predict cyber attacks, and view profiles.
