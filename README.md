🛠️ Step-by-Step Setup Guide for Silent Watcher
📁 Step 1: Create a Google Spreadsheet
- Open your browser and go to Google Sheets.
- Click Blank to create a new spreadsheet.
- Rename the sheet to something like Silent Watcher Logs.

🧩 Step 2: Open Extensions → Apps Script
- In the spreadsheet, click on Extensions in the top menu.
- Select Apps Script.
- A new tab will open with the script editor.

💻 Step 3: Add Your Script Code
- Delete any default code in the editor.
- Paste the script code you’ve been given (or I can help write one if needed).
- Click Save 💾.

✅ Step 4: Run Verification
- Click the Run ▶️ button in the toolbar.
- You may be asked to authorize the script—follow the prompts and allow all permissions.
- Once verified, the script is ready to deploy.

🚀 Step 5: Deploy as Web App
- Click Deploy → New Deployment.
- Under Select type, choose Web App.
- Set access to Anyone or Anyone with the link.
- Click Deploy.
- Copy the Web App URL 🔗—this is your magic link!

📱 Step 6: Install Macrodroid on Android
- Go to the Play Store and install Macrodroid.
- Open the app and allow all permissions it requests.
- Search for your saved macro called Silent Watcher.

🔗 Step 7: Paste the Web App Link
- Inside the macro setup, find the action that requires a URL.
- Paste the Web App link you copied earlier.
- Save the macro.

🕵️ Step 8: Silent Monitoring Begins
- Once everything is set up, your phone will start logging data silently to the spreadsheet.
- You can open the spreadsheet anytime to view the logs and monitor activity.


🔐 Key Concepts Used
| Concept | Role in Script | 
| PropertiesService | Stores the spreadsheet ID for later use | 
| LockService | Prevents race conditions when multiple requests hit the script simultaneously | 
| doPost(e) | Triggered when a POST request is sent to the Web App | 
| Utilities.formatDate() | Formats timestamps for logging | 
| ContentService | Sends back a JSON response to the sender | 





