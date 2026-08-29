# AI Automation Portfolio

This repository documents my hands-on learning journey in AI automation, 
built while completing the "AI Agent Mastery" course. Each project below 
represents a real automation workflow solving a practical business problem, 
built using no-code tools like Zapier and n8n.

---

## Project 1: Automated Customer Confirmation Email

**Problem:**
When a potential customer fills out a contact/inquiry form, they often 
receive no immediate confirmation that their submission was received. 
This creates uncertainty and a poor first impression, and manually 
replying to every submission wastes time.

**Solution:**
Built an automated workflow that triggers instantly when someone submits 
a Google Form. The system automatically sends a personalized thank-you 
email back to the respondent, confirming their message was received and 
setting expectations for a follow-up.

**How it works:**
1. Trigger: New response submitted on Google Form
2. Action: Zapier extracts the submitted data (Name, Email, Message)
3. Action: Zapier sends a personalized auto-reply email via Gmail, 
   dynamically inserting the respondent's name and their original 
   message into the email body

**Tools used:** Zapier, Google Forms, Gmail

**Business value:** Improves customer experience by providing instant 
acknowledgment, reduces manual follow-up work, and ensures no inquiry 
goes unanswered.

**Form link (demo):** [View Form](https://docs.google.com/forms/d/e/1FAIpQLSfYTpq9EOtSCJlDZurBO3jTgv1YHBN0FLp0z78YgywAg-34tQ/viewform)

---

## Project 2: Internal Team Notification on New Form Submission

**Problem:**
When a business receives inquiries through a form, the team often finds 
out late (only when someone manually checks the form responses), delaying 
response time and risking lost leads.

**Solution:**
Built an automated workflow that instantly notifies the internal team via 
email whenever a new form submission comes in, including all relevant 
submission details, so the team can act quickly without manually checking 
the form.

**How it works:**
1. Trigger: New response submitted on Google Form
2. Action: Zapier extracts submission details (Name, Email, Phone, City, 
   Submission Time)
3. Action: Zapier sends a formatted internal notification email to a 
   fixed team address with all details included

**Tools used:** Zapier, Google Forms, Gmail

**Business value:** Ensures the team is notified in real time, reducing 
response delay and preventing missed leads.

**Debugging note:** Initially, the "To" field was mistakenly set to the 
respondent's dynamic email instead of a fixed internal address — meaning 
the notification was going back to the customer instead of the team. 
Fixed by replacing the dynamic variable with a static team email address, 
confirmed working via test submission.

**Form link (demo):** [View Form](https://docs.google.com/forms/d/e/1FAIpQLSeH-YnbfF9dxtzqKCsvY2XvTP7sNg-n6B7nfZqFEh_iunRehA/viewform)

---

## About Me
Learning AI automation (n8n, Zapier, LangChain, Langflow) with a focus 
on building practical, income-generating automation solutions for 
businesses. This repository will grow as I complete more projects 
throughout the course.

**Contact:** noman.agentic@gmail.com
