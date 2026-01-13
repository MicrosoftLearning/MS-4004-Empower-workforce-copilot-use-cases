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
For Legal professionals, precision, clarity, and compliance are non-negotiable. Whether drafting contracts, reviewing case materials, or advising on regulatory matters, the ability to work efficiently while maintaining legal accuracy is essential.

This module introduces Microsoft 365 Copilot as a transformative tool for Legal professionals. It can help streamline document creation, accelerate legal research, and manage large volumes of information across the Microsoft 365 suite.

In a field where time is critical and detail is everything, Copilot becomes an intelligent partner. It helps Legal teams reduce time spent on repetitive tasks, organize complex case data, and maintain a high standard of quality and compliance in every document. Whether you're reviewing contracts in Word, tracking case timelines in Excel, collaborating with internal teams in Teams, or preparing briefs in PowerPoint, Copilot can enhance your productivity and precision.

This module equips Legal professionals with the tools to use Copilot effectively in their day-to-day work. As a Legal expert, your ability to utilize Microsoft 365 Copilot is essential for:

- **Drafting legal documents**. Copilot can help you quickly generate or revise all sorts of legal documents, such as contracts, non-disclosure agreements (NDAs), and internal policies. For example, it can propose standard language, summarize long clauses, or adjust tone based on the audience.

- **Reviewing and analyzing content**. Copilot supports efficient legal review. For example, it can compare multiple versions of a contract, highlight key differences, and suggest areas that need further attention.

- **Managing legal workflows**. Copilot helps keep tasks and timelines organized. For example, it can track deadlines, generate action lists from meeting notes, and summarize case-related correspondence.

- **Enhancing research and compliance**. Copilot accelerates the process of finding relevant legal references or summarizing past decisions. For example, it can scan and extract key information from documents, emails, and internal files.

This training module is built around realistic, scenario‑driven exercises that reflect the responsibilities of modern Legal teams. These exercises mirror the daily work of Legal professionals—analyzing regulations, assessing risk, drafting guidance, and coordinating cross‑functional compliance efforts. Copilot strengthens these essential functions by accelerating research, improving clarity, and ensuring that legal information is consistent, defensible, and ready for action.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.
