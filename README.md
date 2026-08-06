# Gifted by Grace Learning Haven — Website

The public website for **Gifted by Grace Learning Haven, Inc.**, a nonprofit providing
faith-based, culturally grounded homeschool support for families of gifted learners.

🌐 giftedbygracelearninghaven.org

## What this is

A single-page static site. No database, no plugins, no logins — which means
nothing to hack and nothing to keep updated.

The site is the front door. The heavy lifting is handled by specialist platforms:

| Section    | Powered by            |
|------------|-----------------------|
| Courses    | LearnWorlds           |
| Community  | Swarm                 |
| Coaching   | Calendly + Zoom       |
| Donations  | (Zeffy — recommended) |

## Files

```
index.html    the entire site
404.html      shown for bad URLs
images/       logo, hero photo, favicons
```

## Editing

Change `index.html`, commit, and the live site updates automatically.

Links still needing real URLs are marked with a `data-setup` attribute —
search the file for `data-setup` to find every one.

## ⚠️ Never commit secrets

This repository is public. Do not commit API keys, LearnWorlds credentials,
donor records, or any family information.
