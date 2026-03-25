---
lab:
  title: 'Exercise 1, Task 1: Use Copilot in Excel to identify key manager metrics'
  description: At the end of this task, you should have a summarized view of manager performance and engagement across Contoso, including key indicators of team health. This dataset serves as the foundation for deeper analysis in Task 2, where you use Copilot to generate insights and produce individual manager reports.
  duration: 48 minutes
  level: 100
  islab: true
---

# Exercise 1, Task 1: Use Copilot in Excel to identify key manager metrics
---
Contoso's Chief People Officer, Holly Dickson, provided you with a spreadsheet containing manager-level performance and engagement metrics. Holly then asked you to identify which metrics best indicate manager strengths and which might reveal opportunities for development, such as high attrition or low training completion. You plan to use Microsoft 365 Copilot in Excel to explore and summarize key HR metrics that provide insights into manager effectiveness.

These key HR metrics are stored in the file titled **Contoso_HR_ManagerMetrics.xlsx**. This dataset includes:

- Manager Name
- Department
- Engagement Score (%)
- Attrition Rate (%)
- Training Completion (%)
- Average Team Tenure (Years)
- Internal Promotions (Past Year)
- Performance Rating (1–5)

#### Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in‑place changes to worksheets, tables, and formulas.

- You should use Copilot’s standard prompts in Excel for quick questions, simple summaries, or one‑off insights about the data you’re already viewing. When using the Copilot pane, if you enter a prompt without selecting **Edit with Copilot**, Copilot responds in a chat‑style mode that generates suggestions or content separately, rather than making direct, in‑place changes to the workbook.  
    
- You should use **Edit with Copilot** when you want Copilot to work directly with the worksheet—such as cleaning data, adding formulas, restructuring tables, or making iterative, in‑place changes. **Edit with Copilot** is designed for hands‑on data work, so it understands the structure of the sheet and can apply changes directly, rather than just describing what you could do.

In summary, use chat‑style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands‑on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, it applies those changes directly to the worksheet rather than expecting the user to explicitly apply them through copy and paste.  

This task uses the **Edit with Copilot** functionality.

In addition, Copilot for Excel provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you’ve used Copilot Chat, you know that it also includes a response control selector. However, its options are different from the Excel selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1.  Select the following link to download [**Contoso_HR_ManagerMetrics.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347518) and then store it in your OneDrive account.

2.  In your Microsoft Edge browser, sign in to the **Microsoft 365** home page **(https://www.microsoft365.com)**, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select **Upload a file**, and then open the **Contoso_HR_ManagerMetrics.xlsx** file that you downloaded in Step 1.

4.  On the **Home** tab ribbon, select **Copilot**. In the Copilot pane, leave the response mode selector set to **Auto**. Then verify the **Edit with Copilot** icon appears in the prompt field next to the plus (+) sign. If you don’t see it, select the plus sign and then select **Edit with Copilot** in the drop-down menu. The icon should now appear in the prompt field. 

5. In the Copilot pane, ask Copilot in Excel to summarize this dataset and highlight which metrics most strongly indicate manager effectiveness.

  > [!NOTE]
  > For this first prompt, we’ve provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate._

  **Summarize the dataset in Contoso_HR_ManagerMetrics.xlsx and identify which HR metrics most strongly indicate manager effectiveness. This task is part of an HR review at Contoso to evaluate manager strengths and development opportunities, such as high attrition or low training completion. Use the columns provided in the file (Engagement Score, Attrition Rate, Training Completion, Average Team Tenure, Internal Promotions, Performance Rating). Present the results in a clear, concise table with actionable insights that can be included in a report.**

6.  Review the results in the new sheet.

7.  When working in Excel, you must always be on the workbook that you’re requesting Copilot to use. In this case, select **Sheet1** since you want Copilot to continue working with the spreadsheet data. Next, you want Copilot to identify trends in the data, so ask Copilot to identify managers with engagement scores below 70% and attrition rates above 15%, and present the results in a new sheet.

8.  Review the results. You now want Copilot to create a visualization for this new sheet, so remain in the sheet and place your cursor after the last line of information. This cell is where you want Copilot to insert the visualization. Then ask Copilot to provide a visualization of the managers with engagement scores below 70% and attrition rates above 15%.

9.  Review the results and then return to **Sheet1**. You want to refine your exploration with correlation prompts. Ask Copilot to determine if there are any patterns between training completion and performance ratings, and then present the results in a new sheet.

10.  Review the results and then return to **Sheet1**. Now ask Copilot to create a table that ranks managers by overall team health. It should consider engagement, attrition, and training, and then present the results in a new sheet.  

11. Review the results and then return to **Sheet1**. You now want to visualize the relationship between attrition rate and engagement score. Ask Copilot to create a bar chart that shows attrition rate versus engagement score by department, and then present the results in a new sheet.

12.  Review the results.

13.  Keep the tab open in your Microsoft Edge browser containing the **Contoso_HR_ManagerMetrics.xlsx** file for the next task.

At the end of this task, you should have a summarized view of manager performance and engagement across Contoso, including key indicators of team health. This dataset serves as the foundation for deeper analysis in Task 2, where you use Copilot to generate insights and produce individual manager reports.
