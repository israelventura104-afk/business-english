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
  lesson-02-handling-customer-requests/
  lesson-03-reporting-after-a-conference/
  lesson-04-updating-operations/
  lesson-05-project-meeting-debrief/  # Simple Past + -ed sounds
    index.html
    audio/listening.mp3               # add when recorded
  lesson-06-invoice-dispute/          # Prefixes & suffixes
    index.html
    audio/listening.mp3               # add when ready
  lesson-07-drafting-a-client-proposal/  # Parts of speech
    index.html
    audio/listening.mp3               # add when recorded
  lesson-08-service-recovery-email/      # Parts of speech (client success)
    index.html
    audio/listening.mp3               # add when recorded
  versions/                           # Archived monofile snapshots
```

## Lessons

| # | Title | Focus |
|---|-------|--------|
| 01 | Negotiating a Deadline | First Conditional |
| 02 | Handling Customer Requests | Indirect questions |
| 03 | Reporting After a Conference | -ed / -ing adjectives |
| 04 | Updating Operations | Simple Present |
| 05 | Project Meeting Debrief | Simple Past + -ed pronunciation |
| 06 | Invoice Dispute | Prefixes & suffixes |
| 07 | Drafting a Client Proposal | Parts of speech |
| 08 | Writing a Service Recovery Email | Parts of speech |

## Lesson tabs (same on every unit)

Overview · Vocabulary · Grammar Reference · Practice · Reading · Listening

## Notes

- Interactive quizzes stay in the browser session. Lessons 01–03 also use separate `localStorage` keys so progress does not overwrite across lessons.
- Logo and listening audio are external files (not embedded base64).
- When a lesson’s `audio/listening.mp3` is present, the player shows automatically; otherwise the “audio coming soon” note appears.
- Lesson 05 is written for an automotive logistics coordinator (seat-foam project meeting debrief).
- Lesson 07 is a B2B sales proposal (Helix Analytics → Meridian Foods). Focus: parts of speech / word class. Not a trade fair or expo.
- Lesson 08 is a client-success recovery email (OrbitPay → Greenfield Clinics payroll incident). Focus: parts of speech / word class. Not a trade fair or expo.
- Older single-file builds are kept under `versions/`.