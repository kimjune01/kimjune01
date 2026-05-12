## 46% merge rate · 53 merged · 40 repos · 🔥 3

```mermaid
sankey-beta
    triaged,    submitted, 242
    triaged,    queued,    110
    triaged,    evicted,    48
    submitted,  merged,     26
    submitted,  open,      186
    submitted,  closed,     30
```

```mermaid
xychart-beta
    title "PRs merged per day"
    x-axis ["05-09", "05-10", "05-11", "05-12"]
    y-axis "merged"
    bar [1, 5, 8, 12]
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
| ✅ | sqlpage/SQLPage | [#1284](https://github.com/sqlpage/SQLPage/pull/1284) Fix DuckDB :: casting warning |
| ✅ | cachix/secretspec | [#88](https://github.com/cachix/secretspec/pull/88) fix(test): portable command for empty-output test |
| ✅ | tach-org/tach | [#931](https://github.com/tach-org/tach/pull/931) fix: report syntax errors as errors, not warnings |
| ✅ | njbrake/agent-of-empires | [#1042](https://github.com/njbrake/agent-of-empires/pull/1042) refactor: remove dead claude.config_dir config field |
| ✅ | jmpsec/osctrl | [#810](https://github.com/jmpsec/osctrl/pull/810) Fix race condition in IncExecution and IncError |
| ✅ | JuliaDebug/Infiltrator.jl | [#176](https://github.com/JuliaDebug/Infiltrator.jl/pull/176) fix: dictionary key tab completion |
| ✅ | yrosseel/lavaan | [#551](https://github.com/yrosseel/lavaan/pull/551) Document 'icc' option in lavInspect help page |
| ✅ | IppClub/Dora-SSR | [#97](https://github.com/IppClub/Dora-SSR/pull/97) Fix: remove default always-on-top for runtime window |
| ✅ | aymericzip/intlayer | [#427](https://github.com/aymericzip/intlayer/pull/427) Fix logo animation positioning for RTL languages |
| ✅ | kubescape/kubescape | [#2076](https://github.com/kubescape/kubescape/pull/2076) fix: strip URI prefix before splitting in ReadResource |

## Leaderboard

*voluntary contributions to repos you don't own | non-owner only | [methodology](https://github.com/kimjune01/kimjune01)*

| contributor | merged | rate | repos |
|---|---|---|---|
| SAY-5 | 59 | 67% | 54 |
| kimjune01 | 53 | 46% | 40 |
| mvanhorn | 14 | 82% | 12 |
| ununununium | 12 | 70% | 10 |
| officialasishkumar | 5 | 71% | 4 |

[Join the leaderboard](https://github.com/kimjune01/sweep/blob/master/README.md) · [Protect your repo](https://github.com/kimjune01/sweep/blob/master/action.yml)

## AI SLOP

| PR | time to close | bugs | reason |
|---|---|---|---|
| [uptime-kuma#7371](https://github.com/louislam/uptime-kuma/pull/7371) | <1 min | 0 | cherry-picked |
| [uptime-kuma#7372](https://github.com/louislam/uptime-kuma/pull/7372) | <1 min | 0 | cherry-picked |
| [jellyfin-tui#194](https://github.com/dhonus/jellyfin-tui/pull/194) | 5 min | 0 | ai slop |
| [litestar#4755](https://github.com/litestar-org/litestar/pull/4755) | 7 hrs | 0 | closed per AI policy |
| [gherkin#589](https://github.com/cucumber/gherkin/pull/589) | 3 hrs | 0 | no human in the loop |
| [ruff#25066](https://github.com/astral-sh/ruff/pull/25066) | 2 days | 0 | mainly produced by AI |
| [llama.cpp#22873](https://github.com/ggml-org/llama.cpp/pull/22873) | 2 days | 1 | AI-generated PR detected |

[hypothesis graph](HYPOTHESIS_GRAPH.md)

---

[june.kim](https://june.kim) · AGPL where it matters
