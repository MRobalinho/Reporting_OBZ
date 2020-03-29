# Reporting_OBZ

This is the development of a reporting system for the zero base budget, using PowerBI

## Reporting system to OBZ Budget

To extract the data, run a report from SAP tables COSP and COSS (that have the accounting costs
by cost center and account).

- We have a SAP SET OBZ_TIPO_DESPESA to classify the accounts the Type of Expense
- We have a SAP SET GAC_P% sets have the accounts for spending packages

## Excel File layout to import into PowerBI
-----------------------------------------------
- Empresa				      - Company in text field
- Exercício			      - Year in text field (YYYY)
- Centro custo        - Number of cost center
- Denominação         - Name of cost center
- Data de lançamento  - Date (the system makes a single date per month, on 01 / mm / yyyy)
- Real           		  - Actual month value
- Plano          		  - Planned month
- Comparativo    		  - Actual value of the month for the comparative year
- Tipo Despesa        - Expense type
- Pacote              - Spending Package
- Nome 1         		  - Directors (Department)
- Nome 2         		  - Management


## What is OBZ - Zero Base Budget

Zero-based budgeting is one of the budget planning methodologies that is commonly known as OBZ, this tool requires managers to justify all of their budgeted expenses, rather than a more common approach of just requiring justification for incremental changes to the budget or actual results the previous year. Thus, a manager is theoretically assumed to have a zero expenditure baseline. OBZ is a plan made from scratch, with no background so it works, everything needs to be carefully budgeted and aligned.

In reality, a manager is assumed to have a minimum amount of funding for basic department operations, above which additional funding must be justified. The intention of the process is to continually focus the financing on key business objectives and to close or reduce any activity that is no longer related to those objectives.

The basic process flow under a zero-based budget is:

- Identify strategic business objectives
- Create and evaluate alternative methods to achieve each goal
- Assess alternative funding levels, depending on the planned performance levels to establish priorities.

The concept of tiered expenses can also be used in reverse, where you outline the specific costs and capital investment that will be incurred if you add an additional service or function. Thus, management can make discrete determinations of the exact combination of incremental cost and service for its business. This process will usually result in at least a minimum service level, which establishes a cost base below which it is impossible for a company to go, along with several service gradations above the minimum.

#### References:

http://im-inteligenciademercado.blogspot.com/2017/03/obz-orcamento-base-zero.html
