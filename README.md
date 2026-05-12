# Email-Filtration-Workflow
This workflow automatically checks incoming Gmail emails and stores important filtered emails into Google Sheets for tracking and management.
Gmail Trigger
This node watches your Gmail inbox in real-time.
Whenever a new email arrives, the workflow starts automatically.
If Node
This node checks conditions to decide whether the email is important or matches your filter rules.
It separates emails into “true” or “false” based on the logic you created.
Append Row in Sheet
If the condition is true, this node sends the email data to Google Sheets.
It automatically adds a new row with details like sender, subject, or message info for record keeping
