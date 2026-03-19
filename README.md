# GENIUS LEAGUE

## AI-Powered Parametric Insurance for Income Protection of Gig Delivery Workers

### A Real-Time, Event-Driven Platform for Automated Risk Assessment, Weekly Pricing, and Instant Income Compensation

---

## Inspiration

India’s gig delivery workforce operates in highly uncertain environments where daily income depends entirely on uninterrupted working conditions. External disruptions such as heavy rainfall, extreme heat, and hazardous air quality frequently interrupt operations, leading to immediate income loss.

Despite the predictability of such disruptions through environmental data, there is no system that provides instant financial protection. Traditional insurance systems are slow, reactive, and not designed for short-term, high-frequency disruptions.

This inspired us to design a proactive, automated insurance solution that ensures financial stability for gig workers in real time.

---

## What it does

This project presents an AI-powered parametric insurance platform that protects gig delivery workers from income loss.

The system:

* Evaluates environmental risk using real-world indicators
* Assigns a weekly premium model aligned with gig worker earnings
* Continuously monitors disruption conditions such as AQI, temperature, and rainfall
* Uses predefined parametric triggers to detect disruption events
* Automatically initiates claims without manual intervention
* Instantly calculates and processes payouts

This creates a seamless, zero-touch insurance experience.

---

## How we built it

The system is designed using a modular, event-driven architecture implemented with Java and web technologies.

### Core Components

* **Risk Assessment Engine** – Computes dynamic risk score
* **Premium Calculation Engine** – Determines weekly pricing
* **Trigger Detection Engine** – Monitors disruption conditions
* **Automated Claim Engine** – Initiates payout automatically

---

## Mathematical Model

### Premium Calculation

$$
Premium = Base \times (1 + RiskScore \times 0.1)
$$

### Payout Calculation

$$
Payout = DailyIncome \times 0.7
$$

---

## Example Scenario

Given:

* Daily Income = ₹800
* Risk Score = 5

Then:

$$
Premium = 50 \times (1 + 0.5) = ₹75
$$

$$
Payout = 800 \times 0.7 = ₹560
$$

---

## Code Logic Example

```java
double premium = base * (1 + riskScore * 0.1);
double payout = income * 0.7;
```

---

## Challenges we ran into

* Simulating real-time environmental data without live API integration
* Designing a pricing model that is both simple and realistic
* Structuring automated claim processing without manual validation
* Maintaining clarity in system flow for demonstration purposes
* Creating a clean and intuitive user experience

---

## Accomplishments that we're proud of

* Designed a complete parametric insurance workflow
* Implemented automated claim triggering without manual intervention
* Built a functional prototype demonstrating end-to-end flow
* Successfully aligned with all constraints:

  * Income-only coverage
  * Weekly pricing model
* Developed a scalable architecture for future enhancements

---

## What we learned

* Understanding parametric insurance models
* Designing event-driven systems
* Translating real-world problems into technical solutions
* Importance of simplicity in financial systems
* Backend structuring using Java

---

## What's next for this project

* Integration with real-time APIs
* Fraud detection system
* Dynamic pricing improvements
* Mobile application development
* Payment gateway integration
* Analytics dashboard

---

## System Overview

### Parametric Trigger Conditions

* Rainfall > 80 mm/day
* Temperature > 45°C
* AQI > 400

---

### Workflow

User Input → Risk → Premium → Monitoring → Trigger → Claim → Payout

---

## Prototype Demonstration

https://drive.google.com/file/d/1ZnsEKVEp_0kEKpRf2YEvhDFFtrH1g4eY/view?usp=sharing

---

## Built With

Java (Spring Boot), HTML, CSS, JavaScript, REST APIs, Rule-Based AI Logic, Event-Driven Architecture

---

## Team – Genius League

* Kavuru Gowthami (2300032925) – Team Lead
* Vuyyuru Kalyani (2300080325)
* Yannam Durga Bhavani (2300032092)

---
