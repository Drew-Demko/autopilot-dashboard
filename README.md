# Autopilot Board

Phone dashboard for Autopilot (the Polymarket betting bot in the parent folder): today's betting windows on a day
strip (when to keep the laptop open), balance and profit, the "Is it working?" line, withdrawal progress and the games
being watched live.

This repo holds only the page. It contains no data and no keys. Autopilot posts a small status summary to a private
ntfy channel every 10-30 minutes (`src/autopilot/status.py`), and the page reads the latest one. Open it with the
channel name after `#` in the link, then use Safari's Share > Add to Home Screen.

Hosted with GitHub Pages from the `main` branch.
