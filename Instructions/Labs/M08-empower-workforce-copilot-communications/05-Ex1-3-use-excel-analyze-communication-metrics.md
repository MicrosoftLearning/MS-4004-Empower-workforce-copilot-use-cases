# Exercise 1, Task 3: Use Copilot in Excel to analyze communication metrics
---
As the Communications Manager at Boulder Innovations, part of your role is to assess how internal messages are resonating across the organization. One of your key responsibilities is managing the company’s quarterly newsletter. Boulder’s Senior Leadership Team (SLT) asked you for a quick overview of how different departments are engaging with it—specifically looking at open rates and click-through rates over the past quarter.

- **Open rate**. Indicates whether people are seeing the newsletter. It tells you how many people opened your email out of the total number it was sent to. For example, if you send the newsletter to 100 people and 60 of them open it, your open rate is 60%. This rate helps indicate whether your subject lines or sender name are compelling enough for people to actually open the email.

- **Click-through rate**. Indicates whether people find the email interesting enough to select what’s inside (such as articles, videos, or announcements). For example, if 60 people opened the email and 15 selected a link inside it, your click-through rate is 25% (15 out of 60). This rate tells you if people are engaging with the content rather than just opening the email.

In this exercise, you plan to use Copilot in Excel to analyze the **Boulder Q4 Newsletter Click Rates.xlsx** spreadsheet that breaks down the company’s Q4 newsletter engagement by department. Your goal is to generate a clear, high-level summary that highlights trends, identifies which departments are most and least engaged, and offers insights that could inform future communication strategies. Rather than manually calculating averages or scanning the table yourself, you’re going to use Copilot to instantly surface trends. Doing so saves time and helps you quickly understand which departments might need more support or different messaging strategies.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  Select the following link to download the [**Boulder Q4 Newsletter Click Rates.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347514) file. Once the download is complete, store the file on your OneDrive.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page.

3.  On the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

4.  In **Excel for the web**, select the **Upload a file** button, navigate to your OneDrive, and then select the **Boulder Q4 Newsletter Click Rates** file.

5.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

   > [!CAUTION]
   > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work, or it might show an error when you submit a prompt, even when you wait a while and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

6.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use.

7.  You want Copilot to look for patterns and outliers in the data and to compare each department's performance to the overall average. So instead of using the predefined prompts that appear at the top of the Copilot pane, you decide to enter your own custom prompt to gather this information.  
    <br/>In the **App Skills** pane, ask Copilot to summarize trends in the open spreadsheet and identify any departments with below-average engagement.

8.  Review the results of this prompt. If Copilot provided a table of the engagement trends, select the **+Insert to new sh**eet button that appears below it. Select Sheet 2 to view the table, and then drag the columns to expand their size so that you can read the data. Rename **Sheet 2** to **Below Avg Depts**.

9.  Note the suggested prompts that Copilot displays above the prompt field. These prompts are based on your previous request. If a suggested prompt says something similar to “**show a bar chart comparing open and click-through rates by department**” then select it; otherwise, enter this prompt manually.

10.  Review the chart that Copilot generated. You want to capture this visualization, so select the **+Add to a new sheet** button that appears below the chart. Rename the new sheet to **Dept comparison**.

11.  Let’s take a moment now and look at the suggested prompts that Copilot generates. The suggested prompts are based on your previous request. You can also select the **Refresh** icon that appears above the prompt field to generate a new set of suggested prompts. You can select the **Refresh** icon multiple times to see the full extent of suggested prompts. Select the **Refresh** icon several times to see the types of prompts that are available. Select any of the prompts that are of interest to you.

12.  You now want Copilot to refine your analysis by ranking departments based on their click-through rate. Doing so helps you focus on the departments that are doing especially well, or struggling. Recognizing top performers can help you replicate success, while identifying low performers gives you a clear starting point for improvement. Verify you’re on **Sheet 1** and then ask Copilot to highlight the top three and bottom three departments by click-through rate.

13.  Review the response. For each group, Copilot should provide conditional formatting rules to review and apply. An **Apply** button should appear at the bottom of the response. Select the **Apply** button to apply the conditional formatting rules to the spreadsheet.

14.  Review the results. In our testing, Copilot highlighted the click-through rate for each of the top three departments in green, and it highlighted the rate for each of the bottom three departments in red. Did Copilot do something similar for you?

15.  Since you must report your findings to the SLT, you want Copilot to generate a short summary of the data that was captured in this spreadsheet. Ask Copilot to create a short summary for the executive leadership team regarding overall departmental engagement. Indicate the average open rate across all departments, the average click-through rate, and identify the departments with below-average engagements.

16.  Review the Copilot-generated summary. While the summary is OK, you want Copilot to provide a little better explanation. Ask Copilot to provide the data insights that were the basis for the executive summary.

17.  Review the results. If Copilot generated a table with a more thorough breakdown by department, select the **+Insert to new sheet** button that appears below it. Rename the sheet to **Dept Insights**.

18.  Lastly, you now want to go beyond the data and ask Copilot to help you interpret the results and suggest next steps. You’re looking for practical, strategic recommendations tailored to the underperforming groups. This step turns insights into action, helping you improve future newsletter performance and tailor communication to meet employees where they are. To do so, ask Copilot to provide some suggestions on how we can improve open and click-through rates for low-performing departments.

19.  Review the response. This step turns insights into action, helping you improve future newsletter performance and tailor communication to meet employees where they are. You determine that your analysis is complete given all the data that Copilot in Excel provided. Since Excel automatically saved your file, close this tab in your Microsoft Edge browser.



