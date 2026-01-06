# D2C-BOM-View
D tools to Catalyst BOM Manager


📌 Project Overview

D2C (D-Tools to Catalyst) is an automation and integration solution that connects D-Tools projects directly with Zoho Catalyst.
The system eliminates manual data entry by automatically fetching project details, Bill of Materials (BOM), and Change Orders from D-Tools and displaying them in a structured UI within Catalyst.

This project was built as part of a Technology / Hackathon initiative to streamline project data synchronization and improve operational efficiency.

🚀 Key Features

🔗 Direct D-Tools Project Integration

Paste the D-Tools project link into the Catalyst UI

Automatic project validation and connection

📄 Automatic Project Data Fetch

Project Number (e.g., DWAV-0721)

Core project details

Customer and deal-related information

📦 Bill of Materials (BOM) Sync

Fetches complete BOM from D-Tools

Displays items in a clean, structured format

Easy review and verification

🔄 Change Order Support

Retrieves change orders associated with the project

Keeps data in sync with D-Tools updates

⚡ No Manual Data Entry

Fully automated data flow from D-Tools to Catalyst

🛠️ Tech Stack

Frontend

HTML

CSS

JavaScript

Backend

Zoho Catalyst (Serverless Functions & Cron Jobs)

Node.js

Integration

D-Tools API

Zoho Catalyst Services

🔄 Application Flow

User pastes the D-Tools Project URL into the Catalyst UI

Catalyst validates the project with D-Tools

Project details are fetched automatically

Project Number and metadata are stored

Bill of Materials is retrieved and displayed

Change Orders are synced when available
