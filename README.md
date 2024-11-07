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

<center>
<table style="direction: rtl;align: center; text-align: justify;line-height:200%;font-family:vazir;font-size:medium">
  <tr>
      <td><code>Unnamed: 0</code></td><td>نمایه‌ی داده‌هاست که نیازی به آن نداریم و باید حذف شود.</td>
</tr>

  <tr>
      <td><code>url</code></td><td>لینک معامله</td>
</tr>
 

<tr>
      <td><code>id</code></td><td>شناسه‌ی معامله</td>
</tr>
 
<tr>
      <td><code>Lng</code></td><td>طول جغرافیایی خانه‌ی معامله شده</td>
</tr>
 
  
<tr>
      <td><code>Lat</code></td><td>عرض جغرافیایی خانه‌ی معامله شده</td>
</tr>
 
  
<tr>
      <td><code>Cid</code></td><td>شناسه‌ی خریدار</td>
</tr>
 
       
 
<tr>
      <td><code>tradeTime</code></td><td>زمان انجام معامله</td>
</tr>    

 
<tr>
      <td><code>DOM</code></td><td>تعداد روزی که از زمان گذاشتن آگهی خانه می‌گذرد.</td>
</tr>    

<tr>
      <td><code>totalPrice</code></td><td>قیمتی که خانه به فروش رفته است.</td>
</tr>    
  
<tr>
      <td><code>square</code></td><td>متراژ خانه</td>
</tr>       

<tr>
      <td><code>livingRoom</code></td><td>تعداد اتاق نشیمن</td>
</tr>       


    
<tr>
      <td><code>drawingRoom</code></td><td>تعداد اتاق پذیرایی</td>
</tr>       

    
    
<tr>
      <td><code>kitchen</code></td><td>تعداد آشپزخانه</td>
</tr>       

        
<tr>
      <td><code>bathRoom</code></td><td>تعداد حمام</td>
</tr>       


<tr>
      <td><code>floor</code></td><td>طبقه و ارتفاع خانه</td>
</tr>       

    
<tr>
      <td><code>constructionTime</code></td><td>سال ساخت خانه</td>
</tr>       
  
  
    
<tr>
      <td><code>renovationCondition</code></td><td>وضعیت نوسازی خانه</td>
</tr>       
  
    
<tr>
      <td><code>buildingStructure</code></td><td>ساختار خانه</td>
</tr>       
  

<tr>
      <td><code>ladderRatio</code></td><td>طبقه و ارتفاع خانه</td>
</tr>             
  
<tr>
      <td><code>elevator</code></td><td>خانه آسانسور دارد یا خیر</td>
</tr>       
  
  
<tr>
      <td><code>subway</code></td><td>خانه به مترو دسترسی دارد یا خیر</td>
</tr>    
    
  
<tr>
      <td><code>district</code></td><td>منطقه‌ای که خانه در آن قرار دارد</td>
</tr>    
    

</table>

</center>                                         |

This table provides an overview of the data columns used in the analysis.
