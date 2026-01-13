# Exercise 2, Task 4: Use Copilot Studio to create an FAQ Assistant agent
---
With TR‑Pulse now launched and the first quarterly town hall prepared, Trey Research must ensure employees can continue accessing clear, consistent, and empathetic information—without over‑reliance on email or delays in response.

One of the core components of TR‑Pulse is the TR‑Pulse FAQ Assistant, a no‑code agent designed to provide employees with on‑demand answers about the TR‑Pulse program, how to participate, and where to go for more support when needed. This assistant helps scale transparency while maintaining appropriate boundaries—answering what it can confidently address and routing sensitive or out‑of‑scope questions to the right teams.

As Trey Research’s Communications Manager, you’re responsible for designing and deploying this agent in a way that:

- Reinforces trust through clear, empathetic responses
- Maintains tone and message consistency across TR‑Pulse touchpoints
- Respects organizational boundaries around HR, compliance, and personal matters
- Reduces strain on Communications and leadership teams

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the TR‑Pulse FAQ Assistant agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Before creating the agent, select the following links to download these instructor‑provided documents and store them in your OneDrive:  

    - **TR‑Pulse Program Overview.docx** \- Provides an authoritative, employee‑facing explanation of what TR‑Pulse is, why it exists, and how employees can participate across each quarterly cycle.

    - **TR‑Pulse FAQ.docx** \- Contains a curated set of common employee questions and approved answers about TR‑Pulse to help the agent respond clearly and consistently to everyday inquiries.

    - **TR‑Pulse FAQ Assistant.docx** \- Defines the tone, boundaries, and escalation rules that govern how the FAQ agent responds empathetically while routing sensitive or out‑of‑scope questions appropriately.

    These files represent the authoritative sources the TR‑Pulse FAQ Assistant should rely on when answering employee questions. They intentionally replace generalized SharePoint pages, HR policy repositories, and communications style guides for the purposes of this exercise.

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

4.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** TR‑Pulse FAQ Assistant

    - **Description:** The TR‑Pulse FAQ Assistant answers employee questions about TR-Pulse, drafts empathetic replies, routes edge cases.

    - **Instructions:** The agent should provide answers to employee questions related to TR-Pulse, Trey Research’s quarterly communication experience designed to improve transparency, celebrate employee contributions, and keep teams informed about major initiatives.  
        

5.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, select the three files that you downloaded in Task 1.

6.  In the **Suggested prompts** section, add the following prompts that ask questions about popular business-related topics for Northwind Traders. For example:

    - **Title:** Town Hall participation
        - **Message:** When is the next TR‑Pulse town hall, how do I submit a question in advance, and will a recording and transcript be available afterward?

    - **Title:** Recognize a colleague
        - **Message:** How do I nominate a teammate for the TR‑Pulse recognition spotlight, what criteria are used, and when are honorees announced?

    - **Title:** Highlights and updates
        - **Message:** Where can I see the latest TR‑Pulse progress updates and metrics highlights for my org or project, and how often is this information refreshed?

    - **Title:** TR-Pulse Accessibility
        - **Message:** What accessibility options are available for TR‑Pulse content (live captions, translations, screen‑reader friendly docs, time‑zone friendly formats), and how can I request more accommodations?

    - **Title:** Data privacy and compliance
        - **Message:** How does TR‑Pulse use employee survey feedback and submitted questions, who can access this data, and how is privacy maintained in line with company policy and compliance requirements?

    - **Title:** Support and escalation
        - **Message:** If the TR‑Pulse FAQ agent can’t answer my question, how do I escalate for human support, what’s the typical response time, and what information should I include to speed up things?  
            
7.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

8.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

9.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

    >[!NOTE]
    > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

### Update the agent’s instructions (optional)

Now that you created a working agent using a minimal instruction set, let’s refine its Instructions if time permits.

While short, vague instructions are common in real-world scenarios, they often leave too much room for interpretation, which can limit the quality, consistency, and usefulness of an agent’s responses. By expanding the Instructions with clearer goals, context, tone, and constraints, you give the agent stronger guidance on _how_ it should think and respond.

In the remaining steps in this task, you update the agent’s Instructions using a more detailed version generated with Copilot Chat, then rerun the same suggested prompts as before. Comparing the before-and-after responses helps you see firsthand how well-crafted instructions can dramatically improve an agent’s performance without changing any tools, data sources, or prompts—just the guidance it’s given.

10.  You’re now going to submit a prompt in Copilot Chat that asks it to create a detailed instruction set for your agent. When asking Copilot to generate agent instructions, include the following information in your prompt:
    - What’s the agent’s primary job
    - Who the answers are for
    - What kinds of questions it should and shouldn't answer
    - Which documents it can trust
    - Any rules or constraints it must follow
    - Ask Copilot to return the instructions in a code block for easier copy and pasting.

        Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a Copilot prompt that contains the information outlined above. **Do NOT submit the prompt just yet.**

11.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        >[!NOTE]
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.
    
        **I’m creating a Copilot agent called “TR‑Pulse FAQ Assistant.” This agent’s purpose is to provide accurate, empathetic, and actionable answers to employee questions about the TR‑Pulse quarterly communication experience, including town halls, recognition spotlights, progress updates, metrics, the always‑available FAQ, and participation paths.** 
        
        **The agent is intended for all Trey Research employees (clinical staff, R&D labs, corporate, remote/hybrid). Answers must be inclusive, respectful, and accessible across roles, time zones, and devices.**
        
        **The agent must only use the files assigned as knowledge sources to this agent.**
        
        **Include the following considerations when responding:**
        
        - **Never disclose personal, confidential, or restricted data.**
        - **If a date or detail is not yet confirmed , say “scheduled/targeted for \[month/week\], pending confirmation,” and link to the update source.**
        - **If a metric is unavailable , say “not published,” explain why if known (e.g., validation cycle), and provide the expected refresh cadence.**
        - **If a policy question exceeds agent scope, do not speculate —escalate to the listed owner or policy mailbox.**
        - **When to escalate: Policy interpretation, non‑public data, unresolved access issues, missing source content, or compliance/legal queries.**
        - **How to escalate: Provide the official channel (for example, TR‑Pulse Support Form or Communications Operations mailbox ) and list required details: summary of the question, team/org, relevant links/screenshots, urgency/time dependency, accessibility needs.**
        - **Set expectations: Typical response time window; note that complex items may require cross‑functional review.**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**

12.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

13.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **TR‑Pulse FAQ Assistant** agent appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **TR‑Pulse FAQ Assistant** agent should appear in the list.

14.  Hover over the **TR‑Pulse FAQ Assistant** agent and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

15.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

16.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

17.  In the **TR‑Pulse FAQ Assistant** agent, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?


This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.
