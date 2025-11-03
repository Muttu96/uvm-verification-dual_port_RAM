# 🎯 UVM-Based SoC-Level Verification of Dual Port RAM  

This repository contains the **UVM-based SoC-level verification environment** developed to verify a **Dual Port RAM** — a memory module capable of **simultaneous read and write operations** through two independent ports.  

The project focuses on ensuring **functional correctness**, **data integrity**, and **conflict handling** in concurrent memory access scenarios, which are critical in modern SoC designs.  

---

### 🔍 What’s Verified  

✅ **Dual Port RAM Functionality**  
- Independent read and write operations on both ports  
- Data integrity verification for even, odd, single, and <10 address locations  
- Handling of read-write and write-write collision scenarios  
- Correct reset and re-initialization of memory contents  
- Proper synchronization between concurrent memory accesses  

---

### 🔹 Verification Methodology  
- Developed a **UVM-based modular testbench** with components:  
  - Driver  
  - Monitor  
  - Sequencer  
  - Scoreboard  
  - Coverage  
- Created **independent agents** for multiple address categories (even, odd, single, <10)  
- Conducted **SoC-level verification** involving concurrent access from multiple agents  
- Achieved **83% functional coverage**, validating thorough scenario testing and design robustness  

---

### 🧠 Skills Applied  
- UVM-based Constrained Random Verification  
- Memory Design Verification at SoC Level  
- Functional Coverage and Scenario Analysis  
- RTL Debugging and Testbench Architecture Design  

---

### 🛠️ Tools Used  
- **Synopsys VCS** – Simulation  
- **QuestaSim** – Waveform Analysis  
- **Verdi** – Debug and Signal Tracing  
- **SpyGlass** – Lint and Static Checks  
- **Design Compiler** – Synthesis  

---

### 💡 Learning Outcome  
This project enhanced understanding of **SoC-level memory verification** using **UVM**, focusing on:  
- Data consistency under concurrent access  
- Multi-agent coordination  
- Reusable, scalable UVM environment design  
- Coverage-driven verification methodology  

---

📍 **Author:** Muttu B Naik  
📧 **Email:** [muttunaik5096@gmail.com](mailto:muttunaik5096@gmail.com)  
🔗 **LinkedIn:** https://www.linkedin.com/in/muttunaik5096
