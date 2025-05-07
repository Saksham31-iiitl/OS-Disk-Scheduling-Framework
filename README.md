""# OS Disk Scheduling Framework

An efficient simulation framework for understanding various **Disk Scheduling Algorithms** like FCFS, SSTF, SCAN, C-SCAN, LOOK, and C-LOOK. This project visualizes head movements and computes performance metrics for each algorithm, providing a clear understanding of their behavior.

---

## 📁 **Project Structure**
```
OS-Disk-Scheduling-Framework/
├── algorithms
│   ├── fcfs.ipynb
│   ├── sstf.ipynb
│   ├── scan.ipynb
│   ├── cscan.ipynb
│   ├── look.ipynb
│   └── clook.ipynb
├── utils
│   ├── visualization.ipynb
│   └── metrics.ipynb
├── data
│   └── request_data.csv
└── main.ipynb
```

---

## 🚀 **Features**
- Simulates all major disk scheduling algorithms:
  - **FCFS (First Come First Serve)**
  - **SSTF (Shortest Seek Time First)**
  - **SCAN (Elevator Algorithm)**
  - **C-SCAN (Circular SCAN)**
  - **LOOK**
  - **C-LOOK**
- Plots head movement for each algorithm.
- Calculates key metrics:
  - Total Seek Time
  - Average Seek Time
  - Latency Analysis

---

## ⚙️ **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/OS-Disk-Scheduling-Framework.git
   cd OS-Disk-Scheduling-Framework
   ```

2. Create a virtual environment (Optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ **Usage**
To run the simulation, open `main.ipynb` in Jupyter Notebook or VS Code and execute the cells.  
Select the desired algorithm from the list and observe the head movement visualization and metrics.

---

## 📊 **Example Output**
- Disk movement graph
- Total Seek Time
- Average Seek Time

---

## 🗂️ **Data File**
- The `request_data.csv` contains the I/O requests in sequence. You can modify it to simulate different scenarios.

---

## 🤝 **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📄 **License**
This project is licensed under the MIT License.

---

## ✨ **Acknowledgements**
- Matplotlib for visualization
- Pandas for data handling
- Jupyter for interactive development
""
