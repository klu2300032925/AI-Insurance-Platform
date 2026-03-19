# GENIUS LEAGUE

## AI-Powered Parametric Insurance for Income Protection of Gig Delivery Workers

### A Real-Time, Event-Driven Platform for Automated Risk Assessment, Weekly Pricing, and Instant Income Compensation

---

## Inspiration

India’s gig delivery workforce operates in highly uncertain environments where daily income depends entirely on uninterrupted working conditions. External disruptions such as heavy rainfall, extreme heat, and hazardous air quality frequently interrupt operations, leading to immediate income loss.

Despite the predictability of such disruptions through environmental data, there is no system that provides instant financial protection. Traditional insurance systems are slow, reactive, and not designed for short-term, high-frequency disruptions.

This motivated us to design a proactive, automated insurance solution that ensures financial stability for gig workers in real time.

---

## What it does

This project presents an AI-powered parametric insurance platform that protects gig delivery workers from income loss.

The system:

* Evaluates environmental risk using real-world indicators
* Assigns a weekly premium model aligned with gig worker earnings
* Continuously monitors disruption conditions such as AQI, temperature, and rainfall
* Detects predefined parametric triggers
* Automatically initiates claims without manual intervention
* Instantly calculates and processes payouts

---

## How we built it

The system follows a modular, event-driven architecture implemented using Java and web technologies.

### Core Components

* **Risk Assessment Engine** – Calculates dynamic risk score based on environmental conditions
* **Premium Calculation Engine** – Determines weekly premium using risk-based pricing
* **Trigger Detection Engine** – Monitors disruption thresholds in real time
* **Claim Processing Engine** – Automatically initiates payout

---

## Mathematical Model

### Premium Calculation

```id="nbp9fd"
Premium = Base + (RiskScore * RiskFactor)
```

Where:

* Base = ₹50
* RiskFactor = ₹10
* RiskScore is derived from AQI, temperature, and rainfall conditions

---

### Payout Calculation

```id="wvlm5a"
Payout = DailyIncome * LossFactor
```

Where:

* LossFactor = 0.7 (70% income protection)

---

## Example Scenario

* Daily Income = ₹800
* Risk Score = 5

Result:

* Premium = 50 + (5 * 10) = ₹100
* Payout = 800 * 0.7 = ₹560

---

## Code Logic

```java id="84un0b"
double premium = base + (riskScore * riskFactor);
double payout = income * 0.7;
```

---

## Workflow

User Input → Risk Assessment → Premium Assignment → Continuous Monitoring → Trigger Detection → Claim Activation → Instant Payout

---

## Prototype Demonstration

https://drive.google.com/file/d/1ZnsEKVEp_0kEKpRf2YEvhDFFtrH1g4eY/view

---

## Built With

Java (Spring Boot), HTML, CSS, JavaScript, REST APIs, Event-Driven Architecture

---

## Team – Genius League

* Kavuru Gowthami (2300032925) – Team Lead
* Vuyyuru Kalyani (2300080325)
* Yannam Durga Bhavani (2300032092)

---
