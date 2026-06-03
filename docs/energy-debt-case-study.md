# Project 04 – Energy Debt Repayment Analysis

## Background

Credit management and collections teams need to monitor outstanding debt, repayment behaviour and account risk. A static debt balance report is not enough because it does not clearly show which accounts are improving, weakening or requiring urgent follow-up.

This portfolio project demonstrates how Power BI can support weekly debt review, repayment monitoring and operational prioritisation.

## Business problem

The key business question is:

> Which accounts, customer groups and repayment arrangements need attention first?

Common pain points include:

- Total debt is visible, but repayment behaviour is harder to interpret.
- Missed instalments and weakening repayment plans may not be escalated early enough.
- High-balance accounts need prioritisation, but risk is not only about balance size.
- Teams may spend time manually preparing exception lists.
- Managers need a clearer view of where action is likely to improve recovery outcomes.

## Dashboard objectives

The dashboard is designed to help users:

1. Monitor total outstanding debt and account volume.
2. Compare expected repayment against actual repayment.
3. Identify missed payments, overdue balances and weakening arrangements.
4. Segment customers by risk, balance, payment method or behaviour.
5. Create a practical follow-up list for the credit team.

## Suggested data model

Example tables:

- `FactRepayment` – account, transaction date, expected amount, paid amount, missed payment flag.
- `FactDebtBalance` – account, balance date, outstanding balance, overdue amount, ageing bucket.
- `DimCustomer` – customer type, segment, region, payment method, risk group.
- `DimAccount` – account status, plan type, start date, review status.
- `DimDate` – date, month, quarter, year, financial period.

## Example KPIs

- Total outstanding debt
- Average debt balance
- Paid versus expected amount
- Repayment plan completion %
- Missed payment count
- Overdue balance
- Debt ageing bucket
- Priority risk category

## Insight examples

- A high-balance account may be lower risk if it is consistently repaying as expected.
- A lower-balance account may need action if the repayment arrangement has recently broken.
- Certain customer groups or payment methods may show higher missed-payment behaviour.
- Accounts with repeated underpayment may need affordability review rather than repeated standard chasing.

## Recommended actions

- Create a weekly exception list for high-balance accounts with missed instalments.
- Separate customers who are paying slowly from customers who have stopped paying.
- Review plan affordability when repeated underpayment appears.
- Use customer segment and payment method to tailor contact strategy.
- Track post-contact outcomes to measure whether interventions work.

## Skills demonstrated

- Power BI dashboard design
- DAX measures for debt, repayment and risk KPIs
- Power Query data preparation and exception handling
- Operational reporting for credit management
- Customer segmentation and prioritisation
- Translating analytics into follow-up actions
