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
As Northwind Traders' COO, you now want to complete a budget forecast analysis. With Q4 approaching, you need to forecast Northwind Traders' financial performance and identify areas where operational costs could be optimized. Executives must anticipate risks such as supply chain fluctuations and market shifts that could affect profitability. In this task, you use Copilot in Excel to analyze budget data, project revenues and expenses, and simulate what-if scenarios. This exercise demonstrates how Copilot can help executives make informed financial decisions by revealing trends and cost-saving opportunities before they affect the bottom line.

## Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in-place changes to worksheets, tables, and formulas.

- Use Copilot's standard prompts in Excel for quick questions, simple summaries, or one-off insights about the data you're already viewing.

- Use **Edit with Copilot** when you want Copilot to work directly with the worksheet, such as cleaning data, adding formulas, restructuring tables, or making iterative, in-place changes.

**Edit with Copilot** is designed for hands-on data work, so it understands the structure of the sheet and can apply changes directly, rather than only describing what you could do. In summary, use chat-style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands-on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, applies those changes directly to the worksheet rather than expecting you to apply them through copy and paste.

This task uses the **Edit with Copilot** functionality.

Copilot in Excel also provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you've used **Copilot Chat**, you know that it also includes a response control selector. However, its options are different from the Excel selector. In **Copilot Chat**, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1. Select the following link to download the [**Northwind Traders Q4 budget forecast.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347811) file. Store the file in your OneDrive account for use by Copilot in your tenant.

2. In your web browser, go to the **Microsoft Copilot** home page and select the **App Launcher** (grid icon) on the top-left corner, select **More Apps**, and then select **Excel** from the list of available apps.

3. In **Excel for the web**, select **Upload a file** and then open the **Northwind Traders Q4 budget forecast.xlsx** file.

4. In the bottom-right corner of the document, select the **Copilot** icon to open the Copilot pane. In the Copilot pane, leave the response mode selector set to **Auto**. Verify the pane opens in edit mode—the heading should read **Let's edit your workbook**. Below the heading, confirm that the mode selector is set to **Allow editing** (so Copilot can edit your workbook directly). If it shows **Chat only**, select the drop-down and then select **Allow editing**.

5. In the Copilot prompt field, ask Copilot to analyze the active workbook and forecast expected revenue and expenses for the next quarter. Ask it to highlight potential overspending areas, suggest cost-saving opportunities, and generate charts and tables that summarize key financial metrics.

6. Copilot may ask one or more follow-up questions before generating the analysis. Select the option of your choice, and then select **Submit**.

7. Wait a few minutes and review the analysis that Copilot generated in the Copilot pane. The analysis is adequate, but not as detailed as you hoped. In this step, you ask Copilot to switch into a special analysis workflow known as **Advanced analysis mode**. This mode tells Copilot to take a deeper, calculation-based look at the spreadsheet—examining the data, running comparisons, and identifying trends—rather than only summarizing what's visible. It generates Python code behind the scenes that performs multi-step statistical or exploratory analysis. It's designed for advanced data science analysis, not only "thinking harder."

    Advanced analysis mode isn't a separate setting that you can manually turn on; you must request it through a prompt. A simple prompt such as "Use advanced analysis mode to provide deeper results" is enough to initiate it, but you can also request specific feedback depending on the type of data you're working with. Because this task involves financial analysis and budget forecasting, enter the following prompt:

    ```prompt
    Use advanced analysis mode to provide deeper results. Identify key trends, outliers, and drivers, and explain what they mean. Explore patterns in this data and forecast potential outcomes.
    ```
    
   > [!IMPORTANT]
   > Advanced analysis mode is different from selecting an AI model that offers deeper reasoning. These features aren't equivalent, and they operate at different layers of Copilot in Excel. Choosing an AI model affects how Copilot interprets prompts and explains results within the standard Excel Copilot experience. Advanced analysis mode, on the other hand, changes how the work is performed by enabling deeper, computation-driven analysis—such as multi-step reasoning, Python-based calculations, and more rigorous data analysis. Selecting an AI model doesn't automatically trigger advanced analysis or guarantee deeper computation. In short, AI model selection influences how Copilot thinks and responds, while advanced analysis mode determines how the data is analyzed.

8. Review the results of the advanced analysis in the Copilot pane. Copilot adds a new sheet with the deep analysis at the bottom of the workbook. Review the Copilot explanation of how it produced the results. To keep the new sheet, select **Done** at the bottom of the Copilot pane. Select the new sheet tab, review the data Copilot generated, and then rename the sheet to **Analysis**.

9. Select the **Q4_Forecast** sheet tab to make it the active sheet. In the Copilot prompt field, ask Copilot to create a what-if scenario for a 10% drop in sales on a new sheet, and to display the impact on cash flow. For example, enter:

   ```prompt
   Create a what-if scenario on a new sheet that shows the impact on cash flow of a 10% drop in sales.
   ```

10. Copilot may ask one or more follow-up questions about how costs should behave when sales fall. Select the option of your choice, and then select **Submit**. Copilot adds the what-if scenario to a new sheet at the bottom of the workbook—it might take a minute or two to finish. Select the new sheet tab, review the data Copilot generated, and then rename the sheet to **Sales decline**.

11. Return to the **Q4_Forecast** sheet. After further review of the material that Copilot generated, you notice that it's missing some common charts and graphs that executives typically find valuable. To address this shortcoming, ask Copilot to generate the following visualizations (generate all these charts, or a few if you have time constraints):

    - **Revenue vs. Expenses by Month**: Generate a clustered column chart that compares projected revenue and expenses for Q4. It should show seasonal trends and months with tighter margins.

    - **Profit Margin by Category**: Create a bar chart that highlights which product categories (Beverages, Snacks, Condiments, and so on) have the highest and lowest margins. It should help prioritize high-margin categories for Q4 focus.

    - **Regional Performance Overview**: Generate a stacked column chart that displays revenue contribution by region (North America, Europe, Asia) across Q4 months. It reveals geographic strengths and weaknesses.

    - **Operational Cost Breakdown**: Create a pie chart that shows the proportion of Supply Chain, Marketing, and Labor costs within total expenses. It identifies drivers for optimization.

12. If necessary, return to the **Q4_Forecast** sheet. Scroll to the bottom of the Copilot pane. Copilot may display suggested prompts for further analysis. If suggested prompts appear, feel free to choose any of them for more in-depth analysis. If no suggested prompts appear, try entering your own prompt. This is a good opportunity to explore the breadth of analysis that Copilot in Excel offers. Add any results to a new sheet if you wish.

13. When you are satisfied with the results, select **Done**, and then save the **Northwind Traders Q4 budget forecast.xlsx** file that contains the budget forecast analysis. You will use this file as a knowledge source for the Business Insights agent that you create in Task 4.
