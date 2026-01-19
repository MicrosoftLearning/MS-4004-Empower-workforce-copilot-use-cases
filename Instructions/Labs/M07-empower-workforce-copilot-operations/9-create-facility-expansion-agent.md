# Exercise 2, Task 2: Use Copilot Studio to build a Facility Expansion FAQ agent
---
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

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the Facility Expansion FAQ Assistant agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Select each of the following links to download their respective files and store them in your OneDrive account:

    - [**Contoso_Expansion_Project_Overview.docx**](https://go.microsoft.com/fwlink/?linkid=2347809)

    - [**Contoso_Expansion_FAQ_Reference.docx**](https://go.microsoft.com/fwlink/?linkid=2347517)

    - [**Contoso_Expansion_Knowledge_Pack.docx**](https://go.microsoft.com/fwlink/?linkid=2347808)

    - [**Contoso_Inventory_Move_Schedule.docx**](https://go.microsoft.com/fwlink/?linkid=2347519)

    - [**Contoso_Safety_Protocol_Updates.docx**](https://go.microsoft.com/fwlink/?linkid=2347520)

    - [**Contoso_Temporary_Evacuation_Routes.docx**](https://go.microsoft.com/fwlink/?linkid=2347611)

    - [**Contoso_Vendor_Access_and_Hours.docx**](https://go.microsoft.com/fwlink/?linkid=2347521)

2.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

3.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio’s **Agent Builder** and displays the **New agent** page.

4.  On the **New Agent** page, you want to ask Copilot to create an agent. In the prompt, you should enter the agent’s name and a general description of what the agent is about, who its target audience is, and what you want it to do.  
    <br/>For this agent, enter the following prompt and then select the forward arrow (Send) icon to submit the prompt:  
    <br/>**Create an agent titled Facility Expansion FAQ Assistant. The purpose of this agent is to answer employee questions about Contoso’s Fargo distribution center expansion, such as construction timelines, safety protocols, temporary evacuation routes, inventory move waves, vendor access requirements, and operational impacts—using only approved documents that are assigned to this agent as knowledge sources.**

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

    - **Don’t speculate. If information is missing or ambiguous, flag the gap and provide a polite fallback response, such as: “I don’t have a verified answer for that yet. Please check the Expansion Overview or contact Operations Intake.”**

    - **Politely decline sensitive topics (for example, budget breakdowns or contracts) with: “I’m unable to share that information. Please contact the Project Controller.”**

    - **Keep answers specific to the Fargo expansion and the current 24‑week timeline.**

    - **Provide links/citations and highlight critical dates or zones in the response.**

9.  Review Copilot’s response after updating the instructions. To verify the changes that Copilot made, select the **Configure** tab and then scroll down to the **Instructions** field. Verify that Copilot added the new instructions that you requested.

10.  While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Copilot what it thinks.  
    <br/>To do so, select the **Describe** tab. This time, enter a prompt that asks Copilot what other instructions it would recommend that could improve this agent.

11.  Review Copilot’s recommendations. You’re pleased with its suggestions, so ask Copilot to add them all to the agent’s instructions.

12.  Once Copilot responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Copilot added.

13.  Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and starter prompts.  
    <br/>In the **Configure** tab, scroll down to the **Knowledge** section and verify the **Search all websites** toggle switch is disabled. Copilot should have disabled this toggle switch when it created the agent based on the description you provided in your original prompt, which told it to only use the files that you provide. If the toggle switch is enabled, then disable it now.

14.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the seven files that you downloaded in step 1 and stored on your OneDrive.

15.  For **Suggested prompts**, you can have Copilot generate prompts for you, or you can manually create your own prompts. Let’s try both methods.  
    <br/>To have Copilot generate suggested prompts, select the **Describe** tab and then ask Copilot to generate three suggested prompts for the agent. Note how each prompt has a title and a message.

16.  You now want to enter several of your own prompts. Select the **Configure** tab and scroll down to the **Suggested prompts** section. You should see the three prompts that Copilot added to the agent.  
    <br/>For each prompt that you want to manually add, select the **Add a suggested prompt** option that appears below the prompts.  
    <br/>Six suggested prompts are displayed below that are related to popular facility expansion topics. Review these prompts, select two or three that you like, and then add them to the agent.

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
                
17.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents. You submit custom prompts in the next task.

18. Once you’re satisfied with the results for the suggested prompts, select the **Create** button to create the agent.

19. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

> [!NOTE]
> At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

