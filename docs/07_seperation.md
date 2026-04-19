# Step 7: Employee Separation / Retirement

## Objective
Process an employee's exit from the organization.

## Types of Separation
| Action | Code |
|--------|------|
| Resignation | 10 |
| Retirement | 11 |
| Termination | 12 |

## SAP Steps for Separation

### 7.1 Run Separation Action
- **T-Code:** PA40
- Employee: 10001 (Rahul Sharma)
- Action Type: 11 – Retirement
- Effective Date: 31.03.2034

### 7.2 Infotypes Updated During Separation
| Infotype | Change |
|----------|--------|
| IT0000 | Action = Retirement, status = Inactive |
| IT0001 | Org assignment end-dated |
| IT0019 | Monitoring of Dates (retirement date stored) |

### 7.3 Final Settlement
- Calculate remaining leave encashment
- Last payroll run for the employee
- Issue Form 16 (Tax document)
- PF withdrawal processed

### 7.4 Verify Employee Status
- **T-Code:** PA20 – Display HR Master Data
- Check IT0000 — Status should show Inactive / Retired

### Result
Employee 10001 is now separated. All records retained in SAP for audit purposes.

### Screenshot
[Insert PA40 separation screenshot here]
