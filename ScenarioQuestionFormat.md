# Business Context

## What It Means

This explains the background situation of the company or team.It answers: “What is happening in the business?”

Why Interviewers Care. They want to see if you understand:

1. Industry
2. Business model
3. Stakeholder goals
4. Real-world scenario

## Example

Business Context:
An e-commerce company noticed quarterly revenue declined by 10%.This sets the stage.You are not jumping into SQL yet — you're understanding the story first.

# Business Problem / Question
## What It Means

This is the actual question the stakeholder is asking.It answers: “What exactly do they want to know or solve?”

Why Interviewers Care

Many candidates confuse symptom with problem.

## Example:

1. Wrong: Revenue dropped.
2. Correct: Why did revenue drop? Which driver caused it?

## Example

Business Problem:

Identify the root cause of revenue decline.Now the problem is clearly defined.

# Data Available
## What It Means

List what data you have access to.It answers: “What information can I use to solve this?”

Why Interviewers Care
Shows:

Data awareness
Practical thinking
Realistic analysis approach

## Example

Data Available:

1. Revenue
2. Order count
3. Customer count
4. Product category
5. Region
6. Marketing spend

This tells the interviewer you know what inputs drive revenue.

# Step-by-Step Approach (Thinking Process)

This is the MOST IMPORTANT section.

This is where you show analytical maturity.

## What It Means

How you logically break down the problem before touching tools.

## Example (Revenue Drop Case)

### Step 1: Break revenue formula

Revenue = Customers × Conversion Rate × Average Order Value

### Step 2: Compare current vs previous quarter

### Step 3: Identify which component changed

### Step 4: Drill down by region/product

This shows structured thinking, not random dashboard clicking.

# Technical / Analytical Solution

## What It Means

Now you apply SQL / Python / Power BI / Excel.

This is execution.

```
Example (SQL)
SELECT 
    Quarter,
    SUM(Revenue)
FROM Sales
GROUP BY Quarter;
```

## Then calculate:

1. Customer count trend
2. AOV trend
3. Conversion trend

Technical skill supports your business thinking.

## Business Recommendation / Insight

This is where 90% of candidates fail.

They stop at analysis.Interviewers want: “So what?”

##  What It Means

Translate analysis into business action.

## Example

1. If customer count declined → Increase marketing acquisition campaigns

2. If AOV declined → Improve cross-sell & upsell

3. If conversion dropped → Improve website UX
