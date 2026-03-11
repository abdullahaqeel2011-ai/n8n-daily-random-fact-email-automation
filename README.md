📧 Daily Random Fact Email Automation (n8n Workflow)

🚀 Daily Random Fact Email is a simple yet powerful n8n automation workflow that automatically sends a random interesting fact to your email every day.

This project demonstrates how to combine scheduled triggers, API requests, and email automation using the n8n workflow automation platform.

Perfect for beginners learning automation, APIs, and workflow orchestration.

🧠 Project Overview

This workflow automatically:

• ⏰ Runs on a scheduled time using the Schedule Trigger
• 🌐 Fetches a random fact from a public API
• 📧 Sends the fact directly to your email
• 🤖 Runs fully automated without manual interaction

The automation helps demonstrate how small workflows can create useful automated systems.

⚙️ How the Workflow Works

The automation follows three simple steps:

1️⃣ Schedule Trigger

• Automatically runs the workflow at a specific time
• Ensures the automation executes daily without manual input
• Acts as the starting point of the workflow

2️⃣ HTTP Request Node

• Sends a request to a public API
• Retrieves a random fact in JSON format
• Extracts the fact text from the API response

API used in this workflow:

https://uselessfacts.jsph.pl/random.json?language=en
3️⃣ Gmail Node

• Sends the fetched fact to a specified email address
• Uses Gmail OAuth authentication
• Automatically formats the email message

Example email:

Subject:

Daily Random Fact

Message:

Random interesting fact fetched from the API
🛠 Technologies Used

• 🤖 n8n Workflow Automation
• 🌐 Public Random Facts API
• 📧 Gmail Integration
• ⚡ HTTP Request Node
• ⏰ Schedule Trigger Node

🎯 Use Cases

This workflow can be used for many automation scenarios such as:

• 📚 Daily knowledge or learning emails
• 📰 Automated newsletters
• 📩 Daily content delivery
• 🤖 API automation practice
• 🎓 Learning n8n workflow automation

📂 Workflow Structure
Schedule Trigger
        │
        ▼
HTTP Request (Fetch Random Fact)
        │
        ▼
Gmail (Send Email)

This simple pipeline demonstrates how automation tools can connect APIs with communication platforms.

🚀 How to Use This Workflow

Follow these steps to run the automation:

1️⃣ Import Workflow

• Download the workflow JSON file
• Open n8n dashboard
• Click Import Workflow
• Upload the JSON file

2️⃣ Configure Gmail Credentials

• Open the Gmail node
• Connect your Gmail OAuth account
• Enter the email where you want to receive the facts

3️⃣ Activate Workflow

• Turn the workflow Active
• The automation will now run automatically based on the schedule

💡 Why This Project Is Useful

This workflow helps demonstrate:

• Automation fundamentals
• API integration in workflows
• Email automation systems
• Real-world workflow orchestration

Even simple automations like this show how automation can save time and deliver value continuously.

🔮 Possible Improvements

You can extend this workflow by adding:

• 📱 Telegram notifications
• 📊 Logging facts into Google Sheets
• 📬 Sending facts to multiple recipients
• 🤖 AI-generated explanations for each fact
• 📱 Social media posting automation

📄 License

This project is licensed under the MIT License, allowing anyone to use, modify, and distribute the workflow for personal or commercial purposes.

👤 Author

Abdullah Aqeel

AI Automation Engineer | Software Quality Assurance Engineer (SQAE)
