# Exploratory Data Analysis Final Project

**Applied Computational Statistics Graduate Program**
*Federal University of Minas Gerais (UFMG)*

## Introduction

This project analyzes the **[Social Anxiety Dataset](https://www.kaggle.com/datasets/natezhang123/social-anxiety-dataset/data)**, investigating behavioral and psychological patterns. As required by the course guidelines, we:

1. **Identify correlations** with anxiety severity levels
2. **Examine relationships** between key variables
3. **Follow methodological steps** outlined in the [course guidelines](guidelines.md)

## Context

Social anxiety, also known as social phobia, affects millions of people worldwide. It is often linked to a complex mix of behavioral patterns, psychological states, lifestyle choices, and genetic predispositions. This synthetic dataset was crafted to reflect real-world patterns and includes high-anxiety cases to support research in detection and intervention.

## Dataset

This project utilizes the [Social Anxiety Dataset](https://www.kaggle.com/datasets/natezhang123/social-anxiety-dataset/data), a comprehensive collection of behavioral, physiological, and psychological measures related to social anxiety. The dataset contains:

- **1,250 anonymized records** from clinical and community samples
- **20 variables** spanning demographic, lifestyle, and mental health indicators
- **Clinically-relevant measures** including physiological markers and therapy history

Data was collected through standardized questionnaires and physiological measurements, designed to capture multidimensional aspects of social anxiety. The target variable (Anxiety_level) provides a quantitative measure of symptom severity, enabling both classification and regression analyses.

### Variables Description

#### 1. Demographic Variables
- **Age**: Participant age (years)
- **Gender**: Self-reported gender (categorical)
- **Occupation**: Current occupation/job field (categorical)

#### 2. Lifestyle Factors
- **Sleep_hours**: Average daily sleep duration (hours)
- **Physical_activity**: Frequency of exercise (scale 1-5)
- **Diet_quality**: Self-reported diet quality (scale 1-5)
- **Alcohol_use**: Frequency of alcohol consumption (scale 1-5)
- **Caffeine_intake**: Daily caffeine consumption (scale 1-5)
- **Smoking_habits**: Smoking frequency (scale 1-5)

#### 3. Physiological Indicators
- **Heart_rate**: Average resting heart rate (bpm)
- **Breathing_rate**: Average resting breathing rate (breaths/min)
- **Stress_level**: Self-reported stress (scale 1-10)
- **Sweating_level**: Frequency of excessive sweating (scale 1-5)
- **Dizziness**: Frequency of dizziness episodes (scale 1-5)

#### 4. Mental Health History
- **Family_history**: Family history of anxiety disorders (binary)
- **Medication_use**: Current use of anxiety medication (binary)
- **Therapy_frequency**: Frequency of therapy sessions (scale 1-5)

#### 5. Life Events
- **Recent_life_events**: Experience of major life events in past year (binary)

#### 6. Target Variable
- **Anxiety_level**: Social anxiety intensity (scale 1-10)


## Disclaimer

This dataset was compiled from real-world survey responses and observational studies on behavioral and psychological factors associated with social anxiety. While it has undergone preprocessing and cleaning for analytical use, users should note that the dataset is intended for educational and research purposes only, and not for clinical diagnosis or treatment.

## References

TBD...
