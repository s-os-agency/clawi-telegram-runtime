# HEARTBEAT.md — Optimized for zero token consumption

# Keep this file empty (or with only comments) to skip heartbeat API calls and burn zero tokens.
# The agent will reply HEARTBEAT_OK immediately when nothing needs attention.

# Only uncomment and add tasks when you explicitly want a periodic check that requires judgment.
# Example (remove the # to activate — costs tokens):
# - Check if any critical alerts arrived in the last hour
# - Verify bot process is still running via /tmp/binance_bot_heartbeat.json

# Current status: IDLE — 0 token consumption on heartbeat polls.
# Bots kept alive by external zero-token watchdog (bot_watchdog.py). User belongings protected.
# Watchdog hardened with instance lock to prevent duplicates.
