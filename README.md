
# Albion Agentic AIOps

An end-to-end **Agentic AIOps** portfolio project built around a realistic university network.  
This project demonstrates how **network telemetry, streaming data, RAG, graph reasoning, and autonomous agents** work together to detect, reason about, and mitigate network issues.

---

## Project Overview

Albion University operates:

- A **main campus** with three buildings
- A **remote campus** 20 miles away
- Multiple faculties and departments
- Internal and external servers
- VLAN-segmented networks
- Dynamic routing and DHCP

This project simulates:

- Network configurations
- Streaming telemetry via Kafka
- Real-time analytics with Spark
- Graph-based topology reasoning
- Agentic AI decision-making
- Automated remediation using Ansible

---

## Architecture


---

## Lab Structure

| Lab | Focus |
|-----|------|
| Lab 1 | Network topology & device configuration |
| Lab 2 | Kafka + Spark streaming pipeline |
| Lab 3 | Graph-based topology reasoning agent |
| Lab 4 | Agent decision logic, arbitration, coalition |
| Lab 5 | Multi-region agents, reputation, drift |
| Lab 6 | Production-grade autonomous agents |

---

## Technologies Used

**Networking**
- VLANs
- DHCP
- RIPv2
- Static routing

**Data & Streaming**
- Apache Kafka
- Apache Spark
- Delta Lake
- PostgreSQL

**AI & Agentic Systems**
- Python
- LangChain
- Vector databases (FAISS/PGVector)
- Graph reasoning (NetworkX)

**Automation**
- Ansible

---

## Repository Structure

labs/
lab1_network/
lab2_streaming/
lab3_graph_agent/
lab4_agent_reasoning/
lab5_multi_region/
lab6_production/

agents/
pipelines/
rag/
automation/
data/
ci-cd/