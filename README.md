# Halal Investment Dashboard

## Overview
This Power BI dashboard evaluates stock compliance with Shariah principles using financial ratios:
<img width="1175" height="826" alt="Halal invest1" src="https://github.com/user-attachments/assets/e9bcea3b-ccdb-47eb-a4f7-c126de2aa9dd" />
<img width="1173" height="811" alt="Halal invest2" src="https://github.com/user-attachments/assets/ef44111b-e5ab-4b55-a7af-f4d6065b4e2e" />
<img width="1177" height="802" alt="halal invest3" src="https://github.com/user-attachments/assets/9e5f88f0-6306-4db1-9be7-a714e39f321c" />

- **Debt/Assets** → Debt Compliance (≤33%)  
- **Cash/Assets** → Liquidity Compliance (≤33%)  
- **Receivables/Assets** → Receivables Compliance (≤33%)

The dashboard includes:
- **Overview Page**: Key performance indicators and sector breakdown.  
- **Detailed Analysis**: Interactive tables and scatter plots.  
- **Company Explorer**: Searchable company-level compliance checks.  

## Tools Used
- **Power BI**: Data visualization and DAX calculations  
- **Data Sources**: [Yahoo Finance]  
- **Metrics**: Halal compliance thresholds (≤33%)

## Key DAX Measures
Use these measures as the **Target value** in your gauge visuals:

```DAX
Debt_Compliance_Target = 0.33
Liquidity_Compliance_Target = 0.33
Receivables_Compliance_Target = 0.33

