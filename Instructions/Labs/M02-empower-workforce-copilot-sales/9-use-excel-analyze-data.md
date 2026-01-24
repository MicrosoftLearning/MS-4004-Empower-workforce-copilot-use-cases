# Exercise 2, Task 2: Use Copilot in Excel to analyze historical RFP data
---
Before you can finalize what your EcoSense 360 RFP Response Agent should know, you need data to guide your priorities when responding to RFPs. Fabrikam’s Sales Operations team maintains a record of past RFP submissions, including details on requested features, deal size, and won/loss outcomes.

Using Copilot in Excel, you plan to analyze this historical RFP data to uncover patterns, such as:

- What are the top requested features?
- Which requirements are most important to hotel clients?
- Where has Fabrikam lost deals in the past?

These insights can help ensure that the EcoSense 360 RFP Response Agent focuses on the topics that matter most to prospective customers and avoids common pitfalls in future RFPs.

As of this writing, you currently have two options when working with Copilot in Excel: Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download the [**Fabrikam_Historical_RFP_Data.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347524) file, which contains the historical RFP data that was created by Fabrikam’s Sales Operations team.

2.  Store the file in the **EcoSense360-RFP-Documents** folder that you created in your OneDrive in the prior task. Doing so makes it available to the EcoSense 360 RFP Response agent that you plan to create in Task 3.

3.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

4.  In **Excel for the web**, open the **Fabrikam_Historical_RFP_Data.xlsx** file.

5.  Select **Copilot** in the Excel ribbon. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, which is expected during the transition.

6.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

7.  Your goal is to have Copilot summarize the data into a list of insights that can guide the EcoSense 360 RFP Response Agent’s content priorities. In the **Apps Skills** pane, ask Copilot to summarize the top 5 most requested product features in past RFPs, highlight patterns in deals Fabrikam lost due to missing requirements, and identify which regions have the highest win rate for EcoSense 360.

8.  Review the results. For each insight, Copilot should provide an option to insert it into a new sheet. Select this option for each insight.

9.  You now want Copilot to create visual summaries of key RFP insights. These visualizations can help the EcoSense 360 RFP Response Agent and the Sales team quickly identify what matters most to clients, where the team excels, and where improvements are needed. Ask Copilot to generate pivot tables, charts, or summary tables to visualize trends. For each visual that Copilot generates, insert it into a new sheet. If the option says **Insert to a sheet** (rather than **Add to new sheet**), then Copilot inserts it into the currently displayed sheet. In this case, add a new sheet before selecting the **Insert to a sheet** option; doing so ensures that each visual is in its own sheet.  
    <br/>Key visuals that you should consider requesting include:
    - Create a bar chart showing the top five most requested features in past RFPs.
    - Generate a stacked column chart of win/loss outcomes by requested feature.
    - Make a bar chart of the frequency of key decision factors in won deals.
    - Show a pie chart of win rates by region.
    - Create a pivot table and heatmap comparing average deal size for won vs. lost RFPs.

> [!WARNING]
> During testing, Copilot in Excel usually generated the first few visuals before running into an internal issue where it couldn’t generate the remaining requests. Due to time constraints with this training, proceed to the next task if you experience this issue. Don’t wait and try again later. Remember, Copilot is still a work in progress, so sometimes these types of issues occur.


