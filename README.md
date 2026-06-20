# 🌱 EcoML – CO₂ + GPU Aware Machine Learning Tracker

⚡ *Real-time CO₂, Energy, CPU/GPU Utilization & Hardware Recommendations directly inside Jupyter Notebook.*
📦 pip install ecoml → *1 line activation → Live performance + emissions pills in output*

---

## 🧠 What Does EcoML Do?

Every time you run a Jupyter cell, EcoML automatically:

✔ Monitors CPU and GPU utilization in real time 
✔ Estimates energy (kWh) & CO₂ (grams)  
✔ Gives an *Eco Score (0-100)*  
✔ Provides recommendations for resource-efficient model training 
✔ Logs all runs to CSV for dashboards  
✔ Shows insights pills *inline inside the output cell*

---

## 🟢 Quick Start

### *1️⃣ Install*

```ssh
pip install ecoml
```
for google colab
```
!pip install ecoml
```
### *2️⃣ import*
```ssh
from ecoml import enable_tracking
enable_tracking()

```
Now you can use it in any Python Notebook (ipynb) file.
