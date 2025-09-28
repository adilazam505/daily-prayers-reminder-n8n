# Daily Prayers Reminder Workflow (n8n)

This project is an **n8n workflow** that sends **daily prayers reminders** and a **daily quote**.  
It’s designed to be portfolio-ready and can be imported directly into n8n.

## Features

- **5 Daily Prayer Reminders:**
  - Fajr (5:00 AM)
  - Zuhr (2:00 PM)
  - Asr (4:30 PM)
  - Maghrib (6:00 PM)
  - Isha (8:00 PM)
- **Daily Islamic Quote at 9:00 AM**
  - Rotates automatically based on the day of the week using a Function node.

## Workflow Structure

1. **Cron Nodes:** Trigger each reminder at the correct time.
2. **Set Nodes:** Define the message for each prayer or quote.
3. **Function Node:** Selects the correct quote for the day of the week.

## How to Use

1. **Import Workflow into n8n:**
   - Go to your n8n instance.
   - Click **Import** → select `daily-prayers-reminder.json`.
2. **Activate the workflow** to start receiving reminders.
3. **Optional:** Connect to a notification service (Telegram, email, etc.) for mobile notifications.

## Tech Stack

- [n8n](https://n8n.io/) – Workflow automation platform



