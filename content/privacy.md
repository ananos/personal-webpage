---
title: Privacy policy for the mini-assistant app
date: 2026-11-08
type: page
share: false
---

This policy covers the mini-assistant app only. It does not apply to this
website (ananos.co.uk), which only hosts the policy.

mini-assistant is a personal tool. I built it for my own use, and it only
accesses my own Google accounts. It is not offered to anyone else.

This page describes which Google user data it accesses, how it uses that data
and where the data goes.

## Data it accesses

When I sign in, I grant mini-assistant these Google permissions:

- **Gmail, read-only** (`gmail.readonly`): message headers, text and
  attachments.
- **Google Calendar, read-only** (`calendar.readonly`): my events.
- **Google Drive, read-only** (`drive.readonly`): my files.
- **Google Tasks** (`tasks`): requested for a planned feature that adds
  follow-ups I approve to my own task list. The current version does not use
  it.

mini-assistant never sends, deletes or changes email, events or files.

## How it uses the data

- It sorts new email into categories (eg. urgent, needs a reply, newsletter).
- It sends me a morning summary of my day: events, and the emails that need
  attention.
- It answers my questions about my calendar, my email and my documents.
- It keeps a local search index of my documents and email attachments.

## Where the data is processed and stored

All processing runs on hardware I own, on my home network: a Mac mini and an
NVIDIA Jetson. The language models also run there. Google user data is not
sent to any third-party AI service.

The data, the search index and the sign-in tokens stay on those machines. The
tokens are readable only by my user account. Data is kept until I delete it.

The morning summary and the alerts go to my own Telegram account, through the
Telegram Bot API. They contain email senders, subjects, event titles and times.
They do not contain full email text or attachments.

## Sharing

Google user data is not sold, not shared with anyone and not used for
advertising. No person other than me has access to it.

mini-assistant's use and transfer of information received from Google APIs
adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Revoking access

Access can be revoked at any time from the
[Google Account permissions page](https://myaccount.google.com/permissions).
Revoking it stops all further access. I can then delete the local data.

## Contact

Questions about this policy: [anastassios.nanos@gmail.com](mailto:anastassios.nanos@gmail.com).

*Last updated: November 8, 2026.*
