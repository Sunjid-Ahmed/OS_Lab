# 📌 OS_Lab

## 🧠 Priority Scheduling Algorithm (C Implementation)

This repository contains an implementation of the **Priority CPU Scheduling Algorithm (Non-Preemptive)** written in C. It is designed for Operating Systems lab practice.

---

## 📖 What is Priority Scheduling?

Priority Scheduling is a CPU scheduling technique where each process is assigned a priority. The CPU executes the process with the highest priority first.

- Lower priority number ⇒ Higher priority  
- Non-preemptive ⇒ Once a process starts, it runs until completion  

---

## ⚙️ Features

- Non-preemptive scheduling  
- Priority-based execution  
- Tie-breaking rules:
  - Arrival Time (AT)  
  - Burst Time (BT)  
- Calculates:
  - Completion Time (CT)  
  - Turnaround Time (TAT)  
  - Waiting Time (WT)  

---

## 🧾 Process Structure

| Field | Description |
|------|-------------|
| ID   | Process ID |
| AT   | Arrival Time |
| BT   | Burst Time |
| PR   | Priority |
| CT   | Completion Time |
| TAT  | Turnaround Time |
| WT   | Waiting Time |

---

## 🧮 Scheduling Logic

Processes are sorted using the following order:

1. Priority (ascending)  
2. Arrival Time (ascending)  
3. Burst Time (ascending)  

---

## ▶️ Sample Output

```
Process AT  BT  PR  CT  TAT WT
P1      3   2   1   5   2   0
P4      3   3   1   8   5   2
P2      5   1   3   9   4   3
P3      6   7   4   16  10  3
```

---

## 🚀 How to Run

### Compile:
```
gcc priority.c -o priority
```

### Run:
```
./priority
```

---

## 👨‍💻 Author

Sunjid Ahmed Siyem  
CSE Student | Cyber Security Enthusiast  

---

## 📚 License

This project is for educational purposes only.
