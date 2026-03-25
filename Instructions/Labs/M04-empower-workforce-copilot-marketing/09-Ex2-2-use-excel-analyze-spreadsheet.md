---
lab:
  title: 'Exercise 2, Task 2: Use Copilot in Excel to analyze a marketing spreadsheet'
  description: 'Before Copilot, a marketing professional could manually create a sparkline to this spreadsheet by performing the following steps (don’t perform these steps; this is just for comparison purposes): <br/'
  duration: 58 minutes
  level: 100
  islab: true
---

# Exercise 2, Task 2: Use Copilot in Excel to analyze a marketing spreadsheet
---
One of Contoso’s marketing analysts provided you with a monthly performance tracking spreadsheet that shows monthly sales and marketing activity across the LATAM regions for Contoso's Chai Tea product in the past year. You want to use Copilot in Excel to analyze this data and identify key trends, uncover correlations between marketing engagement and sales performance, and determine which factors might be driving product success in different months.

#### Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in place changes to worksheets, tables, and formulas. 

- You should use Copilot’s standard prompts in Excel for quick questions, simple summaries, or one off insights about the data you’re already viewing. 
- You should use **Edit with Copilot** when you want Copilot to work directly with the worksheet—such as cleaning data, adding formulas, restructuring tables, or making iterative, in place changes. 

**Edit with Copilot** is designed for hands on data work, so it understands the structure of the sheet and can apply changes directly, rather than just describing what you could do. In summary, use chat style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, it applies those changes directly to the worksheet rather than expecting the user to explicitly apply them through copy and paste.

This task uses the **Edit with Copilot** functionality.

In addition, Copilot for Excel provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you’ve used Copilot Chat, you know that it also includes a response control selector. However, its options are different from the Excel selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1.  In the prior exercise, you downloaded a Word version of the Contoso Chai Tea market trends report. In this exercise, you download an Excel spreadsheet version of this report. 
    <br/><br/>Select the following link to download a copy of the [**Contoso Chai Tea market trends**](https://go.microsoft.com/fwlink/?linkid=2268822) spreadsheet. Store this file in your OneDrive.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select **Upload a file** and then open select the **Contoso Chai Tea market trends.xlsx** file that you downloaded in Step 1.

4.  On the **Home** tab ribbon, select **Copilot**. In the Copilot pane, leave the response mode selector set to **Auto**. Then verify the **Edit with Copilot** icon appears in the prompt field next to the plus (+) sign. If you don’t see it, select the plus sign and then select **Edit with Copilot** in the drop-down menu. The icon should now appear in the prompt field.

5.  In the Copilot pane, ask Copilot to show a visual representation of the data insights from this spreadsheet. Ask it to add the visual representation to a new sheet. It might take a minute or two for Copilot to generate this visual.

6.  Review the results. At the end of the Copilot pane, if Copilot offers any suggested prompts to add more visualizations, feel free to submit any of them if they interest you.

7.  Select **Sheet 1**. In looking at the data in the spreadsheet, you notice there are some spikes and anomalies in the data. Rather than just reporting numbers, you want to look for connections between marketing activities (like social media campaigns or search trends) and sales outcomes. To do so, ask Copilot to identify the top three sales months for Total Chai Sales and flag any other months with anomalies or data quality issues. Also ask it to analyze what possibly influenced those sales and anomalies by looking at the other data in the spreadsheet during those months.

8.  Review Copilot’s response in the new sheet that it created. When you’re done, return to **Sheet 1**.

9.  You now want to see if there’s any connection between sales and marketing signals. Ask Copilot to analyze correlations between Social Media Engagement (views), Online Searches for Chai, and Total Chai Sales. Summarize the strongest relationships and any lag effects you detect.

10.  Review Copilot’s response in the new sheet that it created. When you’re done, return to **Sheet 1**.

11.  In Excel, a **sparkline** is a tiny, simple chart that fits inside a single cell. It visually shows the trend of a data series across months, such as sales, engagement, or searches. Because sparklines represent data trends for a row or column, they’re great for quickly spotting patterns, spikes, or dips without taking up much space.  
    <br/>For this spreadsheet, you want to see which months had spikes or dips in Social Media Engagement, Online Searches, and Total Chai Sales. Doing so enables you to quickly spot if the months with the most activity on social media are also the months when sales were highest.

        Before Copilot, a marketing professional could manually create a sparkline to this spreadsheet by performing the following steps **(don’t perform these steps; this is just for comparison purposes)**:
    <br/>
        1.  **Select the cells for a metric:**
              1.  For example, select the range of cells for “Total Chai Sales” (January to December).

        2.  **Insert a Sparkline:**
              1.  Go to the “Insert” tab in Excel.
              2.  Choose “Line Sparkline.”
              3.  In the dialog, set the data range (for example, B2:B13 for Total Chai Sales).
              4.  Set the location range to a cell next to your data (for example, C2).

        However, you want to see how Copilot can automate this process. To do so, ask Copilot to add sparklines to show the monthly trend between Total Chai Sales, Social Media Engagement, and Online Searches.

12.  Review the results. In our testing, Copilot added the sparklines to the Correlation Analysis sheet that it created earlier. Visually compare each sparkline to see if their spikes occur in the same months. When you're done, return to **Sheet 1**.

13.  You now want Copilot to analyze your data and suggest a possible formula or calculation that could be useful for your dataset. Doing so is especially helpful in the context of columns that require formulas to provide more insights or automate calculations. Ask Copilot to analyze the data and suggest ways to automate or enhance future work with formulas to make the data analysis faster and more efficient.

14.  Review Copilot’s response in the new sheet that it created. Feel free to submit any of Copilot's suggested prompts to improve its analysis of this spreadsheet.  
