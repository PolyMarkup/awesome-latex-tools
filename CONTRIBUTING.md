# Contributing

Thanks for helping to improve **Awesome LaTeX Tools**. This list lives at <https://github.com/PolyMarkup/awesome-latex-tools>, and all contributions are released under [CC0 1.0](LICENSE). The CC0 choice follows the convention for awesome lists, so anyone can reuse the data.

## What belongs here

An entry should be a tool, platform or resource that is useful to people who write, build or publish LaTeX documents. It must meet all of these criteria:

1. **It exists and works.** The link resolves and the project is usable today.
2. **It is relevant to LaTeX** (including TeX engines, LaTeX-adjacent formats such as BibTeX, and alternatives that people use instead of LaTeX).
3. **It is maintained or established.** Prefer projects with a release or commit in the last two years, or long-standing references that are still accurate. Archived or abandoned projects are not accepted.
4. **It is not a duplicate.** Search the README before adding.
5. **It has a stable home.** Link to the official site or repository, not a blog post or an aggregator page about it.
6. **No affiliate links, tracking parameters or paid placements.**
7. **Disclose a conflict of interest.** If you maintain or work on the tool, say so in the pull request. Self-submissions are welcome if they meet the criteria and the description stays neutral.

Individual LaTeX templates, single-package forks and personal blogs are generally out of scope. Prefer collections, official class files, and well-known resources.

## Entry format

```markdown
- [Name](https://example.org) - Short, neutral description in one sentence. `OSS`
```

- Keep the description to one sentence, in sentence case, ending with a period. Avoid marketing language ("best", "powerful", "revolutionary").
- End the line with exactly one license tag:
  - `OSS` - open-source license (OSI-approved or equivalent).
  - `Free` - free of charge but not open source, or a resource such as a guide or forum.
  - `Freemium` - a free tier with paid plans.
  - `Proprietary` - paid or closed source with no free tier.
- Keep each section sorted alphabetically (case-insensitive) by name.
- Put the entry in the most specific existing category. If none fits, open an issue first to discuss a new one.

## Pull request process

1. Fork the repository and create a branch.
2. Edit `README.md` only (and the table of contents counts, if you add or remove entries).
3. Add one entry per pull request when possible, so each can be reviewed on its own. Use a title such as `Add Name`.
4. Fill in the pull request template.
5. The link-check workflow runs on every pull request. Fix any broken links it reports. Some sites block automated checkers; maintainers may add them to `lychee.toml`.
6. A maintainer reviews the entry against the criteria above. They may ask you to adjust the description or category.

Prefer not to open a pull request? Use the "Suggest a tool" issue form instead.

## Removing entries

Open an issue or pull request if a link is dead, a project is archived or abandoned, or a description or license tag is wrong.

## Conduct

Be respectful and keep reviews about the content. Maintainers may close contributions that are spammy, promotional or off-topic.
