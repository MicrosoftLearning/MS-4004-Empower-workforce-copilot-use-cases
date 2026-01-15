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

    - **TR‑Pulse FAQ.docx -** Contains a curated set of common employee questions and approved answers about TR‑Pulse to help the agent respond clearly and consistently to everyday inquiries.

    - **TR‑Pulse FAQ Assistant.docx** \- Defines the tone, boundaries, and escalation rules that govern how the FAQ agent responds empathetically while routing sensitive or out‑of‑scope questions appropriately.

    These files represent the authoritative sources the TR‑Pulse FAQ Assistant should rely on when answering employee questions. They intentionally replace generalized SharePoint pages, HR policy repositories, and communications style guides for the purposes of this exercise.

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

4.  On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
    <br/>**Create an agent titled TR‑Pulse FAQ Assistant. The purpose of this agent is to provide answers to employee questions related to TR-Pulse, Trey Research’s quarterly communication experience that’s designed to improve transparency, celebrate employee contributions, and keep teams informed about major initiatives. The agent should only use the files assigned to it as knowledge sources.**

5.  After you selected the forward arrow, the **Agent Builder** form appeared for your new agent. At the top of the form is a **Describe** tab and a **Configure** tab.

    - The **Describe** tab enables you to carry on a conversation with Copilot. This tab is displayed by default.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    Wait a minute or two for Copilot to create the agent, at which time it displays the agent’s name and description in the **Agent preview** pane.

6.  Select the **Configure** tab at the top of the form. Let’s see what Copilot did based on the prompt that you entered.

7.  On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down to the **Instructions** field. Copilot generated these instructions based on the description that you provided in your initial prompt. Review the detailed level of instructions that Copilot generated.

    > [!IMPORTANT]
    > The beauty of the Agent Builder process is that Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

8.  If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Copilot to update the instructions for you.  
    <br/>After reviewing the **Instructions**, you decide that you want to have Copilot add a couple of other items to the instruction set. To do so, select the **Describe** tab and then enter the following prompt:

    **Update the Instructions to include the following items:**
    
    - **Never disclose personal, confidential, or restricted data.**
    - **If a date or detail is not yet confirmed , say “scheduled/targeted for \[month/week\], pending confirmation,” and link to the update source.**
    - **If a metric is unavailable , say “not published,” explain why if known (for example, validation cycle), and provide the expected refresh cadence.**
    - **If a policy question exceeds the agent’s scope, don’t speculate; instead, escalate to the listed owner or policy mailbox.**
    - **When to escalate: Policy interpretation, non‑public data, unresolved access issues, missing source content, or compliance/legal queries.**
    - **How to escalate: Provide the official channel (for example, TR‑Pulse Support Form or Communications Operations mailbox ) and list required details: summary of the question, team/org, relevant links/screenshots, urgency/time dependency, accessibility needs.**
    - **Set expectations: Typical response time window; note that complex items may require cross‑functional review.**

9.  Review Copilot’s response after updating the instructions. To verify the changes that Copilot made, select the **Configure** tab and then scroll down to the **Instructions** field. Verify that Copilot added the new instructions that you requested.

10.  While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.  
    <br/>To do so, select the **Describe** tab. This time, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

11.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent’s instructions.

12.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

13.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is disabled. Copilot should have disabled this toggle switch when it created the agent based on the description you provided in your original prompt, which told it to only use the files that you provide. If the toggle switch is enabled, then disable it now.

14.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, select the three files that you downloaded in Step 1.

15.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

16.  You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
        <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
        <br/>Six suggested prompts are displayed below that are related to popular business-related topics for Northwind Traders. Review these prompts, select two or three that you like, and then add them to the agent.
    
        - **Title:** Town Hall participation
            - **Message:** When is the next TR‑Pulse town hall, how do I submit a question in advance, and will a recording and transcript be available afterward?  
                
        - **Title:** Recognize a colleague
            - **Message:** How do I nominate a teammate for the TR‑Pulse recognition spotlight, what criteria are used, and when are honorees announced?  
                
        - **Title:** Highlights and updates
            - **Message:** Where can I see the latest TR‑Pulse progress updates and metrics highlights for my org or project, and how often is this information refreshed?  
                
        - **Title:** TR-Pulse Accessibility
            - **Message:** What accessibility options are available for TR‑Pulse content (live captions, translations, screen‑reader friendly docs, time‑zone friendly formats), and how can I request other accommodations?  
                
        - **Title:** Data privacy and compliance
            - **Message:** How does TR‑Pulse use employee survey feedback and submitted questions, who can access this data, and how is privacy maintained in line with company policy and compliance requirements?  
                
        - **Title:** Support and escalation
            - **Message:** If the TR‑Pulse FAQ agent can’t answer my question, how do I escalate for human support, what’s the typical response time, and what information should I include to speed up things?  
            
17.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

18. Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

19. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.
