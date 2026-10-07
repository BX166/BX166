# AICraft

One OpenAI-compatible endpoint, reachable from mainland China and from outside it.

Site and docs — <https://aicraftapi.com>
Contact — contact@aicraftapi.com

## Getting the model list

`GET /v1/models` with your key returns the ids your key can actually call. Use that list rather than a table copied from anywhere, ours included — it changes.

```bash
curl https://aicraftapi.com/v1/models \
  -H "Authorization: Bearer $AICRAFT_API_KEY"
```

## In the community

- **Codewhale** — contributed the AICraft provider row and its documentation upstream, and keeps the model catalog in [issue #6304](https://github.com/codewhale-hq/Codewhale/issues/6304) current. Credited in `docs/CONTRIBUTORS.md`.
- **[china-llm-gateway](https://github.com/BX166/china-llm-gateway)** — notes on calling Chinese model APIs from outside China.
- **[aicraft-api-samples](https://github.com/BX166/aicraft-api-samples)** — minimal runnable examples.
