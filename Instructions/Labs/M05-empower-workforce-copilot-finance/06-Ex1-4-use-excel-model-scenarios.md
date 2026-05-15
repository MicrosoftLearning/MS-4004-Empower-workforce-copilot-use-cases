---
lab:
  title: 'Exercise 1, Task 4: Use Copilot in Excel to model What-If scenarios'
  description: Let's begin by requesting the what-if scenario. Ask Copilot to create a what-if scenario that doubles each EBITDA value and increases synergy savings midpoints by 20%.
  duration: 42 minutes
  level: 100
  islab: true
---

# Exercise 1, Task 4: Use Copilot in Excel to model What-If scenarios
---
Robin Kline, Fabrikam’s Finance Manager, asked you to update the Relecloud acquisition financials to reflect new assumptions, such as adjusted valuation multiples and projected synergy savings. Robin wants you to:

- Update the Relecloud acquisition numbers based on a series of what-if scenarios.
- Create charts that visualize the effect of these changes.

This task showcases Copilot’s ability to perform dynamic modeling and visualization, which are essential tools for any financial analyst preparing data-driven recommendations.

Perform the following steps to complete this task:

1. Select the following link to download the [**Relecloud Acquisition Financials.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347812) file. Store the file in your OneDrive account for use by Copilot in your tenant.

2. In your Microsoft Edge browser, go to the **Microsoft 365 Copilot** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

   > [!NOTE]
   > If **Apps** does not appear in the navigation pane, you can select the **App Launcher** icon (grid icon) in the top left corner of the page, select **More Apps**, and then select **Excel** from the list of apps that appears.

3. In **Excel for the web**, select the **Upload a file** button, navigate to your OneDrive, and then select the **Relecloud Acquisition Financials** spreadsheet that you downloaded in step 1.

4. In the bottom-right corner of the document, select the **Copilot** icon to open the Copilot pane. In the Copilot pane, leave the response mode selector set to **Auto**. Verify the pane opens in edit mode—the heading should read **Let's edit your workbook**, and the prompt field should display the placeholder text **Describe what you'd like to edit**. Below the heading, confirm that the mode selector is set to **Allow editing** (so Copilot can edit your workbook directly). If it shows **Chat only**, select the drop-down and then select **Allow editing**.

5. Let’s begin by updating the Relecloud acquisition numbers based on a series of what-if scenarios. Verify you’re in the **Financial Analysis** sheet. In the Copilot prompt field, submit the following prompt:

    `Using the current values in the Financial Analysis sheet as the baseline, create a what-if scenario in a new sheet for the Relecloud acquisition model. Increase each EBITDA value by 100% (treat a 1x increase as doubling the current EBITDA amount). For synergy savings, use the midpoint of each estimated annual benefit range in the Integration Planning sheet as the baseline, increase each midpoint by 20%, and show the original and updated values side by side. Include totals where appropriate and clearly label the new sheet.`

6. Review the results. Remain in this new what-if sheet and then ask Copilot to perform an EBITDA what-if scenario in which it generates the following charts in a new sheet to make it easy to visualize the magnitude and timing of improvements:

    - Column Chart comparing original vs. updated EBITDA and total synergy savings over time.  

    - Line Chart showing EBITDA trend before and after the change.  

7. Review the results. Select the **Financial Analysis** sheet and then ask Copilot to perform another what-if scenario in which it updates the acquisition financial model based on the following what-if scenario: Model the impact if synergy savings are delayed by 12 months and only 75% are realized. Ask Copilot to return the results in a new sheet.

8. Review the results. Remain in this new what-if sheet and then ask Copilot to generate the following charts in a new sheet that show both the timing and reduction in benefits, highlighting the impact on cash flow and ROI:

    - Stacked Column Chart showing annual synergy savings (original vs. delayed/reduced).  

    - Line Chart for cumulative synergy savings over time.

9. Review the results. Select the **Financial Analysis** sheet and then ask Copilot to perform a what-if scenario that updates the financial model based on operating expenses that are 10% higher due to integration challenges. Ask Copilot to return the results in a new sheet.

10. Review the results. Remain in this new what-if sheet and then ask Copilot to generate the following charts in a new sheet that highlight the effect on profitability and expense trends:

    - Line Chart for operating expenses and EBITDA over time (original vs. scenario).  

    - Column Chart comparing net income before and after the change.

11. Review the results. If you want to update the spreadsheet further, select any of Copilot's suggested prompts.
