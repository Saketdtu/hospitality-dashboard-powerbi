
---

### **2. Hospitality Analytics Dashboard**  
*(Power BI + DAX)*  

```markdown
# Hospitality Analytics Dashboard  
![PowerBI](https://img.shields.io/badge/Power_BI-Visualization-yellow)
![DAX](https://img.shields.io/badge/DAX-Data_Modeling-lightgrey)

Interactive dashboard analyzing hotel booking data with actionable business insights.

## Project Goal  
To visualize hospitality KPIs and enable data-driven decisions through dynamic filtering and time intelligence.

## Key Metrics Analyzed  
- **Revenue Analysis**: Monthly trends, hotel-type comparison  
- **Cancellation Rates**: By market segment & country  
- **Guest Demographics**: Adult/children ratio, customer type  
- **Booking Channels**: Direct vs agent vs corporate  

## Tools Used  
- **Power BI Desktop**: Dashboard development  
- **DAX Formulas**: For calculated metrics:  
  ```DAX
  Total Revenue = [adr] * ([stays_in_week_nights] + [stays_in_weekend_nights])
  Profit Margin = DIVIDE([Total Revenue] - [Cost], [Total Revenue])
