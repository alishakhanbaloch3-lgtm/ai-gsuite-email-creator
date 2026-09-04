# 🚀 AI-Powered Google Workspace Email Creator (n8n Workflow)

An automated workflow built with **n8n** and **Google Gemini AI Agent** to automatically process new user records from Google Sheets and generate standardized user accounts and credentials.

## 📌 Features
- **Automated Trigger:** Listens for new updates in connected Google Sheets.
- **Data Normalization:** Cleanly parses usernames and removes invalid spaces/special characters using JavaScript.
- **AI Agent Processing:** Utilizes Google Gemini Chat Model to format output into clean JSON containing `givenName`, `familyName`, `primaryEmail`, and secure `password`.
- **Looping Mechanism:** Iterates through multiple records safely using n8n Loop Over Items node.

## 🛠 Tech Stack
- **Automation Tool:** n8n
- **AI Model:** Google Gemini Chat Model
- **Trigger Source:** Google Sheets Trigger
- **Scripting:** JavaScript (Node.js)

## 🚀 How to Import & Use
1. Download the `Gmail Creator.json` file from this repository.
2. Open your **n8n** instance.
3. Create a new workflow → Click menu → **Import from File**.
4. Upload the JSON file and configure your Google Sheets credentials.
