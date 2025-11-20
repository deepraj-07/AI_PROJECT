# 🧠 **AI Smart City Experiments – 10 Project Collection**

This repository contains **10 AI-based simulation experiments**, each demonstrating intelligent agents, optimization algorithms, environment modeling, and real-world smart-city logic.

Each project includes:

- ⭐ **Problem Description**  
- 🚀 **Solution Concept**  
- 🧮 **Algorithm Used**  
- 🤖 **AI / Agent Concepts**  
- 🟦 **PEAS Model** (Performance, Environment, Actuators, Sensors)

---

# 🔵 **1. Traffic Light Optimizer**

### **Problem Description**  
Simulates 4 adaptive traffic lights to minimize vehicle waiting time.

### **Solution Concept**  
Each signal is an agent checking queue length, timers, and neighbors.

### **Algorithm Used**  
**Rule-Based Adaptive Control**  
- Long queue → GREEN  
- Max green time reached → RED  

### **AI Concepts**  
- Multi-agent coordination  
- Perception → queue length  
- Action → signal switching  

### **PEAS**  
**P:** Waiting time  
**E:** Intersection  
**A:** Traffic lights  
**S:** Queue sensors  

---

# 🟢 **2. Garbage Collection Routing**

### **Problem Description**  
Find shortest path for truck visiting multiple garbage points.

### **Solution Concept**  
Choose nearest unvisited point repeatedly.

### **Algorithm Used**  
- Greedy Nearest Neighbor  
- Dijkstra Shortest Path  

### **AI Concepts**  
- Graph search  
- Route optimization  

### **PEAS**  
**P:** Total distance  
**E:** City road graph  
**A:** Vehicle  
**S:** Distance matrix  

---

# 🟣 **3. Smart Parking Allocation**

### **Problem Description**  
Assign incoming vehicles to the nearest free parking spot.

### **Solution Concept**  
Central allocator selects the closest free slot.

### **Algorithm Used**  
**Greedy Assignment Algorithm**

### **AI Concepts**  
- Constraint satisfaction  
- Resource allocation  

### **PEAS**  
**P:** Walking distance  
**E:** Parking grid  
**A:** Spot allocator  
**S:** Slot availability  

---

# 🟠 **4. Energy Distribution Agents**

### **Problem Description**  
Distribute limited electricity among multiple buildings.

### **Solution Concept**  
Allocate energy proportionally to demand.

### **Algorithm Used**  
**Proportional Allocation Formula**  
```
alloc[i] = demand[i] / total_demand * supply
```

### **AI Concepts**  
- Distributed decision-making  
- Load balancing agents  

### **PEAS**  
**P:** Load variance  
**E:** Microgrid  
**A:** Energy controllers  
**S:** Demand sensors  

---

# 🔵 **5. Water Supply Optimizer**

### **Problem Description**  
Fair distribution of limited water to households.

### **Solution Concept**  
Proportional distribution with constraints.

### **Algorithm Used**  
**Constraint-Based Proportional Distribution**

### **AI Concepts**  
- Optimization  
- Fair division  

### **PEAS**  
**P:** Demand satisfaction  
**E:** Water network  
**A:** Valves  
**S:** Demand meters  

---

# 🔴 **6. Emergency Response Dispatchers**

### **Problem Description**  
Assign emergency vehicles to incidents with minimal delay.

### **Solution Concept**  
Pick nearest available ambulance/fire truck.

### **Algorithm Used**  
**Greedy Nearest Neighbor**

### **AI Concepts**  
- Reactive agents  
- Time-critical decision making  

### **PEAS**  
**P:** Response time  
**E:** City map  
**A:** Emergency vehicles  
**S:** Incident coordinates  

---

# 🟡 **7. Pollution Control Monitors**

### **Problem Description**  
Monitor pollution and mitigate hotspots in a city grid.

### **Solution Concept**  
Simulate diffusion and reduce values above threshold.

### **Algorithm Used**  
- Grid Averaging  
- Threshold Mitigation  

### **AI Concepts**  
- Distributed sensing  
- Environmental modeling  

### **PEAS**  
**P:** Pollution reduction  
**E:** 2D grid  
**A:** Mitigation systems  
**S:** Pollution sensors  

---

# 🟤 **8. Streetlight Energy Saver**

### **Problem Description**  
Streetlights brighten on motion detection and dim otherwise.

### **Solution Concept**  
Each pole behaves as an event-driven agent.

### **Algorithm Used**  
**State Machine:**  
BRIGHT ↔ DIM based on motion/timeout

### **AI Concepts**  
- Sensor-based AI  
- Event-driven automation  

### **PEAS**  
**P:** Energy saved  
**E:** Street at night  
**A:** Light intensity controller  
**S:** Motion detectors  

---

# 🚌 **9. Smart Bus Routing**

### **Problem Description**  
Optimize bus arrival frequency to reduce passenger wait time.

### **Solution Concept**  
Simulate queues and test multiple frequencies.

### **Algorithm Used**  
**Queueing Theory:**  
```
Avg Wait Time = 1 / (2 × frequency)
```

### **AI Concepts**  
- Demand modeling  
- Queue simulation  

### **PEAS**  
**P:** Passenger waiting time  
**E:** Bus route  
**A:** Bus dispatching  
**S:** Demand readings  

---

# ♻️ **10. Waste Segregation AI**

### **Problem Description**  
Classify waste items automatically for smart recycling.

### **Solution Concept**  
Use Random Forest classifier for synthetic features.

### **Algorithm Used**  
**Random Forest (Multiple Decision Trees)**

### **AI Concepts**  
- Supervised ML  
- Classification  

### **PEAS**  
**P:** Accuracy  
**E:** Sorting belt  
**A:** Sorting arm  
**S:** Feature extractor/camera  

---

# 🎯 **Summary**

These 10 experiments demonstrate:

- Intelligent agent design  
- Smart city automation  
- Optimization & ML algorithms  
- Interactive simulations (Pygame / Matplotlib)  
- Real-world AI decision-making  

---
>> **LINK** : https://shorturl.at/dI0tb
