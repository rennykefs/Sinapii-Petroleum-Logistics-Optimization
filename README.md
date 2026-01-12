# Sinapii-Petroleum-Logistics-Optimization

## 1. Project Overview
Fuel distribution in Kenya largely follows historical routing decisions, which often leads to sub-optimal logistics performance. This project analyzes petroleum logistics operations and applies data-driven route optimization to reduce distance traveled, fuel costs, and delivery time.
The case study models fuel movement from coastal and inland depots (Mombasa, Nairobi, Kisumu) to downstream delivery destinations, identifying inefficiencies and proposing optimized routing strategies.

## 2. Business Problem
Petroleum logistics operators face challenges such as:
- Inefficient routing based on legacy practises
- High fuel consumption and transport costs
- Poor fleey utilization
- Limited Visibility into cost leakeage per route

These inefficiencies directly reduce margins in fuel distribution operations.

## 3. Project Objectives 
- Identify sub-optimal delivery routes
- Calculate real-world road distances using a routing API
- Demonstrate how optimization models can support operational decisions

## 4. Technical Approach
### 4.1 Data Preparation
- Depot locations (latitude, longitude)
- Delivery destinations
- Vehicle capacity assumptions


Sensitive or proprietary data is simulated and anonymized to reflect real petroleum logistics operations.

### 4.2 Distance Calculation
Instead of straight-line distances, the project integrates a routing / distance API to compute:
- Actual drivable road distance
- Depot: destination distance matrix

This makes the optimization realistic and deployable 

### 4.3 Impact Analysis
Evalauted Improvements across:
- Distance and reliability
- Depot trip per share
- On time delivery rate
- Depot level performance
- Time of Day Delivery


## 5. Project Architecture
Depot & Destination Coordinates

        ↓
Routing / Distance API

        ↓
Distance & Cost Matrix

        ↓
Route Optimization Model

        ↓
Business Insights & Visualization

## 6. Security and API keys
- Api keys are not commited
- Script containing API key not uploaded

## 7. Skills Demonstrated 
- Petroleum logistics domain understanding
- Supply Chain Analytics
- Route optimization and operations research
- Api Intergration
- Python Data analysis
- Business focused data story telling

## Author
Reinhardt Kefa
Petroleum Engineer| ML Engineer| Data Scientist 






