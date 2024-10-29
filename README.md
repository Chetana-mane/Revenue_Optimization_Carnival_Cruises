
# Carnival Cruises: World Cruise 2025 Revenue Management Case Study



---

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Carnival Corporation Overview](#carnival-corporation-overview)
4. [Importance of Revenue Optimization](#importance-of-revenue-optimization)
5. [Demand and Scenario Planning for 2025](#demand-and-scenario-planning-for-2025)
6. [Optimal Passenger Allocation for Revenue Maximization](#optimal-passenger-allocation-for-revenue-maximization)
7. [Cabin Type Allocation Strategy](#cabin-type-allocation-strategy)
8. [Estimating Cancellation Rates](#estimating-cancellation-rates)
9. [Overbooking Strategies](#overbooking-strategies)
10. [Recommendations & Conclusions](#recommendations--conclusions)

---

## Introduction

The purpose of this project is to apply revenue management and optimization strategies to maximize profits for Carnival Cruises' World Cruise 2025, using historical data and demand projections. By analyzing passenger demand, cabin allocation, and overbooking strategies, we develop actionable insights for enhancing revenue and occupancy rates across key routes.

---

## Objectives

- **Analyze Demand Data**: Extract insights from historical data and updated demand projections.
- **Optimize Passenger Allocation**: Apply linear programming techniques to allocate passengers optimally and increase revenue.
- **Minimize Revenue Risks**: Develop overbooking strategies and mitigate potential cancellations.
- **Maximize Revenue Growth**: Implement strategies to increase revenue, reaching projected goals.

---

## Carnival Corporation Overview

Carnival Corporation is one of the world’s largest leisure travel companies, with over 100 ships operating under nine major cruise brands:

| Brand                       | Description                     |
|-----------------------------|---------------------------------|
| **AIDA**                    | German cruise line              |
| **Carnival Cruise Lines**   | Popular North American brand    |
| **Costa**                   | Italian cruise line             |
| **Cunard**                  | Luxury cruise line              |
| **Holland America Line**    | Premium cruise line             |
| **Princess Cruises**        | Family-friendly cruise line     |
| **P&O Cruises Australia**   | Australian cruise line          |
| **P&O Cruises UK**          | Historic UK cruise line         |
| **Seabourn**                | Ultra-luxury cruise line        |

---

## Importance of Revenue Optimization

Effective revenue optimization is essential for ensuring Carnival Corporation's financial sustainability. For the 2025 World Cruise, focusing on **P&O Cruises UK**, this involves:
- Tailoring pricing, cabin allocation, and marketing strategies based on demand.
- Analyzing demand fluctuations for popular routes, including Southampton, Dubai, Australia, Singapore, and San Francisco.

---

## Demand and Scenario Planning for 2025

The project anticipates increased tourism in key regions, notably:

- **Dubai** (28%) – Noted for festivals and as a central hub.
- **San Francisco** (33%) – Known for cultural and tech tourism.
- **Australia** (22%) – Popular for natural attractions.
- **Singapore** (20%) – Hosting international events like the World Aquatics Championships.

### Projected Demand Increases
![image](https://github.com/user-attachments/assets/95532ed7-8dfb-4cff-a11d-7ad02c6e878a)


Projected demand increases were incorporated into our scenario planning to enhance route profitability and adjust cabin allocations.
![image](https://github.com/user-attachments/assets/05867197-e214-47b7-8bb2-ca8c2a5c2f4e)

---

## Optimal Passenger Allocation for Revenue Maximization

1. **Demand Analysis**: Historical and projected data were utilized to adjust passenger allocations dynamically based on route popularity.
2. **Linear Programming Approach**: Using the PULP library, we set up a linear programming model to:
   - Define decision variables per route.
   - Formulate the objective function for maximizing total revenue.
   - Apply constraints based on the maximum number of passengers and projected tourism growth.
3. **Comparative Analysis**: The approach allowed us to boost occupancy rates from an average of 93-95% in 2022 to over 97% in most routes for 2025.
4. **Revenue Outcomes**: Increased revenue from £20.6M to £21.5M, demonstrating the efficacy of optimized allocation.
![image](https://github.com/user-attachments/assets/00512e3e-eebc-40b5-a442-0d4ad3577c35)


![image](https://github.com/user-attachments/assets/531707bd-6b5e-4d70-85c2-8409bdc3c2f3)

---

## Cabin Type Allocation Strategy

### Methodology
1. **Booking Percentage Calculation**: Calculated booking percentages for each cabin type (Balcony, Suite, Oceanview, Inside) based on historical demand.
2. **Passenger Allocation**: Using 2025 demand data, passengers were allocated across cabin types. 

#### Example Allocation for SOU-SOU Route
| Cabin Type  | Allocation |
|-------------|------------|
| Balcony     | 485        |
| Suite       | 93         |
| Oceanview   | 108        |
| Inside      | 125        |

### Results
This cabin allocation approach maximized revenue by ensuring high occupancy for all cabin types, tailored per route.
![image](https://github.com/user-attachments/assets/ca5b49b2-1cb3-4933-9a4d-c416189e66a1)



---
## Estimating Cancellation Rates

Using historical data:
- **Cancellation Rates Calculation**: Identified average cancellation rates across routes, e.g., SOU-HKG (0.40), AKL-HKG (0.50).
- **Revenue Safeguards**: Developed strategies to mitigate revenue impact from cancellations, such as dynamic pricing and customer retention incentives.

### Key Insights
- **Customer Targeting**: Focus on marketing to low-cancellation sectors.
- **Operational Planning**: Adjust staffing and resource allocation based on expected cancellation rates to optimize costs.

---

## Overbooking Strategies

**Formula**: Expected denied customers = `(Capacity / Probability of show) * Probability of denial`

#### Example Calculation
- **Capacity**: 313
- **Probability of Show**: 75%
- **Probability of Denial**: 20%

### Assumptions
- Stable booking and cancellation patterns.
- Moderate overbooking for routes with increased demand (e.g., **SYD**, **DXB**).
- Managed overbooking levels for suites to preserve premium service quality.

### Risks and Rewards
- **Rewards**: Increased revenue, optimized capacity, higher profitability.
- **Risks**: Customer dissatisfaction, potential reputational risk, and associated compensation costs.

---

## Recommendations & Conclusions

### Key Recommendations
1. **Cabin Configuration Optimization**: Use upper-beds for expanded capacity, maximizing revenue per trip.
2. **Comprehensive Water Activities Package**: Offer packages that include diving, aquatic sports, and local experiences to increase onboard spending.
3. **Enhanced Revenue via Local Partnerships**: Collaborate with tourism entities for co-branded events along the cruise route.
4. **Leverage Technology**: Incorporate wearable tech, VR, AR, AI chatbots, and predictive AI for enhanced passenger experiences and operational efficiency.

### Conclusion

By strategically managing demand, optimizing cabin allocation, and implementing overbooking and cancellation management strategies, Carnival Cruises can achieve an estimated total revenue of £21.5 million in 2025, reflecting a growth of approximately £1 million over the previous year. The approach ensures both financial sustainability and an enriched passenger experience.



---

> **Note**: This repository includes all project files, Python scripts, data analysis, and insights used in the 2025 World Cruise revenue management study.

