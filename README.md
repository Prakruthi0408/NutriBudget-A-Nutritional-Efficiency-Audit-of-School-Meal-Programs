# NutriBudget: A Nutritional Efficiency Audit of School Meal Programs

## Project Overview

This project explores a critical public policy question:  
**Are schools delivering the maximum nutritional value for every dollar spent on meals?**

Using food-level nutrient data and simulated school menus, we conducted a complete audit of nutritional efficiency across multiple schools. The goal was not just to analyze nutrition and cost — but to provide actionable insights that can inform better budgeting, smarter food procurement, and healthier outcomes for students.

---

## Objective

To audit the nutritional cost-efficiency of public school meal programs by:
- Simulating realistic school menus
- Calculating a custom Nutrition Efficiency Index (NEI)
- Identifying cost-inefficient food items
- Simulating improvements through smarter substitutions
- Recommending data-driven reallocation strategies

---

## Dataset

**Augmented USDA Nutrition Dataset**  
- Source: USDA FoodData Central (base), enhanced with:
  - Simulated `Price_per_100g_USD`
  - Calculated `Nutrition Efficiency Index (NEI)`
- Features include: calories, protein, fats, carbohydrates, sodium, iron, calcium, vitamins, and more

---

## Business Questions Answered

1. **Which schools are delivering the highest nutrition per dollar across their weekly menus?**  
   Identified top-performing schools using the NEI per dollar metric.

2. **Which schools are overspending for underperforming meals?**  
   Flagged inefficient schools with high costs but low nutritional return.

3. **What specific foods or meals are contributing to low nutritional efficiency in these schools?**  
   Diagnosed the low-NEI items driving down school performance.

4. **How much cost savings or nutritional improvement can be achieved by substituting better alternatives?**  
   Simulated realistic swaps that significantly improved NEI while reducing cost.

5. **What is the recommended reallocation strategy for improving the nutritional efficiency of low-ranked schools?**  
   Demonstrated measurable improvements in NEI per dollar and proposed a scalable optimization strategy.

---

## Key Features and Methods

- Nutrition Efficiency Index (NEI): Custom metric using protein, calcium, and iron weighted per dollar
- Simulated weekly menus for 10 schools using random sampling
- Outlier handling, missing value imputation, and percent-based NEI thresholds
- Substitution engine: matches low-efficiency foods with high-efficiency, lower-cost items
- Before vs After analysis of school performance
- Final reallocation plan with cost-neutral efficiency uplift

---

## Insights & Impact

- Schools with the lowest NEI per dollar were able to improve performance by up to 44x using simple, cost-effective substitutions
- High spending is not always the issue — poor menu design and inefficient ingredient choices are often to blame
- This audit approach can be used by school districts or policymakers as a replicable framework for nutrition-cost optimization

---

## Tools Used

- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Data Cleaning and Simulation
- Markdown Narratives and Audit Interpretation

---

