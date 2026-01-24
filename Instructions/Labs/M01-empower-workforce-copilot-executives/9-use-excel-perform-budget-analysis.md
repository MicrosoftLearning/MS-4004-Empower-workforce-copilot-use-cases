# Exercise 2, Task 2: Use Copilot in Excel to perform budget forecast analysis
---
As Northwind Traders’ COO, you now want to complete a budget forecast analysis. With Q4 approaching, you need to forecast Northwind Traders’ financial performance and identify areas where operational costs could be optimized. Executives must anticipate risks such as supply chain fluctuations and market shifts that could affect profitability. In this task, you plan to use Copilot in Excel to analyze budget data, project revenues and expenses, and simulate what-if scenarios. This exercise demonstrates how Copilot can help executives make informed financial decisions by revealing trends and cost-saving opportunities before they affect the bottom line.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE] 
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download the [**Northwind Traders Q4 budget forecast.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347811) file. Store the file in your OneDrive account for use by Copilot in your tenant.

2.  In your Microsoft Edge browser, sign in to the **Microsoft 365** home page (https://www.microsoft365.com), select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel** **for the web**, open the **Northwind Traders Q4 budget forecast.xlsx** file.

4.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**, since you want Copilot to work with the spreadsheet that’s currently open. If your version of Excel already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION] 
    >This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

    If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

5.  In the **Apps Skills** pane, ask Copilot to analyze the active workbook and forecast expected revenue and expenses for the next quarter. Ask it to highlight potential overspending areas, suggest cost-saving opportunities, and generate charts and tables summarizing key financial metrics.

6.  Review the analysis that Copilot generated in the App Skills pane. While the analysis is OK, it’s not as detailed as you were hoping for. At the bottom of the App Skills pane, above the Copilot prompt field, should be several prompts. If one of the prompts says “**Get deeper results using advanced analysis mode**,” select that prompt. If this prompt doesn’t appear, then manually enter it in the prompt field. When Copilot asks if you’re ready to get started, select the **Start** button.

7.  Review the results. Scroll to the bottom of the **App Skills** pane and review the new prompts that Copilot offers. Examples might include “**Visualize profit margin trends by category and region**” and “**Analyze risk factor distribution across months and regions**.” Feel free to select any of these prompts for more in-depth analysis. Now is a good opportunity to explore the breadth of analysis that Copilot in Excel offers.

8.  When you’re done analyzing the data, ask Copilot to create a “What-if Scenario” for a 10% drop in sales and display the effect on cash flow. Note how Copilot adds this analysis to the current workbook that contains the advanced analysis results.

9.  Upon further review of the material that Copilot generated, you feel that it’s missing some common charts and graphs that executives typically find valuable. To address this shortcoming, ask Copilot to generate the following visualizations (feel free to generate all these charts, or just a select few if you have time constraints):

    - **Revenue vs. Expenses by Month**. Generate a clustered column chart that compares projected revenue and expenses for Q4. It should show seasonal trends and months with tighter margins.

    - **Profit Margin by Category**. Create a bar chart that highlights which product categories (Beverages, Snacks, Condiments, and so on) have the highest and lowest margins. It should help prioritize high-margin categories for Q4 focus.

    - **Regional Performance Overview**. Generate a stacked column chart that displays revenue contribution by region (North America, Europe, Asia) across Q4 months. It reveals geographic strengths and weaknesses.

    - **Operational Cost Breakdown**. Create a pie chart that shows the proportion of Supply Chain, Marketing, and Labor costs within total expenses. It should identify major cost drivers for optimization.


10.  Save the **Northwind Traders Q4 budget forecast.xlsx** file that contains the budget forecast analysis. You plan to use this file as a knowledge source for the Business Insights agent that you create in Task 4.

