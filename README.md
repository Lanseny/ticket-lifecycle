<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Step 1: Ticket Creation

**Scenario:** A user encounters an issue with their email and needs assistance.

1. **User Submission:**
   - The user visits the support portal and clicks on **Open a New Ticket**.
   - The user fills out the ticket form, including details such as the subject ("Email Issue"), description ("Unable to send emails"), and selects the appropriate help topic ("Email Support").
   - The user submits the ticket.

2. **Email Submission:**
   - Alternatively, the user sends an email to the support address (e.g., support@example.com).
   - osTicket fetches the email and automatically creates a ticket with the email content.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 Step 2: Ticket Assignment and Initial Response

1. **Ticket Assignment:**
   - The newly created ticket appears in the support team's queue.
   - An agent or the system auto-assigns the ticket to the appropriate department based on the help topic.

2. **Initial Response:**
   - The assigned agent reviews the ticket.
   - The agent sends an initial response to the user, acknowledging receipt of the ticket and providing an estimated resolution time.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Step 3: Ticket Categorization and Prioritization

1. **Categorization:**
   - The agent categorizes the ticket based on the issue type (e.g., software, hardware, network).
   - The ticket is tagged for easier tracking and reporting.

2. **Prioritization:**
   - The agent sets the ticket priority (e.g., Low, Medium, High) based on the issue's impact on the user or business operations.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
  Step 4: Ticket Investigation and Updates

1. **Investigation:**
   - The agent investigates the issue by reviewing the user's description and any attached files.
   - If necessary, the agent contacts the user for additional information or clarification.

2. **Updates:**
   - The agent updates the ticket with their findings and any progress made.
   - The user receives notifications for each update, keeping them informed about the status.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  Step 5: Ticket Resolution and Closure

1. **Resolution:**
   - The agent identifies the solution and implements it (e.g., fixes the email configuration issue).
   - The agent updates the ticket with the resolution details and changes the ticket status to "Resolved."

2. **User Confirmation:**
   - The user is notified of the resolution and asked to confirm if the issue is resolved.
   - If the user confirms, the agent closes the ticket. If the issue persists, the user can reopen the ticket, and the agent will continue to work on it.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### Step 6: Post-Resolution Activities

1. **Ticket Closure:**
   - Once the user confirms the issue is resolved, the agent closes the ticket.
   - The ticket status changes to "Closed," and the ticket is archived.

2. **Feedback and Survey:**
   - Optionally, a satisfaction survey is sent to the user to gather feedback on the support experience.
   - The feedback is reviewed for continuous improvement.



**Example Scenario: User Unable to Access Email**

1. **Ticket Creation:**
   - User submits a ticket via the support portal with the subject "Unable to Access Email" and describes the issue.

2. **Ticket Assignment and Initial Response:**
   - Ticket is assigned to the IT Support department.
   - The agent sends an initial response: "We have received your ticket and are looking into the issue."

3. **Ticket Categorization and Prioritization:**
   - Ticket is categorized under "Email Issues."
   - Priority is set to "High" due to its impact on the user’s workflow.

4. **Ticket Investigation and Updates:**
   - The agent investigates and finds the user's email account locked due to multiple failed login attempts.
   - The agent updates the ticket: "Identified the issue. Unlocking the account."

5. **Ticket Resolution and Closure:**
   - The agent unlocks the user’s email account and updates the ticket with resolution details.
   - The user confirms the issue is resolved. The agent closes the ticket.

6. **Post-Resolution Activities:**
   - A satisfaction survey is sent to the user.
   - The feedback is reviewed, and positive feedback is noted.

 Conclusion:

Understanding the ticket lifecycle in osTicket helps streamline support processes, ensuring efficient issue resolution and user satisfaction. By following these steps, support teams can effectively manage tickets from creation to closure.
