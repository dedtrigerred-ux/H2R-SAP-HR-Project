# Step 6: Time & Leave Management

## Objective
Configure and process employee leave in SAP.

## Leave Types Configured
| Leave Type | Days/Year |
|------------|-----------|
| Annual Leave | 24 |
| Sick Leave | 12 |
| Casual Leave | 8 |
| Maternity Leave | 182 |

## SAP Configuration Steps

### 6.1 Define Absence Types
- **T-Code:** PT60 / SPRO
- Path: IMG → Time Management → Time Data Recording → Absences → Define Absence Types
- Create: Annual Leave (0100), Sick Leave (0200), Casual Leave (0300)

### 6.2 Assign Leave Quota
- **T-Code:** PA30
- Infotype: IT2006 - Absence Quotas
- Employee: 10001 (Rahul Sharma)
- Quota Type: Annual Leave
- Entitlement: 24 days
- Validity: 01.01.2024 – 31.12.2024

### 6.3 Employee Applies for Leave
- **T-Code:** PA30
- Infotype: IT2001 - Absences
- Absence Type: Annual Leave
- Start: 15.04.2024, End: 19.04.2024 (5 days)
- Save

### 6.4 Check Attendance/Absence Report
- **T-Code:** PT60 – Time Evaluation
- **T-Code:** S_AHR_61016362 – Absence report

### Screenshot
[Insert leave application screenshot here]
