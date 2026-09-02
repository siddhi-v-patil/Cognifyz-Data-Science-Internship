# Level 2 — Task 3: Feature Engineering

## Internship

Cognifyz Data Science Internship

## Task

Feature Engineering

## Objective

The objective of this task is to create meaningful new features from the existing restaurant dataset.

The task focuses on:
- Extracting additional features from existing columns.
- Encoding categorical variables into numerical values.

## Features Created

### 1. Restaurant Name Length

Calculated the number of characters in each restaurant name.

```python
df["Restaurant Name Length"] = df["Restaurant Name"].str.len()
