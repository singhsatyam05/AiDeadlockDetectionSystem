🔒 Deadlock Detection System (OS Project)
📌 Overview

This project is a Deadlock Detection System built using Python (Tkinter GUI) that simulates a Resource Allocation Graph (RAG). It allows users to visually create processes, resources, and their relationships (allocation & request edges) to analyze system states and detect deadlocks.

The system is designed as an educational tool for Operating Systems, helping users understand how deadlocks occur and how they can be resolved.

🚀 Features

🧩 Graphical User Interface (GUI) using Tkinter

🔄 Dynamic Resource Allocation Graph (RAG) simulation

➕ Add processes and resources with multiple instances



🔗 Create:

Request edges (Process → Resource)

Allocation edges (Resource → Process)

🧠 Deadlock Detection Algorithm implementation



⚠️ Identifies:

Deadlocked processes

Involved resources

📖 Deadlock Resolution Guide with suggestions

💾 Save & Load graph state using JSON

↩️ Undo / Redo functionality

🖱️ Drag-and-drop node positioning



🛠️ Technologies Used

Python

Tkinter (GUI)

Data Structures (Dictionary, Defaultdict, Sets)

Operating System Concepts (Deadlock Detection, RAG)



⚙️ How It Works

Create Processes (P1, P2, …) and Resources (R1, R2, …)

Add:

Request edges → when a process requests a resource

Allocation edges → when a resource is assigned

Run Deadlock Detection Algorithm:

Uses available resources and current allocations

Simulates process execution

Detects unsafe states

Displays:

Deadlocked processes

Resources causing deadlock

Provides a step-by-step resolution guide



🧠 Algorithm Used

The project uses a Deadlock Detection Algorithm similar to Banker’s Algorithm logic:

Maintains:

Available resources

Allocation matrix

Request matrix

Iteratively checks if processes can finish

Processes that cannot finish → Deadlocked



📂 Project Structure

ResourceAllocationGraph → Core logic (processes, resources, detection)

RAGSimulator → GUI and user interaction

JSON support → Save/Load system state





👨‍💻 Contributors

Satyam Kumar Singh

HArishvardhan



📌 Future Improvements

Add Banker’s Algorithm (Deadlock Avoidance)

Improve UI with animations

Add step-by-step execution visualization

Export graph as image
