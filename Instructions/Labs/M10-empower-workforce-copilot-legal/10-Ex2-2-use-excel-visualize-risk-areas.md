---
lab:
  title: 'Exercise 2, Task 2: Use Copilot in Excel to visualize cross department risk areas'
  description: Create a list titled ‘Open Questions for Legal Review’. Include 10 questions. These should be open-ended legal questions that help identify compliance gaps, clarify ownership of risk, and prompt strategic legal discussion. The questions should encourage deeper legal review and collaboration with other departments.
  duration: 44 minutes
  level: 200
  islab: true
---

# Exercise 2, Task 2: Use Copilot in Excel to visualize cross department risk areas
---
At Lamna Healthcare Company, the Legal team is working on building a comprehensive risk assessment framework to identify and categorize potential legal or compliance risks within the business. With increasing regulations and the complexity of managing multiple legal requirements, the team wants to streamline their risk management process. To do so, they need a visual tool that helps them map out the risks and their associated mitigation strategies. As General Counsel, you're tasked with helping the Legal team create and visualize this framework using Copilot in Microsoft Excel. You want to use Excel to help organize the data into a risk matrix and identify medical device compliance risks. This information can then be presented to department heads for further review and collaboration.

Your role is to guide your team in using Copilot in Excel to generate a 2x2 risk matrix, with axes for Likelihood and Impact. Copilot can then add key device compliance risks, including:

- Device traceability gaps

- Improper sterilization documentation

- Misconfigured clinical access permissions

- Noncompliance with incident‑reporting requirements

Copilot can then categorize each risk based on their risk levels. You want Copilot to color-code each quadrant to reflect the risk priority and help suggest mitigation actions for each identified risk. You also want to add a section for open questions, which can facilitate further legal review and discussion. This visual risk assessment should be a valuable tool for the Legal team to communicate with other departments, ensuring alignment and action on key compliance risks across Lamna Healthcare Company.

#### Using Copilot in Excel

Excel provides two ways to use Copilot: standard Copilot prompts for asking questions and getting insights about the data in the workbook, and **Edit with Copilot** in the Copilot pane for making direct, in‑place changes to worksheets, tables, and formulas.

- You should use Copilot's standard prompts in Excel for quick questions, simple summaries, or one‑off insights about the data you're already viewing. When using the Copilot pane, if you enter a prompt without selecting **Edit with Copilot**, Copilot responds in a chat‑style mode that generates suggestions or content separately, rather than making direct, in‑place changes to the workbook.
    
- You should use **Edit with Copilot** when you want Copilot to work directly with the worksheet—such as cleaning data, adding formulas, restructuring tables, or making iterative, in‑place changes. **Edit with Copilot** is designed for hands‑on data work, so it understands the structure of the sheet and can apply changes directly, rather than just describing what you could do.

In summary, use chat‑style Copilot for thinking and generating ideas; use **Edit with Copilot** for hands‑on editing inside the file. **Edit with Copilot** proposes specific changes (formulas, columns, cleanup steps) and, once you confirm, it applies those changes directly to the worksheet rather than expecting you to explicitly apply them through copy and paste.

This task uses the **Edit with Copilot** functionality.

In addition, Copilot for Excel provides a response control selector that lets you choose which AI model Copilot uses to work with your workbook. You can leave this set to **Auto** (the default option) and let Copilot select a model for you, or choose a specific model when you want to influence how Copilot approaches the task.

If you've used Copilot Chat, you know that it also includes a response control selector. However, its options are different from the Excel selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might appear to be similar, they control different aspects of Copilot and aren't the same setting.

This task uses the default **Auto** selector mode.

Perform the following steps to complete this task:

1. In your Microsoft Edge browser, go to the **Microsoft 365 Copilot** home page, select the **App Launcher** (grid icon), select **More Apps**, and then select **Excel** from the **Apps** menu.

2. In **Excel for the web**, create a new blank workbook and save it to your OneDrive as **Lamna Risk Matrix.xlsx**.

3. In the bottom-right corner of the document, select the **Copilot** icon to open the Copilot pane. In the Copilot pane, leave the response mode selector set to **Auto**. Verify the pane opens in edit mode—the heading should read **Let's edit your workbook**, and the prompt field should display the placeholder text **Describe what you'd like to edit**. Below the heading, confirm that the mode selector is set to **Allow editing** (so Copilot can edit your workbook directly). If it shows **Chat only**, select the drop-down and then select **Allow editing**.

4. In the Copilot pane, ask Copilot to create a 2x2 risk matrix table. It should compare Low and High Likelihood to Low and High Impact. It should leave the cells within the table blank for now.

5. Review the results. In cell **A1**, replace the **Column 1** value with **Likelihood/Impact**. If necessary, drag the column border to the right to see the entire value you just entered in A1.

6. You now want to populate the matrix with legal risks in appropriate cells based on their Likelihood and Impact. To do so, ask Copilot to populate the matrix with the following four legal risks in appropriate cells based on their Likelihood and Impact: "Device traceability gaps: High Likelihood, High Impact," "Improper sterilization documentation: Low Likelihood, High Impact," "Misconfigured clinical access permissions: High Likelihood, Low Impact," and "Noncompliance with incident‑reporting requirements: Low Likelihood, Low Impact."

7. Verify that Copilot listed each legal risk in the correct cell based on its likelihood and impact. To make the row headings stand out from the actual data in the table, confirm that the values in cells **A2** and **A3** are bold. Copilot typically bolds these row headings automatically when it creates the matrix. If they aren't bold, ask Copilot to bold the values in cells **A2** and **A3**.

8. At this point, you're satisfied with the risk matrix. However, you later realize that you should add mitigation strategies in a separate worksheet. Ask Copilot to add a new sheet for Mitigation Strategies. It should include a table with two columns: 'Legal Risk' and 'Mitigation Strategy.' In the Legal Risk column, it should include the following risks: Device traceability gaps, Improper sterilization documentation, Misconfigured clinical access permissions, and Noncompliance with incident‑reporting requirements. In the Mitigation Strategy column, ask Copilot to suggest mitigation strategies for each risk.

   > [!NOTE]
   > Copilot might display a message stating that information from these sources may be used in answers and will be visible to anyone with access to the workbook, followed by a list of organizational sources (such as files, emails, and chats) and the **Use Selected** and **Use None** buttons. Because you want Copilot to base the mitigation strategies on general best practices rather than unrelated organizational content, select **Use None** to continue.

9. Review the results. You now want Copilot to generate a list of questions for legal review. Ask Copilot to add a new sheet that contains legal questions for review. Ask it to create a list of 10 open-ended legal questions that help identify compliance gaps, clarify ownership of risk, and prompt strategic legal discussion. The questions should encourage deeper legal review and collaboration with other departments.

10. Review the results and select **Done** to confirm the changes. Feel free to have Copilot make other changes to any of the worksheets. For example, to format for readability and sharing, you could optionally adjust column widths and center text in the risk matrix table. Or you could submit any of Copilot's suggested prompts that are of interest to you.

11. Once you finish updating the sheets in this workbook, you can close this tab in your Microsoft Edge browser.
