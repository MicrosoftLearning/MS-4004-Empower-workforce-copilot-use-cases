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

As of this writing, you currently have two options when working with Copilot in Excel—Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download **Contoso_HR_ManagerMetrics.xlsx** and then store it in your OneDrive account.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page **(https://www.office.com)**, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select **Upload a file**, and then open the **Contoso_HR_ManagerMetrics.xlsx** file that you stored in your OneDrive.

4.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

5.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

6.  In the **Apps Skills** pane, ask Copilot in Excel to summarize this dataset and highlight which metrics most strongly indicate manager effectiveness.
  
    > [!NOTE]
    > For this first prompt, we’ve provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate.

    **Summarize the dataset in Contoso_HR_ManagerMetrics.xlsx and identify which HR metrics most strongly indicate manager effectiveness. This task is part of an HR review at Contoso to evaluate manager strengths and development opportunities, such as high attrition or low training completion. Use the columns provided in the file (Engagement Score, Attrition Rate, Training Completion, Average Team Tenure, Internal Promotions, Performance Rating). Present the results in a clear, concise table with actionable insights that can be included in a report.**

7.  Review the results. At the end of the response, select the **+Insert to new sheet** button (this button sometimes appears as **Add to new sheet**). If the **+Insert to new sheet** button doesn’t appear, then copy and paste the results into a new sheet. Review the results that Copilot added into Sheet2. Rename Sheet2 as **Summary**.

    > [!CAUTION]
    > If you ask Copilot to generate a table or graphic that you can add to a new sheet, it might provide a button to add the chart to the existing sheet (for example, **Add to sheet** rather than **Add to new sheet**). If you add a table or graphic to an existing sheet, ensure the cursor is in a selected cell below the data; otherwise, the table or graphic is displayed wherever the cursor is situated, which might be on top of the data.

8.  When working in Excel, you must always be on the workbook that you’re requesting Copilot to use. In this case, select **Sheet1** to return to the spreadsheet, since you want Copilot to continue working with the spreadsheet data.

9. You now want Copilot to identify trends in the data. Ask Copilot to identify managers with engagement scores below 70% and attrition rates above 15%, and present the information in a table that can be inserted into a new sheet.

10.  Review the results. Add the table to a new sheet titled **Manager scores**.

11.  Ensure you’re still in the **Manager scores** sheet. Have Copilot provide a visualization of these manager metrics that can be added to a new sheet.

12.  Review the results. Add the results to a new sheet titled **Manager charts**.

13.  Return to **Sheet1**. You want to refine your exploration with correlation prompts. Ask Copilot to determine if there are any patterns between training completion and performance ratings. Present the results in a visual chart that can be added to a new sheet.

14.  Review the results. Add the chart to a new sheet titled **Performance correlation**.

15.  Now ask Copilot to create a table that ranks managers by overall team health. It should consider engagement, attrition, and training when doing so. Present the information in a table that can be inserted into a new sheet. 
    
16.  Review the results. Add the results to a new sheet titled **Team Health**.

17.  Return to **Sheet1**. You now want to visualize the relationship between attrition rate and engagement score. Have Copilot create a bar chart showing attrition rate versus engagement score by department.  
    
18. Review the results. Add the results to a new sheet titled **Attrition correlation**.

19. Keep the tab open in your Microsoft Edge browser containing the **Contoso_HR_ManagerMetrics.xlsx** file for the next task.


At the end of this task, you should have a summarized view of manager performance and engagement across Contoso, including key indicators of team health. This dataset serves as the foundation for deeper analysis in Task 2, where you use Copilot to generate insights and produce individual manager reports.
