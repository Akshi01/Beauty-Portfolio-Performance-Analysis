# Beauty Portfolio Performance Analysis

## Business Problem
Large beauty portfolios are often managed using surface-level metrics 
like popularity and revenue. These signals can conflict; highly engaged 
products don't always deliver strong satisfaction, and highly rated 
products often remain under-leveraged. This project evaluates what 
actually drives product and category performance across a large beauty 
e-commerce portfolio.

## Objective
To analyse product and category-level performance across price tiers, 
engagement, satisfaction, and operational health, and identify where 
the business should grow, maintain, or rationalise its assortment.

## Dataset
- Source: Kaggle (Sephora public dataset)
- 8,485 products across 41 secondary categories
- Attributes: engagement (loves count), ratings, pricing, 
  merchandising flags, category structure

## Approach
The analysis was conducted in two parts:

**Part 1 - Product Performance Analysis**
Evaluated portfolio performance across price tiers, categories, brands, 
and promotional attributes to identify what drives engagement vs 
satisfaction.

**Part 2 - Portfolio Health Scorecard**
Built a repeatable scoring framework evaluating all 41 secondary 
categories across four dimensions: engagement, satisfaction, review 
intensity, and stockout risk. Each category was assigned a Portfolio 
Role: Grow, Maintain, Review, or Rationalise.

## Key Findings
- Budget products drive 80%+ of portfolio engagement; premium pricing 
  adds minimal perceived value
- High engagement does not consistently map to high satisfaction; 
  a structural engagement-satisfaction gap exists across the portfolio
- Only 2 categories (Cheek and Makeup Palettes) qualify as Grow, 
  performing strongly on both dimensions
- 10 categories flagged for Review; 3 flagged for Rationalisation
- Stockout risk is concentrated in high-demand categories including 
  Makeup Palettes (10%) and Lip (11%), representing direct revenue loss

## Tools
Excel (Power Query, Pivot Tables, Data Visualization)

## Reports
- [Part 1 - Product Performance Analysis](./Report_1_Product_Analysis.pdf)
- [Part 2 - Portfolio Health Scorecard](./Report_2_Portfolio_Scorecard.pdf)
