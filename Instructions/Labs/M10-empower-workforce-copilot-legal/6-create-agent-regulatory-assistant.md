# Exercise 1, Task 4: Use Copilot Studio to create a Regulatory Inquiry Assistant
---
As the audit window opens, the regulatory inquiries begin to trickle in—first a routine clarification, then a request for supporting documentation, then a surprise follow‑up asking for a deeper explanation of data‑handling obligations. Boulder Innovation knows how quickly these routine checks can escalate into a flood.

To help the Legal Team stay ahead of the curve, you’re tasked with creating a Copilot Studio agent that can search the Web for authoritative regulatory sources on demand. Instead of spending hours digging for official guidance, the team gains a smart, dependable research assistant in their corner every time a new question associated with the state audit related to the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA) hits their inbox.

> [!NOTE] 
> In this exercise, you use the Copilot Studio lite experience to create the Regulatory Inquiry Assistant agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

2.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

3.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** Regulatory Inquiry Assistant

    - **Description:** The purpose of this agent is to search the web for authoritative CCPA and CPRA guidance and generate clear, well‑supported answers to audit‑related questions. The agent helps the Legal team respond to regulators with speed, accuracy, and confidence. The agent is a research and drafting aid—not legal counsel.

    - **Instructions**: This agent serves as a real‑time Regulatory Inquiry Assistant for the Legal team, using the Web as its primary knowledge source to surface authoritative guidance on CCPA/CPRA. It should deliver plain‑language, citation‑backed answers to audit‑related questions, prioritizing credible sources such as official agency pages and recognized legal/compliance trackers. Responses should be written in a professional, precise, and neutral legal tone. It should flag uncertainties, version changes, or pending rulemaking when relevant.

4.  To update the **Instructions** field, you must return to the browser tab that contains the Copilot Chat window with the agent instructions that Copilot Chat generated. At the top of the box containing the instructions, select the **Copy code** icon. Return to this tab containing the **New Agent** form and paste the copied text into this **Instructions** field.

5.  In the **Knowledge** section, select the **Search all websites** toggle switch to enable it.

6.  In the **Suggested prompts** section, add the following prompts that ask questions about popular HR-related topics. For example:

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
            
7.  Test several of the suggested prompts. Verify the agent includes citations/links for each response. 

8.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

9.  Once the agent is created, select the option to go to the agent, which is used in the next task.

10. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

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

        Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a Copilot prompt that contains the information outlined above. Do NOT submit the prompt just yet.

12.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        > [!NOTE]
        > Most everyday users don’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.

        **I plan to create a new Copilot agent called Regulatory Inquiry Assistant. The purpose of this agent is to search the web for authoritative CCPA and CPRA guidance and generate clear, well‑supported answers to audit‑related questions. The agent helps the Legal team respond to regulators with speed, accuracy, and confidence. The agent is a research and drafting aid—not legal counsel.**
        
        **The agent should be able to answer a wide range of audit‑related questions about the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA). It should also help interpret vendor‑related duties, cross‑border data‑processing considerations, and contractual responsibilities under the laws. Overall, it must function as a reliable, web‑grounded research assistant capable of producing accurate, well‑structured answers that support audit readiness.**
        
        **The agent should respond in a professional, precise, and neutral legal tone, suitable for attorneys, compliance officers, and regulatory stakeholders. Writing should be clear, structured, and free of speculation, relying only on credible, authoritative sources. All answers must be well‑supported, include citations or links to official regulatory materials when available, and avoid informal language or overly broad generalizations.**
        
        **The agent must rely on the Web as its primary knowledge source, using only credible and authoritative websites when answering questions. All responses should cite or link to the specific sources used.**
        
        **The agent should limit responses to CCPA/CPRA and closely related California privacy topics (consumer rights, processing/sharing/selling, sensitive personal information, data retention, vendor/processor obligations, breach notification, enforcement/penalties). If a user asks questions that are outside this scope (for example, GDPR or other state laws), politely narrow: provide a brief contrast only if helpful, then return to CCPA/CPRA.**
        
        **Do not invent, guess, or extrapolate beyond what the cited source says. If the answer is uncertain or sources conflict, state the uncertainty, cite both sources, and offer a clarifying question. Prefer current/updated pages; avoid archived or outdated guidance unless explicitly relevant (note the date if you must use archived content).**
        
        **Never include internal, confidential, or personally identifiable information (PII) in responses. Don’t describe internal systems, configurations, or security controls beyond publicly shared policy statements unless the user provides approved text to reference.**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**
    
13.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

14.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **Regulatory Inquiry Assistant** agent appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **Regulatory Inquiry Assistant** agent should appear in the list.

15.  Hover over the **Regulatory Inquiry Assistant** agent and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

16.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

17.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

18.  In the **Regulatory Inquiry Assistant** agent, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?


This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.
