<div align='center'>
  <img style="width:30%" src='https://github.com/user-attachments/assets/5e4d7324-408d-428a-9072-39dc27f267d1'/>
</div>

<div align='center'> 
  <h1> 🏡 Real Estate Market Analysis 📊 </h1> 
</div>

Welcome to the **Real Estate Market Analysis** project!  
This project explores **property + customer datasets** to uncover trends in:

- Property prices 🏷️
- Customer demographics 👥
- Building types 🏢
- Country & State segmentation 🌍
- Sales patterns over time 📅

The workflow covers **data cleaning → merging → analysis → visualization → insights**.

---

## 🌟 Features

| **Feature** | **Description** |
| ----------- | --------------- |
| 🔧 Data Cleaning | Handle missing values, inconsistent entries, and format dates |
| 🔗 Dataset Merging | Merge **267×19** rows using `customer_id` |
| 📊 Descriptive Statistics | Summary stats by building, state, and country |
| 🧩 Segmentation | Building type segmentation, State Pareto analysis |
| 📈 Visualizations | Age histograms, deal satisfaction by country, Pareto charts, revenue trends, stacked area charts |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 🧩 Key Insights

| **Finding** | **Conclusion** |
| ----------- | -------------- |
| **Building Type Distribution** | Building 4 properties are larger, costlier, and have highest satisfaction |
| **Country Breakdown** | USA had duplicated text formatting; fixed via string cleaning |
| **State Pareto** | Few states dominate majority of sales; cumulative frequency validates US-only entries |
| **Age Analysis** | Age groups created → shows differences in buying patterns |
| **Price Bands** | 10 price intervals reveal sold vs unsold distribution |
| **Age–Price Relationship** | Weak–moderate correlation observed via covariance & correlation |

---

### 🔹 Detailed Visualizations

<table align="center" style="width:100%; border-collapse:collapse;">

<tr>
<td style="text-align:center; padding:12px;">
  <img width="500" alt="Deal Satisfaction by Country" src="https://github.com/user-attachments/assets/deed281d-48e5-4810-ad62-b91bce52422f">
  <p style="font-size:14px; margin-top:8px;"><strong>Deal Satisfaction by Country</strong></p>
</td>

<td style="text-align:center; padding:12px;">
  <img width="500" alt="Age Distribution Histogram" src="https://github.com/user-attachments/assets/bac09e22-e740-437e-8ea4-fab951497c1d">
  <p style="font-size:14px; margin-top:8px;"><strong>Age Distribution Histogram</strong></p>
</td>
</tr>

<tr>
<td style="text-align:center; padding:12px;">
  <img width="500" alt="US Segmentation by State Pareto Diagram" src="https://github.com/user-attachments/assets/b30ae102-077d-43bb-8196-8a24a6ac7d79">
  <p style="font-size:14px; margin-top:8px;"><strong>US Segmentation by State Pareto</strong></p>
</td>

<td style="text-align:center; padding:12px;">
  <img width="500" alt="Total Sales per Year per Building (Stacked Area Chart V2)" src="https://github.com/user-attachments/assets/5616a36c-416a-44dd-8801-7dc218d2c67e">
  <p style="font-size:14px; margin-top:8px;"><strong>Stacked Area Chart V2</strong></p>
</td>
</tr>

<tr>
<td style="text-align:center; padding:12px;">
  <img width="500" alt="Total Sales per Year per Building (Stacked Area Chart)" src="https://github.com/user-attachments/assets/ab5bb82a-52af-4849-951c-a37c495777cd">
  <p style="font-size:14px; margin-top:8px;"><strong>Stacked Area Chart</strong></p>
</td>

<td style="text-align:center; padding:12px;">
  <img width="500" alt="Total Revenue per Year in $M Line Chart" src="https://github.com/user-attachments/assets/8e5c9f16-41a5-4eb8-93ae-87db71a1f360">
  <p style="font-size:14px; margin-top:8px;"><strong>Total Revenue per Year</strong></p>
</td>
</tr>

</table>



