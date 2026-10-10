---
name: map-a-process
description: Map, change, or export a business process as a Wavelength flow. Use when the user asks for a flowchart, a process map, or a change to a saved Wavelength flow.
---

# Map a process in Wavelength

1. For a new process, call create_flow_from_text with the user's description.
2. For a saved flow, find it with search_flows or list_flows, then change it with edit_flow. Change only what the user asks.
3. Use one decision for each branch, and label each branch, for example Yes and No.
4. When the user wants a file or a docs block, call export_flow with mermaid, svg, drawio, or json.
5. Show the result and give the flow link.
