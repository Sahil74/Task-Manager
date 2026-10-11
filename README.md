# Task-Manager

An interactive Excel operations dashboard designed to track team productivity, cross-departmental workload distribution, and task execution status across project lifecycles.

---
![Task Manager Dashboard Overview](DashBoard.PNG)


---

## 🔍 Key Insights & Findings

* **Execution Bottleneck:** Over **45%** of all logged work items (82 out of 179) are currently stuck in the *In Progress* stage, pointing to a potential choke point in task completion velocity[cite: 1].
* **Workload Friction:** Active task completion lags behind total intake, with combined inactive items (**47 tasks** marked as *Not Started* or *On Hold*) closely competing with total completed deliverables (51 tasks)[cite: 1].
* **Capacity Imbalance:** Operational volume is unevenly distributed across departments, leading to heavy active task loads for key individual assignees (such as Isabella Martin and Priya Shah)[cite: 1].

---

### Visual Breakdown
1. **Work Items by Status (Bar Chart):** Tracks throughput across *Completed*, *In Progress*, *Not Started*, and *On Hold* stages.
2. **Workload Volume (Donut Chart):** Visualizes task volume across core units including *Customer Experience*, *Finance*, *Marketing*, *Operations*, and *People & Culture*.
3. **Top Assignees Load Breakdown (Stacked Bar Chart):** Highlights individual capacity, completion ratios, and status distribution across key team members.

---

## 📁 Dataset Schema

| Field Name | Description |
| :--- | :--- |
| `Work Item ID` | Unique tracking identifier |
| `Work Item` | Description of task or deliverable |
| `Department` | Functional team responsible |
| `Assigned To` | Designated team lead |
| `Opened Date` | Task creation timestamp |
| `Target Date` | Expected completion date |
| `Task Duration (days)` | Total calculated turnaround time |
| `Progress Status` | Current state (`Completed`, `In Progress`, `Not Started`, `On Hold`)[cite: 1] |
| `Overdue Flag` | Missed deadline indicator |
| `Latest Note` | Recent comments or blocker details |

---

## 🛠️ Tools Used

* **Microsoft Excel:** Data cleanup, formula calculations, and interactive dashboard design.
