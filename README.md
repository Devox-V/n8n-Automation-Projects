## n8n SEO Automation

This repository contains n8n workflow automations focused on SEO, content architecture, and keyword intelligence.
All workflows are exported as JSON files and can be imported directly into n8n.

⚠️ This repository stores workflow logic only.
No credentials, API keys, or execution data are included.

📁 Project Structure
n8n-Automation-Projects/
├── workflows/
│   ├── Content Architect.json
│   └── Keyword architect.json
├── .gitignore
└── README.md

Explanation

workflows/ → Contains exported n8n workflow JSON files

.gitignore → Prevents secrets, databases, and runtime data from being committed

README.md → Project documentation

🔄 Available Workflows
1️⃣ Content Architect

Purpose:
Helps design structured, SEO-friendly content by analyzing inputs such as keywords, intent, or page requirements.

Typical use cases:

Content outline generation

SEO content planning

Topical structure automation

AI-assisted content workflows

2️⃣ Keyword Architect

Purpose:
Automates keyword research and organization logic for SEO and content strategy.

Typical use cases:

Keyword clustering

SEO planning workflows

SERP-based keyword processing

Input preparation for content pipelines

📥 How to Use These Workflows
Step 1: Clone or Download the Repository
git clone https://github.com/Devox-V/n8n-Automation-Projects.git


OR download the ZIP from GitHub.

Step 2: Import Workflow into n8n

Open n8n

Click Import workflow

Select a .json file from the workflows/ folder

Review nodes and connections

Add your own credentials (API keys, tokens, etc.)

Activate the workflow

🔐 Credentials & Security

Credentials are NOT included

API keys must be added manually inside n8n

.env, databases, and credential files are ignored via .gitignore

This ensures:

No secret leakage

Safe public sharing

Clean version control

🚀 Why This Repository Exists

Version control for n8n workflows

Easy backup and reuse

Portfolio and learning reference

Clean separation of logic vs execution

Foundation for future automation projects

🧠 Best Practices Followed

Workflow logic stored as JSON

No runtime or execution data committed

Git used only for versioning

n8n used only for execution

Clear and minimal structure

📌 Notes

File names may be updated to kebab-case in future versions

Workflows may evolve as automation logic improves

This repository focuses on maintainability, not raw execution
