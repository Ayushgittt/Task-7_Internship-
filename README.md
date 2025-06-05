# Task-7_Internship-

# 🚀 MERN Stack Application with Docker Compose + Netdata Monitoring

This project demonstrates how to deploy a **MERN (MongoDB, Express.js, React, Node.js)** application using **Docker Compose**, and monitor its resource usage and container metrics using **Netdata**.

---

## 🧩 Project Structure

- **Frontend** - React.js
- **Backend** - Node.js + Express
- **Database** - MongoDB
- **Monitoring** - Netdata (via Docker)

---

## 🐳 Step 1: Start MERN Application using Docker Compose

We use Docker Compose to containerize and orchestrate the entire MERN stack. All services are defined in a `docker-compose.yml` file.

![0](https://github.com/user-attachments/assets/07fe2b44-0389-474b-9c17-58311fce0722)
![3](https://github.com/user-attachments/assets/723c1bed-4d7c-4daf-98d9-99368812ea6f)

---
### 📈 Step 2: Start Netdata Container

![1](https://github.com/user-attachments/assets/8e7d261c-ad8f-4500-a3d1-2abfd9e5c282)

---

### 📊 Step 3: Monitor System Metrics with Netdata
The Netdata dashboard gives real-time visibility into:
✅ CPU Usage
✅ Memory Usage
✅ Disk I/O
✅ System Uptime
![4](https://github.com/user-attachments/assets/09ae4c4c-f562-438a-a844-f38b1917fd70)
![4](https://github.com/user-attachments/assets/511d7445-b6d2-41b1-b8c1-a44e10d065e0)
![6](https://github.com/user-attachments/assets/dc3f08c2-18d6-46b3-aa7a-aca94ebc5eef)
![7](https://github.com/user-attachments/assets/d552045f-24c6-4cf5-b3f9-e6cde9edf772)

---
### 🐋 Step 4: Monitor Docker Containers
Netdata automatically detects Docker containers and provides:
 - Container-level CPU/memory/network stats
 - Container health and uptime graphs
 - Process usage inside containers
![9](https://github.com/user-attachments/assets/d3a1764c-da24-4a8e-bc44-44ccc9eb652c)

---
### 🔍 Step 5: Anomaly Detection in Netdata
Netdata provides Anomaly Detection, a machine-learning-based system that learns normal system behavior and flags deviations. It’s useful for detecting:

- Abnormal CPU/memory usage
- Sudden spikes in network traffic
- Container misbehavior
- 🧠 How it works:
     - Learns from past system behavior
     - Displays anomaly scores over time
     - Helps in proactive alerting and troubleshooting
![8](https://github.com/user-attachments/assets/c1816e71-c5e4-4e44-8989-941cf75f017d)

---
### 📁 Step 6: Extract Logs from Netdata
![10](https://github.com/user-attachments/assets/e13fa1a7-3f11-4c1c-8f2f-636d83f19cfa)



