<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Fyrhaven/Fyrhaven-CRM/blob/main/brand/fyrhaven-lockup-dark.svg">
    <img src="https://github.com/Fyrhaven/Fyrhaven-CRM/blob/main/brand/fyrhaven-lockup.svg" alt="Fyrhaven — mail · records · people" width="300">
  </picture>
</p>

<h3 align="center">Your mail. Your records. Your rock.</h3>

<p align="center">
  Mail hosting and a CRM for people who run their own mail server.<br>
  Built on <a href="https://stalw.art">Stalwart</a> and
  <a href="https://github.com/bulwarkmail/webmail">Bulwark Mail</a>.
</p>

---

## What this is

A mail server gives you contacts, and then stops: no companies, no projects, no
time, no record of what you agreed with whom. Fyrhaven is that missing layer —
contacts and companies, projects with milestones, time and expenses, follow-ups,
private notes and consent records — living **next to your mail**, on
infrastructure you can point at.

Two pieces, one idea:

| | What it is |
|---|---|
| **Fyrhaven CRM** | A plugin for Bulwark Mail: find and merge duplicate contacts across every address book, a 360° view of each contact and company, projects, follow-ups, contact health and retention, a GDPR toolkit, import and export, smart search. English and German, drawn with the host's own interface |
| **The record server** | Where the plugin's own records live: a small key/value service, no runtime dependencies, encrypted at rest, SQLite or an S3-compatible bucket. Yours to run, or ours |

The plugin is useful with no server at all. The server is what makes a note
follow you to the next device.

## The name

*Fyr* — lighthouse. *Haven* — a sheltered place for ships. Records on something
solid, whether that is a server in your rack or one of ours.

## What we will not claim

Records on the hosted service are encrypted at rest with a key the service
unwraps in order to serve them, **so the operator can read them**. That is the
price of a server-held key; it is written on the
[privacy page](https://fyrhaven.com/privacy) rather than implied away, and a
customer-held key is not built yet.

## Where things are

- **The shop** — <https://fyrhaven.com> · a trial without a card · terms, privacy
  and imprint
- **The source** — [Fyrhaven/Fyrhaven-CRM](https://github.com/Fyrhaven/Fyrhaven-CRM):
  the plugin and the record server in one repository, with the test suite that
  pins their behaviour. The repositories in this organisation are private until
  launch; the shop is the public front today
- **Writing to us** — <hello@fyrhaven.com>
