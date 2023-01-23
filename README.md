# Customer-Segmentation

## Description
- Downloaded from Kaggle, this dataset is small in size - with 2240 rows and 29 columns.
- This dataset was selected to implement the concepts of **Agglomerative Clustering** to segment the data to different customer groups and **Profiling** to categorize and analyze the groups.

## Workflow 

```mermaid
flowchart LR
  A[Installations] --> B[Imports]
  B --> C[Loading the Dataset]
  C --> D[EDA and Data Cleaning]
  D --> E[Dimensionality Reduction]
  E --> F[Clustering]
  F --> G[Profiling]
  G --> H[Inference]
```

## Inference 

| Cluster | Is a Parent | Members in Family | Age | Income | Relationship Status | Children
| --- | --- | --- | --- | --- | --- | --- |
| 0 | Yes | 2 to 4 | > 35 and relatively older | Average | Married | Might have a teenager |
| 1 | No | 1 or 2 | > 30 and relatively older | High | Inclined to be married | No kids |
| 2 | More inclined to be one | 1 to 3 | 30 to 50 | Low | Inclined to be married | Max 1 kid |
| 3 | Yes | 2 to 5 | > 35 and relatively older | Average | Married | 1 to 3 (kids and teenager)|
