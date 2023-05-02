# Mail Mission Viewer

## TODO:

**Basic functionality:**

somehow needs to be not visible to the public, can use Vercel deployment thing or some auth provider (Slack auth?)

- [ ] maybe have a list of “providers” (airtable form bases) that can be easily added to that feed into one todo list?
- [ ] I think the main page should look something like the Bank admin task dashbooard. Mail mission name and number of pending requests.
- [ ] show page for table/type-of-mail-mission (mail-viewer.hc.com/baseId) would show a list of all the address info etc., and instructins on how to process that particular mail mission type
  - [ ] show page for specific mail mission (mail-viewer.hc.com/baseId/recordId) would show all the info for that specific request
    - [ ] and :white_check_mark: or :x: reject button that writes to Airtable
- [ ] slack notifications

**New features that might be in scope, in order of reasonableness:**

- [ ] “generate pdf” with size for Dymo label printer
- what if it worked w/ the dymo api + a template label to one-click print them (the dymo connect api is awful but this is def possible)
- [ ] what if the main page was a kanban board or project tracker-type thing instead? it’d make it a lot easier to keep track of everything in one place and sort mail “tasks” into (not started/begun/in mailbox)
- [ ] dynamic filters by country or other fields - save preferred filters to account
- [ ] button with templated email to requestor saying their thing was sent, with tracking info (if applicable) and x-day estimate

**More extra helpful features we shouldn’t do right now:**

- ~~[ ] automated label purchasing~~

**A plan?**  
nextjs, serverless, using airtable as a database  
MVP: sync from various airtable databases into one central one, show it as a list on the dashboard, and allow you to mark requests as "done" - all authenticated thru slack
