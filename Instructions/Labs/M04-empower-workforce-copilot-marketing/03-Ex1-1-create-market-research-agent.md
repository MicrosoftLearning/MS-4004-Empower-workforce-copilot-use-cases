---
lab:
  title: 'Exercise 1, Task 1: Use Agent Builder to create a Market Research Agent'
  description: This agent should be product agnostic. Relecloud recently implemented Microsoft 365 Copilot, so you plan to use it for researching WorkSmart 360. But moving forward, the Marketing team plans to use it for any number of the company's products.
  duration: 40 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365
    - Microsoft 365 Copilot
---

# Exercise 1, Task 1: Use Agent Builder to create a Market Research Agent
---
Relecloud is preparing to launch WorkSmart 360 in the commercial office market. It's critical that Relecloud's Marketing department understands the competitive landscape, customer preferences, and emerging trends to inform the campaign. Your first step is to build a Market Research Agent that can aggregate this information from web sources, social media, and research reports.

This agent should be product agnostic. Relecloud recently implemented Microsoft 365 Copilot, so you plan to use it for researching WorkSmart 360. But moving forward, the Marketing team plans to use it for any number of the company's products.

> [!NOTE]
> In this exercise, you use the Agent Builder experience to create the Market Research Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Agent Builder experience.

Perform the following steps to complete this task:

1. In your web browser, go to the [Microsoft Copilot](https://m365.cloud.microsoft.com) home page.

2. In **Microsoft Copilot**, in the left navigation pane, under **Agents**, select **New agent**. Doing so opens **Agent Builder** and displays the **New agent** page.

3. On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent's name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    
    For this agent, enter the following prompt and then select the forward arrow **(Send)** icon to submit the prompt:  
    
    ```prompt
    Create an agent titled Market Research Agent. The purpose of this agent is to gather and analyze market insights for a requested product. The agent should draw from web sources such as social media, research reports, customer sentiment, and competitor activity to uncover trends and opportunities and inform marketing strategy for the requested product. This agent will be used by members of the Marketing department.
    ```

4. After you submit the prompt, the **Agent Builder** form appears for your new agent. The **Agent Builder** chat pane appears on the left, and the agent details appear on the right. At the top of the form are a **Configure** tab and a **Preview** tab.

    - The **Agent Builder** chat pane on the left enables you to carry on a conversation with **Agent Builder** to refine your agent.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    - The **Preview** tab enables you to test the agent by entering starter prompts or custom messages.

    Wait a minute or two for Microsoft Copilot to create the agent. Once the agent is created, its name and description appear on the **Configure** tab.

5. Make sure the **Configure** tab is selected at the top of the form. Let's see what Microsoft Copilot did based on the prompt that you entered.

6. On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down through the **Instructions** section. Microsoft Copilot generated these instructions based on the description that you provided in your initial prompt. Review the level of detail in the generated instructions.

   > [!IMPORTANT]
   > The beauty of the Agent Builder process is that Microsoft Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

7. If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Microsoft Copilot to update the instructions for you.

    After reviewing the **Instructions**, you wonder whether they could be improved. You aren't sure how to improve them, so you decide to ask Microsoft Copilot what it thinks.  
    
    To do so, select the **Agent Builder** chat pane. Enter a prompt asking Microsoft Copilot what other instructions it would recommend to improve this agent.

8. Review Microsoft Copilot's recommendations. You're pleased with its suggestions, so ask Microsoft Copilot to add them all to the agent's instructions.

9. Once Microsoft Copilot responds that it updated the instructions, on the **Configure** tab, scroll through the **Instructions** section. Note the new items that Microsoft Copilot added.

10. Now that you're satisfied with the instructions, you're ready to configure the agent's knowledge sources and starter prompts.  
    
    On the **Configure** tab, scroll down to the **Knowledge** section and verify that the **Web search** toggle switch is enabled. Microsoft Copilot should have enabled this toggle switch when it created the agent based on the description you provided in your original prompt (that is, "...**draw from web sources such as** ..."). If the toggle switch isn't enabled, enable it now.

11. For **Suggested prompts**, you can have Microsoft Copilot generate prompts for you, or you can manually create your own prompts. Let's try both methods.  
    
    To have Microsoft Copilot generate suggested prompts, select the **Agent Builder** chat pane and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

12. You now want to enter several of your own prompts. On the **Configure** tab, scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    
    For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    
    Six suggested prompts related to popular market research actions are displayed below. Add the first prompt (**Market insights report**), as it is used in the next task. Then review the remaining prompts, select two or three others that you like, and add them to the agent as well.
    
    - **Title:** Market insights report (Note: This prompt is used in the next task; ensure that you add this prompt.)
        - **Message:** Generate a downloadable market insights summary report in Microsoft Word that includes top trends, audience behaviors, competitive developments, and recommended marketing actions for {Product Category}. Include cultural shifts, content consumption patterns, and influencer roles. Recommend how these insights can shape messaging and channel strategy.

    - **Title:** Social media analysis
        - **Message:** Analyze recent social media conversations about {Product Name}. Summarize overall sentiment, key themes, and top pain points. Highlight any emerging trends or cultural signals that could influence marketing strategy.

    - **Title:** Competitor positioning
        - **Message:** Provide a competitor scan for {Product Category}. Identify major competitors' positioning, recent product announcements, pricing changes, and marketing campaigns. Summarize implications for our product and suggest counter‑strategies.

    - **Title:** Industry research synthesis
        - **Message:** Review publicly available industry reports and whitepapers on {Product Category}. Summarize market drivers, inhibitors, and forecast trends. Highlight strategic opportunities and risks for our product.

    - **Title:** Launch campaign ideas
        - **Message:** Based on current market sentiment and competitor activity, propose three actionable recommendations for a launch campaign for {Product Name}. Include rationale, expected impact, and priority ranking (P1–P3).

    - **Title:** Market landscape brief
        - **Message:** Create a downloadable executive‑ready market landscape brief for {Product Category}. Include audience sentiment, competitor positioning, emerging trends, and actionable recommendations for marketing strategy. Structure the output with headings and bullet points for clarity.
    
13. On the **Preview** tab, test several of the suggested prompts. Verify that the agent is correctly using web search to gather relevant, up-to-date market information.

    > [!NOTE]
    > This agent relies on public web search to gather information. For the best experience when testing the suggested prompts, use a real product name and product category. Fictional products may return limited or less relevant results.

14. Once you're satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

15. Once the agent is created, a dialog box appears indicating that the agent was successfully created. In this dialog box, you can either start chatting with the agent or share it. Select the **Start chat** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn't required since you're working within your own tenant.





