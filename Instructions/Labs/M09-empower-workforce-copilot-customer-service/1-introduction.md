# Lab Setup:

In this module, we'll create prompts for Microsoft 365 Copilot that reference files. First, let’s upload all required files to OneDrive to ensure they're accessible throughout the lab.


### Uploading Files to OneDrive

Follow the steps below to upload all files needed to **OneDrive**:

1. Log into the virtual machine provided by your tenant provider as the local **Administrator** account with the password `Pa55w.rd`.
2. In the Windows taskbar, select **Microsoft Edge**.
3. In the address bar, enter `https://www.office.com`.
4. Under **Welcome to Microsoft 365**, select **Sign in**.
5. At the **Sign-in prompt**, enter `userx@yourtenant.onmicrosoft.com` (username and tenant provided by your tenant provided) and select **Next**.
6. At the **Enter password** screen, enter the password (provided by tenant provider) for the User account, then select **Sign in**.
7. If prompted to **Stay signed in**, select **Don't show this again** and then **Yes**.
8. In **Microsoft 365**, select **Apps**.
9. Within **Apps**, select **OneDrive**.
10. In **OneDrive**, in the top-left corner, select **+** (add new) > **File upload**.
11. In **File Explorer**, select **This PC** > **Local Disk (C:)** and open the **ResourceFiles** folder.
12. Select all files within the **ResourceFiles** folder, then select **Open** to upload them to **OneDrive**.
13. When the upload is complete, you should see **Uploaded 29 items to My files** in the bottom center of the screen.
14. Leave **Edge** open and move on to the next task.

### Referencing Files in Copilot

When using Copilot, you may find that some files aren’t immediately available in the suggestions. This occurs because certain Copilot experiences only reference files from the **Most Recently Used (MRU)** list, while others let you browse **OneDrive** directly. To ensure a file appears in the **MRU** list, simply open it in the relevant Microsoft 365 app, and it will be added automatically.

> [!IMPORTANT]
> Microsoft 365 Copilot can only work with files saved to **OneDrive**. Files stored locally on your PC will need to be moved to **OneDrive** for Copilot to access them.

# Introduction
---
For Customer Service professionals, delivering prompt, empathetic, and effective support is the cornerstone of exceptional customer experiences. Whether resolving issues, answering inquiries, or managing service workflows, the ability to communicate clearly and act quickly is vital.

This module introduces you to the capabilities of Microsoft 365 Copilot and how Customer Service professionals can use it to streamline operations, personalize interactions, and improve service outcomes across the Microsoft 365 ecosystem. In the fast-paced world of customer support, Copilot becomes more than just a helpful assistant—it’s a strategic partner that empowers you to reduce response times, resolve issues more effectively, and ensure consistent, high-quality service. 

This module equips Customer Service professionals with practical tools and techniques to help you deliver outstanding support experiences. As a professional in Customer Service, your ability to effectively use Microsoft 365 Copilot is key to:

- **Improving response quality and speed**. Copilot can help you draft clear, professional replies to customer emails. For example, it can analyze previous interactions and suggest personalized responses that match the customer’s tone and history.

- **Streamlining ticket management**. Copilot supports efficient issue tracking and documentation. For example, it can help summarize cases, autofill forms, or generate follow-up actions based on customer interactions.

- **Creating and maintaining support content**. Copilot enables faster creation of internal and customer-facing documentation. For example, it can help in drafting FAQs, step-by-step guides, or product troubleshooting articles directly in Word or Loop.

- **Enhancing team collaboration**. Copilot keeps teams aligned and informed. For example, it can summarize chats and meetings in Teams, generate task lists, and track progress on escalated issues or service improvement plans.

Microsoft 365 Copilot acts as a smart, AI-powered assistant designed to help you stay proactive, organized, and responsive. This module enables you to harness the power of Copilot to elevate customer satisfaction, streamline operations, and become a more agile and empowered Customer Service professional.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.
