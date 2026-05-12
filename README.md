## 44% merge rate · 0 streak (09:13 UTC)

```mermaid
sankey-beta
    triaged,    submitted, 343
    triaged,    throttled, 136
    triaged,    rejected,  44
    submitted,  resolved,  47
    submitted,  dripped,   102
    submitted,  open,      194
    resolved,   merged,    21
    resolved,   closed,    26
```

```mermaid
xychart-beta
    title "PRs merged per day"
    x-axis ["05-09", "05-10", "05-11", "05-12"]
    y-axis "merged"
    bar [1, 5, 8, 7]
```

*since 2026-05-09T00:34:00Z (pipeline epoch)*

<details>
<summary>verify</summary>

```graphql
{ merged: search(query: "is:pr is:merged author:kimjune01 created:>2026-05-09T00:34:00Z", type: ISSUE) { issueCount }
  closed: search(query: "is:pr is:closed is:unmerged author:kimjune01 created:>2026-05-09T00:34:00Z", type: ISSUE) { issueCount } }
```

</details>

## Feed

| | repo | PR |
|---|------|----|
| ❌ | ggml-org/llama.cpp | [#22965](https://github.com/ggml-org/llama.cpp/pull/22965) server: fix n_predict=-2 (generate until cont |
| ❌ | cucumber/gherkin | [#589](https://github.com/cucumber/gherkin/pull/589) fix(c): segfault when one placeholder is a pr |
| ✅ | JuliaDebug/Infiltrator.jl | [#176](https://github.com/JuliaDebug/Infiltrator.jl/pull/176) fix: dictionary key tab completion |
| ❌ | dhonus/jellyfin-tui | [#194](https://github.com/dhonus/jellyfin-tui/pull/194) refactor: fix clippy warnings for code qualit |
| ✅ | yrosseel/lavaan | [#551](https://github.com/yrosseel/lavaan/pull/551) Document 'icc' option in lavInspect help page |
| ✅ | IppClub/Dora-SSR | [#97](https://github.com/IppClub/Dora-SSR/pull/97) Fix: remove default always-on-top behavior fo |
| ❌ | risingwavelabs/risingwave | [#25609](https://github.com/risingwavelabs/risingwave/pull/25609) fix: use full column subset for distinct agg  |
| ❌ | kanidm/kanidm | [#4337](https://github.com/kanidm/kanidm/pull/4337) Fix false positive permission warning for cac |
| ❌ | kubescape/kubescape | [#2097](https://github.com/kubescape/kubescape/pull/2097) fix: harden vulnerability manifest URI parsin |
| ✅ | aymericzip/intlayer | [#427](https://github.com/aymericzip/intlayer/pull/427) Fix logo animation positioning for RTL langua |

## Leaderboard

*voluntary contributions to repos you don't own | non-owner only | [methodology](https://github.com/kimjune01/kimjune01)*

| contributor | merged | rate | repos |
|---|---|---|---|
| SAY-5 | 59 | 67% | 54 |
| kimjune01 | 15 | 51% | 15 |
| mvanhorn | 14 | 82% | 12 |
| ununununium | 12 | 70% | 10 |
| officialasishkumar | 5 | 71% | 4 |

[Join the leaderboard](https://github.com/kimjune01/sweep/blob/master/README.md) · [Protect your repo](https://github.com/kimjune01/sweep/blob/master/action.yml)

## AI SLOP

| PR | time to close | bugs | title |
|---|---|---|---|
| [uptime-kuma#7371](https://github.com/louislam/uptime-kuma/pull/7371) | <1 min | 0 | 🚨⚠️AI Slop⚠️🚨 cherry-picked |
| [uptime-kuma#7372](https://github.com/louislam/uptime-kuma/pull/7372) | <1 min | 0 | 🚨⚠️AI Slop⚠️🚨 cherry-picked |
| [litestar#4755](https://github.com/litestar-org/litestar/pull/4755) | 7 hrs | 0 | closed per AI policy |
| [ruff#25066](https://github.com/astral-sh/ruff/pull/25066) | 2 days | 0 | mainly produced by AI |
| [llama.cpp#22873](https://github.com/ggml-org/llama.cpp/pull/22873) | 2 days | 1 | AI-generated PR detected |

[hypothesis graph](HYPOTHESIS_GRAPH.md)

---

[june.kim](https://june.kim) · AGPL where it matters
