# Comment Alerts for Jira — public docs

Setup guide and privacy policy for the Marketplace listing. Served by GitHub Pages.

- `index.html` — documentation and setup guide (the listing's Documentation URL)
- `privacy.html` — privacy policy (the listing's Privacy Policy URL)
- `support.html` — support page (the listing's Support URL)
- `jira-email-when-someone-comments.html`, `notify-only-assignee-and-reporter.html`,
  `jira-automation-comment-email.html` — guides, linked from the index
- `style.css` — shared styles

## Before submitting the listing

Three placeholders appear across both pages and must be replaced:

| Placeholder | What to put |
| --- | --- |
| `LEGAL ENTITY` | The name your Marketplace partner account is verified as |
| `SUPPORT EMAIL` | An address you actually monitor — reviewers check it |

Find every occurrence with:

```
grep -rn "LEGAL ENTITY\|SUPPORT EMAIL" .
```

The app code itself lives in a separate private repository.
