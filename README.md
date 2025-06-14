# 📌 GRC Project Plan Overview: “Mini RMF with NIST 800-53 Mapping”

## 💼 Table of Contents:
* **Folder Structure**
* **Asset inventory**
* **Risk register**
* **Risk scoring**
* **Control selection and implementation status**
* **Compliance dashboard**

## Step 1 - Folder STructure
grc-risk-framework/
├── data/
│   ├── assets.csv
│   ├── risk_register.csv
├── controls/
│   └── nist80053_sample.json
├── scripts/
│   ├── risk_assessment.py
│   └── control_mapper.py
├── reports/
│   └── risk_report.md
├── dashboard/
│   └── app.py  (for later)
└── README.md

## Step 2 - Create (Assets.CSV)
    - Path: data/assets.csv
![image](https://github.com/user-attachments/assets/a69356a8-04a8-4722-96e9-bd15400996e6)
    
## Step 3 - Create (risk_register.csv)
    - Path: data/risk_register.csv
![image](https://github.com/user-attachments/assets/e85b075f-524f-4602-a0be-9874e5c9260a)

## Step 4 - Create a Control Set (nist800-53.json)
   - Path: controls/nist800-53.json
json

[
  {
    "control_id": "AC-2",
    "control_name": "Account Management",
    "description": "Manage information system accounts, including establishing, activating, modifying, disabling, and removing accounts."
  },
  {
    "control_id": "AC-6",
    "control_name": "Least Privilege",
    "description": "Employ the principle of least privilege, allowing only authorized access for users."
  },
  {
    "control_id": "SC-7",
    "control_name": "Boundary Protection",
    "description": "Monitor and control communications at the external boundary and key internal boundaries."
  }
]



    
    


