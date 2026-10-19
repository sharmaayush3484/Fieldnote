
Fieldnote - Survey Operations Workspace

Fieldnote is a comprehensive, client-side operations management workspace tailored for market research and survey delivery portfolios. It enables research teams to track active pipelines, handle complex multi-stage delivery handoffs, manage team capacities, and keep financial metrics seamlessly aligned in one unified interface.

 Key Features

• Project Log & Pipeline: Centralized dashboard to capture new work, track study details (sample size n, markets), project ownership (Project Managers and Supervisors), and real-time delivery progress.
• 5-Stage Survey Workflow: Standardized, operational task tracking across the five critical pillars of survey execution:
	1. Scripting 📝
	2. Fieldwork 📊
	3. Overlay ⚙️
	4. Tabulation 📑
	5. OE (Open-Ended) Coding 💻
• Capacity & Team Hours: Robust resource allocation engine monitoring hours allocated versus actual hours used by separate internal teams (e.g., SP, DP, QA teams).
• Project Hub & Invoicing: Document management system supporting multiple asset types (SOWs, Cost Sheets, Questionnaires) alongside an automated invoicing engine tracking Draft, Sent, Paid, and Closed finances.
• Business Development: Integrated pipeline tracking for proposal deadlines, upcoming RFPs, and quote status reminders.
• Team Directory: Clear operational matrices indicating workspace responsibilities, active projects, and real-time step ownership statuses (Open, In Progress, Blocked, Done).

🛠️ System Architecture & Data Architecture

This application operates as a secure local-first browser application.
• Zero Server Dependency: There is no remote authentication server, backend API database, or active team synchronization.
• Data Persistence: Project records, file registries, and operational variables are stored locally within the user's browser storage context.
• Security Context: Uploaded project files remain exclusively on the local machine's device cache.
