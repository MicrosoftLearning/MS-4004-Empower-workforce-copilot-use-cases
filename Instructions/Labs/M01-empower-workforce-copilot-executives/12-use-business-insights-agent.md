Now that you created and configured the Northwind Business Insights Agent, your next step is to practice using it to answer executive-level business questions. In this task, you plan to interact with the agent by asking questions based on the company’s Q3 sales data and Q4 budget forecast. By doing so, you can verify the agent is correctly sourcing information from the knowledge source documents and delivering actionable insights.

Perform the following steps to complete this task:

1.  The **Northwind Business Insights** **Agent** should still be open in your Microsoft Edge browser after you completed the prior task.

2.  Using the agent, ask various questions about Northwind Traders’ performance, forecasts, and risks. Use any of the following questions as a starting point, and feel free to create your own. While answers might vary, the types of answers you can expect are provided so that you can verify the accuracy of the agent.

    > [!NOTE:]
    > Business insights provided by the agent may vary. The examples provided here are representative of the types of insights you should expect to see.
    
    - **Q4 Budget Forecast questions and answers**
        - What is the projected revenue and profit margin for Beverages in North America for December, and what insights can you draw from this information? 
            - Answer:
                - Projected Revenue: $101,996
                - Profit Margin: 0.16 (16%)
                - Key insights:
                    - A 16% margin indicates steady profitability, but it’s lower than some other categories projected for Q4 (for example, Condiments reaching up to 29%). This situation suggests Beverages might have higher cost components or competitive pricing pressures.
                    - December typically sees strong beverage demand due to holidays, so the revenue projection aligns with seasonal trends. However, the margin suggests that promotional discounts or increased logistics costs might be impacting profitability.
                    - While Beverages show stable performance, any supply chain disruptions or cost escalations could quickly erode margins given the relatively modest buffer compared to high-margin categories.
                    - Executives could explore premium product positioning or cost optimization to push margins closer to 20% without sacrificing volume.  
                    
        - Provide a list of the top three product categories and regions that have the highest projected risk factor in Q4? How can Northwind Traders mitigate these risks? 
            - Answer:
                - Condiments, North America (0.29, Supply Chain Fluctuation)
                - Condiments, Asia (0.29, Stable)
                - Dairy, Europe (0.28, Demand Variability)
                - Risk mitigation:
                    - **Supply Chain Fluctuation (Condiments – Asia & North America)**
                        - **Diversify suppliers:** Secure multiple sourcing options to reduce dependency on single suppliers.
                        - **Increase safety stock:** Build buffer inventory for high-demand periods to absorb disruptions.
                        - **Leverage local procurement:** Reduce reliance on international shipping by sourcing regionally where possible.
                    - **Demand Variability (Dairy – Europe)**
                        - **Dynamic pricing strategies:** Implement flexible pricing to stimulate demand during slow periods.
                        - **Promotional campaigns:** Target seasonal promotions to stabilize sales and maintain margins.
                        - **Forecast accuracy:** Use advanced analytics to refine demand predictions and adjust production accordingly.
                    - **Cross-Category Risk Management**
                        - **Scenario planning:** Model the financial effect of cost surges or demand drops to prepare contingency actions.
                        - **Cost optimization:** Review logistics, labor, and marketing spend to maintain profitability under stress.
                        - **Risk monitoring:** Establish real-time dashboards for supply chain and demand signals to act quickly.  
                    - **Executive Action Points**
                        - Prioritize Condiments for supply chain resilience measures.
                        - Implement demand stimulation strategies for Dairy in Europe.
                        - Conduct stress tests for Q4 scenarios (for example, +10% cost increase, -15% demand drop).
    
    - **Q3 Sales Data questions and answers**
        - What was the total revenue and profit for Snacks in North America in Q3? Provide a breakdown by month and overall totals. 
            - Answer:
                - July: Revenue $51,551, Profit $5,670.61
                - August: Revenue $23,890, Profit $3,344.60
                - September: Revenue $30,627, Profit $10,413.18
                - Total Q3 Revenue: $106,068
                - Total Q3 Profit: $19,428.39
        
        - How did profit margins for Dairy in Asia change from July through September? What might explain this change? 
            - Answer:
                - July: 0.15 (15%)
                - August: 0.22 (22%)
                - September: 0.27 (27%)
                - Change: Profit margin increased steadily from July to September. Causes of change include:
                    - **Improved supply chain stability.** Early Q3 likely saw higher logistics costs or delays, reducing margins. By August and September, stabilization likely lowered costs, boosting profitability.
                    - **Seasonal demand surge.** Dairy products often see increased consumption toward late summer and early fall in Asia, driving higher sales volumes and better economies of scale.
                    - **Pricing adjustments.** Strategic price increases or reduced discounting in August and September could explain the margin growth without impacting demand.
                    - **Cost optimization initiatives.** Mid-quarter improvements in margins could reflect operational efficiencies, such as renegotiated supplier contracts or reduced wastage.  
                    
    - **Cross-document questions and answers**
        - How do the projected profit margins for Q4 compare to actual margins in Q3 for Condiments in North America? Provide key insight analysis. 
            - Answer:
                - Q3 Actual Margins (from Q3 sales data):
                    - July: 0.15
                    - August: 0.20
                    - September: 0.12
                - Q4 Projected Margins (from Q4 forecast):
                    - October: 0.26
                    - November: 0.29
                    - December: 0.17
                - **Significant improvement in Q4.** Margins are projected to rise sharply in October and November compared to Q3, peaking at 29% in November. This forecast is nine percentage points higher than the best month in Q3 (August at 20%).
                - **December drop.** December’s margin falls to 17%, still above September’s 12%, but notably lower than October and November. This situation suggests potential seasonal cost pressures or promotional discounts impacting profitability.
                - **Overall trend.** Q4 projections indicate a strong recovery and growth in profitability, likely driven by improved supply chain stability and optimized pricing strategies. However, the December dip signals the need for cost control and margin protection measures during year-end operations.
    
        - What “what-if” scenarios should executives be most concerned about, given recent sales and forecasted risks?
            - Answer:
                - From Q4 forecast “What-If Scenarios”:
                    - Increase Supply Chain Cost (+10%)
                    - Decrease Demand (-15%)
                    - Increase Marketing Spend (+8%)
                    - Labor Cost Surge (+12%)
                - Given recent declines in some categories and regions, “Decrease Demand” and “Labor Cost Surge” are particularly concerning, as they could further reduce profitability in already struggling segments.
                - While marketing can boost demand, categories with thin margins (for example, Snacks in Asia, which saw a 41% profit decline YoY) might not absorb extra costs effectively, risking negative return on investment.
                - Labor-intensive categories like Dairy in Asia and Europe, which are projected to have strong Q4 margins, could see profitability squeezed if labor costs rise unexpectedly.
    

3.  In addition to the previous questions, submit one or two of your own custom queries if you wish. Review the agent’s responses. For each answer, verify that it references the correct data source and provides clear, actionable insights.
