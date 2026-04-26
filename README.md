# Demand Forecasting Model
An inventory demand forecasting model built in Excel analyzing 560 weeks of egg sales data to optimize order quantities and minimize stockout risk.    

**Models Built**
- 4-Week Moving Average — baseline forecast using rolling average of prior 4 periods.  
- **Exponential Smoothing** (α = 0.2) — adaptive forecast weighting recent demand more heavily for faster response to demand shifts.  
- **Service Level Model** (80th Percentile Buffer) — extends the exponential smoothing forecast with a rolling buffer derived from historical forecast errors, deliberately over-ordering slightly to protect against stockouts.  

**Key Findings**   
- Moving average outperformed exponential smoothing on forecast error within the training period.   
- The service level model trades a small reduction in average weekly profit (~12%) for meaningful protection against stockouts, reflecting a real-world inventory management tradeoff.  
- Optimal order quantity anchored to Week 301 training-period forecast plus one standard deviation of historical errors.  

**Tools**   
Excel · Moving Average · Exponential Smoothing · Service Level Analysis · Profit Optimization   
**Skills Demonstrated**   
Financial modeling · Demand planning · Inventory optimization · Forecasting under uncertainty   
