# vacatures-checken

A Claude Skill that finds IT and network vacancies in your Gmail job alerts and recruiter mails from the last 7 days, opens the vacancy pages for details, and rates each one against your personal profile. It only reads; it never changes anything in the mailbox and never applies anywhere.

The skill itself is written in Dutch. See [`SKILL.md`](SKILL.md) for the full behavior.

## Requirements

- The Gmail connector, enabled in the chat (the **+** button, then **Connectors**).
- Web fetching, to open vacancy pages.

## What it does

| Step | Rule |
|---|---|
| Fetch | Job alerts and recruiter mails from the last 7 days, read and unread |
| Select | IT and network roles only, duplicates shown once |
| Details | Opens the vacancy page for every Good or Partial fit to read requirements, tasks, hours and contract |
| Rating | Good / Partial / No fit, based on level, travel distance, salary, requirements and type of work |
| Output | Table sorted by rating, shortest travel time first, with follow-up questions when information is missing |

## Personal profile

The rating needs a personal profile (location, travel distance, education, certificates, experience, desired level, salary). It is left empty in this public version: fill in the **Profiel van de gebruiker** section in `SKILL.md` yourself.

## When it activates

When you ask something like "check vacatures" or "welke vacatures passen bij mij?".

## Installation

Copy this folder into your Claude skills directory, or upload it as a skill in Claude.
