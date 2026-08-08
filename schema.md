# Data Mapping Schema

This blueprint shows how the Tally form answers map directly to the Notion database columns.

| Tally Form Field | Field Type | Notion Property | Notion Data Type |
| :--- | :--- | :--- | :--- |
| "What is the title?" | Short Answer | Title | Title |
| "What type of content is this?" | Multiple Choice | Type | Select (`Book`, `Course`, `Article`) |
| "Paste the link here" | URL Input | URL | URL |
| "How would you rate it?" | Multiple Choice | Rating | Select (`⭐`, `⭐⭐`, `⭐⭐⭐`) |
| "What is your biggest takeaway?"| Long Answer | Key Takeaway | Text |
| "Upload your media below"| Media Input | Media | Files |
