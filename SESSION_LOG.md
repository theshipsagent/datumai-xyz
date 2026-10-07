# Session log

Notes on work done in this repo, newest first. This file is kept off the live site by `_config.yml`.

---

## 2026-10-07: cleanup, README, landing page, test-site setup

### What this site is

- **datumai.xyz is a test domain** for putting up test pages. It's kept separate from the real domain, **oceandatum** (`.ai`), which this repo doesn't touch.
- The landing page on it isn't important. It was left as is at the end of the session.

### Domain facts (from public records, checked 2026-10-07)

| Item | Value |
|---|---|
| Registrar | GoDaddy.com, LLC |
| Registered | 2026-01-03, the same day as this repo's first commit |
| Expires | **2027-01-03**: renew in GoDaddy before then if it's still wanted |
| DNS | GoDaddy name servers (`ns41`/`ns42.domaincontrol.com`), with A records pointing at GitHub Pages |

Public records hide the owner's name. To confirm the domain is yours, check GoDaddy under **My Products → Domains**.

### Changes merged into `main`

| PR | Change |
|---|---|
| [#1](https://github.com/theshipsagent/datumai-xyz/pull/1) | Cleanup: tab title changed from "The Ship's Agent \| Coming Soon" to "Datum \| Coming Soon"; contact button class renamed from `.linkedin-link` to `.contact-link`; unused `.test-link` CSS and the empty nav container removed |
| [#2](https://github.com/theshipsagent/datumai-xyz/pull/2) | Added `README.md`: file layout, editing and previewing, deployment |
| [#3](https://github.com/theshipsagent/datumai-xyz/pull/3) | Full landing page (hero, About, Focus, Reports "coming soon", Contact) using the 4 previously unused photos; `noindex, nofollow` meta tag; `_config.yml` keeping `README.md` off the site; README updated to describe the test site |
| [#4](https://github.com/theshipsagent/datumai-xyz/pull/4) | Tab title shortened to "Datum" |

Each change was checked on the live site after merging: the new page and title were showing, all images loaded, and `/README.md` returned "not found".

### Current state

- `index.html` is the landing page, with draft copy that makes no specific claims (no clients, figures or services).
- The site is hidden from search engines (`noindex, nofollow`).
- Merging into `main` publishes to datumai.xyz within a minute or two.

### Open items (none urgent)

- The draft copy on the page was never reviewed. That's fine while the page is only a placeholder.
- The Contact button emails `contact@theshipsagent.com`. Change it if Datum should use a different address.
- Renew the domain before **2027-01-03** if it's still needed.
- Possible next step, not started: give each test page its own folder (for example `datumai.xyz/some-test/`), so tests don't overwrite each other or the homepage.
