# Bug Journal

A personal debugging and QA journal documenting real-world bugs, technical problems, and practical workarounds.

I record issues I encounter while using software, hardware, and different systems. This journal is a public portfolio of how I observe problems, reproduce them, investigate their causes or triggering conditions, and find workarounds.

Where possible, each entry includes reproducible steps, expected behavior, actual behavior, and a tested workaround. Observations are kept separate from hypotheses; missing information is marked explicitly.

## Statistics

| Metric | Count |
| --- | ---: |
| Bugs documented | 1 |
| Workarounds found | 1 |
| Reported upstream | 0 |
| Fixed upstream | 0 |

Counts cover unique entries in `journal/`, including resolved entries. An Issue or Discussion about the same entry is not counted again. Upstream counts include only documented reports or confirmed fixes. These statistics are maintained manually when entries change.

## Journal

| Discovered | Entry | Status |
| --- | --- | --- |
| 2026-09-28 | [CarPlay audio route not restored after phone call](journal/2026-09-28-carplay-audio-route.md) | Workaround available |

## Entry structure

Use the [bug entry template](.github/ISSUE_TEMPLATE/bug-report.md) for new entries. It is available through **Issues → New issue**; the headings can also be copied into a Markdown file or Discussion.

Each entry records:

- A specific title and discovery date.
- The product, device, software version, and relevant environment.
- The problem, expected behavior, and actual behavior.
- Numbered reproduction steps and reproducibility.
- A workaround, if found, and an optional cause or hypothesis.
- Upstream reporting details, current status, and additional notes.

Entries live in `journal/YYYY-MM-DD-short-description.md`. Issues track investigations and follow-up; Discussions provide space for observations, questions, and shared workarounds. See [CONTRIBUTING.md](CONTRIBUTING.md) for writing guidance, labels, and Discussion categories.

## Privacy

Entries must not contain personal data, tokens, API keys, serial numbers, or other sensitive information. Logs, screenshots, and upstream links must be reviewed and redacted before publication.
