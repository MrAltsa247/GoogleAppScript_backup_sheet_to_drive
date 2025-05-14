# GoogleAppScript_backup_sheet_to_drive
This script creates a backup copy of the active Google Sheet and stores it in a designated folder in your Google Drive. It helps preserve historical data, protects against accidental changes or deletions, and maintains versioned records automatically.

🗂️ GoogleAppScript_backup_sheet_to_drive
📋 Overview
This script creates a backup copy of the active Google Sheet and stores it in a designated folder in your Google Drive. It helps preserve historical data, protects against accidental changes or deletions, and maintains versioned records automatically.

✅ Benefits
Automatically keeps a timestamped backup of your data

Prevents data loss due to accidental edits or deletions

Ideal for weekly/monthly reports, logs, finance records, etc.

Supports manual run or scheduled backup (e.g., every night)

📊 Spreadsheet Structure
This script works on any Google Spreadsheet. You only need to:

Define the backup folder ID

Optionally rename the backup file pattern

🧰 Setup Instructions
Create a folder in Google Drive to store backups

Copy the folder ID from the URL
Example: https://drive.google.com/drive/folders/YOUR_BACKUP_FOLDER_ID

Open the Google Spreadsheet you want to backup

Go to Extensions > Apps Script

Paste the script below

Replace "YOUR_BACKUP_FOLDER_ID" with your actual folder ID

Run the function backupSpreadsheet()

Optionally, create a time-based trigger (e.g., daily at 2 AM)


⚠️ Notes
Backups are stored as .gsheet files (Google Spreadsheet copies)

If needed, you can manually export as PDF/Excel with minor changes

Use Triggers > Time-driven trigger to automate recurring backups
