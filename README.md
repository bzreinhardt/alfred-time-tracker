# alfred-time-tracker

## Setup
1. Install the Workflow in Alfred
2. Change the options in the "tasks" List Filter to whatever options you want
3. Create your logfile and make sure that the script in the workflow points at it. By default it's `~/Work/time_log.csv`
4. Copy `com.user.timelog.plist` to `~/Library/LaunchAgents`
6. Load the LaunchAgent:
```bash
launchctl load ~/Library/LaunchAgents/com.user.timelog.plist`
launchctl start com.user.timelog
```
