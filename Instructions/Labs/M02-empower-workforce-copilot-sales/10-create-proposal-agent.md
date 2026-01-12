# Exercise 2, Task 3: Use Copilot Studio to build an RFP response agent
---
While Fabrikam’s sales success with EcoSense 360 generated strong interest from hotels and resorts, it also created a new challenge. The Sales team is spending hours each week responding to early-stage RFPs that ask similar questions about integrations, energy savings, and product capabilities. To address this bottleneck, Fabrikam's VP of Sales tasked you with developing a Copilot agent that can automatically handle these initial inquiries. 

You plan to use Copilot Studio to build an agent that performs two functions: first, it provides preliminary answers drawn from existing EcoSense 360 product materials, and second, it generates a response for a submitted RFP. This agent should reduce response times, free the Sales team to focus on higher-value opportunities, and give prospective clients a faster, more engaging experience.

> [!NOTE]
> In this exercise, you use the Copilot Studio lite experience to create the EcoSense 360 RFP Response Agent. This simplified experience is designed for everyday business users and requires no programming skills. By contrast, software developers who build more complex, advanced agents typically use the full Copilot Studio experience.

Perform the following steps to complete this task:

1.  Select the following links to download all the documents that will provide knowledge source content for the new EcoSense 360 RFP Response Agent:
    - **EcoSense_360_Compliance_Certification_Summary**
    - **EcoSense_360_Customer_Case_Study**
    - **EcoSense_360_Integration_Compatibility_Guide**
    - **EcoSense_360_Sample_Pricing_Sheet**
    - **EcoSense_360_Technical_Specifications**

    Store these files in the **EcoSense360-RFP-Documents** folder that you created in your OneDrive in Task 1. These documents are the knowledge sources for the EcoSense 360 RFP Response Agent that you create later in this task.

2.  Select the following link to download the RFP document that you plan to use when testing the new EcoSense 360 RFP Response Agent:
    - **VanArsdel_RFP.docx**

    Store this RFP file in your **OneDrive** folder. 

    > [!CAUTION]
    > Don’t store the **VanArsdel_RFP.docx** file in the **EcoSense360-RFP-Documents** folder. This folder is only for the knowledge source documents for the new agent.

3.  Open a new tab in your Microsoft Edge browser and then open Microsoft 365.

4.  In Microsoft 365, select **New agent** in the navigation pane. Doing so opens **Copilot Studio** and displays the **New agent** page. Select the **Configure new agent** button.

5.  On the **New Agent** page in Copilot Studio, the **Configure** tab is displayed by default. Copy and paste in the following features for this agent:
    - **Name:** EcoSense 360 RFP Response Agent
    - **Description:** The EcoSense 360 RFP Response Agent should provide accurate, consistent answers to individual questions related to customer sales proposals. It should also generate a complete, customer-ready RFP response to customer RFPs for the EcoSense 360 energy management solution.
    - **Instructions:** This agent should provide answers to questions related to customer sales proposals. It should also be able to generate a complete, customer-ready response to customer RFPs for the EcoSense 360 energy management solution. RFP responses should be based on the template file titled: **EcoSense_360_RFP_Template.dotx**.

6.  In the **Knowledge** section, select the **Upload from device** icon that appears next to the **Enter a URL or name or drop files here** field. In the **File Explorer** window that appears, navigate to your **OneDrive** folder and select the **EcoSense360-RFP-Documents** folder. Select all of the files in this folder and then select the **Open** button.

7.  Scroll to the bottom of the **Knowledge** section and verify all the selected documents appear in the list of **Uploaded files**.

8.  In the **Suggested prompts** section, add the following prompts that ask questions about the EcoSense 360 energy management solution:

    - **Title:** Product overview and benefits
        - **Message:** Provide a product overview and list of benefits.

    - **Title:** Competitor differentiation
        - **Message:** Provide a one-page summary of differentiators compared to competitors.

    - **Title:** Product integration
        - **Message:** Explain how the product integrates with existing hotel management systems.

    - **Title:** Product integration
        - **Message:** How does the EcoSense 360 integrate with HVAC and lighting systems?

    - **Title:** Pricing
        - **Message:** What pricing options are available for large resort chains?

    - **Title:** Energy savings and ROI
        - **Message:** Draft an executive summary highlighting energy savings and ROI for hotels.

