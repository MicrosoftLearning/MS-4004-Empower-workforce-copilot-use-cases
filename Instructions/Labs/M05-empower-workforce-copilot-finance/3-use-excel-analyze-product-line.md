# Exercise 1, Task 1: Use Copilot in Excel to analyze new product line COGS
---
The Finance team is finalizing Cost of Goods Sold (COGS) estimates for Fabrikam’s new EcoSmart product line. As the team’s lead financial analyst, you're tasked with verifying the latest COGS data provided by the Operations team and ensuring leadership can easily review the most relevant numbers. Leadership wants to understand which product features or materials are driving higher production costs so they can evaluate where to optimize suppliers or production processes.

To accomplish these goals, you plan to use Microsoft Copilot in Excel to go beyond sorting and filtering. You want to analyze patterns in the COGS data, identify top cost drivers, and generate a summary of insights that can be shared with the Operations team.

This task reflects how financial analysts actually work, focusing on both insights and data manipulation. It shows how Copilot can analyze data contextually, uncover relationships or anomalies, and produce a management-ready summary in minutes.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download the **EcoSmart COGS Estimates.xlsx** file. Store the file in your OneDrive account for use by Copilot in your tenant.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page **(https://www.office.com)**, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, select the **Upload a file** button, navigate to your OneDrive, and then select the **EcoSmart COGS Estimates** spreadsheet.

4.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

5.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

6.  In the **Apps Skills** pane, ask Copilot to analyze the data to help you understand the dataset. Submit the following prompt:
  
    > [!NOTE]
    > For this first prompt, we’ve provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate._
    
    **I’m a financial analyst for Fabrikam. I was asked to analyze the EcoSmart COGS Estimates spreadsheet for Fabrikam’s new EcoSmart product line. Can you please review the dataset in this spreadsheet and provide two things: (1) a clear description of each key column and its purpose, and (2) a list of any missing or inconsistent data points that could affect accuracy. Present your findings in a concise, structured format that is easy to share with the Operations team.**

7.  Select the **Copy** icon that appears below the results. Then add a new sheet to the workbook and paste in the results. Rename the sheet from **Sheet2** to **Analysis Summary**.

8.  Select **Sheet1** to return to the dataset. Your next task is to identify cost trends. Ask Copilot to find patterns in the data and summarize which product features or components have the highest average COGS.

9.  Review the results. If Copilot generated a table or chart, insert it into the workbook. The way in which you insert a visual depends on the insert option that Copilot provides. When Copilot generates a table or chart in the **App Skills** pane, it provides one of the following options:

    - **Insert to sheet**. This option inserts the visual into the active sheet. In doing so, it inserts the visual starting in whichever cell is currently selected. When you select this option, make sure you first select a cell below the final line of data so that the visual isn’t inserted in the middle of the data.

    - **+Insert to new sheet (sometimes this displays as +Add to new sheet)**. This option creates a new sheet and inserts the data in it. You can then rename the sheet from SheetX (where X is the number that Copilot assigned to the new sheet) to a more representative name. Keep in mind that after it inserts the visual into a new sheet, Copilot doesn’t return you to the datasheet from which the visual was created. If you want to perform other analysis using that datasheet, you must select it yourself.

10.  Insert the visual into either the active sheet or a new sheet, depending on the insert option Copilot provided. If you inserted it into a new sheet, rename the new sheet to **Cost Trends** and then select **Sheet1** to return to the dataset sheet.

11.  You now want Copilot to identify any anomalies in the COGS data. Ask Copilot to look for any outliers or anomalies in the COGS data that could indicate data errors or unusually high material costs.

12.  Review the results. If Copilot generated a visual of anomalies, then insert the visual into the active sheet or new sheet, depending on the option it provided. If you inserted it into a new sheet, rename the new sheet to **Anomalies** and then select **Sheet1** to return to the dataset sheet.

13.  You now want to ask Copilot to generate a brief summary report of the top three cost drivers and any opportunities to reduce costs.

14.  Review the results. In our testing, Copilot generated a table of information and a textual summary of the cost drivers and cost reduction opportunities. If Copilot generated similar results for you, you decide to insert both the table and the text into a new sheet. There’s two ways to insert the table and text, but the table appears differently in each. Perform the following steps to see how the results appear in each method:  

        - **Method 1 - Insert the table and text at the same time**. Select the **Copy** icon that appears below the results. Then add a new sheet to the workbook and paste in the results. Note the appearance of the table.
    
        - **Method 2 - Insert the table and the text separately**. Select the **Insert to new sheet** button that appears below the table. Copilot should create a new sheet that contains this table. Next, select the **Copy** icon that appears below the results just as you did in the prior step to copy all the results. Paste the copied content at the bottom of this new sheet. 
    
            This new sheet now has two tables—one that Copilot inserted and one that you pasted in along with the text. Note how the table that was copied in with the text isn’t quite as visually appealing as the table that Copilot inserted. Since the inserted table is more attractive, delete the table that came with the copied text. Rename the sheet to **Cost Summary** and then delete the sheet that you created in Method 1.  
        
15.  Select **Sheet1** to return to the dataset. Finally, ask Copilot to create a bar chart that shows the top five product features by average COGS. Insert this chart to a new sheet and rename it to **Top 5 COGS**.


16. Save the updated spreadsheet so that you can use it for later presentation. You plan to reference these findings in a future meeting with your Finance Manager to discuss next steps.
