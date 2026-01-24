# Exercise 2, Task 2: Use Copilot in Excel to visualize cross department risk areas
---
At Lamna Healthcare Company, the Legal team is working on building a comprehensive risk assessment framework to identify and categorize potential legal or compliance risks within the business. With increasing regulations and the complexity of managing multiple legal requirements, the team wants to streamline their risk management process. To do so, they need a visual tool that helps them map out the risks and their associated mitigation strategies. As General Counsel, you’re tasked with helping the Legal team create and visualize this framework using Copilot in Microsoft Excel. You want to use Excel to help organize the data into a risk matrix and identify medical device compliance risks. This information can then be presented to department heads for further review and collaboration.

Your role is to guide your team in using Copilot in Excel to generate a 2x2 risk matrix, with axes for Likelihood and Impact. Copilot can then add key device compliance risks, including:

- Device traceability gaps

- Improper sterilization documentation

- Misconfigured clinical access permissions

- Noncompliance with incident‑reporting requirements

Copilot can then categorize each risk based on their risk levels. You want Copilot to color-code each quadrant to reflect the risk priority and help suggest mitigation actions for each identified risk. You also want to add a section for open questions, which can facilitate further legal review and discussion. This visual risk assessment should be a valuable tool for the Legal team to communicate with other departments, ensuring alignment and action on key compliance risks across Adatum Corporation.

As of this writing, you currently have two options when working with Copilot in Excel - Copilot Chat and App Skills (soon to be replaced with Agent Mode). Use the following guidance when determining which option to use:

- **Copilot Chat** works outside the workbook context. It’s great for explanations or general help, but it can’t create or modify workbook content unless you explicitly attach files. Even then, you work outside the workbook context.

- **Apps Skills/Agent Mode** works directly in the open workbook file, meaning learners can say things like “Update the current workbook” or “Create a risk table in the open workbook” and Copilot performs the task **in the open workbook itself**, exactly where it’s needed. Apps Skills is the feature used in this training task.

> [!NOTE]
> Copilot in Excel is transitioning from **App Skills** to **Agent Mode**. If the Copilot menu displays two options, **Chat** and **App Skills**, keep in mind that App Skills is being retired (rollout began in December 2025 and completes by late February 2026). After retirement, selecting Copilot in the Excel ribbon opens the **Copilot Chat** pane; from there, use **Agent Mode** (Tools > Agent Mode) when you want Copilot to work directly with the open workbook.

Perform the following steps to complete this task:

1.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **Excel** from the **Apps** menu.

2.  In **Excel for the web**, create a new blank workbook.

3.  On the **Home** tab, select **Copilot**. If a menu appears with **Chat** and **App Skills** as the two options, select **App Skills**. If your version of Excel has already transitioned from App Skills to Agent Mode, then selecting Copilot in the ribbon opens the Copilot Chat pane; from there, select **Tools > Agent Mode**.

    > [!CAUTION]
    > This task is written for the **App Skills** option, which is the current Copilot feature at the time of this writing. However, depending on your version of Excel, the **App Skills** option might not work or it might show an error when you submit a prompt, even when you wait awhile and try again later. If App Skills is unavailable or can’t complete your request, **open Copilot Chat and continue this task using your best judgment**. Within Chat, describe the steps you want Copilot to take (for example, “Create a risk table in the workbook”) and use the result as guidance to finish the task manually, if needed. Your Copilot experience might vary depending on your rollout stage, and that’s expected during the transition.

4.  If a message appears in the App Skills window indicating that **AutoSave is turned off**, select the **Turn on Autosave** button to continue. If you have multiple OneDrive accounts, Copilot prompts you to select the OneDrive account you want to use. Then assign a name to the workbook; in this case, enter **Device Risks**.

5.  In the **App Skills pane** that appears, enter the following prompt: 
    <br/><br/>**Create a 2x2 risk matrix table. It should compare Low and High Likelihood to Low and High Impact. Leave the cells within the table blank for now.**

6.  Review Copilot’s response in the App Skills pane. At the end of the response, select the **+Insert to new sheet** button.

7.  In cell **A1**, replace the **Column 1** value with **Likelihood/Impact**. Drag the column border to the right to see the entire value you just entered in A1.

8.  You now want to populate the matrix with legal risks in appropriate cells based on their Likelihood and Impact. To do so, enter the following prompt: 
    <br/><br/>**Populate the matrix with the following four legal risks in appropriate cells based on their Likelihood and Impact: “Device traceability gaps: High Likelihood, High Impact,” “Improper sterilization documentation: Low Likelihood, High Impact,” “Misconfigured clinical access permissions: High Likelihood, Low Impact,” and “Non‑compliance with incident‑reporting requirements: Low Likelihood, Low Impact.”**

9.  Verify that Copilot listed each legal risk in the correct cell based on its likelihood and impact. To make the row headings stand out from the actual data in the table, enter the following prompt: 
     <br/><br/>**Bold the values in cells A2 and A3.**

10.  At this point, you’re satisfied with the risk matrix. However, you later realize that you should add mitigation strategies in a separate work sheet. Since you’re now dealing with multiple sheets, you want to make their names more user-friendly than just Sheet1 and Sheet2. Rename **Sheet 1** to **Risk Matrix**. Then add a new sheet and title it **Mitigation Strategies**.

11.  Select the **Mitigation Strategies** sheet and then enter the following prompt asking Copilot to create a table for mitigation actions: 
    <br/><br/>**Create a table with two columns: ‘Legal Risk’ and ‘Mitigation Strategy.’ In the Legal Risk column, include the following risks: Device traceability gaps, Improper sterilization documentation, Misconfigured clinical access permissions, and Non‑compliance with incident‑reporting requirements. In the Mitigation Strategy column, suggest mitigation strategies for each risk.**

12.  Review the mitigation strategies table that Copilot displayed in the Apps Skills pane. You’re happy with the results, so select the **+Insert to new sheet** button that appears below the table.

13. You now want Copilot to generate a list of questions for legal review in a separate work sheet. Add a new sheet and title it **Open Legal Questions**.

14. In the **Open Legal Questions** sheet, you want Copilot to generate a list of open questions for legal review. To do so, enter the following prompt: 
    <br/><br/>**Create a list titled ‘Open Questions for Legal Review’. Include 10 questions. These should be open-ended legal questions that help identify compliance gaps, clarify ownership of risk, and prompt strategic legal discussion. The questions should encourage deeper legal review and collaboration with other departments.**

15. Review the open legal questions that Copilot generated. In our testing, sometimes Copilot displayed an **+Insert to new sheet** button below the questions, and other times it didn’t. If the **+Insert to new sheet** button appears, then select it. Otherwise, highlight the questions in the Copilot pane, copy them (**Ctrl+C**), and then paste them (**Ctrl+V**) in the sheet.

16. Feel free to have Copilot make other changes to any of the worksheets. For example, to format for readability and sharing, you could optionally adjust column widths and center text in the risk matrix table.

17. Once you finish updating the sheets in this workbook, you can close this tab in your browser.

