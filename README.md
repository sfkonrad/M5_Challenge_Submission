# **M5_Challenge_Submission**
## **Financial Planning with APIs and Simulations**
### For this Project, we created two financial analysis tools for a local Credit Union by using a single Jupyter notebook:

### **Part 1: Financial Planner for Emergencies** 
> The members are now able to use this tool to visualize their current savings. Further, they can then determine if they have enough reserves for an emergency fund.

### **Part 2: Financial Planner for Retirement** 
> This tool forecasts the performance of the member's retirement portfolio over the course of 30 years. To do this, we developed a tool that makes Alpaca API calls via the Alpaca SDK to obtain both live and historical price data for use in our Monte Carlo simulations.

We then proceeded to use the statistics generated from the Monte Carlo simulation(s) to answer critical questions about the portfolio in our Jupyter notebook.

![image](./README_images/IMAGE_Cumulative_Portfolio_Return_Trajectories.jpg)



---
###  **NOTE**
At the time this repo was updated (2021.02.04.18:00PST) it appears that my local dev environment was experiencing some issues with calling data for `ten_year_ago` from its corresponding dataframe. The script appears to be running correctly. However as a result, the incoming data being called for the 30-Year MC simulations is corrupted and will need to be re-read and committed to the repo again at a later time. For perspective, the `95% CI Upper` in v2.0 is currently represented as `75.5114`; it should be just over 1/5 of that value, apprx. `17.5`.

**Until then, please accept ["M5_Challenge_v1.0_KonradK_financial_planning_tools.ipynb"](https://github.com/sfkonrad/M5_Challenge_Submission/blob/main/M5_Challenge_v1.0_KonradK_financial_planning_tools.ipynb) as the submission on record for the Module_5_Challenge.**

v2.0 incorporates experimental feature like 
- Automated calls for current dates
- A questionaire form asking the user to confirm data imputed to the script
![image](./README_images/IMAGE_questionaire.jpg)

![image](./README_images/IMAGE_30_year_timedelta.jpg)
![image](./README_images/IMAGE_30_year_bad_head.jpg)
![image](./README_images/IMAGE_30_year_bad_values.jpg)
