# Mail Mission Viewer

## TODO:

**Basic functionality:**

- maybe have a list of “providers” (airtable form bases) that can be easily added to that feed into one todo list?
- I think the main page should look something like the Bank admin task dashbooard. Mail mission name and number of pending requests.
- Show page (mail-viewer.hc.com/baseId/recId) would show all the relevant information (address, name, date, etc, and instructions on how to fulfill this type of mail mission)
  - and :white_check_mark: or :x: reject button that writes to Airtable

**New features that might be in scope, in order of reasonableness:**

- “generate pdf” with size for Dymo label printer
- what if it worked w/ the dymo api + a template label to one-click print them (the dymo connect api is awful but this is def possible)
- what if the main page was a kanban board or project tracker-type thing instead? it’d make it a lot easier to keep track of everything in one place and sort mail “tasks” into (not started/begun/in mailbox)
- button with templated email to requestor saying their thing was sent, with tracking info (if applicable) and x-day estimate

**More extra helpful features we shouldn’t do right now:**

- automated label purchasing
