One of Contoso’s marketing analysts provided you with a monthly performance tracking spreadsheet that shows monthly sales and marketing activity across the LATAM regions for Contoso's Chai Tea product in the past year. You want to use Copilot in Excel to analyze this data and identify key trends, uncover correlations between marketing engagement and sales performance, and determine which factors might be driving product success in different months.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  In the prior exercise, you downloaded a Word version of the Contoso Chai Tea market trends report. In this exercise, you download an Excel spreadsheet version of this report. Select the following link to download a copy of the [**Contoso Chai Tea market trends**](https://go.microsoft.com/fwlink/?linkid=2268822) spreadsheet. Store this file in your OneDrive.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

3.  In **Excel for the web**, open the **Contoso Chai Tea market trends.xlsx** file.

4.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

5.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

6.  In the **Apps Skills** pane, ask Copilot to show a visual representation of the data insights from this spreadsheet.

7.  In looking at the data in the spreadsheet, you notice there are some spikes and anomalies in the data. Rather than just reporting numbers, you want to look for connections between marketing activities (like social media campaigns or search trends) and sales outcomes. To do so, ask Copilot to identify the top three sales months for Total Chai Sales and flag any other months with anomalies or data quality issues. Also ask it to analyze what possibly influenced those sales and anomalies by looking at the other data in the spreadsheet during those months.

8.  Review Copilot’s response. Select the **Copy** icon at the bottom of the results, open a new sheet, and then paste in the copied text. Doing so enables you to document the reasons behind the high sales months and the months with anomalies. Rename the sheet to **Data analysis**. When you’re done, return to **Sheet 1**.

9.  You now want to see if there’s any connection between sales and marketing signals. Ask Copilot to analyze correlations between Social Media Engagement (views), Online Searches for Chai, and Total Chai Sales. Summarize the strongest relationships and any lag effects you detect.

10.  Review Copilot’s response. If Copilot includes a chart along with its analysis, it might include a button to insert the chart to a new sheet. If so, select this button. 

11. Since you also want to save Copilot’s analysis, select the **Copy** icon at the bottom of the results, position your cursor below the chart in the new sheet, and then paste in the copied text. Notice how the chart was pasted in a second time along with the text. Since the original chart that you inserted looks better, delete the lines containing the second chart that was pasted in with the text. Rename the sheet to **Engagement Correlation**. When you’re done, return to **Sheet 1**.

12.  In Excel, a **sparkline** is a tiny, simple chart that fits inside a single cell. It visually shows the trend of a data series across months, such as sales, engagement, or searches. Because sparklines represent data trends for a row or column, they’re great for quickly spotting patterns, spikes, or dips without taking up much space.  
    <br/>For this spreadsheet, you want to see which months had spikes or dips in Social Media Engagement, Online Searches, and Total Chai Sales. Doing so enables you to quickly spot if the months with the most activity on social media are also the months when sales were highest.
    <br/><br/>Before Copilot, a marketing professional could manually create a sparkline to this spreadsheet by performing the following steps **(don’t perform these steps; this is just for comparison purposes)**:
    <br/><br/>
        1.  **Select the cells for a metric:**
              1.  For example, select the range of cells for “Total Chai Sales” (January to December).
        2.  **Insert a Sparkline:**
              1.  Go to the “Insert” tab in Excel.
              2.  Choose “Line Sparkline.”
              3.  In the dialog, set the data range (for example, B2:B13 for Total Chai Sales).
              4.  Set the location range to a cell next to your data (for example, C2).
<br/><br/>However, you want to see how Copilot can automate this process. To do so, ask Copilot to add sparklines to show the monthly trend between Total Chai Sales, Social Media Engagement, and Online Searches.

13.  Review the results. Visually compare the sparklines for each to see if their spikes occur in the same months. You want to add these sparklines to a new sheet, but Copilot displayed an **Insert to sheet** button. Since you want to add these charts to a new sheet rather than Sheet 1, open a new sheet and then select the **Insert to sheet** button. Rename the sheet **Social Media sparklines**, and then return to **Sheet 1**.

14.  You now want Copilot to analyze your data and suggest a possible formula or calculation that could be useful for your dataset. Doing so is especially helpful in the context of columns that require formulas to provide more insights or automate calculations. Basically, Copilot suggests ways to automate or enhance your work with formulas to make the data analysis faster and more efficient. To do so, ask Copilot to show a suggestion for a formula column.

15.  Note the suggestion that Copilot provides. In the suggestion that you received, select the **Show explanation** drop-down arrow. Review Copilot's explanation that describes the calculation. When you finish reviewing the formula suggestion, select the **+Insert column** button to insert the column into your Excel table. Note how Copilot added the column of data to the end of your Excel table in **Sheet 1**.

16.  This feature intrigues you, so you now want to see what other formula suggestions it provides. Ask Copilot to show a suggestion for another formula column. In the suggestion that you received, review the explanation and insert the formula column into your spreadsheet.

17.  Repeat this previous step two more times to see what other formulas Copilot can generate for you.
