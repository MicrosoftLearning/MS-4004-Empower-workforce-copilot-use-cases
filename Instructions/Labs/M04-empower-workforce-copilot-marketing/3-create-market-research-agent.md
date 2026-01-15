# Exercise 1, Task 1: Use Copilot Studio to create a Market Research Agent
---
Relecloud is preparing to launch WorkSmart 360 in the commercial office market. It’s critical that Relecloud’s Marketing department understand the competitive landscape, customer preferences, and emerging trends to inform the campaign. Your first step is to build a Market Research Agent that can aggregate this information from web sources, social media, and research reports.

This agent should be product agnostic. Relecloud recently implemented Microsoft 365 Copilot, so you plan to use it for researching WorkSmart 360. But moving forward, the Marketing team plans to use it for any number of the company’s products.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the Market Research Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

2.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

3.  On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
    <br/>**Create an agent titled Market Research Agent. The purpose of this agent is to gather and analyze market insights for a requested product. The agent should draw from web sources such as social media, research reports, customer sentiment, and competitor activity to uncover trends and opportunities and inform marketing strategy for the requested product. This agent will be used by members of the Marketing department.**

4.  After you selected the forward arrow, the **Agent Builder** form appeared for your new agent. At the top of the form is a **Describe** tab and a **Configure** tab.

    - The **Describe** tab enables you to carry on a conversation with Copilot. This tab is displayed by default.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    Wait a minute or two for Copilot to create the agent, at which time it displays the agent’s name and description in the **Agent preview** pane.

5.  Select the **Configure** tab at the top of the form. Let’s see what Copilot did based on the prompt that you entered.

6.  On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down to the **Instructions** field. Copilot generated these instructions based on the description that you provided in your initial prompt. Review the detailed level of instructions that Copilot generated.

    > [!IMPORTANT]
    > The beauty of the Agent Builder process is that Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

7.  If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Copilot to update the instructions for you.  
    <br/>After reviewing the **Instructions**, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.  
    <br/>To do so, select the **Describe** tab. Enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

8.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent’s instructions.

9.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

10.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is enabled. Copilot should have enabled this toggle switch when it created the agent based on the description you provided in your original prompt (that is, “…**drawing from web sources such as** …”). If the toggle switch isn’t enabled, then do so now.

11.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

12.  You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    <br/>Six suggested prompts are displayed below that are related to popular market research actions. Review these prompts, select two or three that you like, and then add them to the agent.
    
        - **Title:** Social media analysis
            - **Message:** Analyze recent social media conversations about {Product Name}. Summarize overall sentiment, key themes, and top pain points. Highlight any emerging trends or cultural signals that could influence marketing strategy.

        - **Title:** Competitor positioning
            - **Message:** Provide a competitor scan for {Product Category}. Identify major competitors’ positioning, recent product announcements, pricing changes, and marketing campaigns. Summarize implications for our product and suggest counter‑strategies.

        - **Title:** Industry research synthesis
            - **Message:** Review publicly available industry reports and whitepapers on {Product Category}. Summarize market drivers, inhibitors, and forecast trends. Highlight strategic opportunities and risks for our product.

        - **Title:** Market insights report (Note: This prompt is used in the next task)
            - **Message:** Generate a downloadable market insights summary report that includes top trends, audience behaviors, competitive developments, and recommended marketing actions for {Product Category}. Include cultural shifts, content consumption patterns, and influencer roles. Recommend how these insights can shape messaging and channel strategy.

        - **Title:** Launch campaign ideas
            - **Message:** Based on current market sentiment and competitor activity, propose three actionable recommendations for a launch campaign for {Product Name}. Include rationale, expected impact, and priority ranking (P1–P3).

        - **Title:** Market landscape brief
            - **Message:** Create a downloadable executive‑ready market landscape brief for {Product Category}. Include audience sentiment, competitor positioning, emerging trends, and actionable recommendations for marketing strategy. Structure the output with headings and bullet points for clarity.
    
13.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

14.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

15.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

