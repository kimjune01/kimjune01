## 47% merge rate · 1 streak (06:03 UTC)

```mermaid
sankey-beta
    triaged,    submitted, 264
    triaged,    throttled, 182
    triaged,    rejected,  17
    submitted,  resolved,  38
    submitted,  dripped,   74
    submitted,  open,      152
    resolved,   merged,    18
    resolved,   closed,    20
```

```mermaid
xychart-beta
    title "PRs merged per day"
    x-axis ["05-09", "05-10", "05-11", "05-12"]
    y-axis "merged"
    bar [1, 5, 8, 4]
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
| ✅ | aymericzip/intlayer | [#427](https://github.com/aymericzip/intlayer/pull/427) Fix logo animation positioning for RTL langua |
| ❌ | dhonus/jellyfin-tui | [#193](https://github.com/dhonus/jellyfin-tui/pull/193) fix: reduce CPU usage with frame limiter |
| ✅ | kubescape/kubescape | [#2076](https://github.com/kubescape/kubescape/pull/2076) fix: strip URI prefix before splitting in Rea |
| ✅ | chojs23/concord | [#45](https://github.com/chojs23/concord/pull/45) fix: align cursor position with newline-aware |
| ❌ | immich-app/immich | [#28377](https://github.com/immich-app/immich/pull/28377) fix(web): add focus-visible outlines to sideb |
| ❌ | immich-app/immich | [#28375](https://github.com/immich-app/immich/pull/28375) fix(web): add focus-visible outlines to sideb |
| ✅ | rustledger/rustledger | [#1094](https://github.com/rustledger/rustledger/pull/1094) fix: swap gitleaks-action for standalone bina |
| ✅ | jmpsec/osctrl | [#807](https://github.com/jmpsec/osctrl/pull/807) Fix OSX quick-enroll: stop osqueryd before un |
| ❌ | ggml-org/llama.cpp | [#22873](https://github.com/ggml-org/llama.cpp/pull/22873) server : fix n_predict=-2 (generate until con |
| ❌ | dhonus/jellyfin-tui | [#192](https://github.com/dhonus/jellyfin-tui/pull/192) fix: reduce idle CPU usage with frame rate li |

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
