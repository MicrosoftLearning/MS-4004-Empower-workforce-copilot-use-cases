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

### Introduction
---
Modern IT departments face increasing demands to deliver projects faster, support innovation, and ensure successful technology adoption across their organizations. Microsoft 365 Copilot is transforming the way IT professionals work by providing intelligent, AI-powered assistance that streamlines complex tasks, enhances collaboration, and drives measurable outcomes.

In this module, you learn how Microsoft 365 Copilot can serve as a valuable tool for IT professionals, allowing them to navigate the intricacies of technology management with ease. By utilizing Copilot, IT professionals can save time and focus on critical aspects of their role. For example, Copilot can assist IT departments in enhancing system reliability, implementing innovative solutions, and proactively addressing IT challenges.

Throughout this module, you experience how Copilot provides the following key benefits for IT personnel:

- **Accelerated project planning and execution**. Copilot enables IT teams to quickly synthesize information from emails, chat logs, and documents, creating unified project frameworks that clarify goals, deliverables, milestones, and risks. Copilot can automate routine documentation and reporting, freeing IT professionals to focus on strategic decision-making and innovation.

- **Enhanced collaboration and communication**. Copilot integrates seamlessly with tools like Whiteboard, PowerPoint, and Viva Engage, facilitating brainstorming sessions, executive presentations, and engaging communications. IT teams can use Copilot to draft announcements, best-practice guides, and training materials that help end users understand and embrace new technologies.  

- **Streamlined technology adoption**. Copilot assists IT professionals in planning and executing feature rollout campaigns. With Copilot, IT can create clear, user-friendly resources and measure the effect of adoption initiatives, ensuring employees are confident and productive with new tools.  

- **Data-driven insights and continuous improvement**. Copilot’s Analyst and Surveys agents empower IT teams to gather feedback, visualize adoption trends, and generate actionable insights for leadership. By identifying blockers and opportunities, IT can continuously refine strategies to maximize technology value and user satisfaction.

Microsoft 365 Copilot is more than just an automation tool—it’s a digital partner that helps IT professionals work smarter, not harder. By integrating Copilot into daily workflows, IT teams can:

- Reduce manual effort and administrative overhead.
- Improve project transparency and governance.
- Deliver faster, more effective technology rollouts.
- Foster a culture of collaboration, learning, and innovation.

As you progress through this training, you experience firsthand how Copilot can transform IT operations, making your team more agile, efficient, and impactful.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”

Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.
