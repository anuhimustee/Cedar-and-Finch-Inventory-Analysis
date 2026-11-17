### CEDAR & FINCH DISTRIBUTION

> Supply Chain Division | Internal Brief
> CONFIDENTIAL
> REF: CF-SC-2026-01

# **Operation Stock Balance**

## **BACKGROUND**

Cedar & Finch Distribution supplies household cleaning products, paper goods and everyday home essentials
to retailers across the United States through a network of regional warehouses. Its purchasing team uses
product reorder points, supplier lead-time estimates and standard order quantities to replenish stock.
Management reviews total inventory value and sales, but has not systematically tested whether inventory is
held in the right products, quantities and locations.

## **THE INCIDENT**
At the year-end review, the Finance Director raised a concern: substantial cash was tied up in warehouse
inventory, yet the sales team continued to report unfulfilled customer demand. Buyers were requesting
additional stock to prevent shortages, while warehouse teams reported products that had barely moved for
months.
A preliminary review suggested that some frequently unavailable products might be stocked elsewhere in the
network. Other shortages appeared to follow supplier delays or demand increases. None of these explanations
has been confirmed. Before approving the next purchasing budget, the leadership team wants to understand
why stockouts and excess inventory coexist, and whether changes to replenishment or allocation could
improve availability without simply buying more.

> **"We have money sitting on the shelves, yet customers cannot get what they ordered. Show me
> where the imbalance is, why it happens, and what we should change before we commit more
> cash."**

## **MY ROLE**
I assumed the role of just have joining Cedar & Finch Distribution as a Junior Data Analyst in the Supply Chain team. The take is that I just have ONE
assignment and that is to analyze raw inventory, customer-demand and replenishment records for 2025 using Excel,
Power Query, Power Pivot and DAX. Clean and normalize the source data, build a star or snowflake model,
investigate shortages and excess stock at product-warehouse level, and recommend evidence-based changes
to replenishment and stock allocation.

---

**FLAGGED SIGNALS (UNVERIFIED)**

- Demand And Replenshiment Mismatch: Some reorder points and order quantities may no longer reflect current demand or its variability.
- Supplier Lead-Time Inconsistency: Actual replenishment times may exceed planning assumptions or vary substantially between orders.
- Inventory in the Wrong Location: A warehouse may face shortages while another holds surplus stock of the same product.
- Slow-Moving Stock Concentration: A small set of products may account for a disproportionate share of inventory value without matching customer demand.

## **ANALYTICAL DELIVERABLES**
1. **Inventory Overview & Baseline KPIs:**
Establish stockout frequency, unit fill rate, inventory value, turnover and days of cover. Define
time periods and denominators; distinguish demand from fulfilled sales.
2. **Data Clenaing & Model Build:**
Clean and normalize the raw records in Power Query. Build a star or snowflake schema in
Power Pivot with clear table grains, keys and relationships.
3. **Product-Warehouse Imbalance Analysis:**
Identify products and locations with recurring shortages, surplus stock or slow movement.
Compare local shortages with stock elsewhere in the network.
4. **Replenshiment & Supplier Diagnostic:**
Investigate demand variability, reorder settings, order quantities, and planned versus actual
supplier lead times. Separate evidence from assumptions.
5. **Demand Outlook & Replenshiment Scenarios:*
Estimate near-term demand and shortage exposure. Compare revised reorder points, safety
stock or transfers, stating assumptions and service-versus-inventory trade-offs.
6. **Recommendation Dashboard & Written Report:**
Create an interactive Excel dashboard and a report presenting quantified insights, prioritized
actions and limitations. Link each recommendation to evidence.
