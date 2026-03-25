---
lab:
  title: 'Exercise 2, Task 2: Use Copilot in Excel to perform budget forecast analysis'
  description: 'As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:'
  duration: 30 minutes
  level: 100
  islab: true
---

# Exercise 2, Task 2: Use Copilot in Excel to perform budget forecast analysis
---
As Northwind Traders’ COO, you now want to complete a budget forecast analysis. With Q4 approaching, you need to forecast Northwind Traders’ financial performance and identify areas where operational costs could be optimized. Executives must anticipate risks such as supply chain fluctuations and market shifts that could affect profitability. In this task, you plan to use Copilot in Excel to analyze budget data, project revenues and expenses, and simulate what-if scenarios. This exercise demonstrates how Copilot can help executives make informed financial decisions by revealing trends and cost-saving opportunities before they affect the bottom line.

#### Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in‑place changes to worksheets, tables, and formulas.

- You should use Copilot’s standard prompts in Excel for quick questions, simple summaries, or one‑off insights about the data you’re already viewing.

- You should use **Edit with Copilot** when you want Copilot to work directly with the worksheet—such as cleaning data, adding formulas, restructuring tables, or making iterative, in‑place changes.

**Edit with Copilot** is designed for hands‑on data work, so it understands the structure of the sheet and can apply changes directly, rather than just describing what you could do. In summary, use chat‑style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands‑on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, it applies those changes directly to the worksheet rather than expecting the user to explicitly apply them through copy and paste.

This task uses the **Edit with Copilot** functionality.

In addition, Copilot for Excel provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you've used Copilot Chat, you know that it also includes a response control selector. However, its options are different from the Excel selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1.  Select the following link to download the [**Northwind Traders Q4 budget forecast.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347811) file. Store the file in your OneDrive account for use by Copilot in your tenant.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** tab, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select **Upload a file** and then open the **Northwind Traders Q4 budget forecast.xlsx** file.

4.  On the **Home** tab ribbon, select **Copilot**. In the Copilot pane, leave the response mode selector set to **Auto**. Then verify the **Edit with Copilot** icon appears next to the plus (+) sign in the prompt field. If you don't see it, select the plus sign and then select **Edit with Copilot** in the drop-down menu. The icon should now appear in the prompt field. 

5.  In the Copilot prompt field, ask Copilot to analyze the active workbook and forecast expected revenue and expenses for the next quarter. Ask it to highlight potential overspending areas, suggest cost-saving opportunities, and generate charts and tables summarizing key financial metrics.

6.  Review the analysis that Copilot generated in the Copilot pane. While the analysis is fine, it’s not as detailed as you were hoping for. In this step, you’re going to ask Copilot to switch into a special analysis workflow known as **Advanced analysis mode**. This mode tells Copilot to take a deeper, calculation-based look at the spreadsheet—examining the data, running comparisons, and identifying trends—rather than just summarizing what’s visible. It generates Python code behind the scenes that performs multi-step statistical or exploratory analysis. It’s designed for advanced data science analysis, not just “thinking harder.” 

    Advanced analysis mode isn’t a separate setting that users can manually turn on; it must be requested through a prompt. While a simple prompt such as “Use advanced analysis mode to provide deeper results” is enough to initiate it, you can also request specific feedback depending on the type of data you’re dealing with. Since this task deals with financial analysis and budget forecasting, let’s enter the following prompt:

    **Use advanced analysis mode to provide deeper results. Identify key trends, outliers, and drivers, and explain what they mean. Explore patterns in this data and forecast potential outcomes.**

   > [!IMPORTANT]
   > Advanced analysis mode is different from selecting an AI model that may offer deeper reasoning. These features aren’t equivalent, and they operate at different layers of Copilot in Excel. Choosing an AI model affects how Copilot interprets prompts and explains results within the standard Excel Copilot experience. Advanced analysis mode, on the other hand, changes how the work is performed by enabling deeper, computation‑driven analysis—such as multi‑step reasoning, Python-based calculations, and more rigorous data analysis. Selecting an AI model doesn’t automatically trigger advanced analysis or guarantee deeper computation. In short, AI model selection influences how Copilot thinks and responds, while advanced analysis mode determines how the data is analyzed.

7.  Review the results of the advanced analysis that Copilot performed. At the end of the results, select the **Add to new sheet** icon. It might take a minute or two for Copilot to add its deep analysis into a new sheet. Once Copilot finishes copying its data to the sheet, analyze the data and then rename the sheet to **Analysis**.

8.  Return to the **Q4_Forecast** sheet and then ask Copilot to create a “What-if Scenario” for a 10% drop in sales and display the impact on cash flow.

9.  Once Copilot creates the “What-if Scenario” content, select the **Add to new sheet** icon. It might take a minute or two for Copilot to add this what-if scenario into a new sheet. Once Copilot finishes copying its data to the sheet, analyze the data and then rename the sheet to **Sales decline**.

10. Return to the **Q4_Forecast** sheet. Upon further review of the material that Copilot generated, you feel that it’s missing some common charts and graphs that executives typically find valuable. To address this shortcoming, ask Copilot to generate the following visualizations (feel free to generate all these charts, or just a select few if you have time constraints):

    - **Revenue vs. Expenses by Month**. Generate a clustered column chart that compares projected revenue and expenses for Q4. It should show seasonal trends and months with tighter margins.

    - **Profit Margin by Category**. Create a bar chart that highlights which product categories (Beverages, Snacks, Condiments, and so on) have the highest and lowest margins. It should help prioritize high-margin categories for Q4 focus.

    - **Regional Performance Overview**. Generate a stacked column chart that displays revenue contribution by region (North America, Europe, Asia) across Q4 months. It reveals geographic strengths and weaknesses.

    - **Operational Cost Breakdown**. Create a pie chart that shows the proportion of Supply Chain, Marketing, and Labor costs within total expenses. It should identify major cost drivers for optimization.

11. If necessary, return to the **Q4_Forecast** sheet. Scroll to the bottom of the Copilot pane and review the suggested prompts that Copilot offers. Feel free to select any of these prompts for more in-depth analysis. This is a good opportunity to explore the breadth of analysis that Copilot in Excel offers. Feel free to add any results to a new sheet if you wish.

12. Save the **Northwind Traders Q4 budget forecast.xlsx** file that contains the budget forecast analysis. You plan to use this file as a knowledge source for the Business Insights agent that you create in Task 4.
