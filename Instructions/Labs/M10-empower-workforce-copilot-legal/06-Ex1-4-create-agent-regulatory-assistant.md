# Exercise 1, Task 4: Use Copilot Studio to create a Regulatory Inquiry Assistant
---
As the audit window opens, the regulatory inquiries begin to trickle in—first a routine clarification, then a request for supporting documentation, then a surprise follow‑up asking for a deeper explanation of data‑handling obligations. Boulder Innovation knows how quickly these routine checks can escalate into a flood.

To help the Legal Team stay ahead of the curve, you’re tasked with creating a Copilot Studio agent that can search the Web for authoritative regulatory sources on demand. Instead of spending hours digging for official guidance, the team gains a smart, dependable research assistant in their corner every time a new question associated with the state audit related to the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA) hits their inbox.

> [!NOTE] 
> In this exercise, you use the Copilot Studio lite experience to create the Regulatory Inquiry Assistant agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

2.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

3.  On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
    <br/>**Create an agent titled Regulatory Inquiry Assistant. The purpose of this agent is to search the web for authoritative CCPA and CPRA guidance and generate clear, well‑supported answers to audit‑related questions. The agent helps the Legal team respond to regulators with speed, accuracy, and confidence. The agent is a research and drafting aid—not legal counsel.**

4.  After you selected the forward arrow, the **Agent Builder** form appeared for your new agent. At the top of the form is a **Describe** tab and a **Configure** tab.

    - The **Describe** tab enables you to carry on a conversation with Copilot. This tab is displayed by default.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    Wait a minute or two for Copilot to create the agent, at which time it displays the agent’s name and description in the **Agent preview** pane.

5.  Select the **Configure** tab at the top of the form. Let’s see what Copilot did based on the prompt that you entered.

6.  On the **Configure** tab, the **Name** and **Description** fields should be filled in based on the prompt that you entered. Scroll down to the **Instructions** field. Copilot generated these instructions based on the description that you provided in your initial prompt. Review the detailed level of instructions that Copilot generated.

   > [!IMPORTANT]
   > The beauty of the Agent Builder process is that Copilot automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

7.  If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Copilot to update the instructions for you.  
    <br/>After reviewing the **Instructions**, you decide that you want to have Copilot add a couple of other items to the instruction set. To do so, select the **Describe** tab and then enter the following prompt:

    **Update the Instructions to include the following items: Responses should be written in a professional, precise, and neutral legal tone. The agent should flag uncertainties, version changes, or pending rulemaking when relevant.**

8.  Review Copilot’s response after updating the instructions. To verify the changes that Copilot made, select the **Configure** tab and then scroll down to the **Instructions** field. Verify that Copilot added the two new instructions that you requested.

9.  While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.
    <br/><br/>To do so, select the **Describe** tab. This time, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

10.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent's instructions.

11.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

12.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is enabled. Copilot should have enabled this toggle switch when it created the agent based on the description you provided in your original prompt (that is, “**The purpose of this agent is to search the web**…”). If the toggle switch isn’t enabled, then do so now.

13.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

14.  You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    <br/>Six suggested prompts are displayed below that are related to popular regulatory topics. Review these prompts, select two or three that you like, and then add them to the agent.

        - **Title:** Consumer Rights Timelines
            - **Message:** What response timelines and verification requirements apply to verified consumer requests under CCPA/CPRA (access, deletion, correction), and what exceptions could limit fulfillment?  
                
        - **Title:** Sharing vs. Selling Definitions & Impacts
            - **Message:** How does CPRA define and distinguish “sharing” from “selling” personal information, and what are the practical compliance impacts for opt‑out rights and cross‑context behavioral advertising?  
                
        - **Title:** Breach Notification Basics
            - **Message:** What are the core elements, timelines, and recipient requirements for breach notifications affecting California residents, and which authoritative sources should be cited in regulatory communications?  
                
        - **Title:** Data Retention & Minimization Guidance
            - **Message:** Summarize current CPRA requirements for data retention, minimization, and purpose limitation in plain language suitable for Legal review. Provide a concise explanation of disclosure expectations, then list five operational steps a business should take to build or update a retention schedule. Prefer authoritative web sources (for example, California Privacy Protection Agency, statute pages) and include citations with direct links to the most recent guidance.  
                
        - **Title:** Service Provider/Contractor Obligations
            - **Message:** Outline the contractual obligations for service providers and contractors under CCPA/CPRA, describing required clauses (use restrictions, assistance with consumer requests, onward‑transfer controls, audits/assessments) and practical implications for vendor management. Present a brief table of “clause name → purpose” to aid template drafting and cite authoritative sources (.gov or official agency guidance) with links to the relevant statutory text.  
                
        - **Title:** Enforcement & Penalties Risk Brief
            - **Message:** Develop a concise risk brief that explains enforcement mechanisms and penalties under CCPA/CPRA, noting the roles of the California Privacy Protection Agency and the Attorney General. Include a risk matrix (low/medium/high) for three common noncompliance scenarios—failure to honor opt‑outs, inadequate consumer‑request handling, and insufficient disclosures—and add recommended corrective actions. Ground the brief in authoritative web sources and provide citations with direct links.  
            
15.  Test several of the suggested prompts. Verify the agent includes citations/links for each response.

16.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

17. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.





