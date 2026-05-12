## 46% merge rate · 2 streak (03:50 UTC)

```mermaid
sankey-beta
    triaged,    submitted, 182
    triaged,    throttled, 133
    triaged,    rejected,  11
    submitted,  resolved,  32
    submitted,  dripped,   40
    submitted,  open,      110
    resolved,   merged,    15
    resolved,   closed,    17
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
| ✅ | rustledger/rustledger | [#1094](https://github.com/rustledger/rustledger/pull/1094) fix: swap gitleaks-action for standalone bina |
| ✅ | jmpsec/osctrl | [#807](https://github.com/jmpsec/osctrl/pull/807) Fix OSX quick-enroll: stop osqueryd before un |
| ❌ | ggml-org/llama.cpp | [#22873](https://github.com/ggml-org/llama.cpp/pull/22873) server : fix n_predict=-2 (generate until con |
| ❌ | dhonus/jellyfin-tui | [#192](https://github.com/dhonus/jellyfin-tui/pull/192) fix: reduce idle CPU usage with frame rate li |
| ✅ | scverse/pertpy | [#965](https://github.com/scverse/pertpy/pull/965) Fix plot_multicomparison_fc ValueError with d |
| ✅ | azerty9971/xtend_tuya | [#930](https://github.com/azerty9971/xtend_tuya/pull/930) Fix battery device class ambiguity for generi |
| ❌ | dapr/dapr | [#9924](https://github.com/dapr/dapr/pull/9924) refactor: simplify workflow concurrency confi |
| ✅ | apache/airflow | [#66686](https://github.com/apache/airflow/pull/66686) Fix FAB role deletion foreign key constraint  |
| ❌ | astral-sh/ruff | [#25066](https://github.com/astral-sh/ruff/pull/25066) [flake8-todos] Recognize Jira-style issue IDs |
| ✅ | antonmedv/fx | [#414](https://github.com/antonmedv/fx/pull/414) Fix file argument detection when stdin is /de |

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
