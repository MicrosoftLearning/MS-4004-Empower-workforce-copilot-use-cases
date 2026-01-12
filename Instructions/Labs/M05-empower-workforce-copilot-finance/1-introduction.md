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
By using Microsoft 365 Copilot, Finance professionals can save time and effort, streamline their work, and make informed decisions based on data insights. This module equips Finance professionals with the skills and knowledge necessary to use Microsoft 365 Copilot to streamline your workflow and enhance your productivity. 

As a Finance professional, your ability to effectively use Microsoft 365 Copilot is crucial for:

- **Automating financial tasks**. Copilot can help Finance professionals automate repetitive financial tasks. For example, it can help you with budgeting, forecasting, and even tax preparation.

- **Providing insights**. Copilot can help Finance professionals gain insights into their financial data. For example, it can help you analyze financial statements, identify trends, and even predict future outcomes.

- **Improving productivity**. Copilot can help Finance professionals save time by automating manual tasks. For example, it can help you with data entry, report generation, and even proofreading.

- **Collaboration**. Copilot can help Finance professionals collaborate more effectively. For example, it can help you with project management, team communication, and even document sharing.

In today’s dynamic business landscape, Finance professionals are expected to deliver rapid insights, manage risk, and drive strategic decisions—all while navigating complex data, contracts, and collaboration demands. Microsoft 365 Copilot is transforming the Finance function by embedding AI-powered assistance directly into the Office apps that Finance teams use every day. For example:

- **Copilot in Excel** enables analysts to automate data cleaning, uncover trends, and visualize financial metrics instantly. Instead of spending hours manipulating spreadsheets, Finance teams can ask Copilot to analyze cost drivers, model what-if scenarios, and generate management-ready summaries—freeing up time for deeper analysis and strategic recommendations.

- **Copilot in Word** streamlines the creation of reports, contract comparisons, and policy briefs. Finance professionals can quickly draft, revise, and summarize complex documents, ensuring clarity and consistency in communications with leadership and stakeholders.

- **Copilot in PowerPoint** accelerates the development of executive presentations. It can automatically generate slides from financial analysis or contract reviews, which helps Finance teams present key findings, risks, and recommendations with visual clarity. Content can be tailored for both operational and executive audiences.

- **Copilot in Outlook** makes collaboration seamless by drafting professional emails that solicit feedback, coordinate reviews, and embed collaborative Loop components. Finance teams can generate multiple email drafts, compare versions, and select the best approach for engaging colleagues.

- **Copilot in Teams and Loop** enhances teamwork by summarizing meeting notes, extracting action items, and turning insights into structured, actionable content. Finance professionals can use Copilot to facilitate real-time collaboration, track progress, and ensure alignment across departments.

Whether you’re analyzing financial data, managing contracts, or preparing executive briefings, Microsoft 365 Copilot acts as a digital partner—empowering Finance teams to work smarter, faster, and with greater confidence.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.
