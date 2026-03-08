# Health-Monitoring-System-Project-
This project is built using Spring Boot and MySQL and exposes REST APIs that can be integrated with web or mobile applications.
# AI-Powered Personal Health Monitoring System

## Project Overview

The AI-Powered Personal Health Monitoring System is a backend application designed to help users manage and monitor their health information efficiently.

The system allows users to track symptoms, manage medicines, store emergency contacts, and analyze health risk using AI-based prediction.

This project is built using Spring Boot and MySQL and exposes REST APIs that can be integrated with web or mobile applications.

---

## Problem Statement

Many people struggle to keep track of their health data such as symptoms, medications, and emergency contacts. In critical situations, important information may not be easily accessible.

This system helps users:

- Track their symptoms
- Manage their medication schedules
- Store emergency contacts
- Analyze health risk using AI prediction

By centralizing health information, users can monitor their health more effectively.

---

## Features

### 1. User Management
Users can register and store their basic health information.

APIs:
- Create user
- Retrieve user data

---

### 2. Symptom Tracking

Users can log their symptoms and monitor their health condition.

APIs:
- Add symptom
- Get all symptoms
- Delete symptom

Example symptoms:
- Fever
- Headache
- Fatigue

---

### 3. Medicine Management

Users can store information about medicines they are taking.

APIs:
- Add medicine
- View medicines
- Delete medicine

Medicine details include:
- Medicine name
- Dosage
- Time
- Frequency

---

### 4. Emergency Contact System

Users can store emergency contacts who can be notified in case of health emergencies.

APIs:
- Add emergency contact
- Get emergency contacts
- Delete emergency contact

Example contacts:
- Family member
- Doctor
- Friend

---

### 5. AI Health Risk Prediction

The system analyzes user health data and predicts possible health risk levels.

Example prediction:

Input:
- Age
- Blood pressure
- Sugar level
- Symptoms

Output:
- Risk level (Low / Medium / High)
- Possible disease
- Health recommendation

---

## Tech Stack

Backend:
- Spring Boot
- Java

Database:
- MySQL

ORM:
- Hibernate / JPA

API Type:
- REST APIs

Testing:
- Postman

---

## Project Structure
