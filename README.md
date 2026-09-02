# StockPulse V1 Fixed Publication

Public-safe static publication for the separate StockPulse V1 Fixed Live Shadow experiment.

- Project: `stockpulse-v1-fixed`
- Status: `V1 Fixed · Live Shadow`
- Data source: read-only public projection only
- Reports: `reports/YYYY-MM-DD/{morning,evening}/`
- Lab: https://devsnack-blog.vercel.app/labs/stockpulse-v1-fixed

This repository does not contain private run evidence, raw prompts, credentials,
raw model artifacts, raw per-row predictions, or execution logs. It is separate
from the historical `stockpulse-publication` namespace.

## Structure

```text
index.html
reports/YYYY-MM-DD/morning/index.html
reports/YYYY-MM-DD/evening/index.html
data/{project,source-manifest,runs,evaluations,improvements,findings,metrics,publication,projection}.json
```

The publication is generated from a validated projection bundle. GitHub Pages is
the only publication target for this V1 Fixed lane. Telegram and historical V1
publication writes remain disabled.
