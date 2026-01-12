Contoso broke ground on the Fargo distribution center expansion. The company is tracking project milestones in Loop (Task 1). As the Operations Leader, you received feedback that leadership and frontline teams need reliable, one‑stop answers to recurring questions about construction timelines, temporary access changes, safety requirements, and inventory move windows—without flooding Operations with emails or chat pings.

Questions are coming in from across the organization:

- Frontline staff (warehouse/floor teams) seeking day‑to‑day guidance.
- Supervisors and Coordinators (safety, logistics) who need quick references.
- Leadership and project program managers who want authoritative answers to status/impact questions.

Many of the questions that Operations staff ask are similar every day. For example:

- “Is Dock 3 open yet?”
- “Which temporary evacuation routes apply to Packing?”
- “When do CHAI‑12 and COFF‑08 move?”
- “What PPE is required in the new wing?”

The scope of questions is beginning to overwhelm the Operations team, especially given the fact that answers must be consistent, citation‑based, and available 24/7. To address this issue, you decide to take advantage of Microsoft 365 Copilot’s AI assistant functionality and create a Q&A agent that can:

- Answer natural‑language questions about the expansion using connected, approved documents.

- Show citations/links so users can trust and verify details.

- Use guardrails (only answer from sources; no speculation; redirect to Operations Intake when content is missing; politely decline when a question falls outside its scope).

- Offer concise fallbacks.

> [!NOTE:]
> In this exercise, you use the Copilot Studio lite experience to create the Facility Expansion FAQ Assistant agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Select each of the following links to download their respective files and store them in your OneDrive account:
    - **Contoso_Expansion_Project_Overview.docx**
    - **Contoso_Expansion_FAQ_Reference.docx**
    - **Contoso_Expansion_Knowledge_Pack.docx**
    - **Contoso_Inventory_Move_Schedule.docx**
    - **Contoso_Safety_Protocol_Updates.docx**
    - **Contoso_Temporary_Evacuation_Routes.docx**
    - **Contoso_Vendor_Access_and_Hours.docx**

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

4.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:

    - **Name:** Facility Expansion FAQ Assistant

    - **Description:** The Facility Expansion FAQ Assistant helps employees, supervisors, and vendors quickly find accurate, up‑to‑date information about the Fargo distribution center expansion.

    - **Instruction:** This agent should answer questions about Contoso’s Fargo distribution center expansion, such as construction timelines, safety protocols, temporary evacuation routes, inventory move waves, vendor access requirements, and operational impacts—using only approved documents and verified project sources.

5.  To update the **Instructions** field, you must return to the browser tab that contains the Copilot Chat window with the agent instructions that Copilot Chat generated. At the top of the box containing the instructions, select the **Copy code** icon. Return to this tab containing the **New Agent** form and paste the copied text into this **Instructions** field.

6.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the seven files that you downloaded in step 1 and stored on your OneDrive**.**

7.  In the **Suggested prompts** section, add the following prompts that ask questions about popular facility expansion topics. For example:

    - **Title:** Construction Timeline Check
        - **Message:** What construction phase are we currently in for the Fargo distribution center expansion, and which areas of the building are affected this week?

    - **Title:** PPE & Safety Requirements
        - **Message:** What PPE is required in the construction-adjacent zones, and do these requirements change during the 24‑week expansion?

    - **Title:** Temporary Evacuation Route Guidance
        - **Message:** What is the temporary evacuation route for the Packing area during the expansion, and where is the nearest assembly point?

    - **Title:** Inventory Move Wave Details
        - **Message:** Which SKUs are included in the next inventory move wave, and what are the start and end dates for that wave?

    - **Title:** Vendor Access & Parking Instructions
        - **Message:** Where should vendors park during the expansion, and what are the temporary access hours and check‑in rules?

    - **Title:** Operational Impacts Summary
        - **Message:** What operational impacts should staff expect over the next few weeks due to the ongoing construction and dock upgrades?  
            
8.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents. You submit custom prompts in the next task.

9.  Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

10. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

    > [!NOTE:]
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
    
        Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a Copilot prompt that contains the information outlined above. **Do NOT submit the prompt just yet.**

12.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        > [!NOTE:]
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.

        **I’m creating a Copilot agent called “Facility Expansion FAQ Assistant.” The agent should answer staff, supervisor, and vendor questions about Contoso’s Fargo distribution center expansion, such as: current construction phase status; dock closures and re‑open dates; PPE requirements; temporary evacuation routes by zone; inventory move wave dates and SKUs; forklift routing changes; vendor access hours, parking, and escorted entry rules; and any operational impacts during the 24‑week project.**
        
        **Use a professional, concise, and action‑oriented tone. Prioritize clarity for frontline staff and supervisors. Structure responses with short labels, bullet points, and one‑sentence summaries when appropriate. Include a brief “What to do next” step if the answer implies required actions.**
        
        **Use the files assigned to this agent as the knowledge sources.  
        <br/>Cite a source for every answer. Do not speculate; answer only from the connected approved sources. If information is missing or outdated, flag the gap and provide a fallback: _“I don’t have a verified answer for that yet. Please check the Expansion Overview or contact Operations Intake.”_ Politely decline sensitive topics (for example, budget breakdowns or contracts) with: _“I’m unable to share that information. Please contact the Project Controller.”_ Keep answers specific to the Fargo expansion and the current 24‑week timeline. Provide links/citations and highlight critical dates or zones in the response.**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**
        
13.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

14.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **Facility Expansion FAQ Assistant** agent appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **Facility Expansion FAQ Assistant** agent should appear in the list.

15.  Hover over the **Facility Expansion FAQ Assistant** agent and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

16.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

17.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

18.  In the **Facility Expansion FAQ Assistant** agent, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?

This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance, without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.
