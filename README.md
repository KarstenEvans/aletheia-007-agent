# Aletheia 007 Agent

> **An Aletheia 007 agent for your digital footprint: find exposure, verify matches, and pursue removal—with your permission.**

A privacy-first specification for checking a user's own public name, email, username, and possible account exposure; preparing lawful UK/EU correction or removal requests; and offering opt-in recurring monitoring.

[Open the live resource page](https://karstenevans.github.io/aletheia-007-agent/aletheia-007-agent-rsc.htm) · [Download the HTML file](https://raw.githubusercontent.com/KarstenEvans/aletheia-007-agent/main/aletheia-007-agent-rsc.htm)

## Current status: working browser pilot (v1.2.0)

**[Open the live 007 application](https://karstenevans.github.io/aletheia-007-agent/)**. This is a real, free, browser-based application with user-triggered read-only GitHub/GitLab public username checks, a session-only case tracker, editable removal drafts, AI handoffs and JSON/CSV/encrypted export. It is **not** a full internet search engine, autonomous agent, encrypted storage vault, scheduler, email sender or guaranteed deletion service. Browser/API availability must be checked on the deployed site.

The test handle `KarstenEvans` is a real public GitHub username, not invented data. No deletion or third-party contact is performed.

## Files

| File | Purpose | Link |
|---|---|---|
| `index.html` + `styles.css` + `app.js` | Runnable public-facing browser dashboard | [Open app](https://karstenevans.github.io/aletheia-007-agent/) |
| `aletheia-007-agent.md` | Canonical portable agent behaviour and safeguards | [View specification](./aletheia-007-agent.md) |
| `aletheia-007-agent-rsc.htm` | Human-facing resources and dated trust check | [Open live page](https://karstenevans.github.io/aletheia-007-agent/aletheia-007-agent-rsc.htm) · [View source](./aletheia-007-agent-rsc.htm) · [Download HTML](https://raw.githubusercontent.com/KarstenEvans/aletheia-007-agent/main/aletheia-007-agent-rsc.htm) |

Planned Swindon.org.uk location: <https://swindon.org.uk/resources/aletheia-007-agent-rsc.htm>

## Core safeguards

- Checks only the user's own data or data they are formally authorised to manage.
- Treats names and reused usernames as possible matches, not proof of identity.
- Does not use login attempts, password-reset flows, stolen records, or dark-web dumps.
- Never requests or stores passwords, recovery codes, private keys, or authentication cookies.
- Requires informed approval before sending a request, complaint, email, or form.
- Keeps live personal data, case files, evidence, and secrets out of GitHub and CI logs.
- Makes recurring monitoring optional, editable, and stoppable.

## Using the specification

Open the [live app](https://karstenevans.github.io/aletheia-007-agent/) and select a public handle, or load `aletheia-007-agent.md` into a compatible AI or agent environment. Before accepting a name or email address, the runtime must disclose whether processing is local, hosted, or unknown and identify any external services receiving the query.

The HTML file is a companion resource page, not the executable agent.

## Licence

Copyright © 2026 Karsten Evans.

This project is free software licensed under the [GNU General Public License, version 3 or later](./LICENSE) (`GPL-3.0-or-later`). It is provided without warranty. See `LICENSE` for the complete terms.

## Important

This project provides technical and informational assistance, not legal advice. Data-protection rights have exceptions and vary by jurisdiction. No search result or removal outcome is guaranteed.