9.  Add any other suggested prompts if you wish.

10.  Test several of the suggested prompts. Verify the agent is correctly pulling in data from the knowledge source documents.

11.  You now want to add a suggested prompt to generate an RFP response. We held off on having you enter this suggested prompt because the Test pane in Copilot Studio currently doesn’t let you attach files to the prompt. To avoid any confusion when testing the prompts that ask questions, we felt it was best to add this final prompt at the end. Add the following suggested prompt:

        - **Title:** Generate an RFP response
            - **Message:** Create an RFP response for the attached RFP. Format the result into a Word document based on the EcoSense_360_RFP_Template. Provide a link to download the document.

12.  Select the **Create** button to create the agent. 

13.  Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

        > [!NOTE]
        > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

14.  In the **EcoSense 360 RFP Response Agent** window, select the **Generate an RFP response** suggested prompt (**Create an RFP response for the attached RFP**). Attach the **VanArsdel_RFP.docx** file from your OneDrive account and then submit the prompt.

15.  Review the results. One of two results should occur:

        - During our testing, Copilot indicated that it couldn’t generate a downloadable Word document. If you experience this same situation, then select the **Copy** option at the end of the results to copy the RFP response to your clipboard. Then open **Word**, paste in the copied text, delete any extraneous verbiage that might appear at the start and end of the results, and then save the file to your OneDrive as **VanArsdel-RFP-Proposal.docx**. Leave the file open.

        - Since Microsoft 365 Copilot is still a work in progress, it might provide a downloadable Word document for you by the time you perform this exercise. If Copilot generates the document, select the link to download it, and then open the downloaded Word document.

        > [!IMPORTANT]
        > Before you create the Word document or download the generated document (if Copilot’s able to generate one), review the suggested prompts at the end of the results. Feel free to submit any of these prompts if you want the agent to update the results. For example, it may ask whether you want to include a cover page and table of contents. Or, it may ask if you want it to make additional updates, such as expanding the compliance matrix with more requirements. Now is your opportunity to have the agent customize the RFP response with any extra features. Once you’re satisfied with the final version, then copy and paste it into a Word document, or have the agent provide an updated link to the revised document (if it’s able to do so).

16.  Review the RFP response in the Word document. Remember, the agent used the predefined template file titled **EcoSense_360_RFP_Template.dotx** as the basis for its response. If it didn’t fill out any of the fields in the template, then you must manually update them yourself (or remove or replace them). At this point, you can still use the agent to help you. Submit a prompt to the agent that contains your query and then copy and paste the result into the RFP response file where appropriate.

17.  Leave the **VanArsdel-RFP-Proposal.docx** open as it’s used in the final task in this exercise. 

### Update the agent’s instructions (optional)

Now that you created a working agent using a minimal instruction set, let’s refine its Instructions if time permits. 

While short, vague instructions are common in real-world scenarios, they often leave too much room for interpretation, which can limit the quality, consistency, and usefulness of an agent’s responses. By expanding the Instructions with clearer goals, context, tone, and constraints, you give the agent stronger guidance on _**how**_ it should think and respond.

In the remaining steps in this task, you update the agent’s Instructions using a more detailed version generated with Copilot Chat and then rerun the same suggested prompts as before. Comparing the before-and-after responses helps you see firsthand how well-crafted instructions can dramatically improve an agent’s performance without changing any tools, data sources, or prompts—just the guidance it’s given.

