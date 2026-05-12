# June Kim

## 15 merged across 15 repos — 27% merge rate (01:13 UTC)

```mermaid
sankey-beta
    triaged, qa_passed, 44
    triaged, gate_fail, 7
    qa_passed, dripped, 28
    qa_passed, org_blocked, 16
    dripped, merged, 15
    dripped, closed, 40
```

```graphql
{ merged: search(query: "is:pr is:merged author:kimjune01 created:>2026-04-11", type: ISSUE) { issueCount }
  closed: search(query: "is:pr is:closed is:unmerged author:kimjune01 created:>2026-04-11", type: ISSUE) { issueCount } }
```

## Writing

[june.kim](https://june.kim)

## Day job

Research engineer at EA — AI agents that play games on real consoles, detect bugs, report them through an event pipeline.

---

Build in public. AGPL where it matters. Questions? june@june.kim
