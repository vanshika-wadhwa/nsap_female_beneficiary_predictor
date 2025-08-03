# NSAP Eligibility Predictor using IBM AutoAI

This project aims to automate the identification of eligible social welfare schemes (under NSAP) for citizens based on demographic data using a machine learning model built with **IBM Watson AutoAI**.

## 🔍 Problem Statement
Many citizens are unaware of which NSAP scheme they are eligible for. Government officials face delays and manual bottlenecks in processing applications.

## 🎯 Objective
Build and deploy a machine learning classification model that:
- Takes in applicant details (age, gender, income, etc.)
- Predicts the most suitable NSAP scheme
- Helps automate and speed up the eligibility screening process

## 📊 Dataset
Source: [AI Kosh NSAP Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html)

Features include:
- Age
- Gender
- Disability
- Income
- Marital Status
- Target: NSAP Scheme Category

## 🧠 Model Development

| Step | Tool |
|------|------|
| Data Upload | IBM Watson Studio |
| Model Training | IBM AutoAI |
| Model Deployment | IBM Cloud Lite |
| Testing | Web interface with JSON output |

## 📈 Sample Output

```json
{
  "prediction": "IGNWPS",
  "confidence": 98.7
}
