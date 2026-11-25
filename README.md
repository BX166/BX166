# AICraft

One OpenAI-compatible endpoint, reachable from mainland China and from outside it.

International site and docs — <https://aicraftapi.net>
Domestic site (mainland China) — <https://aicraftapi.com>
Contact — contact@aicraftapi.com

## Getting the model list

`GET /v1/models` with your key returns the ids your key can actually call. Use that list rather than a table copied from anywhere, ours included — it changes.

```bash
curl https://aicraftapi.net/v1/models \
  -H "Authorization: Bearer $AICRAFT_API_KEY"
```

## In the community

- **models.dev** — the AICraft provider entry is proposed in [PR #10219](https://github.com/anomalyco/models.dev/pull/10219) (open), built from the published catalog and pricing.
- **[china-llm-gateway](https://github.com/BX166/china-llm-gateway)** — notes on calling Chinese model APIs from outside China.
- **[aicraft-api-samples](https://github.com/BX166/aicraft-api-samples)** — minimal runnable examples.
