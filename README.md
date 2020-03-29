# Reporting_OBZ
Reporting system to OBZ Budget

To extract the data, run a report from SAP tables COSP and COSS (that have the accounting costs
by cost center and account).

- We have a SAP SET OBZ_TIPO_DESPESA to classify the accounts the Type of Expense
- We have a SAP SET GAC_P% sets have the accounts for spending packages

## File layout to import into PowerBI
-----------------------------------------------
Empresa				- Company in text field
Exercício			- Year in text field (YYYY)
Centro custo        - Number of cost center
Denominação         - Name of cost center
Data de lançamento  - Date (the system makes a single date per month, on 01 / mm / yyyy)
Real           		- Actual month value
Plano          		- Planned month
Comparativo    		- Actual value of the month for the comparative year
Tipo Despesa        - Expense type
Pacote              - Spending Package
Nome 1         		- Directors (Department)
Nome 2         		- Management
