# Data Visualization and Storytelling: DecodeLabs Project 4

Three charts that turn analysis of 1,200 customer orders (Jan 2023 to
Jun 2025) into a clear story for decision-makers. Built in Python
(matplotlib) on Google Colab.

## Goal
Communicate insights clearly: choose the right chart for each question,
and highlight the key point.

## The story (SCR framework)
- **Situation:** 1,200 orders worth about 1.26M were placed between
  January 2023 and June 2025.
- **Complication:** only about 19% of orders were delivered, about 41%
  were cancelled or returned, and first-half revenue fell about 10% each year.
- **Resolution:** find out why orders fail, and focus on the products that
  earn the most from delivered orders (Laptop leads, Desk trails).

## Charts
1. chart1.png: order status (bar chart). 41% of orders were cancelled or returned.
2. chart2.png: delivered revenue by product (bar chart). Laptop leads; Desk trails.
3. chart3.png: first-half revenue by year (line chart). Revenue fell about 10% every year.

## Design principles used
- Chart type matched to the question (bars to compare, line for a trend)
- Titles that state the conclusion, not the topic
- Grey for context, one highlight colour for the key insight
- Direct labels on bars instead of legends
- Bar charts start at zero, no 3D, no pie charts

## Files
- Visualization_notebook.ipynb: the code
- chart1.png, chart2.png, chart3.png: the charts

## Tools
Python, pandas, matplotlib, Google Colab

## Limitations
Revenue figures include cancelled and returned orders unless stated
otherwise. TotalPrice is calculated before coupon discounts.
