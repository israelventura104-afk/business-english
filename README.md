# Business English Course Portal

Scenario-based Business English lessons by **Israel Ventura**.

Live site: https://israelventura104-afk.github.io/business-english/

## Structure

```
business-english/
  index.html                          # Course menu (hub)
  assets/logo.png                     # Brand logo
  favicon.png
  lesson-01-negotiating-a-deadline/
    index.html
    audio/listening.mp3
  lesson-02-handling-customer-requests/
    index.html
    audio/listening.mp3
  lesson-03-reporting-after-a-conference/
    index.html
    audio/listening.mp3
  lesson-04-updating-operations/
    index.html
    audio/listening.mp3               # add when ready
  versions/                           # Archived monofile snapshots
```

## Lessons

| # | Title | Focus |
|---|-------|--------|
| 01 | Negotiating a Deadline | First Conditional |
| 02 | Handling Customer Requests | Indirect questions |
| 03 | Reporting After a Conference | -ed / -ing adjectives |
| 04 | Updating Operations | Simple Present |

## Notes

- Progress / answers use **separate** `localStorage` keys per lesson (so lessons do not overwrite each other). Data stays in the browser only.
- Logo and listening audio are external files (not embedded base64).
- Lesson 04 listening audio: drop `lesson-04-updating-operations/audio/listening.mp3` when ready; the page auto-shows the player if the file exists.
- Older single-file builds are kept under `versions/`.
