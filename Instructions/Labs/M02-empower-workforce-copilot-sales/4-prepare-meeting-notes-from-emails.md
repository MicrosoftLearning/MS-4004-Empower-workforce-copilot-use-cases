
# Prepare your meeting notes from emails using Business Chat
---
In today's dynamic business landscape, effective communication is key to staying ahead. As Sales personnel navigate the vast ocean of information, Business Chat emerges as a powerful tool they can use to streamline their communication experience. Within Teams, Business Chat empowers you with a quick and efficient overview of key discussions, ensuring they stay informed without being overwhelmed.

When you think of Microsoft Teams, you typically think of Teams' chat. However, when you use Microsoft 365 Copilot, the Copilot experience in Teams can focus not only on your chat experience, but also on your email and meeting data from Outlook. It does so through two Copilot features that are available in Teams:

 -  **Microsoft 365 Copilot in Teams**. This Copilot feature accesses the specific chat thread that you have open. However, it doesn't access organizational data outside of Teams. When you open a chat thread, select the **Copilot** icon in the upper-right corner of your chat page to open the **Copilot** pane for that thread. Microsoft 365 Copilot in Teams helps you quickly get up-to-speed and synthesize key information across all your Teams chat threads. When you open a chat thread in Teams, Copilot retrieves information from the chat thread that is up to 30 days old.
 -  **Business Chat in Teams**. This Copilot feature accesses all your Teams' Chat experiences AND your email and meetings from Outlook. It uses Graph-grounded chat to access your Teams and Outlook data. To use this feature, select the Copilot option that appears at the top of the Chat pane. Doing so opens a Copilot page within Teams.

The focus of this exercise is on Business Chat within Teams, and specifically, the functionality that can access your Teams and Outlook data. It's designed to streamline various aspects of your work in Microsoft Teams by working alongside users and provide suggestions and recommendations based on the context of their work.

In this training exercise, you plan to use Business Chat to summarize the emails, meetings, and chats regarding an actual topic in your work environment. When Business Chat synthesizes your data in this manner, it reaches across your Microsoft 365 tenant to gather this information.

### Exercise

As a Sales executive for your organization, think of an actual project that you participated in over the past 30 days. You receive an almost endless number of emails, not to mention all the meetings and virtual discussions that you participate in. You're feeling a bit overwhelmed as you struggle to remember all the key points that were covered in all these different communication threads. If only there was an AI tool that could synthesize all your communication history and provide a concise recap of all activity for a given thread. And then it dawns on you.

You remember hearing about a new Business Chat feature that was added to Microsoft Teams. It can review all your communication activity across both Outlook and Teams, provide a summation of that activity, and determine the action items that you're responsible for. You decide to take advantage of this new Microsoft 365 Copilot feature to save you the time and effort needed to manually review all your communication activity.

Perform the following steps to Business Chat within Teams to synthesize your communications involving an actual thread you're involved in. At the same time, you plan to employ the prompting best practice of "iterate, iterate, iterate" by digging deeper into those items.

1.  You should look through threads in BOTH your Outlook Inbox and your Teams Chat to find a topic or project name that appears in both your emails and chats. You'll enter the name of this topic/project in the prompt that you enter into Microsoft 365 Copilot in the next step.
2.  In **Microsoft Teams**, select **Copilot** at the top of the Chat pane. Doing so opens a **Copilot** window.
3.  In the **Copilot** window, enter the following text in the prompt at the bottom of the page. Replace "topic/project of your choice" with the name that you chose from the first step, and then select the **Send** icon.
    
    **Summarize all my emails, meetings, and chats over the past 30 days related to \{topic/project of your choice\}**.
4.  Once Copilot summarizes this information, you should examine the options that appear above the prompt field that are related to the summarized list of emails, meetings, and chats. Select one of the options to see how Copilot responds.
5.  If more options appear above the prompt that are related to the option you previously selected, select one of those options now. As you progress through the following steps, pay particular attention to the predefined prompts that appear here and note how they change after each prompt. They may trigger a question or action that you hadn't previously thought of.
6.  You now want to know what action items you're responsible for from the list of emails, meetings, and chats that Copilot gathered. Enter the following prompt and select the **Send** icon:
    
    **Based on the information that you synthesized from my emails, meetings, and chats, create a list of action items that I'm responsible for**.
7.  You should review the list of items. While this list of action items is a good start, you feel that Copilot can make the information even more valuable by ranking the action items based on their order of importance. Enter the following prompt and select the **Send** icon:
    
    **Please rank these action items by order of importance**.
8.  You should review Copilot's response. While it tries to rank the items, "order of importance" can be a subjective filter that can vary depending on the specific context and priorities of the project. Now that you know how Copilot struggles with subjective requests such as "order of importance," that knowledge can help you in future prompts. How so? Knowing this Copilot limitation can prevent you from wasting time by asking it to complete tasks that it can't adequately resolve. In fact, when you utilize this knowledge in upcoming prompts, you’re implementing one of the effective prompting techniques you acquired during earlier training - **Understand Copilot's limitations**.
9.  Given these results, you decide to follow another prompting best practice - **Iterate, iterate, iterate**. Instead of listing action items by order of importance, which Copilot can't sufficiently do, you decide to focus on the action items that are related to a specific person, meeting, or topic that's of importance to you. Enter the following prompt and replace \{person/meeting/topic name of your choice\} with the name of the person, meeting, or topic that you want to focus on first:
    
    **In all of the action items that you found for me, which ones involve \{person/meeting/topic name of your choice\}**?
10. You should review the list of action items that Copilot provides. If you wish, ask Copilot any other questions or direct it to complete any other task that may be of interest to you related to this project or topic.
