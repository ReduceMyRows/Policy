
# Virginia Soda Tax | Economic Policy Analysis

**Applied Microeconomics · Public Finance · Demand Estimation · Policy Simulation**

An illustrative economic analysis evaluating the potential effects of a hypothetical 5% soda tax in Virginia on consumer demand, tax revenue, and distributional outcomes.

## 1. Research Objective

This project examines how consumer responses to a soda tax may differ across income groups and how these differences affect projected tax revenue.

The analysis focuses on three questions:

1. How responsive is soda consumption to changes in price?
2. How does price elasticity differ across income groups?
3. How do tax pass-through assumptions influence consumption and projected government revenue?

## 2. Data & Preparation

The analysis uses simulated retail sales data, combined with ZIP-code-level Census income information.

**Dataset:**
- 100 simulated retail stores
- 36 months of sales observations
- ZIP-level income classifications
- Product prices, quantities, and sales revenue

**Data processing:**
- Microsoft Power Query (M)
- Data extraction, cleaning, and transformation
- Integration of retail and Census income data
- Relational data modeling and validation

The repository includes supporting Power Query/Power BI materials used to prepare the analytical dataset.

## 3. Methodology

### Demand Elasticity Estimation

A log-log demand specification estimates the relationship between price and quantity demanded:

\[
\ln(Q_{it}) = \alpha + \beta \ln(P_{it}) + \varepsilon_{it}
\]

Where:

- \(Q_{it}\): Quantity demanded
- \(P_{it}\): Retail price
- \(\beta\): Estimated price elasticity of demand
- \(\varepsilon_{it}\): Error term

Elasticities are estimated separately across income groups to examine differences in price sensitivity.

### Tax Revenue Simulation

A hypothetical 5% soda tax is applied under alternative tax pass-through assumptions.

The simulation examines:

- Changes in consumer prices
- Expected changes in quantity demanded
- Projected tax revenue
- Differences in responses across income groups

## 4. Illustrative Results

### Estimated Price Elasticities

| Income Group | Price Elasticity |
|---|---:|
| High Income | -0.71 |
| Medium Income | -0.93 |
| Low Income | -1.94 |
| **Overall** | **-0.98** |

The simulated results suggest greater price sensitivity among lower-income consumers.

Under the modeled full-pass-through scenario, projected tax revenue is approximately **$84.0 million**.

These estimates are conditional on the simulated dataset and model assumptions. They should not be interpreted as observed causal effects or official revenue forecasts for Virginia.

## 5. Repository Contents

The repository contains materials supporting the analysis, including:

- **Research report (PDF):** Policy scenario, methodology, results, and interpretation.
- **Power Query / Power BI:** Data preparation, Census integration, and analytical data model.
- **Supporting data and documentation:** Available inputs, transformations, and related research materials.

## 6. Limitations

- The sales dataset is simulated rather than observed retail transaction data.
- Price elasticities depend on the assumed demand specification.
- Revenue projections are sensitive to tax pass-through and behavioral assumptions.
- The analysis does not estimate actual health outcomes or evaluate an implemented Virginia soda tax.

## 7. Tools & Methods

**Software:** Microsoft Excel, Power Query (M), Power BI

**Methods:** Log-log regression, price elasticity estimation, income segmentation, scenario analysis, and revenue modeling.

---

**Author:** Wataru Hoeltermann  
**Research Area:** Applied Economics & Public Policy  
**Portfolio:** [reducemyrows.github.io](https://reducemyrows.github.io/)
