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
In today’s competitive sales landscape, professionals are expected to identify new opportunities, respond rapidly to client needs, and deliver value at every interaction. Yet, the pressure to do more with less time is ever-present. Microsoft 365 Copilot is designed to be your AI-powered sales partner, helping Sales teams shift their focus from repetitive tasks to building relationships and driving results.

Copilot integrates seamlessly with the Microsoft 365 apps that Sales professionals use every day, such as Word, Outlook, Excel, and Teams. It also enables Sales professionals to create their own custom agents or use Copilot’s prebuilt agents. Incorporating Copilot into everyday sales workflows delivers several critical advantages:

- **Accelerated research**. Copilot Chat and Copilot agents can quickly analyze markets, competitors, and customer trends, turning scattered data into actionable insights. In turn, Sales teams can make informed decisions faster and with greater confidence.

- **Smarter sales content**. With Copilot in Word and PowerPoint, Sales professionals can instantly generate proposals, pitch decks, and return on investment (ROI) summaries tailored to each customer’s unique challenges, ensuring every communication is professional and impactful.

- **Personalized engagement**. In Outlook and Teams, Copilot helps craft persuasive, tailored emails and messages, maintaining a consistent, professional tone while addressing each buyer’s specific needs.

This module includes hands-on lab exercises that demonstrate Copilot’s value in real-world Sales scenarios. These exercises are designed to provide practical, hands-on experience with Copilot’s capabilities. By working through real-world scenarios, you see firsthand how Copilot:

- Reduces time spent on repetitive tasks.
- Improves the quality and consistency of sales materials.
- Enables Sales professionals to focus on high-value activities, like engaging clients and strategizing for growth.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.

