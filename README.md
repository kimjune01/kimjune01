## 64% merge rate · 1 streak (01:33 UTC)

```mermaid
sankey-beta
    triaged,    submitted,  82
    triaged,    throttled,  149
    triaged,    gate fail,  7
    submitted,  resolved,   14
    submitted,  dripped,    30
    submitted,  open,       38
    resolved,   merged,     9
    resolved,   closed,     5
```

*since 2026-05-09 (pipeline epoch)*

## Feed

- ✅ [jmpsec/osctrl#807](https://github.com/jmpsec/osctrl/pull/807) Fix OSX quick-enroll: stop osqueryd before unload
- ❌ [ggml-org/llama.cpp#22873](https://github.com/ggml-org/llama.cpp/pull/22873) server : fix n_predict=-2 (generate until context full)
- ❌ [dhonus/jellyfin-tui#192](https://github.com/dhonus/jellyfin-tui/pull/192) fix: reduce idle CPU usage with frame rate limiter
- ✅ [scverse/pertpy#965](https://github.com/scverse/pertpy/pull/965) Fix plot_multicomparison_fc ValueError with default figsize
- ✅ [azerty9971/xtend_tuya#930](https://github.com/azerty9971/xtend_tuya/pull/930) Fix battery device class ambiguity for generic sensors
- ❌ [kimjune01/speedygrad#1](https://github.com/kimjune01/speedygrad/pull/1) increase matvec MV_ROWS_PER_THREAD from 4 to 16
- ❌ [kimjune01/speedygrad#2](https://github.com/kimjune01/speedygrad/pull/2) onnx: data-driven generic parser for simple protobuf message
- ❌ [kimjune01/speedygrad#4](https://github.com/kimjune01/speedygrad/pull/4) llm: contiguous weights + rollout prune for quantized GGUF i
- ❌ [dapr/dapr#9924](https://github.com/dapr/dapr/pull/9924) refactor: simplify workflow concurrency config getters
- ✅ [apache/airflow#66686](https://github.com/apache/airflow/pull/66686) Fix FAB role deletion foreign key constraint violation

## 🚨⚠️AI Slop⚠️🚨
- [uptime-kuma#7371](https://github.com/louislam/uptime-kuma/pull/7371)
- [uptime-kuma#7372](https://github.com/louislam/uptime-kuma/pull/7372)
- [ruff#25066](https://github.com/astral-sh/ruff/pull/25066)
- [llama.cpp#22873](https://github.com/ggml-org/llama.cpp/pull/22873)
- [litestar#4755](https://github.com/litestar-org/litestar/pull/4755)

<details>
<summary>verify</summary>

```graphql
{ merged: search(query: "is:pr is:merged author:kimjune01 created:>2026-05-09", type: ISSUE) { issueCount }
  closed: search(query: "is:pr is:closed is:unmerged author:kimjune01 created:>2026-05-09", type: ISSUE) { issueCount } }
```

</details>

## Writing

[june.kim](https://june.kim)

---

Build in public. AGPL where it matters. Questions? june@june.kim
