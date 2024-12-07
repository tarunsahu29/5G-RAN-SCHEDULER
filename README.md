# 📶 **5G RAN Scheduling Simulation**

---

## 👥 **Group Information**

- **Group Number**: 56
- **Group Members**:
  1. **Tarun Manoj Kumar Sahu**
     - **ID**: 202151171
     - **Role**: Lead Developer
  2. **Member 2**
     - **ID**: 202151172
     - **Role**: Data Analyst
  3. **Member 3**
     - **ID**: 202151173
     - **Role**: Algorithm Specialist
  4. **Member 4**
     - **ID**: 202151174
     - **Role**: Visualization Expert
  5. **Member 5**
     - **ID**: 202151175
     - **Role**: Report Generator

---

## 📜 **Overview**

The **5G RAN Scheduling Simulation** project replicates and evaluates the behavior of various scheduling algorithms used in **5G Radio Access Networks (RANs)**. This simulation compares multiple strategies for bandwidth allocation while considering:

- **Quality of Service (QoS)** requirements.
- **Fairness** in bandwidth distribution.

It provides **graphical** and **textual reports** to assess the performance of each scheduling algorithm, enabling detailed evaluations of fairness and efficiency.

---

## ✨ **Features**

### 🛠 **Scheduling Algorithms**

This simulation includes the following scheduling strategies:

- 🔄 **Round Robin Scheduling**
- 🕒 **Shortest Job First (SJF)**
- ⭐ **Priority-based Scheduling**
- ⚖️ **Weighted Proportional Fair Scheduling**
- ⏳ **Earliest Deadline First (EDF)**
- 📶 **Maximal Scheduling with Interference Mitigation**
- 📋 **Queue-based Scheduling**

### 📊 **Fairness Metrics**

- Evaluates fairness for each algorithm using **variance in allocated bandwidth**.
  - 🔹 **Lower variance** → Fairer allocation.

### 🔀 **Dynamic User Generation**

- Generates users dynamically with randomized:
  - Bandwidth requests.
  - QoS levels (Low, Medium, High).
  - Priorities.

### 📈 **Visual Reports**

- Graphical plots to visualize:
  - **QoS Distribution** across users.
  - **Bandwidth Allocation** for each algorithm.

### 📋 **Textual Reports**

- A summary report includes:
  - Detailed bandwidth allocation for each algorithm.
  - **Fairness comparison** of algorithms based on metrics.

### 📁 **Output Folder**

- Saves all reports and plots:
  - **Images** in `output/`
  - **Summary Text Report** as `simulation_results.txt`

---

## 📥 **Installation**

### 🖥 **Prerequisites**

- **Python 3.7 or higher** is required.
- The following Python libraries must be installed:
  - `pandas` - For data handling and analysis.
  - `matplotlib` - For generating graphs and plots.
  - `numpy` - For numerical calculations and fairness metrics.

### ⚙️ **Install Dependencies**

Run the following command in your terminal to install all required packages:

```bash
pip install pandas matplotlib numpy
```
