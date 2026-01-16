# Exercise 1, Task 4: Use Copilot in Excel to model What-If scenarios
---
Robin Kline, Fabrikam’s Finance Manager, asked you to update the Relecloud acquisition financials to reflect new assumptions, such as adjusted valuation multiples and projected synergy savings. Robin wants you to:

- Update the Relecloud acquisition numbers based on a series of what-if scenarios.
- Create charts that visualize the effect of these changes.

This task showcases Copilot’s ability to perform dynamic modeling and visualization, which are essential tools for any financial analyst preparing data-driven recommendations.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.
- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download the **Relecloud Acquisition Financials.xlsx** file. Store the file in your OneDrive account for use by Copilot in your tenant.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select the **Upload a file** button, navigate to your OneDrive, and then select the **Relecloud Acquisition Financials** spreadsheet that you downloaded in step 1.

4.  Select **Copilot** in the Excel ribbon. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work or it might show an error when you submit a prompt, even when you wait awhile and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

5.  In the **Apps Skills** pane, you now want Copilot to update the acquisition financial model based on a what-if scenario and then create charts that visualize the effect of this change.

    > [!TIP]
    > During testing, if we asked Copilot to perform both steps in a single prompt, it would return an error indicating it was having trouble working on an answer. However, we didn’t experience any issue when we split our request into separate prompts. Keep that in mind when working with Copilot, since multiple requests in a single prompt can sometimes be problematic.
    
    Let's begin by requesting the what-if scenario. Ask Copilot to update the Relecloud acquisition financials to reflect a 1x increase in the earnings before interest, taxes, depreciation, and amortization (EBITDA) multiple and a 20% increase in synergy savings.

6.	Review the results. Select the option to insert the table into a new sheet.

7.  Verify you’re still in this new sheet. Then ask Copilot to generate the following charts to make it easy to visualize the magnitude and timing of improvements:
    - Column Chart comparing original vs. updated EBITDA and total synergy savings over time.
    - Line Chart showing EBITDA trend before and after the change.

8.  Review the results and charts. Insert the first chart into a new sheet. Then place your cursor in a cell below the chart and insert the second chart into the same sheet. Repeat for any other charts. Rename the sheet **What-if EBITDA**.

9.  You now want to perform another what-if scenario. Ask Copilot to update the acquisition financial model based on the following what-if scenario: Model the effect if synergy savings are delayed by 12 months and only 75% are realized.

10.	Review the results. Select the option to insert the table into a new sheet. 

11.	Verify you’re still in this new sheet. Then ask Copilot to generate the following charts that show both the timing and reduction in benefits, highlighting the effect on cash flow and return on investment (ROI):
    - Stacked Column Chart showing annual synergy savings (original vs. delayed/reduced).
    - Line Chart for cumulative synergy savings over time.

12.  Review the results and charts. Insert the first chart into a new sheet. Then place your cursor in a cell below the chart and insert the second chart into the same sheet. Repeat for any other charts. Rename the sheet **What-if Synergy savings**.

13. You now want to perform one final what-if scenario. Ask Copilot to update the financial model for a scenario where operating expenses are 10% higher due to integration challenges.

14.	Review the results. Select the option to insert the table into a new sheet. 

15.	Verify you’re still in this new sheet. Then ask Copilot to generate the following charts that highlight the effect on profitability and expense trends:
    - Line Chart for operating expenses and EBITDA over time (original vs. scenario).
    - Column Chart comparing net income before and after the change.

16.  Review the results and charts. Insert the first chart into a new sheet. Then place your cursor in a cell below the chart and insert the second chart into the same sheet. Repeat for any other charts. Rename the sheet **What-if Expenses**.
