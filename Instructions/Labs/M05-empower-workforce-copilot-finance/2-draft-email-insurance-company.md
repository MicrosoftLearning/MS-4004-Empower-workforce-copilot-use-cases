# Draft an email to your insurance company using Microsoft 365 Copilot in Outlook
---
Microsoft 365 Copilot in Outlook is an AI-powered tool that can help Finance professionals save time and effort when drafting custom emails and email replies. With Copilot, you can quickly generate email drafts that Copilot tailors to your specific needs, without having to spend hours writing and editing them. In this training, you use Microsoft 365 Copilot in Outlook to draft a new email based on a series of user-supplied prompts.

> **IMPORTANT:** Copilot scenarios in Outlook are only available on a user’s primary mailbox. They aren't available on a user’s archive mailbox, group mailboxes, or shared and delegate mailboxes that the user has access to. Microsoft only supports Copilot for Outlook on mailboxes hosted on Exchange Online. Additionally, Microsoft 365 Copilot in Outlook is only supported in Microsoft 365 work or school accounts and Microsoft accounts with specific email domains. It's supported both through Microsoft 365 Copilot with your Microsoft Entra ID account, and Copilot Pro with your MSA account. Any Microsoft account using an account from a third-party email provider can still use Outlook, but won’t have access to the Copilot features in Outlook.

### Exercise

As the CFO for Northwind Traders, you want to use Microsoft 365 Copilot in Outlook to draft an email to the company's health insurance carrier, Humongous Insurance. You were recently notified by your insurance agent that Northwind's health insurance premiums would be increasing across the board - more than 9% for individual policies and more than 15% for family policies. This rate of increase is considerably higher than industry averages.

The purpose of this email is twofold:

To express your concern over the level of increases.

To request a meeting with the insurance carrier’s team to discuss the matter and explore alternative options.

Perform the following steps to create this email:

1.  In **Microsoft 365**, open **Outlook**.
2.  Open a **New** email.
3.  On the **Message** tab that opens, select **Copilot** in the ribbon. In the drop-down menu that appears, select **Draft with Copilot**.
4.  In the body of the message, a **Draft with Copilot** window appears. The prompt field contains the message: **What do you want this email to say**? At the bottom of the field is a **Generation options** icon. Select this icon to see the options that Copilot provides when creating an email.
5.  In the drop-down menu that appears, you see that you can change the Tone and Length of the email. You decide to start out by setting the **Tone** to **Formal** and the **Length** to **Long**. Select these options now.
6.  Enter the following prompt in the **What do you want this email to say**? field and then select the **Generate** button:
    
    **I'm the CFO for Northwind Traders. Draft an email to our insurance carrier, Humongous Insurance, expressing my concern for the level of increases in our company's health insurance premiums for the coming year. Request a meeting with the insurance carrier’s team to discuss the proposed increases and explore alternative options.** 
7.  Scroll through the draft to review it. At the top of the message, Copilot displays the start of the prompt that you just entered (that is "**I'm the CFO for Northwind Traders...**"). Select this section of the prompt to see what happens.
8.  Copilot displays a **Rewrite with Copilot** window that allows you to edit the prior prompt and regenerate an entirely new message. At this point, you're happy with the message, but you want to see how it would change when using a different tone and length. Select the **Generation options** icon that appears below the prompt. Change the **Tone** to **Direct** and the **Length** to **Medium**, and then select the **Generate** button.
9.  Review the revised draft. At the top of the **Rewrite with Copilot** window, note the "**I'm the CFO for Northwind Traders...**" link. Also note how Microsoft 365 Copilot indicates this draft is "**2 of 2**", meaning you're looking at the second of two Copilot drafts. You can select the back arrow (&lt;) to go back to the previous Copilot draft, which in this case is the first draft that has a **Formal** tone and a **Long** length.
    
    If you generate multiple Copilot drafts, as you'll do in this exercise, you can use these arrows to go back and forth between drafts to find one that you like. If you find a draft that you want, you can select one of the available buttons to either **Keep it** or **Regenerate** a new draft with the same tone and length. Note the salutation and complementary close, the overall tone of the message for this Direct draft, and the change in Length. While you want to get straight to the point, you feel the **Direct** tone is far too impersonal, so you want to generate a new draft with a different tone.
