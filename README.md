# Data Analysis of Beijing Real Estate

## Project Description

In this project, we analyze real estate data from Beijing to extract comprehensive and useful insights. The project includes multiple stages of data cleaning, transformation, and visualization to uncover trends and patterns in the housing market. The final results of our analysis are illustrated using a variety of visualizations.

This project consists of five main parts:

1. **Data Loading and Initial Cleaning**  
   In the first stage, we load the dataset and remove unnecessary columns. Additionally, we handle any missing values to ensure data quality.

2. **Data Formatting**  
   In this step, we convert columns to the appropriate formats and remove any redundant data, preparing the data for further analysis.

3. **Feature Engineering**  
   New features are created based on the existing data, which will be beneficial for deeper analysis in the subsequent steps.

4. **Geographical Visualization**  
   Using the longitude and latitude of the properties, we plot them on a map to gain a general view of property distribution across different areas.

5. **Temporal Analysis**  
   Finally, using transaction dates, we analyze the timing of transactions to observe any patterns over time.

## Required Libraries

This project utilizes the following libraries. Make sure they are installed by using the `requirements.txt` file provided.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

## Installation

You can install the required libraries by running the following command:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file contains the necessary libraries for this project.

## Data Description

The main dataset file contains the following columns:

| Column         | Description                                                                                     |
|----------------|-------------------------------------------------------------------------------------------------|
| InvoiceNumber  | A unique 6-digit number assigned to each invoice. If this number starts with the letter 'C,' it indicates that the invoice is canceled. |
| ProductCode    | A unique 5-digit number assigned to each product type.                                          |
| ProductName    | The name of the product.                                                                        |
| Quantity       | The quantity ordered for each product in the invoice.                                           |
| InvoiceDate    | The date the invoice was created.                                                               |
| UnitPrice      | The price per unit for each item.                                                               |
| CustomerId     | A unique 5-digit number assigned to each customer.                                              |
| Country        | The customer's country of residence.                                                            |

This table provides an overview of the data columns used in the analysis.
