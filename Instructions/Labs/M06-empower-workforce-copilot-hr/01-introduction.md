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
Human Resources (HR) departments are at the heart of every organization, responsible for supporting employees, managing policies, and driving engagement. As the workplace evolves, HR teams face increasing demands for efficiency, responsiveness, and data-driven decision-making. Microsoft 365 Copilot offers a powerful solution—utilizing artificial intelligence to streamline HR tasks, enhance employee experiences, and unlock new strategic capabilities.

Copilot can help HR departments in numerous ways, including:

- **Automating routine tasks**. Copilot can handle repetitive HR inquiries, such as questions about benefits, leave policies, promotions, and relocation. By integrating Copilot with your organization’s HR documents and systems, employees receive instant, accurate answers—reducing the workload on HR staff and improving service quality.

- **Enhancing data-driven insights**. HR professionals can use Copilot to analyze workforce data, identify trends in engagement and attrition, and generate actionable reports. Copilot in Excel, for example, can summarize manager performance metrics, visualize team health, and uncover patterns that inform coaching and development strategies.

- **Supporting strategic communication**. Copilot assists HR teams in drafting clear, professional communications—whether it’s summarizing survey results, preparing feedback for managers, or composing policy updates. Copilot ensures consistency and saves valuable time by automating the creation of emails and reports. 

- **Empowering employee self-service**. Custom Copilot agents enable employees to access HR information on their own, from policy details to relocation support. This self-service approach fosters transparency, empowers employees, and allows HR teams to focus on higher-value work.

- **Connecting internal and external knowledge**. Copilot can synthesize information from both company data and web sources. For example, employees relocating to a new city can use Copilot to research local schools, housing, and amenities—combining internal policies with external insights for holistic support.

This training module guides you through the following practical exercises that demonstrate Copilot’s effect on HR operations:

- **Delivering manager insights**. Learn how Copilot in Excel helps HR analyze manager performance, identify strengths and opportunities, and communicate findings to leadership.

- **Building an HR self-service agent**. Discover how to create custom Copilot agents that answer employee questions, streamline policy access, and support real-world scenarios like relocation and promotions.

By the end of this module, you should clearly see how Copilot can transform HR workflows, improve employee experiences, and enable your team to operate more strategically.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.
