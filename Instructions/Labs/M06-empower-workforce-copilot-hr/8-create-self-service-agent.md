# Exercise 2, Task 1: Create an HR self-service agent for company employees
---
You’re an HR Analyst at Adatum Corporation, a mid-sized technology firm with approximately 3,000 employees across multiple U.S. locations. Adatum’s HR department receives hundreds of inquiries each month about benefits, promotions, relocation, and other company policies.

To reduce costs and improve service, you were asked to create an HR self-service agent in Microsoft 365 Copilot. The purpose of this agent is to answer employee questions using official HR policy documents as its knowledge base.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the HR self-service agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Select each of the following links to download their respective HR policy files and store them in your OneDrive account:

    - **Adatum Code of Conduct and Workplace Behavior.docx**

    - **Adatum Employee Benefits Policy.docx**

    - **Adatum Leave of Absence Policy.docx**

    - **Adatum Promotion and Career Development Policy.docx**

    - **Adatum Relocation Policy.docx**

    - **Adatum Remote Work and Flexible Schedule Policy.docx**

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

4.  On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
    <br/>**Create an agent titled HR Self-Service Assistant. The purpose of this agent is to provide Adatum Corporation's employees with answers to their HR-related questions. The agent should only use the approved HR policy documents that are assigned to this agent as knowledge sources.**

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

    - **Cite a source for every answer.**
    - **Don’t speculate. If information is missing or ambiguous, flag the gap and provide a polite fallback response, such as: “I don’t have a verified answer in the assigned HR sources. Please contact HR Support or see the HR Policy Portal."**
    - **Politely decline sensitive or case‑specific topics (compensation details, medical data, manager‑only policies) with a privacy‑aware message and redirect: “I can’t access or share personal/sensitive information. Please contact HR Support for individualized assistance.”**
    - **Avoid jargon; define terms briefly if needed.**

9.  Review Copilot’s response after updating the instructions. To verify the changes that Copilot made, select the **Configure** tab and then scroll down to the **Instructions** field. Verify that Copilot added the two new instructions that you requested.

10.  While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.  
    <br/>To do so, select the **Describe** tab. This time, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

11.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent’s instructions.

12.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

13.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is disabled. Copilot should have disabled this toggle switch when it created the agent based on the description you provided in your original prompt, which told it to only use the files that you provide. If the toggle switch is enabled, then disable it now.

14.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the six files that you downloaded in step 1 and stored on your OneDrive.

15.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

16.  You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    <br/>Six suggested prompts are displayed below that are related to popular HR-related topics. Review these prompts, select two or three that you like, and then add them to the agent.

        - **Title:** Relocation Policy
            - **Message:** What is Adatum’s relocation policy for employees who are moving due to a promotion?  
                
        - **Title:** Benefits Enrollment & Plan Changes
            - **Message:** When is the next open enrollment window for benefits, and how do I change my medical or dental plan?  
                
        - **Title:** Paid time off (PTO) & Leave
            - **Message:** How does PTO accrue at Adatum, what is the year‑end carryover policy, and how do I submit a PTO request?  
                
        - **Title:** Promotion Criteria
            - **Message:** What are the general promotion criteria for moving from an individual contributor role to a manager role at Adatum?  
                
        - **Title:** Paydays, Deductions, and Pay Statements
            - **Message:** When are regular paydays, where can I find my pay statements, and how are common deductions (benefits, taxes, retirement) handled?  
                
        - **Title:** Parental Leave
            - **Message:** What is Adatum’s parental leave policy?  
                
17.  Test several of the suggested prompts (you submit custom prompts in the next task). Verify the agent is correctly pulling in data from the knowledge source documents. You perform more extensive usage of this agent in a later task.

18. Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

19. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.


