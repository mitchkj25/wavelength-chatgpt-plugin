---
name: send-to-tools
description: Send or attach a Wavelength flow to Jira, Confluence, Notion, Salesforce, ServiceNow, a HubSpot deal, Google Drive, or a chat channel or webhook. Use when the user wants a flow in another tool.
---

# Send a flow to another tool

1. Call list_connections to see which tools the user has connected in Wavelength. If the tool is not connected, tell the user to connect it in Wavelength Settings, then Integrations.
2. Find the flow with search_flows or list_flows.
3. Find the target:
   - Jira: find_jira_targets, then send_flow_to_jira.
   - Confluence: find_confluence_targets, then send_flow_to_confluence.
   - Notion: find_notion_pages, then send_flow_to_notion.
   - Salesforce: find_salesforce_records, then send_flow_to_salesforce.
   - ServiceNow: find_servicenow_records, then send_flow_to_servicenow.
   - HubSpot deal: search_crm_deals, then attach_flow_to_crm.
   - Google Drive: save_flow_to_drive.
   - Slack, Teams, Google Chat, Discord, or webhooks: list_channels, then send_flow_to_channel.
4. If more than one target matches, show the options and let the user choose. Do not guess.
5. Tell the user where the flow went and give the link that the tool returns.
