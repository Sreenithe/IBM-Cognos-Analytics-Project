# IBM-Cognos-Analytics-Project
Case study done in IBM Cognos analytics
Problem statement , dataset
 
Case Study 15 
SwiftRoute Logistics - Delivery & Fleet Analytics 
Industry: Logistics & Supply Chain Modules: Reporting, Exploration, Dashboard, Story 
Making 
 
 
 Real-Time Business Scenario 
SwiftRoute Logistics manages a fleet of 500 vehicles delivering goods for e-commerce, FMCG, and 
pharmaceutical clients across 20 states in India. Operations management is troubled by rising fuel 
costs, increasing delivery failures, vehicle breakdowns causing delays, and customer complaints about 
damaged shipments. The Fleet Manager wants IBM Cognos Analytics to monitor delivery efficiency, 
vehicle health, driver performance, and client SLA compliance. 
 
 

 Dataset / Data Available 
• Shipment ID, Client Name, Client Industry, Origin City, Destination City, Route Name 
• Vehicle ID, Vehicle Type (Truck/Van/Bike), Driver Name, Driver Experience (years) 
• Dispatch Date, Expected Delivery Date, Actual Delivery Date, Delivery Status (On-Time/Delayed/Failed) 
• Distance (km), Fuel Used (liters), Fuel Cost, Breakdown Flag, Damage Flag, Customer Rating (1–5) 
 
 
❓  Case Study Questions 
 
Q1 [Reporting]  Create a Delivery Performance Report grouped by Client Name showing Total 
Shipments, On-Time Deliveries, Delayed, Failed, and SLA Compliance Rate % (On-Time / Total 
* 100). Apply Conditional Styling: SLA Compliance < 85% in Red, 85–95% in Amber, > 95% 
in Green. Add prompts for Client Industry and Route Name. Add Header with SwiftRoute 
branding, Footer with 'Operations Confidential'. 
 
Q2 [Reporting]  Build a Vehicle Breakdown & Damage Report listing Vehicle ID, Vehicle Type, 
Driver Name, Breakdown Count, Damage Count, and Total Fuel Cost. Apply Conditional 
Styling: Vehicles with Breakdown Count > 3 in the month highlighted in Red. Add a calculated 
Fuel Efficiency column = Distance / Fuel Used. Summarize total breakdown cost impact in the 
footer. Use Trebuchet MS, size 11. 
 
Q3 [Reporting]  Using Report Visualize Prompt, allow Fleet Managers to select chart type (Bar or 
Line) to view Route-wise On-Time Delivery Rate across all 20 states. Add prompts for Vehicle 
Type and Month. Apply Conditional Styling: Routes with Delivery Failure Rate > 10% in Red. 
Summarize the top 3 problem routes and top 3 best routes as text annotations. 
  
Q4 [Exploration]  Use Cognos Exploration on the SwiftRoute dataset to analyze the relationship 
between Driver Experience and Delivery Failure Rate. Investigate whether certain Vehicle Types 
are more prone to breakdowns and how that affects SLA compliance. Explore the correlation 
between Distance and Fuel Efficiency. Document findings with annotated exploration charts. 
 
Q5 [Dashboard]  Design a SwiftRoute Fleet Operations Dashboard with: (1) KPI tiles — Total 
Shipments, On-Time Rate %, Breakdown Count, Total Fuel Cost, (2) A Bar chart for Shipments 
by Client, (3) A Line chart for Daily Delivery Volume Trend, (4) A Pie chart for Delivery Status 
Distribution, (5) A Driver Performance table by Rating. Add Route and Vehicle Type filters. 
 
Q6 [Story Making]  Create a Cognos Story for SwiftRoute's Monthly Fleet Review: Scene 1 — 
Operations Overview & Fleet Statistics, Scene 2 — Client SLA Compliance Performance, Scene 
3 — Delivery Failure & Damage Analysis, Scene 4 — Vehicle Breakdown Trends & Fleet 
Health, Scene 5 — Driver Performance & Fuel Efficiency, Scene 6 — Route Optimization & 
Cost Reduction Recommendations.
