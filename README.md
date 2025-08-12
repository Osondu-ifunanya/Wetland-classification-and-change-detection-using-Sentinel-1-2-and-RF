
# Wetland Classification and Change Detection using Sentinel-1 & Random Forest (Synthetic Data)

## 📌 Overview

This project demonstrates **wetland classification and change detection** using **synthetic Sentinel-1 SAR data** with a **Random Forest (RF) classifier**. It simulates mapping and detecting temporal changes in wetland extent for environmental monitoring.

## 🛰 Data

* **Synthetic Sentinel-1 SAR Data** (VV & VH polarizations)
* Generated to mimic real-world SAR backscatter for wetlands and non-wetlands
* Two synthetic time periods (T1 & T2) for change detection

## ⚙ Methods

1. **Synthetic Data Creation** – Gaussian distributions to simulate SAR backscatter.
2. **Feature Extraction** – VV, VH, and derived ratios.
3. **Random Forest Classification** – Train model on synthetic data for wetland mapping.
4. **Change Detection** – Compare classified maps from T1 and T2 to identify changes.

## 📂 Folder Structure

```
wetland_rf/
│── data/              # Synthetic SAR datasets
│── notebooks/         # Jupyter Notebook for training & analysis
│── results/           # Classified maps & change detection results
│── wetland_rf.py      # Main script
│── README.md          # Project description
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/wetland-rf.git
   cd wetland-rf
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:

   ```bash
   python wetland_rf.py
   ```

## 📊 Output

* Classified wetland map for each time period
* Change detection map showing wetland gain/loss

## 📈 Applications

* Wetland conservation planning
* Habitat monitoring
* Environmental impact assessments


