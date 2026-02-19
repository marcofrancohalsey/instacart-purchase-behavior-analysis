## Instacart Purchase Behavior Analysis
### Overview

This project analyzes customer purchasing behavior using order, product, and user data. The objective is to quantify ordering frequency, basket size, and reorder patterns.

### Data

The analysis uses five relational datasets: orders, products, aisles, departments, and order-product records. Together they describe purchase timing, cart composition, and product taxonomy.

### Methodology
#### Load and inspect the data

Review structure, identifiers, and missing values.

#### Preprocess the data

Remove redundant duplicates, evaluate missing values according to their meaning, and standardize data types based on analytical role.

#### Analyze the data

Evaluate ordering time patterns, weekly activity, reorder intervals, basket sizes, and product-level reorder behavior.

#### Key findings

- Order activity increases from morning and peaks mid-afternoon. Weekly demand is highest on Sunday and Monday.

- Most customers place between one and three orders. The mean is three orders, and the median is two.

- Orders contain an average of 10 items, with a median of 8. Large baskets are uncommon.

- The mean reorder rate is 0.39 at product level and 0.49 at customer level, indicating consistent repeat purchasing.

- Top-ranked products across purchases, reorders, and first-added items are staple groceries, including bananas, strawberries, and milk.

### Tools

Python, Pandas, NumPy, Matplotlib