# 2026+ Release schedule

This is a draft to be presented on the next Steering Working Group in September

## 2026/27 Timeline

| Version | Jun 26 | Jul | Aug | Sep | Oct | Nov | Dec | Jan 27 | Feb | Mar | Apr | May | Jun | Jul |
|--------------|--------|-----|-----|-----|-----|-----|-----|--------|-----|-----|-----|-----|-----|--------|
| **CDM 5**    | ⬜      | | | | | | |        | | | | | |        | |
| **CDM 6**    | 🟩     | 🟧 | 🟧 | 🟧 | 🟧 | 🟧 | 🟧 | 🟧     | 🟧 | 🟧 | 🟧 | 🟧 | 🟧 | ⬜      | 
| **CDM 7**    | 🟦     | 🟩 | 🟩 | 🟩 | 🟩 | 🟩 | 🟩 | 🟩     | 🟩 | 🟩 | 🟩 | 🟩 | 🟩 | 🟧     |
| **CDM 8**    |        | 🟦 | 🟦 | 🟦| 🟦 | 🟦 | 🟦 | 🟦     | 🟦 | 🟦 | 🟦 | 🟦 | 🟦 | 🟩     |
| **CDM 9**    |        | | |  |  |  |  |        |  |   |  |  |  | 🟦     |

See definitions below.

## 2026/27 Timeline

## 2026/27 Timeline

```mermaid
%%{init: {'theme':'base','themeVariables':{'taskTextColor':'#ffffff','activeTaskBkgColor':'#3b82f6','activeTaskBorderColor':'#2563eb','taskBkgColor':'#22c55e','taskBorderColor':'#16a34a','critBkgColor':'#f59e0b','critBorderColor':'#d97706','doneTaskBkgColor':'#94a3b8','doneTaskBorderColor':'#64748b','gridColor':'#e2e8f0'},'gantt':{'displayMode':'compact','barHeight':34,'barGap':6,'leftPadding':80}}}%%
gantt
    title CDM Version Lifecycle 2026/27
    dateFormat YYYY-MM-DD
    axisFormat %b %y

    section CDM 5
    EOL         :done, 2026-06-01, 2026-07-01

    section CDM 6
    Current     :2026-06-01, 2026-07-01
    Maintenance :crit, 2026-07-01, 2027-07-01
    EOL         :done, 2027-07-01, 2027-08-01

    section CDM 7
    Preview     :active, 2026-06-01, 2026-07-01
    Current     :2026-07-01, 2027-07-01
    Maintenance :crit, 2027-07-01, 2027-08-01

    section CDM 8
    Preview     :active, 2026-07-01, 2027-07-01
    Current     :2027-07-01, 2027-08-01

    section CDM 9
    Preview     :active, 2027-07-01, 2027-08-01
```

**Legend:** 🟦 Preview · 🟩 Current · 🟧 Maintenance · ⬜ End of life

**Legend:** 🟦 Preview · 🟩 Current · 🟧 Maintenance · ⬜ End of life

# Release States

Release states are defined as follows:
* 🟦 Development – versions that include new designs from the “main” branch that are still under development.  All tests must pass but the model may continue to evolve before being released into production.
* 🟩 Production - the "latest and greatest" stable version that ideally everyone should upgrade to, and where enhancements compatible with the existing models will be included. We should aim for a release to be in Production for around a year if we can, to alleviate upgrade costs to consumers. 
* 🟧 Maintenance – when a new Production version is released then the current Production will go into Maintenance. Only critical bug fixes and changes related to critical regulatory requirements should be ported to Maintenance releases. Otherwise, functional changes would not be ported to maintenance releases.  The intention would be to have only 1 version at a time in maintenance, so each time a new Production version drops, the previous Maintenance release would go to Unsupported.
* ⬜ Unsupported/End of Life – There will be no bug fixes or other support for the version.  TBD: We may perform security scans on some more recent unsupported versions and report any identified vulnerabilities, but will not perform security remediations.

  
At any point we want a maximum of one centrally supported development version, one production version, and one maintenance version.

