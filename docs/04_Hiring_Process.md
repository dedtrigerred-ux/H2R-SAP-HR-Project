# Step 4: Hiring an Employee (PA40)

## Objective
Hire a new employee into the SAP system.

## Pre-requisite
- Org structure must be ready
- Position must exist

## Steps to Hire

### 4.1 Initiate Hiring Action
- **T-Code:** PA40
- Path: SAP Easy Access → Human Resources → Personnel Management → Administration → HR Master Data → PA40 – Personnel Actions

### 4.2 Enter Details
1. Enter Personnel Number: Leave blank (system auto-assigns, e.g., 10001)
2. Select Action Type: **01 – Hiring**
3. Start Date: 01.04.2024
4. Click Execute (F8)

### 4.3 Infotypes to Fill
| Infotype | Name | Key Data |
|----------|------|----------|
| IT0000 | Actions | Action type, Start date |
| IT0001 | Org Assignment | Company code TN01, Personnel Area TN01, Position 60000001 |
| IT0002 | Personal Data | Name: Rahul Sharma, DOB: 15.06.1995, Gender: Male |
| IT0006 | Addresses | Address: 45 MG Road, Noida, UP |
| IT0007 | Planned Working Time | Work Schedule: FULL (40hrs/week) |
| IT0008 | Basic Pay | Pay Scale: IT Grade A, Basic: 50,000/month |
| IT0009 | Bank Details | Bank: SBI, IFSC: SBIN0001234, A/C: 1234567890 |

### 4.4 Save Each Infotype
After filling each infotype, click Save before moving to the next.

### Result
Employee ID 10001 - Rahul Sharma is now hired in the system.

### Screenshot
[Insert PA40 screenshot here]
