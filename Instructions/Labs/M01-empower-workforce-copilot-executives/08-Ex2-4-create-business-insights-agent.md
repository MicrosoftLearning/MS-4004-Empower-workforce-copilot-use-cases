---
lab:
  title: 'Exercise 2, Task 4: Create a Northwind Business Insights agent'
  description: This scenario shows how Copilot agents empower executives to move from reactive management to proactive, insight-driven leadership.
  duration: 44 minutes
  level: 100
  islab: true
---

# Exercise 2, Task 4: Create a Northwind Business Insights agent
---
To stay ahead of market trends, Northwind Traders' leadership needs real-time visibility into performance metrics across sales, supply chain, and customer sentiment. Rather than waiting for periodic reports, you plan to create a Northwind Business Insights agent in Microsoft 365 Copilot to proactively monitor key indicators and flag emerging issues for Northwind executives. In this task, you configure the agent to track performance and deliver actionable insights, allowing you to respond quickly to deviations from forecasted results.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the Northwind Business Insights Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

This scenario shows how Copilot agents empower executives to move from reactive management to proactive, insight-driven leadership.

Perform the following steps to complete this task:

1. Open a new tab in your web browser and then open the **Microsoft Copilot** home page.

2. In **Microsoft Copilot**, under **Agents**, select **New agent**. Doing so opens **Agent Builder** and displays the **New agent** page.

    On the **New Agent** page, you want to ask Copilot to create an agent. Enter a prompt that includes the agent's name, a description of its purpose, the target audience, and the tasks it should perform.

    For this agent, enter the following prompt and then select the **Send** icon to submit the prompt:

    ```prompt
    Create an agent titled Northwind Business Insights Agent. The purpose of this agent is to provide responses to questions related to Northwind Traders' sales performance, supply chain health, customer sentiment, and results compared to the Q4 budget forecast. The agent should only use the files assigned to it as knowledge sources. The agent is intended for an executive audience.
    ```

3. After you submit the prompt, the **Agent Builder** form appears for your new agent. If the **What's new in Agent Builder** dialog appears, select **Get started**. The **Agent Builder** chat pane appears on the left, and the agent details appear on the right. At the top of the form are a **Configure** tab and a **Preview** tab.

    - The **Agent Builder** chat pane on the left enables you to carry on a conversation with Copilot to refine your agent.

    - The **Preview** tab enables you to test the agent by entering starter prompts or custom messages.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    Wait a minute or two for Copilot to create the agent, at which time it displays the agent's name and description in the **Agent preview** pane.

4. Select the **Configure** tab at the top of the form to review what Copilot generated based on your prompt.

5. On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down to the **Instructions** field. Copilot generates these instructions based on the description that you provided in your initial prompt. Review the instructions that Copilot generated.

   > [!IMPORTANT]
   > The beauty of the Agent Builder process is that Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

6. If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Copilot to update the instructions for you.

    After reviewing the **Instructions**, you decide that you want to have Copilot add a few other items to the instruction set. In the **Agent Builder** chat pane, enter the following prompt:

    ```prompt
    Update the Instructions to include the following items: When generating responses, the agent should flag missing or incomplete information, never invent data or rely on sources outside the defined knowledge source documents, and stay within Northwind Traders' business context.
    ```

7. Review Copilot's response after updating the instructions. To verify the changes that Copilot made, on the **Configure** tab, scroll through the **Instructions** section. Verify that Copilot added the new instructions that you requested.

8. While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.

    In the **Agent Builder** chat pane, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

9. Review Copilot's recommendations. You're pleased with its suggestions, so ask Copilot to add them all to the agent's instructions.

10. Once Copilot responds that it updated the instructions, on the **Configure** tab, scroll through the **Instructions** section. Note the new items that Copilot added.

11. Now that you're satisfied with the instructions, you're ready to configure the agent's knowledge sources and starter prompts.

    In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Web search** toggle switch is disabled. Copilot should have disabled this toggle switch when it created the agent based on the description you provided in your original prompt, which told it to only use the files that you provide. If the toggle switch is enabled, then disable it now.

12. In the **Knowledge** section, select **+ Add knowledge**, and then select **Attach cloud files** (cloud icon). In the **Pick items** window that appears, locate and select the **Q3 Executive Briefing.docx** file from Task 1 and the **Northwind Traders Q4 budget forecast.xlsx** file from Task 2 as knowledge sources for the agent.

13. For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let's try both methods.

    To have Copilot generate suggested prompts, in the **Agent Builder** chat pane, ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a **Title** and a **Message**.

14. You now want to enter several of your own prompts. On the **Configure** tab, scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.

    For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.

    Six suggested prompts are displayed below that are related to popular financial topics and actions. Review these prompts, select two or three that you like, and then add them to the agent.

    - **Title:** Top risks
        - **Message:** What are the top risks to meeting our Q4 revenue forecast?

    - **Title:** Customer sentiment trends
        - **Message:** Summarize customer sentiment trends from the latest reports. (Note: This prompt is interesting, given the data in the knowledge sources. See what happens when you use this prompt.)

    - **Title:** Budget vs. Sales
        - **Message:** Compare actual sales performance to the Q4 budget forecast.

    - **Title:** Bottlenecks
        - **Message:** Identify supply chain bottlenecks that could affect Q4 delivery timelines.

    - **Title:** Top-performing product categories
        - **Message:** Highlight the top-performing product categories based on recent sales data.

    - **Title:** Emerging market trends
        - **Message:** What emerging market trends should we watch for in the next quarter?

15. Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

16. Once you're satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

17. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either start a chat with the agent or share it. Select the **Start chat** option.

   > [!NOTE]
   > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn't required since you're working within your own tenant.
