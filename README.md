# Smart Health Kiosk – AI-Based Healthcare Assistance System

## Overview
Smart Health Kiosk is an AI-driven healthcare assistance simulation developed under the Intel Unnati CoE Initiative.

The system demonstrates how intelligent software can assist in emergency handling, wearable health monitoring, and localized healthcare recommendations using Python-based data processing and rule-based decision logic.

---

## Problem Statement
This project simulates a smart healthcare kiosk that:

- Assists users during medical emergencies
- Processes basic health data
- Provides location-aware health suggestions
- Demonstrates pre-arrival hospital data sharing

---

## Tech Stack
- Python
- Pandas
- CSV-based data modeling
- Rule-based decision logic
- Basic GUI interface

---

## Features
- Emergency response simulation
- Location-based healthcare suggestions
- Pre-arrival hospital alert simulation
- Wearable vital monitoring (simulated)
- Doctor & medicine recommendation system

---

## Project Architecture


User Input
↓
GUI Layer (app.py)
↓
Logic Engine (logic.py)
↓
CSV Data Sources
↓
Decision Rules & Output


---

## Project Structure


app.py → Main GUI application
logic.py → Core processing logic
rules.csv → Location + season rules
medical_history.csv → Simulated patient records
doctors.csv → Doctor dataset
README.md → Documentation


---

## Requirements

- Python 3.x
- pandas

Install dependencies:

```bash
pip install pandas

Run the project:

python app.py
Future Improvements

IoT wearable integration

Cloud-based hospital alert system

REST API integration

ML-based health risk prediction

Team

Aishwarya Shanmukh

Deekshitha P

Gandla Rupasree

Mentor: Prof. Sitaram V Yaji
