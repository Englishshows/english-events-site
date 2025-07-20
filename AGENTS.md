# AGENT Instructions

This project hosts a simple static site listing English-language events in Amsterdam.

* **events.json** contains all event entries. The web pages load this file to show the events.
* **amsterdam_event_sources.md** lists venue websites where upcoming events are found.

## Updating Events

When you update `events.json`:
1. First run `/bin/date` to log the time.
2. Gather events for the current month from the venues in `amsterdam_event_sources.md`.
3. Ensure entries are unique and sorted chronologically by the `date` field.

Further details on how to update are in `docs/update_instructions.md`.
