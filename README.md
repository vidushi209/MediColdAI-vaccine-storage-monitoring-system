# MediCold AI – Intelligent Cold Chain Monitoring System

## Overview
MediCold AI is an IoT and Machine Learning-based cold chain monitoring system designed to ensure safe storage of vaccines and temperature-sensitive medicines.

The system uses ESP32 with multiple sensors and an LSTM-based anomaly detection model to predict spoilage risks and monitor environmental conditions in real time.

## Features
- Real-time temperature monitoring (DS18B20)
- Humidity monitoring (DHT22)
- Door status detection (Reed switch)
- GPS tracking (NEO-6M)
- Offline-first buffering system
- Relay-based automated corrective action
- LSTM anomaly detection model
- Cloud-connected dashboard
- SMS and Email alerts

## Tech Stack

Hardware:
ESP32, DHT22, DS18B20, GPS module, Reed switch, Relay module

Software:
Python
TensorFlow
Scikit-learn
Firebase / MQTT
Flask / Streamlit Dashboard

## Project Pipeline

Sensors → ESP32 → MQTT → Cloud Database → ML Prediction → Dashboard + Alerts

## Team Members

- Nazia Bano – Hardware Development
- Vidushi Raghav – Machine Learning Model
- Shivani – Dashboard Development

## Status

Project under development (Final Year B.Tech Project)
