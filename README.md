# Distributed IoT Data Aggregation

**Author:** [Your Name]  
**Date:** [Date]  
**Repository:** distributed-iot-data-aggregation  
**Keywords:** IoT, Data Aggregation, Consensus-based, Smart City, SDG9, SDG11

---

## 📘 Project Overview

IoT devices deployed across smart cities generate large volumes of streaming sensor data. Efficient aggregation of this data is critical for analytics, decision-making, and sustainable infrastructure. Traditional centralised aggregation models can suffer from bottlenecks, single points of failure, and high communication overhead.

This project proposes and evaluates a **consensus-based distributed aggregation system** where nodes collaborate to aggregate data locally, reducing network load and improving resilience. A Python simulation compares this model with a baseline centralised aggregation in terms of message overhead, latency (rounds to converge), and accuracy.

---

## 🎯 Objectives

- Design a distributed aggregation architecture using consensus algorithms.  
- Implement simulation code in Python for nodes, cluster heads, and a sink.  
- Generate or use sensor readings, simulate message exchanges and aggregation.  
- Compare with centralised aggregation approach.  
- Visualise results and draw insights for smart city deployments.  
- Connect findings to SDG 9 (Industry, Innovation & Infrastructure) and SDG 11 (Sustainable Cities & Communities).

---

## 🛠️ Getting Started

### Requirements  
- Python 3.7+  
- Libraries: `numpy`, `pandas`, `networkx`, `matplotlib`, `seaborn`

```bash
pip install numpy pandas networkx matplotlib seaborn
