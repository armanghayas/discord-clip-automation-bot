# Discord Clip System Bot

## Overview

Discord Clip System Bot is a backend automation bot developed by Arman Ghayas built to **run and manage the Clip system** using Discord as a control panel.

This bot is not a chat or fun bot.  
It is a **system bot** used to control clip-related automation, Instagram scraping jobs, campaigns, and scheduled tasks from inside a Discord server.

---

## What This Bot Is

- A **Discord-based automation bot**
- Used to **operate the Clip system**
- Runs Instagram scraping jobs in the background
- Uses Discord channels and buttons as a control dashboard
- Stores data and job states in a database

---

## What This Bot Is NOT

- Not a moderation bot  
- Not a meme or music bot  
- Not a public Discord community bot  
- Not a finished SaaS product  

This is a **backend automation tool**.

---

## Main Features

### Discord Control Panel
- Uses slash commands and buttons
- Create and manage clip campaigns
- Start and stop jobs directly from Discord
- Discord acts as a lightweight dashboard

### Instagram Scraping
- Scrapes public Instagram data related to clips
- Uses cookie-based login (no official API)
- Supports multiple scraping modules
- Designed for automation, not manual use

### Job Scheduler
- Run scraping jobs automatically
- Start, stop, and manage long-running tasks
- Jobs continue even after restarts

### Database Integration
- Uses Supabase for storage
- Saves:
  - Campaigns
  - Jobs
  - Scraped data
  - Bot state

---

## How It Works (Simple Flow)

1. Bot runs inside a Discord server  
2. Discord is used to control the Clip system  
3. User starts a campaign or job  
4. Bot scrapes Instagram data automatically  
5. Data and job status are saved in the database  

---

## Tech Stack

- Node.js
- discord.js
- Supabase
- Instagram scraping (cookie-based)
- Custom scheduler and job system

---

## Project Structure (Simplified)

- `index.js` – Main bot entry
- `deploy-commands.js` – Slash command setup
- `scheduler.js` – Job scheduling logic
- `db.js` – Database connection
- `scraper files` – Instagram scraping logic
- `utils.js` – Helper functions

---

## Limitations

- Scraping may break if Instagram changes
- No proxy rotation by default
- Requires technical knowledge to deploy
- Discord is the only interface (no web UI)

---

## Use Cases

- Clip systems
- Instagram monitoring
- Automation workflows
- Internal tools
- Proof of automation and bot development skills

---

## Author & Contact

**Arman Ghayas**  
Founder – **ArmanX AI**

AI Agent & Automation Developer  
I build bots, AI agents, workflow automations, and custom AI systems.

I am **open to work**, freelance projects, and collaborations.

📧 Email: info@armanxai.com  
📞 Phone / WhatsApp: +92-333-9576464  
🌐 Website: https://www.armanxai.com

---

## License

This project is for educational and internal automation use.  
Use responsibly.
