# GENIUS LEAGUE

## AI-Powered Parametric Insurance for Income Protection of Gig Delivery Workers

### A Real-Time, Event-Driven System for Automated Risk Assessment, Weekly Pricing, and Instant Income Compensation in India’s Gig Economy

---

## 1. Problem Landscape

India’s gig economy delivery workforce operates on a highly dynamic, daily-income model where earnings are directly dependent on active working hours. External disruptions such as extreme weather conditions, high pollution levels, and sudden regional restrictions can immediately halt operations, leading to unavoidable income loss.

These disruptions are frequent and unpredictable, yet there is no lightweight, accessible insurance solution designed specifically to protect gig workers from short-term income shocks. Existing systems are either slow, manual, or not tailored to the nature of gig-based employment.

This creates a critical need for a real-time, automated income protection mechanism.

---

## 2. Solution Overview

This project proposes an **AI-powered parametric insurance platform** that provides instant income protection through automated decision-making.

Instead of traditional claim-based systems, this solution uses **event-driven parametric triggers** to detect disruptions and initiate payouts without manual intervention.

Key capabilities include:

* Real-time monitoring of environmental and operational conditions
* Automated claim triggering based on predefined thresholds
* Instant payout calculation based on income loss
* Weekly subscription model aligned with gig worker earnings

---

## 3. Target Persona

### Delivery Partner Profile

* Works in food, grocery, or e-commerce delivery
* Operates in urban, high-demand environments
* Earns income per delivery task
* Highly dependent on environmental conditions

### Key Challenges

* Work disruption during heavy rainfall or extreme temperatures
* Reduced productivity due to pollution exposure
* Inaccessibility of delivery zones during restrictions
* No financial fallback during inactive periods

---

## 4. Disruption Intelligence Model

The system continuously evaluates external factors that impact worker productivity.

### Environmental Factors

* Heavy rainfall and waterlogging
* Extreme temperature conditions
* Hazardous air quality levels

### Social and Operational Factors

* Government-imposed curfews
* Local strikes and restrictions
* Delivery zone closures

---

## 5. Parametric Trigger Framework

### Example Trigger Conditions

* Rainfall > 80 mm/day
* Temperature > 45°C
* Air Quality Index > 400

When these thresholds are exceeded, the system automatically triggers compensation.

---

## 6. Weekly Pricing Model

### Mathematical Logic

Premium calculation:

$$
Premium = Base + (RiskScore \times RiskFactor)
$$

Where:

* Base = ₹50
* RiskFactor = ₹10
* RiskScore is derived from AQI, temperature, and rainfall

Payout calculation:

$$
Payout = DailyIncome \times LossFactor
$$

Where:

* LossFactor = 0.7

---

### Example

* Daily Income = ₹800
* Risk Score = 5

$$
Premium = 50 + (5 \times 10) = ₹100
$$

$$
Payout = 800 \times 0.7 = ₹560
$$

---

## 7. System Workflow

1. User inputs location and income
2. Risk score is calculated
3. Weekly premium is generated
4. System monitors external data
5. Trigger condition detected
6. Claim initiated automatically
7. Instant payout processed

---

## 8. Intelligent Processing (Java-Based)

* Risk score calculation using environmental parameters
* Dynamic premium adjustment
* Fraud detection (planned):

  * Duplicate claim detection
  * Location validation

---

## 9. Technology Stack

* Backend: Java (Spring Boot)
* Frontend: HTML, CSS, JavaScript
* APIs: REST APIs
* Data: Environmental APIs (mock/real-time)

---

## 10. Prototype Scope (Phase 1)

* Risk calculation
* Premium generation
* Trigger detection
* Automated payout
* End-to-end simulation

---

## 11. Development Roadmap

### Phase 1

* Research
* Design
* Prototype

### Phase 2

* API integration
* Claim automation

### Phase 3

* Fraud detection
* Dashboard

---

## 12. Demonstration

https://drive.google.com/file/d/1ZnsEKVEp_0kEKpRf2YEvhDFFtrH1g4eY/view?usp=sharing

---

## 13. Expected Impact

* Financial protection for gig workers
* Instant compensation
* Reduced uncertainty
* Scalable model

---

## 14. Team – Genius League

* Kavuru Gowthami (2300032925) – Team Lead
* Vuyyuru Kalyani (2300080325)
* Yannam Durga Bhavani (2300032092)

---

## 15. Markdown & LaTeX Formatting Reference

### Markdown

**bold text**
*italic text*

[Example Link](http://foo.bar)

![Alt text](/path/to/img.jpg)

---

### Code Block Example

```ruby
puts "Hello World!"
```

---

### LaTeX Examples

Inline: ( Premium = Base + RiskScore \times RiskFactor )

Block:

$$
Payout = DailyIncome \times 0.7
$$

---
