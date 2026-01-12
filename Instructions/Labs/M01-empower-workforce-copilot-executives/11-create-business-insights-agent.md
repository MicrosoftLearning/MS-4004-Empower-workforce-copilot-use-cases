# Exercise 2, Task 4: Create a Northwind Business Insights agen
---
To stay ahead of market trends, Northwind Traders’ leadership needs real-time visibility into performance metrics across sales, supply chain, and customer sentiment. Rather than waiting for periodic reports, you plan to create a Northwind Business Insights agent in Microsoft 365 Copilot to proactively monitor key indicators and flag emerging issues for Northwind executives. In this task, you configure the agent to track performance and deliver actionable insights, allowing you to respond quickly to deviations from forecasted results.

> [!NOTE] 
> In this exercise, you use the Copilot Studio lite experience to create the Northwind Business Insights Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

This scenario shows how Copilot agents empower executives to move from reactive management to proactive, insight-driven leadership.

Perform the following steps to complete this task:

1.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

2.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

3.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** Northwind Business Insights Agent

    - **Description:** The Northwind Business Insights Agent should assist company executives by answering questions about key business indicators, potential sales, areas of risk, and so on, using the company’s latest financial documents.

    - **Instructions:** The agent should provide responses to questions related to Northwind Traders' business insights based on its Q3 sales data and its Q4 budget forecast.  

4.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the **Q3 Executive Briefing.docx** file from Task 1 and the **Northwind Traders Q4 budget forecast.xlsx** file from Task 2 as knowledge sources for the agent.

5.  In the **Suggested prompts** section, add the following prompts that ask questions about popular business-related topics for Northwind Traders. For example:

    - **Title:** Top risks
        - **Message:** What are the top risks to meeting our Q4 revenue forecast?

    - **Title:** Customer sentiment trends
        - **Message:** Summarize customer sentiment trends from the latest reports. (Note: This prompt is interesting given the data in the knowledge sources. See what happens when you use it).

    - **Title:** Budget vs. Sales
        - **Message:** Compare actual sales performance to the Q4 budget forecast.

    - **Title:** Bottlenecks
        - **Message:** Identify supply chain bottlenecks that could affect Q4 delivery timelines.

    - **Title:** Top performing product categories
        - **Message:** Highlight the top-performing product categories based on recent sales data.

    - **Title:** Emerging market trends
        - **Message:** What emerging market trends should we watch for in the next quarter?  
            
6.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents. You create custom prompts in the next task.

7.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

8.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

    > [!NOTE]
    > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.
    
### Update the agent’s instructions (optional)

Now that you created a working agent using a minimal instruction set, let’s refine its Instructions if time permits. 

Now that you created a working agent using a minimal instruction set, it’s time to revisit and refine its Instructions. While short, vague instructions are common in real-world scenarios, they often leave too much room for interpretation, which can limit the quality, consistency, and usefulness of an agent’s responses. By expanding the Instructions with clearer goals, context, tone, and constraints, you give the agent stronger guidance on _how_ it should think and respond.
    
In the remaining steps in this task, you update the agent’s Instructions using a more detailed version generated with Copilot Chat, then rerun the same suggested prompts as before. Comparing the before-and-after responses helps you see firsthand how well-crafted instructions can dramatically improve an agent’s performance without changing any tools, data sources, or prompts—just the guidance it’s given.

9.  You’re now going to submit a prompt in Copilot Chat that asks it to create a detailed instruction set for your agent. When asking Copilot to generate agent instructions, include the following information in your prompt:
    - What’s the agent’s primary job
    - Who the answers are for
    - What kinds of questions it should and shouldn't answer
    - Which documents it can trust
    - Any rules or constraints it must follow
    - Ask Copilot to return the instructions in a code block for easier copy and pasting.

    Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a prompt that asks Copilot to create an instruction set for your agent that contains the information outlined above. **Do NOT submit the prompt just yet.**

10.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        > [!NOTE] 
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.
    
        **I’m creating a Copilot agent called “Northwind Business Insights Agent.” This agent’s purpose is to answer questions about key business indicators, potential sales, financial performance, and areas of risk using Northwind’s latest financial documents.**
            
        **The agent is intended for an executive audience and should provide clear, action-oriented insights related to Sales performance, Supply chain health, Customer sentiment, and Results compared to the Q4 budget forecast.**
            
        **The agent should only use the files assigned to it as knowledge sources.**
            
        **When generating responses, the agent should:**
            
        **- Cite sources in every response**
            
        **- Flag missing or incomplete information**
            
        **- Never invent data or rely on sources outside these documents**
            
        **- Stay within the Northwind Traders’ business context**
            
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**

11.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

12.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **Northwind Business Insights** agent appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **Northwind Business Insights** agent should appear in the list.

13.  Hover over the **Northwind Business Insights** agent and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

14.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

15.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

16.  In the **Northwind Business Insights** agent, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?


This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.


