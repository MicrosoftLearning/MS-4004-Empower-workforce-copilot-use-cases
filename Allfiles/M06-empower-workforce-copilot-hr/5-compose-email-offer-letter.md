# Compose an email offer letter using Copilot in Outlook
---
This exercise is the culmination of the previous HR exercises in which you used various copilots to help in the hiring process for a new position. You used Copilot in Word to create a job responsibility spec and analyze a set of resumes that candidates submitted. You then used Copilot in Loop to draft a list of interview questions for the position. And now you're using Copilot in Outlook to draft an email offer letter to the candidate you selected for the new position.

> [!IMPORTANT]
> Keep in mind that Copilot scenarios in Outlook are only available on a user’s primary mailbox. They aren't available on a user’s archive mailbox, group mailboxes, or shared and delegate mailboxes that the user has access to. Microsoft only supports Copilot for Outlook on mailboxes hosted on Exchange Online. Additionally, Copilot in Outlook is only supported in Microsoft 365 work or school accounts and Microsoft accounts with specific email domains. It's supported both through Copilot for Microsoft 365 with your Microsoft Entra ID account, and Copilot Pro with your MSA account. Any Microsoft account using an account from a third-party email provider can still use Outlook. However, it won’t have access to the Copilot features in Outlook.

Also remember from previous use cases that Copilot in Outlook can create multiple drafts of the same email. They can have a different tone and length, along with different content. You can then navigate through the various drafts by selecting the forward and backward arrows at the top of the Copilot window. Copilot tells you which draft you're on (for example, 2 of 5), so you can select the appropriate arrow to quickly return to a particular version.

As you review a generated draft, remember the following best practices that you learned in earlier training:

 -  Note the salutation at the start (Dear/Hello/Hi there, etc.) and the complementary close at the end (Sincerely/Best regards/Thank you, etc.). Are they in the proper tone for the target audience and the type of message that you want to send?
 -  Note the overall tone of the message. Is it too casual, too formal, or too direct for the type of email that you want?
 -  Note the length of the message. Is it too short, where it doesn't explain things in enough detail? Or does it continue on for too long, explaining items in too much detail? And is the length appropriate for the target audience?
 -  Does the message explain items in terms that are too simplistic or complicated given the target audience?

### Exercise

As the HR Manager for Graphic Design Institute, you completed the interview process and you selected your top candidate, Patti Fernandez. You're now ready to make Patti an offer for the position of Senior Animation Designer. To help with this process, you plan to use Copilot in Outlook to draft an email offer sheet.

You want the email to be formal and professional in tone, and it should include the job title, start date, salary, and benefits (which appear in a file you must download). The email should also mention the offer is contingent upon the successful completion of a background check and any other pre-employment screenings that may be required. As an email offer letter, it must also include an attached copy of the offer letter for the candidate to sign and return.

