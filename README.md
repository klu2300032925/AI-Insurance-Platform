# GENIUS LEAGUE

## AI-Powered Parametric Insurance Platform for Gig Delivery Workers

---

## 1. Problem Statement

Gig delivery workers in India operate in a highly dynamic earning environment where their income depends entirely on active working hours. External disruptions such as severe weather, high pollution levels, and sudden operational restrictions can instantly halt their ability to work.

These disruptions are frequent, unpredictable, and unavoidable, yet there is no dedicated system that offers immediate financial protection for such short-term income losses.

This project addresses this gap by introducing an automated parametric insurance platform designed specifically for gig workers, enabling instant compensation without traditional claim processes.

---

## 2. Target Persona

### Selected Delivery Persona

Urban delivery partners working with platforms such as Swiggy, Zomato, and e-commerce services

### Characteristics

* Works approximately 6–8 hours per day
* Earnings depend on completed delivery orders
* Income variability based on demand and conditions
* Highly sensitive to environmental disruptions

### Operational Context

Primarily operates in urban regions with high delivery density and demand fluctuations

---

## 3. Key Disruptions Covered

The system focuses exclusively on income disruption events caused by external conditions.

### Environmental Factors

* Heavy rainfall leading to reduced mobility
* Extreme temperature conditions affecting working hours
* Hazardous air quality impacting productivity

### Operational Factors

* Government-imposed movement restrictions
* Local strikes or shutdowns
* Temporary delivery zone closures

### Parametric Triggers

* Rainfall > 80 mm/day
* Temperature > 45°C
* AQI > 400

Once any defined threshold is exceeded, the system automatically initiates the compensation process.

---

## 4. Weekly Premium Model

To align with the earning cycle of gig workers, the platform adopts a weekly subscription-based pricing model.

### Sample Plans

| Weekly Premium | Coverage Value |
| -------------- | -------------- |
| ₹10/week       | ₹500           |
| ₹20/week       | ₹1000          |

### Pricing Determinants

* Environmental risk intensity
* Location-specific disruption frequency
* Historical data trends
* User activity consistency

This enables dynamic and fair premium allocation across different regions.

---

## 5. Mathematical Model

### Premium Calculation

Premium = Base + (RiskScore × RiskFactor)

Where:

* Base = ₹50
* RiskFactor = ₹10
* RiskScore is computed using environmental indicators

---

### Payout Calculation

Payout = DailyIncome × LossFactor

Where:

* LossFactor = 0.7

---

### Example Scenario

Daily Income = ₹800
Risk Score = 5

* Premium = ₹100
* Payout = ₹560

---

### Code Logic

```java
double premium = base + (riskScore * riskFactor);
double payout = income * 0.7;
```

---

## 6. System Workflow

* User onboarding with location and income details
* Risk score generation based on environmental inputs
* Weekly premium calculation
* Subscription activation
* Continuous monitoring of external data
* Detection of trigger conditions
* Automatic claim initiation
* Instant payout execution

---

## 7. AI / ML Integration

The platform incorporates intelligent decision mechanisms to improve accuracy and efficiency.

### Risk Intelligence

* Computes dynamic risk scores based on real-time and historical data

### Adaptive Pricing

* Adjusts premium values based on changing environmental conditions

### Fraud Prevention

* Detects abnormal claim behavior
* Validates user location authenticity
* Prevents duplicate claim submissions

---

## 8. Technology Stack

### Frontend

* HTML, CSS, JavaScript

### Backend

* Java (Spring Boot)

### Database

* MySQL (for structured storage of users, policies, and transactions)

### APIs

* REST APIs for system communication
* Environmental data APIs for real-time monitoring

### System Design

* Event-driven architecture enabling real-time processing

---

## 9. Parametric Automation System

The system operates through a structured event-driven pipeline ensuring zero manual intervention.

### Execution Flow

User Enrollment
↓
Risk Profiling
↓
Continuous Data Monitoring
↓
Condition Evaluation
↓
Trigger Identification
↓
Policy Validation
↓
Automated Claim Execution
↓
Instant Fund Transfer

This structured vertical flow ensures accurate, fast, and fully automated claim processing without manual involvement.

---

## 10. Platform Features

### Worker-Centric Capabilities

* Seamless onboarding experience
* Flexible weekly coverage plans
* Real-time protection monitoring
* Zero-touch claim processing
* Earnings stability dashboard

### Administrative & System Capabilities

* Centralized risk intelligence dashboard
* Automated fraud detection engine
* Claim lifecycle management system
* Analytics and reporting module

---

## 11. Development Plan

### Phase 1 – Concept & Foundation

* Problem analysis and validation
* User persona definition
* Core system architecture design
* Prototype development

### Phase 2 – System Automation

* Integration with real-time environmental APIs
* Implementation of policy management system
* Development of automated trigger detection engine
* Deployment of claim processing workflows

### Phase 3 – Intelligent Scaling

* Advanced fraud detection mechanisms
* Development of analytics dashboards
* Performance optimization and scalability improvements
* Enhancement of user experience and system reliability

---

## 12. Prototype

🔗 https://drive.google.com/file/d/1ZnsEKVEp_0kEKpRf2YEvhDFFtrH1g4eY/view

---

## 13. Expected Impact

* Immediate financial protection for gig workers
* Reduction in income instability
* Faster and transparent compensation process
* Scalable framework for broader gig economy adoption

---

## 14. Team – Genius League

* Kavuru Gowthami (2300032925) – Team Lead
* Vuyyuru Kalyani (2300080325)
* Yannam Durga Bhavani (2300032092)

---
