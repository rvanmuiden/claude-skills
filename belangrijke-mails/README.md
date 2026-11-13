# belangrijke-mails

A Claude Skill that lists the unread emails from the last 24 hours that actually matter, with sender, subject, a short summary and a priority. It only reads; it never changes anything in the mailbox.

The skill itself is written in Dutch. See [`SKILL.md`](SKILL.md) for the full behavior.

## Requirements

- The Gmail connector, enabled in the chat (the **+** button, then **Connectors**).

## What it does

| Step | Rule |
|---|---|
| Fetch | Unread mail from the last 24 hours (`is:unread newer_than:1d -in:sent`) |
| Filter out | Newsletters, ads, social media notifications, order confirmations, parcel and mail delivery, expired verification codes |
| Keep | Security alerts, bills and invoices, messages from bank or course platform |
| Priority | High: action, reply or deadline. Medium: relevant, no direct action. Low: informational |
| Output | Table sorted by priority, newest first within a priority. Bills always show amount and due date. Codes and passwords are never repeated |
| Vacancies | IT and network vacancies from job alerts and recruiters go into a separate table, each rated Good / Partial / No fit against a personal profile, with follow-up questions when information is missing |

## Personal profile

The vacancy rating needs a personal profile (location, travel distance, education, certificates, experience, desired level, salary). It is left empty in this public version: fill in the **Profiel van de gebruiker** section in `SKILL.md` yourself.

## When it activates

When you ask something like "welke mails zijn belangrijk?" or "wat moet ik lezen in mijn mail?".

## Installation

Copy this folder into your Claude skills directory, or upload it as a skill in Claude.
