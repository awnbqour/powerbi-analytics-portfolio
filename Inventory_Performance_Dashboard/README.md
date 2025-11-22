# Inventory Performance Dashboard

This dashboard provides a comprehensive view of **inventory health and operational stock movement** across branches and vendors.

### 🔍 Key Insights Enabled
- Total stock value over time  
- Units on hand vs. valuation  
- Stockout events (daily, monthly, YOY)  
- Inventory risk quadrant  
- Category → Subcategory → Product drill path  
- Branch-level stock distribution  
- Vendor performance in stockouts  

### 🛠 Techniques Used
- Optimized DAX measures for stock value as-of dates  
- Dynamic filtering across multi-level hierarchies  
- Custom visuals (zebra BI, KPI cards)  
- Star-schema modeling (factInventory, dimProduct, dimBranch…)
