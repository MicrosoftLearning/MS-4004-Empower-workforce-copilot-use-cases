---
lab:
  title: 'Exercise 2, Task 2: Use Copilot in Excel to analyze historical RFP data'
  description: 'Using Copilot in Excel, you plan to analyze this historical RFP data to uncover patterns, such as:'
  duration: 28 minutes
  level: 100
  islab: true
---

# Exercise 2, Task 2: Use Copilot in Excel to analyze historical RFP data
---
Before you can finalize what your EcoSense 360 RFP Response Agent should know, you need data to guide your priorities when responding to RFPs. Fabrikam’s Sales Operations team maintains a record of past RFP submissions, including details on requested features, deal size, and won/loss outcomes.

Using Copilot in Excel, you plan to analyze this historical RFP data to uncover patterns, such as:

- What are the top requested features?
- Which requirements are most important to hotel clients?
- Where has Fabrikam lost deals in the past?

These insights can help ensure that the EcoSense 360 RFP Response Agent focuses on the topics that matter most to prospective customers and avoids common pitfalls in future RFPs.

#### Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in place changes to worksheets, tables, and formulas. 

- You should use Copilot’s standard prompts in Excel for quick questions, simple summaries, or one off insights about the data you’re already viewing. When using the Copilot pane, if you enter a prompt without selecting **Edit with Copilot**, Copilot responds in a chat style mode that generates suggestions or content separately, rather than making direct, in place changes to the workbook. 

- You should use **Edit with Copilot** when you want Copilot to work directly with the worksheet—such as cleaning data, adding formulas, restructuring tables, or making iterative, in place changes. **Edit with Copilot** is designed for hands on data work, so it understands the structure of the sheet and can apply changes directly, rather than just describing what you could do. 

In summary, use chat style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, it applies those changes directly to the worksheet rather than expecting the user to explicitly apply them through copy and paste.

This task uses the **Edit with Copilot** functionality.

In addition, Copilot for Excel provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you’ve used Copilot Chat, you know that it also includes a response control selector. However, its options are different from the Excel selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1.  Select the following link to download the [**Fabrikam_Historical_RFP_Data.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347524) file, which contains the historical RFP data that was created by Fabrikam’s Sales Operations team.

2.  Store the file in the **EcoSense360-RFP-Documents** folder that you created in your OneDrive in the prior task. Doing so makes it available to the EcoSense 360 RFP Response agent that you plan to create in Task 3.

3.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

4.  In **Excel for the web**, select the **Upload a file** button, and then select the **Fabrikam_Historical_RFP_Data.xlsx** file in the **EcoSense360-RFP-Documents** folder.

5. On the **Home** tab ribbon, select **Copilot**. In the Copilot pane, leave the response mode selector set to **Auto**. Then verify the **Edit with Copilot** icon appears in the prompt field next to the plus (+) sign. If you don’t see it, select the plus sign and then select **Edit with Copilot** in the drop-down menu. The icon should now appear in the prompt field.

6.  Your goal is to have Copilot summarize the data into a list of insights that can guide the EcoSense 360 RFP Response Agent’s content priorities. In the Copilot pane, ask Copilot to add a new sheet that summarizes the top five most requested product features in past RFPs, highlight patterns in deals Fabrikam lost due to missing requirements, and identify which regions have the highest win rate for EcoSense 360.

7.  Review the results. You now want Copilot to create visual summaries of key RFP insights. These visualizations can help the EcoSense 360 RFP Response Agent and the Sales team quickly identify what matters most to clients, where the team excels, and where improvements are needed. Ask Copilot to generate the following visualizations of key RFP insights, each of which should be added to a new sheet:

    - Create a bar chart showing the top five most requested features in past RFPs.

    - Generate a stacked column chart of win/loss outcomes by requested feature.

    - Make a bar chart of the frequency of key decision factors in won deals.

    - Show a pie chart of win rates by region.

    - Create a pivot table and heatmap comparing average deal size for won vs. lost RFPs.

> [!WARNING]
> During testing, Copilot in Excel usually generated the first few visuals before running into an internal issue where it couldn’t generate the remaining requests. Due to time constraints with this training, proceed to the next task if you experience this issue. Don’t wait and try again later. Remember, Copilot is still a work in progress, so sometimes these types of issues occur.