10. Select the linked prompt at the top of the window ("**I'm the CFO for Northwind Traders...**") to return back to the **Rewrite with Copilot** window. Select the **Generation options** icon, and this time change the **Tone** to **Casual** and the **Length** back to **Long**. Select **Generate**.
11. Review the new draft. At this point, you realize that you don't like the **Direct** tone and the **Medium** length in draft number two. However, you're sure that you prefer the longer length, but you can't decide whether you prefer the **Formal** or **Casual** tone.
     -  Since the **Casual** draft is currently displayed, you note that the salutation is a bit informal, such as "Hi there" or just "Hello."
     -  You can't remember the exact salutation when you used the **Formal** tone, but it was something along the lines of "Dear so and so."
     -  You also can't remember the phrasing of the complementary close in the first draft that used the **Formal** tone (for example, Sincerely/Best regards/Thank you, etc.).
12. If you can't remember how the two messages appeared beyond the salutations, follow the previous instructions to select the back arrow to return to the first draft, which had a **Formal** tone. If you can't decide which draft you prefer, use the forward and backward arrows to compare the first draft (Formal) and the third draft (Casual). Proceed to the next step once you decide which draft you want to use.
13. At this point, your preferred draft should appear in the Copilot window. Beyond the changes to the tone and length that you previously made, it strikes you that the email message seems a bit sparse. You notice that it doesn't provide any detailed information about the rate increases, at least not broken down by individual and family plans. In the **Anything you'd like to change**? field, enter the following prompt and then select the arrow icon at the end of the field:
    
    > **IMPORTANT:** Do NOT select the **Regenerate** button. Doing so won't update the current draft based on the following prompt. Instead, it generates an entirely new message based ONLY on this prompt - which isn’t what you want.
    
    > **NOTE:** Please compare the level of premium increases being proposed for Northwind Traders in comparison to industry-wide premium increases. Our individual policy premiums increased over 9%, and family policies increased over 15%. Mention how our increases far exceed the industry averages of 6% and 10% increases, respectively.
14. What just happened when you tried to update the email based on this latest prompt? Chances are you received an error message indicating "**Sorry, something went wrong. Copilot is working on it**." The reason you received this error is that when you submit a change request to a draft, Copilot currently accepts only one change at a time per prompt. In this case, you asked for two changes - compare the plan increases to industry averages and specify the specific rate increases.
    
    Here's the current rule of thumb involving prompts when working in Copilot for Outlook:
    
    
     -  When you submit your initial prompt, you can include multiple requests. For example, you could tell Copilot to include information about A, B, and C. In that case, it would generate a draft with all three items.
     -  However, any subsequent prompts to amend a draft AFTER that initial prompt can only include one change request per prompt.
     
15. Given this requirement, you decide to break your previous request into two parts. This time, enter the following prompt, which is part one:
    
    **Please mention that our individual policy premiums increased by over 9%, and family policies increased over 15**%.
16. Review the updated draft. Now enter the following prompt regarding industry averages, which is part two:
    
    **Please mention that average industry premium increases are 6% for individual policies and 10% for family policies**.
17. This draft looks better. However, you decide to add one last note regarding a possible change to high deductible/low premium plans. Enter the following prompt:
    
    **Please mention that we should discuss converting to high-deductible, low premium policies**.
18. After reviewing this latest iteration, you're satisfied with the draft, so select the **Keep it** button.
19. Note how the message appears in the body of the email without the Copilot window. In a real-world scenario, you would either send the email as is, or make any final changes manually. Once you keep a Copilot draft, you must manually make any further changes yourself. You can't go back into Copilot draft mode with that message.
20. Since you won't send this email, select the trash can (**Discard**) icon in the upper right corner of the email screen and then confirm that you want to discard the message.
