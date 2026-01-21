# Autonomous Emergency Response & Preparedness Agent

## Problem Statement
Residential societies often lack structured emergency preparedness systems. Emergency response relies heavily on manual decision-making, leading to delays, panic, and increased risk to life and property during critical situations such as fires, medical emergencies, or gas leaks.

---

## Solution Overview
This project presents an **Autonomous Emergency Response & Preparedness Agent**, a multi-agent AI system designed to handle emergencies end-to-end without manual intervention.

The system autonomously:
- Detects emergency situations
- Assesses severity and risk levels
- Executes appropriate response actions
- Provides real-time safety and evacuation guidance
- Suggests preparedness improvements after incidents

---

## Agentic AI Architecture
The system follows a modular, multi-agent architecture:

Emergency Trigger  
→ Detection Agent  
→ Decision Agent  
→ Sanity Check Agent  
→ Action Agent  
→ Guidance & Preparedness Agents  

Each agent performs an independent role, enabling autonomous and adaptive decision-making.

---

## Key Features
- Fully autonomous emergency response
- Multi-agent decision-making system
- Built-in sanity checks for safety and reliability
- Adaptive behavior based on emergency type and severity
- Preparedness recommendations for future readiness

---

## Sanity Check Mechanism
Before executing any response, the system validates decisions to ensure:
- Emergency type is valid
- Severity aligns with response actions
- Unsafe or illogical actions are prevented

If a sanity check fails, the system halts execution for safety.

---

## Technologies Used
- Python  
- Jupyter Notebook (.ipynb)  
- Agent-based architecture  
- Rule-based logic with reasoning  

---

## How to Run
1. Open the Jupyter Notebook file.
2. Run all cells sequentially.
3. Use the `run_emergency_scenario()` function to simulate different emergencies.

Example:
```python
run_emergency_scenario("Fire")