18.  You’re now going to submit a prompt in Copilot Chat that asks it to create a detailed instruction set for your agent. When asking Copilot to generate agent instructions, include the following information in your prompt:
        - What’s the agent’s primary job
        - Who the answers are for
        - What kinds of questions it should and shouldn't answer
        - Which documents it can trust
        - Any rules or constraints it must follow
        - Ask Copilot to return the instructions in a code block for easier copy and pasting.
    
        Switch to a new tab in your Microsoft Edge browser, open Microsoft 365, and then draft a prompt that asks Copilot to create an instruction set for your new agent. The instructions should contain the information outlined above. **Do NOT submit the prompt just yet.**

19.  Once you finish drafting your prompt, compare it to the following sample prompt, which provides a good template to follow when requesting Copilot to draft a prompt for you. If your prompt includes all the key points found in the sample prompt, then feel free to submit it. Or, copy and paste this sample prompt if you wish:

        > [!NOTE]
        > Most everyday users won’t write prompts this detailed—and that’s okay. The goal of this exercise is to show what great looks like, so you can see how specific, well-structured instructions can transform an agent’s output. Even if your own prompt is shorter or less formal, thinking through the same categories (purpose, audience, tone, constraints) can help you build stronger agents over time.
    
        **I’m creating a Copilot agent called “EcoSense 360 RFP Response Agent.” The agent has two main responsibilities: first, to provide accurate, consistent answers to individual questions, and second, to generate a complete, customer-ready RFP response document using a Word template (.dotx). The RFP response document should address all the questions in a submitted RFP document.**
    
        **Responses must follow the RFP’s formatting rules, include tables for compliance and pricing, and maintain a professional, customer-focused tone**.
    
        **For knowledge sources, the agent should use all available documents stored in the EcoSense360-RFP-Documents folder. You should use the EcoSense_360_RFP_Template.dotx template as the basis for creating an RFP response. This template is also stored in the EcoSense360-RFP-Documents folder.**
        
        **Cite sources for every answer. Flag missing information. Ensure responses are formatted for clarity with short labels and bullet points where appropriate. Never invent figures or use sources beyond the provided files. Keep all answers within the Fabrikam business context.**
        
        **Please generate a code block containing a detailed, production-ready set of instructions that I can paste directly into the agent’s Instructions field. Along with the information that I’ve provided, apply your best judgment when you create the agent’s instructions. Elaborate on the information that I provided and propose sensible defaults, workflows, and constraints aligned with the agent’s goals and the business context. Make the instructions as thorough and comprehensive as possible.**

20.  Review the detailed instruction set that Copilot Chat generated. The level of detail in this instruction set should be much more thorough and comprehensive than the original instruction you provided. At the top of the code block, select the **Copy code** icon to copy the code to your clipboard.

21.  In the Microsoft 365 navigation pane, select **All agents**. In the **Agents Store** window, if the **EcoSense 360 RFP Response Agent** appears in the list of **Your agents**, then proceed to the next step. However, if the agent doesn’t appear, then select **See more** to see the expanded list of agents. The **EcoSense 360 RFP Response Agent** should appear in the list.

22.  Hover over the **EcoSense 360 RFP Response Agent** and select the ellipsis icon that appears, and then select **Edit** in the menu to open the agent in Copilot Studio.

23.  In **Copilot Studio**, highlight the existing text in the **Instructions** field and then paste in **(Ctrl+V)** the instructions that Copilot Chat created and you copied to the clipboard. Select the **Update** button.

24.  In the **Your agent was updated successfully** window, select the **Go to agent** option.

25.  In the **EcoSense 360 RFP Response Agent**, select the same suggested prompts that you tested originally. Do you notice a difference in the agent’s responses given the new instruction set?

26.  Select the suggested prompt to generate an RFP response. As before, attach the **VanArsdel_RFP.docx** file from your OneDrive account and then submit the prompt.

27.  Review the results. Did the RFP results change as a result of the more detailed, comprehensive instructions?

This exercise showed how a clear, detailed instruction set can dramatically improve an agent’s performance—without changing its data or prompts. As you create your own agents, make it a best practice to use Copilot Chat to generate and refine their instruction sets. You not only save time but also ensure each agent you build is accurate, consistent, and aligned with its intended purpose.





