# 🖥️ FCFS CPU Scheduling in C

This repository contains a C program that implements the **First Come First Serve (FCFS) CPU Scheduling Algorithm** used in Operating Systems.

---

## 📖 Description

FCFS is the simplest CPU scheduling algorithm where the process that arrives first gets executed first.

The program calculates:

✔ Waiting Time for each process  
✔ Turnaround Time for each process  
✔ Average Waiting Time  
✔ Average Turnaround Time  

The processes are executed based on their **Arrival Time (AT)**.

---

## 💻 Programming Language

🔹 C

---

## 📥 Input Format

n  
PID1 AT1 BT1  
PID2 AT2 BT2  
...  
PIDn ATn BTn  

Where:

n  → Number of processes  
PID → Process ID  
AT  → Arrival Time  
BT  → Burst Time  

### Example Input

5  
P1 0 4  
P2 1 5  
P3 2 1  
P4 3 2  
P5 10 3  

---

## 📤 Output

The program prints:

✔ Waiting Time of each process  
✔ Turnaround Time of each process  
✔ Average Waiting Time  
✔ Average Turnaround Time  

### Example Output

Waiting Time:  
P1 0  
P2 3  
P3 7  
P4 7  
P5 2  

Turnaround Time:  
P1 4  
P2 8  
P3 8  
P4 9  
P5 5  

Average Waiting Time: 3.80  
Average Turnaround Time: 6.80  

---

## ▶️ How to Run

### Compile the program

gcc fcfs.c

### Run the program

./a.out

---

## 👨‍💻 Author

**Joseph J.**  
🎓 BTech Computer Science and Engineering  
🏫 Vimal Jyothi Engineering College
