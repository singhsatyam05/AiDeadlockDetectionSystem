# 🔒 Deadlock Detection System (OS Project)

## 📌 Overview  
This project is a **Deadlock Detection System** built using **Python (Tkinter GUI)** that simulates a **Resource Allocation Graph (RAG)**. It allows users to visually create processes, resources, and their relationships (allocation & request edges) to analyze system states and detect deadlocks.

The system is designed as an **educational tool for Operating Systems**, helping users understand how deadlocks occur and how they can be resolved.

---

## 🚀 Features  

- 🧩 Graphical User Interface (GUI) using Tkinter  
- 🔄 Dynamic Resource Allocation Graph (RAG) simulation  
- ➕ Add processes and resources with multiple instances  

### 🔗 Edge Creation  
- Request edges (**Process → Resource**)  
- Allocation edges (**Resource → Process**)  

### 🧠 Deadlock Detection  
- Implements a deadlock detection algorithm  
- Identifies:
  - Deadlocked processes  
  - Involved resources  

### 📖 Additional Functionalities  
- Deadlock resolution guide with suggestions  
- 💾 Save & Load graph state using JSON  
- ↩️ Undo / Redo functionality  
- 🖱️ Drag-and-drop node positioning  

---

## 🛠️ Technologies Used  

- **Python**  
- **Tkinter (GUI)**  
- **Data Structures** (Dictionary, Defaultdict, Sets)  
- **Operating System Concepts** (Deadlock Detection, RAG)  

---

## ⚙️ How It Works  

1. Create **Processes (P1, P2, …)** and **Resources (R1, R2, …)**  
2. Add:
   - Request edges → when a process requests a resource  
   - Allocation edges → when a resource is assigned  
3. Run the **Deadlock Detection Algorithm**:
   - Uses available resources and current allocations  
   - Simulates process execution  
   - Detects unsafe states  
4. Displays:
   - Deadlocked processes  
   - Resources causing deadlock  
5. Provides a **step-by-step resolution guide**  

---

## 🧠 Algorithm Used  

The project uses a **Deadlock Detection Algorithm inspired by Banker’s Algorithm**:

- Maintains:
  - Available resources  
  - Allocation matrix  
  - Request matrix  
- Iteratively checks if processes can complete execution  
- Processes that cannot complete → **Deadlocked**  

---

## 📂 Project Structure  

- `ResourceAllocationGraph` → Core logic (processes, resources, detection)  
- `RAGSimulator` → GUI and user interaction  
- JSON support → Save/Load system state  

---

## 👨‍💻 Contributors  

- **Satyam Kumar Singh**  
- **Harishvardhan**  

---

## 📌 Future Improvements  

- Add Banker’s Algorithm (Deadlock Avoidance)  
- Improve UI with animations  
- Add step-by-step execution visualization  
- Export graph as image  
