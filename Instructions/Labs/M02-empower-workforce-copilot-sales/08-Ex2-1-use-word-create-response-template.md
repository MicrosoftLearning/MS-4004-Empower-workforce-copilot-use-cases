---
lab:
  title: 'Exercise 2, Task 1: Use Copilot in Word to generate a standard RFP response template'
  description: To create this template, you plan to define its purpose, specify required sections (such as company overview, technical specifications, integration options, sustainability highlights, and pricing), and format it for easy customization. Once the template is ready, you plan to use it as a knowledge source when building and testing your EcoSense 360 RFP Response Agent in Copilot Studio.
  duration: 30 minutes
  level: 100
  islab: true
---

# Exercise 2, Task 1: Use Copilot in Word to generate a standard RFP response template
---
Before you begin building the EcoSense 360 Request for Proposal (RFP) Response Agent, it's essential to have a standard RFP response template in place. This template can serve as the foundation for both manual responses and for the agent's automated answers, ensuring consistency and professionalism across all submissions.

Your goal in this task is to use Copilot in Word to generate a customizable RFP response template for EcoSense 360, targeted at hotels and resorts. By creating the template first, you provide the agent with a structured document it can reference when responding to client inquiries. This approach allows you to test the agent's capabilities using realistic, branded content and ensures that every automated response aligns with Fabrikam's standards.

To create this template, you plan to define its purpose, specify required sections (such as company overview, technical specifications, integration options, sustainability highlights, and pricing), and format it for easy customization. Once the template is ready, you plan to use it as a knowledge source when building and testing your EcoSense 360 RFP Response Agent in Copilot Studio.

#### Using Copilot in Word

Copilot in Word can work in either **Edit with Copilot** mode or **Chat only** mode. Understanding this distinction is important, because it affects whether Copilot can automatically apply changes to your document or just provide suggestions for you to use.

When **Edit with Copilot** is selected, Copilot acts as an in-document author and editor. You can ask Copilot to create a document from scratch, rewrite sections, add summaries, or refine language—and it can apply those changes directly to the document, typically with your confirmation. In this experience, Copilot behaves like a collaborative writing partner that can both generate and revise content without requiring manual copy and paste. This is commonly the experience when prompting Copilot from within a Word document, such as using the drafting prompt above a blank document or the prompt field in the Copilot pane.

When **Chat only** is selected, Copilot responds in the Copilot pane without changing the document. It can still research topics, summarize information, and draft text, but it does not modify the document directly. Instead, responses remain in the Copilot pane, where you can review them and decide what, if anything, should be added to the document. This approach is useful when you want Copilot to act as a research assistant or idea generator while maintaining full control over the content that gets inserted into your document.

This task uses the **Edit with Copilot** functionality.

1. Create a folder titled **EcoSense360-RFP-Documents** in your OneDrive. When you finish creating the RFP template at the end of this task, you should copy it into this folder. You plan to use this folder to store all the supporting documents that you download in Task 3. These documents are going to provide the knowledge source content for the new EcoSense 360 RFP Response agent.

2. In your web browser, go to the [Microsoft 365 Copilot](https://m365.cloud.microsoft.com) home page, select the **App Launcher** (grid icon), select **More Apps**, and then select **Word** from the list of available apps.

3. In **Word for the web**, create a blank document.

4. In the bottom-right corner of the document, select the **Copilot** icon to open the Copilot pane. Verify the pane is in edit mode and the mode selector is set to **Allow editing** so Copilot can edit your document directly. If the pane is set to **Chat only**, select the mode drop-down, and then select **Allow editing**.

5. In the prompt field that appears in the Copilot pane, ask Copilot to create a standard RFP response template.

   > **Note:**
   > For this first Copilot Chat prompt, we've provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate._

   **Fabrikam's sales team frequently responds to RFPs from hospitality clients seeking smart energy management solutions. Consistency and completeness are critical for successful submissions. Reference the product's technical specifications, integration capabilities, sustainability certifications, and pricing information. Ensure the template aligns with Fabrikam's branding and includes sections for company overview, product overview, technical specifications, integration options, energy savings, sustainability certifications, pricing, and contact information. Include clear headings for each section and placeholder text for client-specific details. The template should be easy to customize for different clients and ready for use by both the sales team and the EcoSense 360** **RFP Response Agent.**

6. Review the generated template. You notice that the template doesn't include a section for a Return on Investment (ROI) case study. Ask Copilot to add a section for a ROI case study.

7. Review the results. There's one final request that you have. You want the RFP response template to include a sample deployment timeline. Ask Copilot to add a sample deployment timeline section.

8. Review the results. At this point, you can make any final changes to the template that you want. For example:

    - For this exercise, remove any reference to the term "Template". While this is a template document, you don't want customers to see this term in the official response they receive from Fabrikam.

    - Review all placeholders to make sure they're clear. Update any that might cause confusion.

    - Make any other changes that you want, such as adjusting section headings or content.

    If you need Copilot's help at this point, request your changes in the Copilot pane.

9. Once you've finished making changes, save the document as **EcoSense_360_RFP_Template** in the **EcoSense360-RFP-Documents** folder you created in OneDrive at the start of this task. Doing so makes it available to the EcoSense 360 RFP Response agent that you created in Task 3.

> **Note:**
> Word for the web saves documents in the standard Word document format (.docx). If you have access to the Word desktop app, you can optionally save the document as a Word Template (.dotx).
