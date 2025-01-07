<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- PHP Manager
- MySQL

<h2>Operating Systems Used </h2>

- Windows 10 Pro </b> (22H2) - x64
- Linux Ubuntu 24.04 - x64

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

1. Ticket Intake

This is the process of receiving and logging a ticket.

    Submission:
        Tickets can be submitted through multiple channels:
            Email: A user sends an email to a configured support email address, and osTicket automatically converts it into a ticket.
            Web Portal: Users log in to the osTicket portal and fill out a ticket submission form.
            Phone Call: Agents manually create tickets based on customer calls.

    Categorization and Routing:
        Tickets are categorized based on department, priority, or issue type.
        Auto-routing assigns tickets to the correct department or agent based on predefined filters or criteria (e.g., keywords, customer type).

    Acknowledgment:
        osTicket sends an automatic acknowledgment email to the user, confirming receipt of the ticket.

2. Ticket Assignment

Once the ticket is logged, it is assigned to an agent or team.

    Automatic Assignment:
        Using round-robin rules or priority-based assignment, osTicket assigns tickets to available agents.
        Tickets may also be automatically escalated based on Service Level Agreements (SLAs).

    Manual Assignment:
        If automation isn't configured or applicable, a manager assigns the ticket manually to a suitable agent.

3. Ticket Triage

During triage, the assigned agent reviews the ticket details.

    Verification:
        The agent ensures that the ticket contains all necessary information.
        If additional information is needed, the agent contacts the user for clarification.

    Classification:
        The agent classifies the ticket further (e.g., hardware issue, software bug).
        Priority may be reassessed and updated (e.g., urgent, low).

    Tagging:
        Tags are applied to make the ticket easier to search and track.

4. Ticket Investigation

The agent begins working on the resolution.

    Diagnosis:
        The agent investigates the issue by replicating the problem, reviewing logs, or consulting internal knowledge bases.

    Collaboration:
        If needed, the agent consults other teams or escalates the ticket to a higher-level team.

    Communication:
        Updates are shared with the user, keeping them informed about the progress.

5. Ticket Resolution

After identifying a solution, the agent resolves the issue.

    Implementation:
        The agent applies the fix, provides instructions, or arranges for external support if necessary.

    Testing:
        The solution is tested to ensure the issue is resolved.

    User Confirmation:
        The user is contacted to confirm that the solution is satisfactory.

6. Ticket Closure

The ticket is officially closed once resolved.

    Resolution Documentation:
        The agent documents the resolution process, steps taken, and outcomes.
        This information is added to the knowledge base if it may help resolve similar future issues.

    Feedback:
        The user may be asked to provide feedback or rate the support provided.

    Closure Notification:
        A closure email is sent to the user, summarizing the ticket and resolution.

7. Post-Closure Actions

Some activities occur after the ticket is closed.

    Reporting and Analytics:
        Tickets are analyzed for performance metrics (e.g., time-to-resolution, SLA compliance).
        Data is used to improve processes and identify common issues.

    Knowledge Base Update:
        Unique or complex solutions are added to the knowledge base for future reference.
