# flagger-k6-webhook

This image builds <https://github.com/grafana/flagger-k6-webhook> with custom overrides.

## Gcloud Build

```
gcloud builds submit --project kraken-v2-dev --config ./cloudbuild_flagger_k6.yml --substitutions='_PROJECT=kraken-v2-dev'
gcloud builds submit --project kraken-v2-prod --config ./cloudbuild_flagger_k6.yml --substitutions='_PROJECT=kraken-v2-prod'
```
