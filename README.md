# Tesla Discounted Cash Flow Valuation

A five-year discounted cash flow model of Tesla built in Excel as a financial-modeling portfolio project. The model uses FY2024 as the base year and incorporates analyst-created assumptions.

## Overview

The model forecasts revenue, operating costs, taxes, capital expenditures, depreciation, and working capital. It then calculates unlevered free cash flow (UFCF) and discounts the projected cash flows to their present value.

Enterprise value is converted to equity value by adding cash and short-term investments and subtracting debt and finance leases.

This is an illustrative scenario analysis, not a price target. Its purpose is to demonstrate the structure, calculations, assumptions, and sensitivity of a complete DCF model.

## Methodology

- **Base year:** FY2024, using Tesla’s Form 10-K
- **Revenue growth:** 12% / 10% / 8% / 6% / 5% over Years 1–5
- **Operating costs:** Cost of revenue, operating expenses, and depreciation are held at their FY2024 percentages of revenue
- **Taxes:** FY2024 effective tax rate applied to EBIT
- **Working capital:** Operating net working capital is held at its FY2024 percentage of revenue
- **Capital expenditures:** Decline from 11.6% of revenue to 7.5% by Year 5 as an analyst assumption, not company guidance
- **Unlevered free cash flow:** NOPAT + depreciation − capital expenditures − change in net working capital
- **Discount rate:** Market-value-weighted WACC incorporating a CAPM-based cost of equity
- **Terminal value:** Gordon Growth Method using a 2.5% terminal-growth rate
- **Equity bridge:** Enterprise value + cash and short-term investments − debt and finance leases

Because operating net working capital is negative, maintaining it as a constant percentage of revenue results in additional cash flow as revenue grows.

## Sensitivity and Scenario Analysis

The model includes a WACC and terminal-growth sensitivity table that recalculates the valuation under different combinations of assumptions.

The output is particularly sensitive to:

- The discount rate
- The terminal-growth rate
- The assumed normalization of capital expenditures

Terminal value represents a significant portion of enterprise value, illustrating the importance of long-term assumptions in a five-year DCF.

## Model Integrity

- Consistent units throughout: $ thousands in the model and $ millions in the valuation summary
- Built-in checks confirming that terminal growth remains below WACC and terminal free cash flow remains positive
- Independent enterprise-value reconciliation
- Tie-out between the base valuation and the sensitivity table
- Centralized assumptions with principal editable inputs identified in blue

## Limitations

- Top-down model with a constant EBIT margin and no assumed operating leverage
- No separate forecasts for the automotive, energy, and services segments
- No separate value assigned to autonomy, robotics, or other optionality
- WACC inputs are not synchronized to a single valuation date
- Basic shares outstanding are used instead of diluted shares


## Skills Demonstrated

Financial statement analysis · Financial forecasting · Excel financial modeling · DCF valuation · WACC analysis · Terminal-value analysis · Sensitivity analysis · Model auditing and integrity checks

## Sources and Disclaimer

Historical financial information was obtained from Tesla’s FY2024 Form 10-K.

This model was created for educational and portfolio purposes. Its assumptions are illustrative, are not Tesla guidance, and do not constitute investment advice or a recommendation to buy or sell any security.
