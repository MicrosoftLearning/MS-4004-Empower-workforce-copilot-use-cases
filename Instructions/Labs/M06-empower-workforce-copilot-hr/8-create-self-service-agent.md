You’re an HR Analyst at Adatum Corporation, a mid-sized technology firm with approximately 3,000 employees across multiple U.S. locations. Adatum’s HR department receives hundreds of inquiries each month about benefits, promotions, relocation, and other company policies.

To reduce costs and improve service, you were asked to create an HR self-service agent in Microsoft 365 Copilot. The purpose of this agent is to answer employee questions using official HR policy documents as its knowledge base.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the HR self-service agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Select each of the following links to download their respective HR policy files and store them in your OneDrive account:
    - Adatum Code of Conduct and Workplace Behavior.docx
    - Adatum Employee Benefits Policy.docx
    - Adatum Leave of Absence Policy.docx
    - Adatum Promotion and Career Development Policy.docx
    - Adatum Relocation Policy.docx
    - Adatum Remote Work and Flexible Schedule Policy.docx

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page **(https://www.office.com)**.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

4.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** HR Self-Service Assistant

    - **Description:** The HR Self‑Service Assistant provides Adatum employees with accurate, easy‑to‑understand answers to common HR questions. It uses the official HR policy documents assigned to this agent as its source of truth and can help with topics such as benefits, paid time off (PTO) and leave policies, promotions, relocation guidelines, payroll schedules, and general HR procedures. The assistant delivers clear, professional, and employee‑friendly guidance while ensuring responses remain consistent with Adatum’s current HR policies and practices.

    - **Instructions:** The agent should provide answers to employees’ HR questions using only the approved HR policy documents assigned to this agent as knowledge sources.  

5.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the six files that you downloaded in step 1 and stored on your OneDrive**.**

6.  In the **Suggested prompts** section, add the following prompts that ask questions about popular HR-related topics. For example:

    - **Title:** Relocation Policy
        - **Message:** What is Adatum’s relocation policy for employees who are moving due to a promotion?

    - **Title:** Benefits Enrollment & Plan Changes
        - **Message:** When is the next open enrollment window for benefits, and how do I change my medical or dental plan?

    - **Title:** PTO & Leave
        - **Message:** How does PTO accrue at Adatum, what is the year‑end carryover policy, and how do I submit a PTO request?

    - **Title:** Promotion Criteria
        - **Message:** What are the general promotion criteria for moving from an individual contributor role to a manager role at Adatum?

    - **Title:** Paydays, Deductions, and Pay Statements
        - **Message:** When are regular paydays, where can I find my pay statements, and how are common deductions (benefits, taxes, retirement) handled?

    - **Title:** Parental Leave
        - **Message:** What is Adatum’s parental leave policy?  
            
7.  Test several of the suggested prompts (you submit custom prompts in the next task). Verify the agent is correctly pulling in data from the knowledge source documents. 

8.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

9.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

    > [!NOTE]
    > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.
    
### Update the agent's instructions (optional)

Now that you created a working agent using a minimal instruction set, let's refine its Instructions if time permits. 

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

        > [!NOTE]
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.

        **I’m creating a Copilot agent called “HR Self-Service Assistant.” This agent’s purpose is to provide authoritative, up‑to‑date answers to employee HR questions—covering benefits, promotions, relocation, leave/absence, payroll, and other policy topics—using only the approved HR policy documents assigned to this agent as knowledge sources.**
        
        **The agent is intended for all company employees and should provide clear, action-oriented insights related to HR topics, such as benefits eligibility and enrollment windows; promotion criteria and process; relocation assistance (policy coverage, reimbursement rules, timelines); paid time off (PTO), leaves (FMLA/state leave), holidays; payroll cycles and deductions; how to contact HR for escalations; and any other HR-related questions that it can find answers to from the knowledge source files.** 
        **<br/><br/>The agent should only use the files assigned to it as knowledge sources.**
        
        **The agent should use a professional, empathetic, and clear tone appropriate for employee communications. Prefer short paragraphs and bullets, label sections, and include “What to do next” guidance when appropriate. Avoid jargon; define terms briefly if needed.**
        **<br/><br/>When generating responses, the agent should:**
        
        - - **Cite a source for every answer**
            - **Don’t speculate; answer only from the agent’s assigned HR documents.**
            - **If information is missing or ambiguous, flag the gap and provide a fallback response, such as: _“I don’t have a verified answer in the assigned HR sources. Please contact HR Support or see the HR Policy Portal._**
            - **Politely decline sensitive or case‑specific topics (compensation details, medical data, manager‑only policies) with a privacy‑aware message and redirect: _“I can’t access or share personal/sensitive information. Please contact HR Support for individualized assistance.”_**
            - **Keep answers strictly within Adatum’s HR policy context and current policy year.**
            - **Highlight deadlines, eligibility criteria, and documentation requirements (forms, receipts) where relevant.**
            - **Provide links or titles of forms/pages (even if placeholders in the lab), and include a standard disclaimer: _“Policies may vary by location or role; verify with HR if unsure.”_**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**

12.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

13.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **HR Self-Service Assistant** agent appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **HR Self-Service Assistant** agent should appear in the list.

14.  Hover over the **HR Self-Service Assistant** agent and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

15.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

16.  In the **Your agent was updated successfull**y window, select the **Go to agent** option.

17.  In the **HR Self-Service Assistant** agent, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?

This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.