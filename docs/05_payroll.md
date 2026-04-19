# Step 5: Payroll Processing

## Objective
Run monthly payroll for the hired employee.

## Payroll Structure for TechNova
| Component | Amount |
|-----------|--------|
| Basic Pay | 50,000 |
| HRA (40%) | 20,000 |
| Conveyance | 2,000 |
| Special Allowance | 8,000 |
| Gross | 80,000 |
| PF Deduction (12%) | -6,000 |
| TDS | -5,000 |
| Net Pay | 69,000 |

## SAP Payroll Steps

### 5.1 Configure Payroll Area
- **T-Code:** OH11
- Payroll Area: IN (India)
- Period: Monthly

### 5.2 Maintain Payroll Control Record
- **T-Code:** PA03
- Set status to: Released for Payroll
- Period: April 2024

### 5.3 Run Payroll Simulation (Test First)
- **T-Code:** PC00_M40_CALC_SIMU (India)
- Enter Payroll Area: IN
- Period: 04/2024
- Click Execute — review results without posting

### 5.4 Run Actual Payroll
- **T-Code:** PC00_M40_CALC
- Same inputs as simulation
- Execute and confirm

### 5.5 Post to Accounting
- **T-Code:** PC00_M40_CIPE
- This posts payroll to FI (Finance) — salary expense booked

### Screenshot
[Insert payroll run screenshot here]
