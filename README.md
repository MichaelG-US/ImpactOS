# ImpactOS — From Data Chaos to Clarity

Concept site for **ImpactOS**, an AI-powered cloud analytics and operational intelligence platform built for nonprofits and humanitarian organizations.

## Stack

- Static HTML + CSS (no build step)
- [Netlify Forms](https://docs.netlify.com/forms/setup/) for the pilot-request form
- Deployed via Netlify

## Local preview

Either open `index.html` directly in a browser, or use the Netlify CLI for local emulation (forms, redirects, etc.):

```bash
netlify dev
```

Then visit <http://localhost:8888>.

## Project layout

```
.
├── index.html       # Landing page (hero, problem, vision, capabilities, agents, roadmap, demo)
├── thanks.html      # Submit confirmation page (form action target)
└── styles.css       # All styling
```

## Form submissions

The pilot-request form is wired to Netlify Forms with a honeypot (`bot-field`) for spam protection. Submissions appear in the Netlify project dashboard under **Forms → pilot-request**.

## Deploy

Push to GitHub and connect the repository to Netlify — no build command, publish directory is the project root.
