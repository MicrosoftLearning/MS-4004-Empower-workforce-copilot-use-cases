
# Manage IT assets using Microsoft 365 Copilot in Excel
---
An IT manager is responsible for managing a large inventory of hardware, software licenses, and other assets within an organization. Each asset must be tracked, updated, and reported regularly to ensure that the IT infrastructure remains operational and compliant. The manager is tasked with analyzing asset data, identifying gaps, and making data-driven decisions to improve resource allocation.

Microsoft 365 Copilot in Excel is a popular tool for helping managers streamline data analysis, generate insights, and automate repetitive tasks, making the process more efficient and less error prone. In this exercise, you take on the role of an IT manager who plans to use Copilot in Excel to assist in asset management and reporting.

### Exercise

As the IT Manager at Contoso Ltd., you oversee the company's critical IT infrastructure, including managing the company's hardware assets such as laptops, printers, servers, routers, and switches. These assets are essential to the productivity of employees, and ensuring their availability, performance, and security is crucial. One of your primary tasks is to track and manage the lifecycle of these assets, including warranty information, repair history, and current status.

However, this process is currently handled manually and is both time-consuming and prone to errors. You rely on various spreadsheets to track asset information such as purchase dates, warranty expiration dates, repair histories, and departmental allocation. Despite your best efforts, it's becoming increasingly difficult to monitor all the data effectively. It's easy to miss critical warranty expiration dates, leading to unexpected repair costs, and the manual process for analyzing asset trends leaves little room for quick decision-making.

Recognizing the need for a more efficient and accurate approach, you plan to use Copilot in Excel to:

Quickly analyze a file containing a list of company assets to identify key trends and issues related to your IT assets and their warranties.

Automatically generate insightful charts and reports to visualize asset data and identify warranty patterns that require immediate attention.

Perform the following steps to complete these tasks using Copilot in Excel.

1. Select the following link to download Contoso's asset management spreadsheet: [Contoso Asset Data](https://go.microsoft.com/fwlink/?linkid=2320505)
1. Once the download is complete, open **File Explorer** and copy the file from your **Downloads** folder to your **Microsoft - OneDrive** folder.
1. In this exercise, you access the document from the Most Recently Used file list in Excel. To get the file to appear in the MRU list, open the document and then close it. 
1. Open your Edge browser (if necessary) and navigate to the **Microsoft 365** home page by entering the following URL: **https://www.office.com**  
1. On the **Microsoft 365** home page, select the **Excel** icon in the navigation pane on the left. If the icon doesn't appear, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** page.
1. In **Excel**, scroll down to the list of all files in the MRU list. The **All** tab is displayed by default. Select the **Contoso Asset Data** file.
1. With the spreadsheet open in **Excel**, select the **Copilot** option on the right side of the ribbon (if the ribbon isn't displayed, hover over the **Home** tab). Doing so opens the **Copilot** pane. 
1. You want to begin by having Copilot identify the assets whose warranties are either past due or due to expire in the next 30, 60, and 90 days. As it does so, you want Copilot to highlight past due warranties in red, warranties due to expire in 30 days (0-30 days) in yellow, warranties due to expire in 60 days (31-60 days) in gray, and warranties due to expire in 90 days (61-90 days) in green. To complete this task, Copilot must create conditional formatting rules to highlight the assets in this manner. Once it defines these rules, you can then direct Copilot to apply them. <br><br>To have Copilot create these conditional formatting rules, enter the following prompt in the prompt field at the bottom of the Copilot pane: **Create the following 4 conditional formatting rules that apply to the column "Warranty Expiration Date". If the date is prior to today's date, then highlight it in red. If the date is due to expire in the next 30 days, then highlight it in yellow.  If the date is due to expire 31 to 60 days from now, then highlight it in gray. If the date is due to expire 61 to 90 days from now, then highlight it in green**.
1. Review each of the conditional formatting rules that Copilot creates. Take special note of the 60-day rule. While you asked Copilot to highlight these assets in Gray, our testing usually found that Copilot assigned White as the fill color. If this happens to you, then enter the following prompt: **In the third rule that you created, you assigned White as the fill color. Please assign Gray instead**. When Copilot responds to this prompt, verify the fill color is now Gray (or Light Gray).
1. If the rules appear to be correct, select the **Apply** button that appears after the conditional rules. Verify the rules are applied correctly.
1. Now let's take a look at how Copilot in Excel can analyze the data in this spreadsheet and create various graphics that represent the data request. Let's begin by entering the following prompt: **Create a bar chart that shows the number of Active laptops by Department**.
1. Review the bar chart. Now let's have Copilot create a pie chart based on this same data. Enter the following prompt: **Create a pie chart that shows the number of Active laptops by Department**.
1. Note how the pie chart that appears in the Copilot pane doesn't include a legend. However, select the **+Add to a new sheet** button that appears below the pie chart. In turn, Copilot adds the pie chart to **Sheet2**, and it displays the list of active laptops by department  and a legend below the pie chart. 
1. In **Sheet2**, select the pie chart. Doing so opens a detailed pane for the pivot table used to create this chart. 
1. Select **Sheet1**. You must be on the actual spreadsheet to make a Copilot request that analyzes the spreadsheet data. Copilot sometimes displays an error message if you stay on Sheet 2 and submit a prompt based on the data in Sheet1. Other times, it provides instruction on how to complete your prompt request given the limited data in the pivot table on the current sheet. In either case, you should select the sheet containing the spreadsheet data before you proceed. 
1. On **Sheet 1**, repeat steps 11-14, except this time use the following two prompts (where the pie chart is added to Sheet3):
   - **Create a bar chart that shows the number of Active laptops whose warranty has expired by Department**. 
      > [!NOTE]
      > In our testing, sometimes Copilot is unable to create this chart. If that's the case with your request, change the prompt to: **Create a bar chart that shows the number of Active laptops whose warranty expiration date is less than today's date by Department**. If you must rewrite the prompt in this manner, it just shows that sometimes Copilot needs a little further explanation to understand your request.
   - **Create a pie chart that shows the number of Active laptops whose warranty has expired by Department**.
1. Select **Sheet1**.
1. On **Sheet 1**, let's see how Copilot in Excel can generate a report based on the spreadsheet data. Submit the following prompt: **Create a report that shows the number of Active laptops whose warranty will be expiring in the next 90 days by Department**.
1. Note how the report that's generated in the Copilot pane is hard to understand given the limited space available on the pane. To see the report in its entirety, select the **+Add to a new sheet** button that appears below the report data. Upon doing so, Copilot adds the report to **Sheet4**. Review the report and note the level of detail that Copilot in Excel provides. 
