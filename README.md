# 🚗 Tableau EV Analysis Dashboard

This project presents a Tableau dashboard designed to analyze Electric Vehicle (EV) data in the United States. The dashboard provides insights into EV adoption patterns, vehicle types, manufacturer trends, and model-level distributions.

---

## 📊 Dashboard Overview

The dashboard includes the following interactive sheets:

1. **Total BEV Vehicles**  
2. **Total PHEV Vehicles**  
3. **Average Electric Range**  
4. **Total Vehicles by Model Year**  
5. **Total Vehicles by State**  
6. **Total Vehicles by Make**  
7. **Total Vehicles by CAFV Eligibility**  
8. **Total Vehicles by Model**

### 🔍 Filters Used

The dashboard provides interactivity using the following filters:

- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**
- **EV Type** (BEV or PHEV)
- **Model**
- **State**
- **Make**

---

## 🧾 Dataset Fields

The dataset used in this dashboard contains various fields grouped into:

### ➤ Dimensions
- `City`, `County`, `State`, `Postal Code`
- `Make`, `Model`, `Model Year`, `EV Type`
- `Vehicle Location`, `Clean Alternative Fuel Vehicle Eligibility`, `Electric Utility`
- `VIN (1-10)`, `2020 Census Tract`, `Legislative District`

### ➤ Measures
- `% of BEV Vehicles`, `% of PHEV Vehicles`
- `Total BEV Vehicles`, `Total PHEV Vehicles`, `Total Vehicles`
- `Electric Range`, `Average Electric Range`
- `Base MSRP`, `Electric_Vehicle_Population`
- `Latitude (generated)`, `Longitude (generated)`

*(See `images/dataset_fields.png` for full list)*

---
## 📂 Repository Structure
```
Tableau-EV-Dashboard/                     # Root directory of the project
│
├── dataset/                              # Contains the dataset used for the dashboard
│   └── electric_vehicle_data.csv         # Raw dataset exported from Tableau
│
├── sheets/                               # Visual assets for documentation
│   ├── dataset_fields.png                # Screenshot of all dataset fields
│   └── dashboard_preview.png             # Final Tableau dashboard screenshot (optional)
│
├── dashboard/                            # Tableau workbook files
│   └── EV_Dashboard.twbx                 # Packaged Tableau workbook
│
├── README.md                             # Project documentation and usage guide
├── .gitignore                            # Files and folders to be ignored by Git
└── LICENSE                               # License information for the repository
```
