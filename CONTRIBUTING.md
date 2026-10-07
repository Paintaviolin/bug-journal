# Writing a useful journal entry

This is a personal debugging journal. Additional reproduction results, corrections, and workarounds are welcome through Issues or Discussions.

1. Describe one concrete problem per entry. Use a short, specific title.
2. Start with the [bug entry template](.github/ISSUE_TEMPLATE/bug-report.md). For a journal file or Discussion, copy the body below the YAML front matter.
3. Record the discovery date as `YYYY-MM-DD`, exact versions, and relevant environmental conditions. Use `Not recorded` or `Unknown` instead of guessing.
4. Give numbered steps someone else can follow, with separate expected and actual results.
5. State reproducibility honestly: for example, `5/5 attempts`, `Intermittent`, or `Unknown — attempt count not recorded`.
6. Explain the workaround and what was observed after applying it. Mark untested suggestions clearly.
7. Separate observations from possible causes. Do not present a hypothesis as a confirmed root cause.
8. Record whether the issue was reported upstream and include a safe public link or a non-sensitive report ID. If reporting status is unavailable, say `Not recorded`. Mark a fix only after verification and record the fixed version.
9. Use one of these statuses: `Open`, `Workaround available`, `Reported`, `Fixed`, or `Cannot reproduce`. A workaround does not mean the bug is fixed.
10. Remove personal data, tokens, API keys, serial numbers, and other sensitive information from text, screenshots, logs, and links.

Save journal entries as `journal/YYYY-MM-DD-short-description.md`. Link related Issues and Discussions to the journal entry so that a single bug is counted once. Update the README index and its four manual statistics when an entry is added or its documented outcome changes.

## Issue labels

Apply only labels supported by the entry. Platform labels may be combined with behavior and outcome labels.

| Label | Use |
| --- | --- |
| `ios` | iOS-related problem |
| `macos` | macOS-related problem |
| `windows` | Windows-related problem |
| `app` | Application-related problem |
| `hardware` | Hardware-related problem |
| `networking` | Connectivity or networking problem |
| `carplay` | CarPlay-related problem |
| `reproducible` | Repeatable behavior confirmed by recorded attempts |
| `intermittent` | Behavior occurs only sometimes |
| `workaround` | A working workaround is documented |
| `reported-upstream` | An upstream report is documented |
| `fixed` | An upstream fix has been verified |
| `investigation` | Further diagnosis is needed |

Keep Issues open while a bug persists, even if a workaround exists. Use the `fixed` label only for a verified fix; a closed Issue alone does not prove an upstream fix.

## Discussion categories

Use the following categories with the **Open-ended discussion** format:

| Category | Description |
| --- | --- |
| Bug Reports | Observed bugs, reproduction results, and technical investigations. |
| Workarounds | Practical workarounds and their verification results. |
| Apple / iOS / macOS | Problems involving Apple devices, iOS, macOS, or CarPlay. |
| Apps & Software | Application and software behavior across platforms. |
| Hardware | Device, peripheral, and hardware-related problems. |
| Networking | Connectivity, network configuration, and routing problems. |
| Other | Technical observations that do not fit another category. |

Choose the most relevant category and link related journal entries or Issues. Category descriptions above can be copied directly when configuring Discussions.
