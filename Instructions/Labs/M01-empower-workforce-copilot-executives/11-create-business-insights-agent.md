# Exercise 2, Task 4: Create a Northwind Business Insights agent
---
To stay ahead of market trends, Northwind Traders’ leadership needs real-time visibility into performance metrics across sales, supply chain, and customer sentiment. Rather than waiting for periodic reports, you plan to create a Northwind Business Insights agent in Microsoft 365 Copilot to proactively monitor key indicators and flag emerging issues for Northwind executives. In this task, you configure the agent to track performance and deliver actionable insights, allowing you to respond quickly to deviations from forecasted results.

> [!NOTE] 
> In this exercise, you use the Copilot Studio lite experience to create the Northwind Business Insights Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

This scenario shows how Copilot agents empower executives to move from reactive management to proactive, insight-driven leadership.

Perform the following steps to complete this task:

1.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

2.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

    On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
        <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
        <br/>**Create an agent titled Northwind Business Insights Agent. The purpose of this agent is to provide responses to questions related to Northwind Traders' Sales performance, Supply chain health, Customer sentiment, and Results compared to the Q4 budget forecast. The agent should only use the files assigned to it as knowledge sources. The agent is intended for an executive audience.**

3.  After you selected the forward arrow, the **Agent Builder** form appeared for your new agent. At the top of the form is a **Describe** tab and a **Configure** tab.
    - The **Describe** tab enables you to carry on a conversation with Copilot. This tab is displayed by default.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.
    
    Wait a minute or two for Copilot to create the agent, at which time it displays the agent’s name and description in the **Agent preview** pane.

4.  Select the **Configure** tab at the top of the form. Let’s see what Copilot did based on the prompt that you entered.

5.  On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down to the **Instructions** field. Copilot generated these instructions based on the description that you provided in your initial prompt. Review the detailed level of instructions that Copilot generated.

    > [!IMPORTANT]
    > The beauty of the Agent Builder process is that Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

6.  If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Copilot to update the instructions for you.  
    <br/>After reviewing the **Instructions**, you decide that you want to have Copilot add a couple of other items to the instruction set. To do so, select the **Describe** tab and then enter the following prompt:

    **Update the Instructions to include the following item: When generating responses, the agent should:**
    
    - **Flag missing or incomplete information**
    - **Never invent data or rely on sources outside the defined knowledge source documents**
    - **Stay within the Northwind Traders’ business context**

7.  Review Copilot’s response after updating the instructions. To verify the changes that Copilot made, select the **Configure** tab and then scroll down to the **Instructions** field. Verify that Copilot added the two new instructions that you requested.

8.  While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.  
    <br/>To do so, select the **Describe** tab. This time, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

9.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent’s instructions.

10.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

11.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is disabled. Copilot should have disabled this toggle switch when it created the agent based on the description you provided in your original prompt, which told it to only use the files that you provide. If the toggle switch is enabled, then disable it now.

12.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the **Q3 Executive Briefing.docx** file from Task 1 and the **Northwind Traders Q4 budget forecast.xlsx** file from Task 2 as knowledge sources for the agent.

13.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

14. You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    <br/>Six suggested prompts are displayed below that are related to popular financial topics and actions. Review these prompts, select two or three that you like, and then add them to the agent.

    - **Title:** Top risks
        - **Message:** What are the top risks to meeting our Q4 revenue forecast?  
            
    - **Title:** Customer sentiment trends
        - **Message:** Summarize customer sentiment trends from the latest reports. (Note: This prompt is interesting given the data in the knowledge sources. See what happens when you use this prompt).  
            
    - **Title:** Budget vs. Sales
        - **Message:** Compare actual sales performance to the Q4 budget forecast.  
            
    - **Title:** Bottlenecks
        - **Message:** Identify supply chain bottlenecks that could affect Q4 delivery timelines.  
            
    - **Title:** Top performing product categories
        - **Message:** Highlight the top-performing product categories based on recent sales data.  
            
    - **Title:** Emerging market trends
        - **Message:** What emerging market trends should we watch for in the next quarter?  
            
15. Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

16. Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

17. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.
