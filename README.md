# Mathematical Modeling of Motor Vehicle Crash Injury Severity in Massachusetts

## Modeling the Future Challenge -- 2025–2026

**Team #24377**

This repository contains our 25-page mathematical modeling research paper investigating motor vehicle crash injury severity in the Commonwealth of Massachusetts.

### Abstract

Motor vehicle crashes represent a major public health and economic risk in Massachusetts. Using statewide police-reported motor vehicle crash data from 2022 - 2023 that were obtained from the MassDOT Crash Data Portal, this project applies an actuarial risk modeling framework to identify structural, behavioral, and environmental factors associated with crash injury severity.

The dataset has 270,493 crashes with more than 100 variables per crash that are limited to, but not excluding roadway characteristics, environmental conditions, crash dynamics, and driver characteristics. 

The crash severity was modeled using an Ordered Logistic Regression model, with outcomes being organized into four severity levels:
* Property damage only
* Injury
* Serious injury
* Fatal injury

The model achieved approximately 75.5% out-of-sample prediction accuracy. Major predictors of severe injury outcomes included driver medical illness, speed-related driving behavior, driving fatigue, and an intersection being present.

### Key Findings

Our analysis found that crash injury severity is associated, and can be identified with, a few risk factors. The model identified the following relationships between severity and:
* Roadway characteristics and speed environments
* Intersection and access-control characteristics
* Lighting and environmental conditions
* Driver characteristics and behavior
* Number of vehicles and manner of collision

This project used the model's results to create mitigation strategies involving infrastructure redesign, speed management, behavioral risk reduction, and roadway lightning.

### Data & Methodology

The dataset obtained was the MassDOT Crash Data Portal, an official Commonwealth of Massachusetts source containing statewide police-reported crash data.

Our model included five major categories for risk:

1. **Road characteristics**: speed limit, number of lanes, roadway type, junction type, traffic control, and access control
2. **Environmental conditions**: lighting, road surface, weather, and day of week
3. **Crash characteristics**: manner of collision, number of vehicles, and first harmful event
4. **Driver characteristics**: driver age and age group
5. **Driver behavior**: driver risk and contributing circumstances

### Tools & Techniques

* Python
* Ordered Logistic Regression
* Statistical modeling
* Actuarial risk modeling
* Exploratory data analysis
* Data cleaning and preprocessing
* Risk factor analysis

### Research Paper

[Read the full 25-page research paper (PDF)!]([./Massachusetts_Motor_Crash_Modeling_Paper.pdf](https://github.com/avnish-kumar1/math-modeling-massachusetts-crashes/blob/main/24377_6_MathMolesReport_1772481394.pdf))

### Authors:
* Avnish Kumar (Newton North High School Class of 2026/Virginia Tech Class of 2030)
* Oren Schwatz (Newton North High School Class of 2028)
* Maxwell (Max) Nelson (Newton North High School Class of 2027)

### Project Timeline

**October 2025 – March 2026**

### Competition

**Modeling the Future Challenge, a program of The Actuarial Foundation — 2025–2026**

**Team #24377**
