# Step 2: Organizational Structure

## Objective
Define the HR organizational structure in SAP.

## SAP Configuration Steps

### 2.1 Create Organizational Plan
- **T-Code:** PPOME
- Path: SAP Easy Access → Human Resources → Organizational Management → Organizational Plan → Organization and Staffing → Change

### 2.2 Objects to Create
| Object Type | Name | ID |
|-------------|------|----|
| O – Org Unit | TechNova HQ | 10000001 |
| O – Org Unit | IT Department | 10000002 |
| O – Org Unit | HR Department | 10000003 |
| C – Job | Software Engineer | 50000001 |
| S – Position | Sr. Developer | 60000001 |

### 2.3 Steps
1. Open PPOME
2. Click "Create" → Select "Organizational Unit"
3. Enter Name: TechNova HQ, Validity: 01.01.2024 – 31.12.9999
4. Save
5. Under TechNova HQ, create sub-units: IT Dept, HR Dept
6. Create Jobs (C) and link Positions (S) to them

### Screenshot
[Insert SAP screenshot of org chart here]
