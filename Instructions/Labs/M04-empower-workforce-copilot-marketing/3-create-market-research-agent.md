# Exercise 1, Task 1: Use Copilot Studio to create a Market Research Agent
---
Relecloud is preparing to launch WorkSmart 360 in the commercial office market. It’s critical that Relecloud’s Marketing department understand the competitive landscape, customer preferences, and emerging trends to inform the campaign. Your first step is to build a Market Research Agent that can aggregate this information from web sources, social media, and research reports.

This agent should be product agnostic. Relecloud recently implemented Microsoft 365 Copilot, so you plan to use it for researching WorkSmart 360. But moving forward, the Marketing team plans to use it for any number of the company’s products.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the Market Research Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  In your Microsoft Edge browser, go to the **Microsoft 365** home page **(https://www.office.com)**.

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

4.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** Market Research Agent

    - **Description:** The Market Research Agent should gather and analyze market insights for a requested product, drawing from social media, research reports, customer sentiment, and competitor activity to uncover trends and opportunities and inform marketing strategy.

    - **Instructions:** The agent should gather and analyze market insights for a requested product, drawing from web sources such as social media, research reports, customer sentiment, and competitor activity to uncover trends and opportunities and inform marketing strategy.

5.  In the **Knowledge** section, select the **Search all websites** toggle switch to enable it.

6.  In the **Suggested prompts** section, add the following prompts that ask generic questions or tasks related to market research. For example:

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

7.  Add any other suggested prompts if you wish.

8.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

9.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

10.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

        > [!NOTE]
        > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

### Update the agent’s instructions (optional)

Now that you created a working agent using a minimal instruction set, let’s refine its Instructions if time permits. 

While short, vague instructions are common in real-world scenarios, they often leave too much room for interpretation, which can limit the quality, consistency, and usefulness of an agent’s responses. By expanding the Instructions with clearer goals, context, tone, and constraints, you give the agent stronger guidance on _how_ it should think and respond.

In the remaining steps in this task, you update the agent’s Instructions using a more detailed version generated with Copilot Chat, then rerun the same suggested prompts as before. Comparing the before-and-after responses helps you see firsthand how well-crafted instructions can dramatically improve an agent’s performance without changing any tools, data sources, or prompts—just the guidance it’s given.

11.  You’re now going to submit a prompt in Copilot Chat that asks it to create a detailed instruction set for your agent. When asking Copilot to generate agent instructions, include the following information in your prompt:
    - What’s the agent’s primary job
    - Who the answers are for
    - What kinds of questions it should and shouldn't answer
    - Which documents it can trust
    - Any rules or constraints it must follow
    - Ask Copilot to return the instructions in a code block for easier copy and pasting.

        Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a Copilot prompt that contains this information. Do NOT submit the prompt just yet.

12.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        > [!NOTE]
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.
    
        **I’m creating a Copilot agent called “Market Research Agent.” The purpose of this agent is to gather and analyze market insights, uncover trends and opportunities, and inform marketing strategy for a requested product.**
        
        **The agent should gather insights from reputable and publicly available sources, including social media conversations, comments, and posts relevant to the product category, industry research reports, whitepapers, and analyst insights, competitor websites, product announcements, marketing materials, and press releases, and news articles, blogs, and other relevant online content that reflect audience sentiment and emerging trends.**
        
        **The agent should use a professional, analytical, and strategic tone — like a marketing strategist briefing a leadership team. Responses should be clear, concise, and structured for readability, using headings, subheadings, or bullet points when summarizing information. Recommendations should be actionable and prioritized where appropriate.**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**

13.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

14.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **Market Research Agent** appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **Market Research Agent** should appear in the list.

15.  Hover over the **Market Research Agent** and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

16.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

17.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

18.  In the **Market Research Agent**, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?

This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.


