# 📌 GRC Project Plan Overview: “Mini RMF with NIST 800-53 Mapping”

## 💼 Table of Contents:
* **Folder Structure**
* **Asset inventory**
* **Risk register**
* **Risk scoring**
* **Control selection and implementation status**
* **Compliance dashboard**

## Step 1 - Folder STructure
![image](https://github.com/user-attachments/assets/0ecd7888-8205-4066-a387-49645feb9629)

## Step 2 - Create (Assets.CSV)
    - Path: data/assets.csv
![image](https://github.com/user-attachments/assets/a69356a8-04a8-4722-96e9-bd15400996e6)
    
## Step 3 - Create (risk_register.csv)
    - Path: data/risk_register.csv
![image](https://github.com/user-attachments/assets/e85b075f-524f-4602-a0be-9874e5c9260a)

## Step 4 - Create a Control Set (nist800-53.json)
   - Path: controls/nist800-53.json
![image](https://github.com/user-attachments/assets/676e952f-4577-4c42-b54d-2d935fcba292)

## Step 5 - Create Risk Assessment Script (risk_assessment.py)
    - Path: scripts/risk_assessment.py
![image](https://github.com/user-attachments/assets/4c41a352-8b3c-46de-9d46-041950e80d28)

## Phase 2 - Control Mapping:
* Map Risk to Relevant NIST 800-53 controls (control_matter.py)
* Track control implementation status
* Prepare a risk report summary (risk_report.md)
* Build a dashborad in Streamlit or Flask (optional)

## Step 1 - Create Control Mapping Logic (control_mapper.py)
    - Path: scripts/control_mapper.py
![image](https://github.com/user-attachments/assets/2a6a8a61-8bfd-4ea4-88ad-92da6efe0227)
    
## Step 2 - Result (risk_register_mapped.csv)
// after control_mapper.py
![image](https://github.com/user-attachments/assets/8c0eb3c6-17cb-4b41-b035-1db92cb59f9b)

## Step 3 - Generate Risk Report
    -  Path: reports/risk_report.md
![image](https://github.com/user-attachments/assets/2f2b5b50-5b9f-4121-8f37-41d9cda230ca)
![image](https://github.com/user-attachments/assets/638bb539-54e0-4ae7-830f-399096ff74a0)
![image](https://github.com/user-attachments/assets/446f2dcb-b2b3-47e7-8f54-d5cb69fb2123)

    

    
            


