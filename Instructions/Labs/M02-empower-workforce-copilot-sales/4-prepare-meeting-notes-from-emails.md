
# Prepare your meeting notes from emails using Microsoft 365 Business Chat
---
In today's dynamic business landscape, effective communication is key to staying ahead. As Sales personnel navigate the vast ocean of information, Microsoft 365 Copilot emerges as a powerful tool they can use to streamline their communication experience. Within Teams, Copilot empowers you with a quick and efficient overview of key discussions, ensuring they stay informed without being overwhelmed.

When you think of Microsoft Teams, you typically think of Teams' chat. However, when you use Microsoft 365 Copilot, the Copilot experience in Teams can focus not only on your chat experience, but also on your email and meeting data from Outlook. It does so through two Copilot features that are available in Teams:

- **Microsoft 365 Copilot in Teams**. This Copilot feature accesses the specific chat thread that you opened. However, it doesn't access organizational data outside of Teams. When you open a chat thread, select the **Copilot** icon in the upper-right corner of your chat page to open the **Copilot** pane for that thread. Copilot in Teams helps you quickly get up-to-speed and synthesize key information across all your Teams chat threads. By default, Copilot retrieves information from the chat thread that is up to 30 days old when you open a chat thread in Teams. You can ask Copilot to search beyond that 30-day mark if necessary.
- **Microsoft 365 Copilot Chat in Teams**. This Copilot feature accesses both your Teams' Chat experiences AND your email and meetings from Outlook. It uses the Graph-grounded chat experience that's included in your Microsoft 365 Copilot license or pay-as-you-go (metered) billing plan to access your Teams and Outlook data. To use this feature, select the **Copilot** option that appears in the Teams navigation pane. Doing so opens the Microsoft 365 Copilot Chat page within Teams.

The focus of this exercise is on Copilot Chat in Teams, which accesses your Teams and Outlook data. It's designed to streamline various aspects of your work in Microsoft Teams by working alongside users and providing suggestions and recommendations based on the context of their work. For example, it can help you:

- Quickly recap past communications (for example, "What's new from Emily?").
- Summarize long threads in a chat window into key points.
- Answer queries to help you stay updated (for example, "Who am I meeting with tomorrow?").

> [!NOTE]
>  This course doesn't include a Microsoft 365 lab tenant with fictitious data. Instead, you must complete this training exercise using your own personal data.

In this training exercise scenario, you plan to use Copilot Chat in Teams to summarize the emails, meetings, and chats regarding an actual topic in your work environment. This scenario is a common task for Sales professionals. When Copilot Chat synthesizes your data in this manner, it reaches across your Microsoft 365 tenant to gather this information.

### Exercise

Think of an actual project that you participated in over the past 30 days. Chances are, you received an almost endless number of emails, not to mention all the meetings and virtual discussions that you participated in. You're feeling a bit overwhelmed as you struggle to remember all the key points that were covered in all these different communication threads. If only there was an AI tool that could synthesize all your communication history and provide a concise recap of all activity for a given thread. And then it dawns on you.

You remember hearing about a Microsoft 365 Copilot feature that was added to Microsoft Teams. It can review all your communication activity across both Outlook and Teams, provide a summation of that activity, and determine the action items that you're responsible for. You decide to take advantage of this Copilot Chat in Teams feature to save you the time and effort needed to manually review all your communication activity.

Perform the following steps using Copilot Chat in Teams to synthesize your communications involving an actual thread you're involved in. At the same time, you plan to employ the prompting best practice of "iterate, iterate, iterate" by digging deeper into those items.

1. You should look through threads in BOTH your Outlook Inbox and your Teams Chat to find a topic or project name that appears in both your emails and chats. You should identify the name of this topic/project so that you can enter it in a Copilot prompt in an upcoming step.
1. In **Microsoft Teams**, select **Copilot** in the navigation pane on the left-side of the screen. Doing so opens the **Microsoft 365 Copilot Chat** window within Teams.
1. Verify the **Work/Web** toggle switch that appears at the top of the page is set to **Work**. The toggle determines whether Copilot uses internal organizational data (**Work**) or the broader internet (**Web**). Since you want to summarize emails, meetings, and chats—which are internal data—then the toggle must be set to **Work**. If it's accidentally set to **Web**, Copilot won’t access your Outlook, Teams, or organizational data, which can lead to confusing or irrelevant results, or a response saying it can’t access that data.
1. In the **Copilot Chat** window, enter the following text in the prompt at the bottom of the page. Replace "topic/project of your choice" with the name that you chose from the first step, and then select the **Send** icon. **Summarize all my emails, meetings, and chats over the past 30 days related to {topic/project of your choice}**.
1. After Copilot responds with a summary of each communication, note the prompts that appear above the main prompt field at the bottom of the page. Copilot generated these prompts based on the summarized list of data that it returned. For example, you may see prompts such as:
   - "List any action items for me"
   - "Provide more details on the meeting with {person's name}"
   - "Summarize the key decisions from these communications"
   - "Draft an email to the team about the project participation"
1. Select one of these prompts to see how Copilot Chat in Teams responds. When you review the response, note how the Copilot-generated prompts change based on the prompt that you selected.
1. Note the iterative nature of this design. As you continue submitting Copilot-generated prompts, each response includes a new set of prompts associated with the data that Copilot returned. This design enables you to continue digging deeper into the communication history of the project, while also requesting that Copilot perform specific tasks in follow-up. For example, emailing a person or team, identifying deadlines, and so on.
1. You now want to know what action items you're responsible for from the list of emails, meetings, and chats that Copilot Chat gathered. Enter the following prompt and select the **Send** icon: **Based on the information that you synthesized from my emails, meetings, and chats, create a list of action items that I'm responsible for**.
1. Review the list of action items that Copilot identified. While this list is a good start, you feel that Copilot can make the information even more valuable by ranking the action items based on their order of importance. Enter the following prompt and select the **Send** icon: **Please rank these action items by order of importance**.
1. Review Copilot's response. While it tries to rank the items, "order of importance" can be a subjective filter that can vary depending on the specific context and priorities of the project. Copilot may be able to make this distinction based on the nature of your action items. Or it may be unable to determine which items are most important. If the latter occurs, you may need to follow the prompting best practice of:  **Iterate, iterate, iterate**. Instead of listing action items by order of importance, which Copilot might not be able to do based on your action items, instead focus on the action items that are related to a specific person, meeting, or topic that's of importance to you. In this case, enter the following prompt and replace {person/meeting/topic name of your choice} with the name of the person, meeting, or topic that you want to focus on first: **In all the action items that you found for me, which ones involve {person/meeting/topic name of your choice}?** And even if Copilot ranked your action items, you could still try this prompt to see how Copilot responds. 
1. You should review the list of action items that Copilot provides. If you wish, ask Copilot other questions, or direct it to complete any other task that may be of interest to you related to this project or topic.
