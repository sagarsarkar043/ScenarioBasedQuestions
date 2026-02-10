

#1 Daily Sales Monitoring
## Business Context

A retail manager wants to see total sales for each day.

## Business Question

“How much did we sell every day?”

## Step-by-Step Thinking

1. Identify metric → Sales Amount

2. Identify grouping → Date

3. Aggregate → SUM

## Table

```Sales(SaleDate, Amount)```

## SQL Solution
```SELECT 
    SaleDate,
    SUM(Amount) AS TotalSales
FROM Sales
GROUP BY SaleDate
ORDER BY SaleDate;
```
## Business Insight

Helps management track daily performance trends.