1.  Select the following link to download the [Graphic Design Institute - Employee benefits](https://edxinteractivepage.blob.core.windows.net/ms-4004/Graphic%20Design%20Institute%20-%20Employee%20benefits.docx) document.
2.  After the file finishes downloading, move it to your OneDrive account, and then open and close the file to get it in your Most Recently Used (MRU) file list.
3.  If you have a Microsoft 365 tab open in your Microsoft Edge browser, then select it now; otherwise, open a new tab and enter the following URL: **https://www.office.com**
4.  In **Microsoft 365**, open **Outlook**.
5.  Open a **New** email.
6.  On the **Message** tab that opens, select **Copilot** in the ribbon. In the drop-down menu that appears, select **Draft with Copilot**.
7.  In the body of the message, a **Draft with Copilot** window appears. Below the **What do you want this email to say?** message is a **Generation options** icon. Select this icon to see the options that Copilot provides when creating an email.
8.  In the drop-down menu that appears, you see that you can change the Tone and Length of the email. You decide to start out by setting the **Tone** to **Formal** and the **Length** to **Long**. Select these settings (if necessary).
9.  Enter the following prompt in the **What do you want this email to say?** field. When you do so, change \[enter date\] in the following prompt with the date you want. Select **Generate** to submit the request.
    
    **I'm the HR Manager for the Graphic Design Institute. Please create an email offer letter to Patti Fernandez that offers her the position of Senior Animation Designer. Patti's planned start date is \[enter date\]. The starting salary is $67,022. Add a note that if Patti accepts the offer, she must sign and return the attached pdf copy of this offer**.
10. Review the first draft that Copilot creates. Note the salutation and complementary close, and the overall tone of the message. If you want to see how these features change when you change the tone and length of the email, then select the linked prompt at the top of the window ("**I'm the HR Manager for the Graph...**") to return to the **Rewrite with Copilot** window. Select the **Generation options** icon and change the **Tone** to **Casual** and the **Length** to Medium. Select **Generate**.
11. At this point, you're not sure whether you prefer the **Formal** or **Casual** tone. If you can't remember how the two messages appeared, make note of the **Casual** salutation and complementary close, and the quality of the message. Then select the back arrow until you return to the second Copilot draft that contained the employee benefits, which had the **Formal** tone. It's up to you whether you want to use **Casual** draft the **Formal**. Just make sure the current draft that you're looking at is the one you want.
12. In looking more closely at your selected draft, you noticed that you forgot to have Copilot mention some of the specific employee benefits at Graphic Design Institute. You want Copilot to review the **Graphic Design Institute - Employee benefits** file and provide a detailed summary of the employee benefits. Attaching a file referenced in a Copilot prompt uses the same attachment process as attaching a file to an email. Select the **Attach file** option in the Outlook ribbon. Locate the file on your OneDrive and attach it to the email.
    
    > [!WARNING]
    > If you attach a file that's referenced in a Copilot in Outlook prompt that you don’t want attached to the final email, then don’t forget to remove the file once you finish with the Copilot draft process. For this email, Graphic Design Institute wants to leave the file attached to the email, so don't remove it.
13. Now enter the following request in the **Anything you'd like to change?** field to have Copilot extract the benefit information from the attached file, and then select the **Send** arrow at the end of the prompt field:
    
    **This first draft looks good. However, I forgot to ask you to review the attached document and add some specific employee benefits in the email. Also include a note saying that Patti should review the attached document for more information on the full complement of benefits provided by Graphic Design Institute**.
    
    > [!WARNING]
    > Don't select the **Regenerate** button. Doing so won't update the current draft based on your request in the prompt. Instead, if you select **Regenerate**, it generates an entirely new message based ONLY on this prompt - which isn’t what you want. Therefore, make sure that when you ask for a change to a draft, you must select the **Send** arrow at the end of the prompt field.
14. What just happened when you tried to update the email draft based on this latest prompt? Chances are you received an error message indicating "**Sorry, something went wrong. Copilot is working on it**."The reason you received this error is that when you submit a change request to a draft, Copilot currently accepts only one change at a time per prompt. In this case, you asked for two changes - add some specific employee benefits and add a note about reviewing the attached document. Here's the current rule of thumb involving prompts when working in Copilot for Outlook:
     -  When you submit your initial prompt, you can include multiple requests. For example, you could tell Copilot to include information about A, B, and C. In that case, it would generate a draft with all three items.
     -  However, any subsequent prompts to amend a draft AFTER that initial prompt can only include one change request per prompt.
15. Given this requirement, you decide to break your previous request into two parts. This time, enter the following prompt, which is part one:
    
    **This first draft looks good. However, I forgot to ask you to review the attached document and add some specific employee benefits in the email**.
16. If Copilot mentioned anything on its own about reviewing the attached document for more information on employee benefits (which it sometimes did in testing), then proceed to the next step. Otherwise, enter the following prompt:
    
    **Add a note saying that Patti should review the attached document for more information on the full complement of benefits provided by Graphic Design Institute**.
17. Review these final changes. In doing so, you just noticed that the draft mentioned nothing about the offer being contingent upon the successful completion of a background check. Since the legal department at Graphic Design Institute wants a background check statement included in any offer letters, enter the following request in the **Anything you'd like to change?** field and then select the **Send** arrow at the end of the prompt field:
    
    **Add a note towards the end of the email that this offer is contingent upon the successful completion of a background check and any other pre-employment screenings that may be required**.
18. After reviewing this change, you're happy with this final draft, so select the **Keep it** button.<br>
19. Note how the message appears in the body of the email and the **Rewrite with Copilot** window disappears. Since you're no longer in Copilot draft mode, you can manually make any changes that you desire at this time. However, since you aren't sending this message, select the trash can (**Discard**) icon in the upper right corner of the email screen to delete the draft of this email.
