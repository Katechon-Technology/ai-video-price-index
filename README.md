# AI video price index

Dated list prices in **USD per second** for 20 text-to-video models (Seedance, Kling, Veo, Wan, MiniMax, Grok Imagine, Vidu, Luma, LTX, PixVerse, Gemini Omni), all quoted from **one provider on one day** so they are comparable.

- **As of:** 2026-10-17
- **Provider:** [Atlas Cloud](https://www.atlascloud.ai/models) list prices
- **Web version:** <https://arc.katechon.technology/ai-video-price-index>
- **Data:** [`data/ai-video-prices.csv`](data/ai-video-prices.csv) · [`data/ai-video-prices.json`](data/ai-video-prices.json) · raw quote file [`data/raw-2026-10-17.json`](data/raw-2026-10-17.json)
- **License:** [CC BY 4.0](LICENSE)

## Prices per second, 2026-10-17

Atlas Cloud list prices, text-to-video, 16:9, USD. "Audio on" is the only price when a model has no audio switch.

| Model | Maker | Resolution | USD/s (audio on, or only price) | USD/s (audio off) | Quoted clip | Atlas model ID |
|---|---|---|---|---|---|---|
| Seedance 2.5 | ByteDance | 720p | $0.377 | $0.377 | $3.77 / 10 s | `bytedance/seedance-2.5/text-to-video` |
| Seedance 2.5 | ByteDance | 1080p | $0.742 | $0.742 | $7.42 / 10 s | `bytedance/seedance-2.5/text-to-video` |
| Seedance 2.0 | ByteDance | 720p | $0.243 | $0.243 | $2.43 / 10 s | `bytedance/seedance-2.0/text-to-video` |
| Seedance 2.0 | ByteDance | 1080p | $0.547 | $0.547 | $5.47 / 10 s | `bytedance/seedance-2.0/text-to-video` |
| Seedance 2.0 Fast | ByteDance | 720p | $0.194 | $0.194 | $1.94 / 10 s | `bytedance/seedance-2.0-fast/text-to-video` |
| Seedance 2.0 Mini | ByteDance | 720p | $0.121 | $0.121 | $1.21 / 10 s | `bytedance/seedance-2.0-mini/text-to-video` |
| Kling 3.0 Pro | Kuaishou | fixed | $0.168 | $0.112 | $1.68 / 10 s | `kwaivgi/kling-v3.0-pro/text-to-video` |
| Kling 3.0 Standard | Kuaishou | fixed | $0.126 | $0.084 | $1.26 / 10 s | `kwaivgi/kling-v3.0-std/text-to-video` |
| Kling 3.0 Turbo | Kuaishou | 720p | $0.112 | — | $1.12 / 10 s | `kwaivgi/kling-v3.0-turbo/text-to-video` |
| Kling 3.0 Turbo | Kuaishou | 1080p | $0.140 | — | $1.40 / 10 s | `kwaivgi/kling-v3.0-turbo/text-to-video` |
| Veo 3.1 | Google | 720p | $0.400 | $0.200 | $3.20 / 8 s | `google/veo3.1/text-to-video` |
| Veo 3.1 | Google | 1080p | $0.400 | $0.200 | $3.20 / 8 s | `google/veo3.1/text-to-video` |
| Veo 3.1 Fast | Google | 720p | $0.096 | $0.080 | $0.77 / 8 s | `google/veo3.1-fast/text-to-video` |
| Veo 3.1 Fast | Google | 1080p | $0.120 | $0.100 | $0.96 / 8 s | `google/veo3.1-fast/text-to-video` |
| Veo 3.1 Lite | Google | 720p | $0.050 | — | $0.40 / 8 s | `google/veo3.1-lite/text-to-video` |
| Veo 3.1 Lite | Google | 1080p | $0.080 | — | $0.64 / 8 s | `google/veo3.1-lite/text-to-video` |
| Wan 3.0 | Alibaba | 720p | $0.100 | $0.100 | $1.00 / 10 s | `alibaba/wan-3.0/text-to-video` |
| Wan 3.0 | Alibaba | 1080p | $0.200 | $0.200 | $2.00 / 10 s | `alibaba/wan-3.0/text-to-video` |
| Wan 3.0 Prime | Alibaba | 720p | $0.140 | $0.140 | $1.40 / 10 s | `alibaba/wan-3.0-prime/text-to-video` |
| Wan 3.0 Prime | Alibaba | 1080p | $0.280 | $0.280 | $2.80 / 10 s | `alibaba/wan-3.0-prime/text-to-video` |
| MiniMax H3 | MiniMax | 768p | $0.080 | — | $0.80 / 10 s | `minimax/h3/text-to-video` |
| MiniMax H3 Max | MiniMax | 768p | $0.080 | — | $0.80 / 10 s | `minimax/h3-max/text-to-video` |
| Grok Imagine Video 1.5 | xAI | 720p | $0.140 | — | $1.40 / 10 s | `xai/grok-imagine-video-v1.5/text-to-video` |
| Grok Imagine Video 1.5 | xAI | 1080p | $0.250 | — | $2.50 / 10 s | `xai/grok-imagine-video-v1.5/text-to-video` |
| Vidu Q3 Pro | Vidu | 720p | $0.125 | $0.125 | $1.25 / 10 s | `vidu/q3-pro/text-to-video` |
| Vidu Q3 Pro | Vidu | 1080p | $0.150 | $0.150 | $1.50 / 10 s | `vidu/q3-pro/text-to-video` |
| Luma Ray 3.2 | Luma | 720p | $0.099 | — | $0.99 / 10 s | `luma/ray-3.2/text-to-video` |
| Luma Ray 3.2 | Luma | 1080p | $0.396 | — | $3.96 / 10 s | `luma/ray-3.2/text-to-video` |
| LTX 2.5 Pro | Lightricks | 720p | $0.132 | $0.132 | $1.32 / 10 s | `ltx/ltx-2.5-pro/text-to-video` |
| LTX 2.5 Pro | Lightricks | 1080p | $0.187 | $0.187 | $1.87 / 10 s | `ltx/ltx-2.5-pro/text-to-video` |
| PixVerse V6 | PixVerse | 720p | $0.060 | $0.045 | $0.60 / 10 s | `pixverse/v6/text-to-video` |
| PixVerse V6 | PixVerse | 1080p | $0.115 | $0.090 | $1.15 / 10 s | `pixverse/v6/text-to-video` |
| Gemini Omni Flash | Google | 720p | $0.125 | — | $1.25 / 10 s | `google/gemini-omni-flash/text-to-video` |

"—" means the model has no audio switch, so one price applies. "fixed" means the model takes no resolution parameter.

## What the numbers say (2026-10-17)

- **Cheapest at 720p:** PixVerse V6 at $0.045 per second (audio off). **Most expensive at 720p:** Veo 3.1 at $0.400 per second with audio.
- **Seedance 2.0** lists at $0.243/s at 720p and $0.547/s at 1080p; **Seedance 2.0 Mini** $0.121/s and **Seedance 2.0 Fast** $0.194/s at 720p; **Seedance 2.5** $0.377/s at 720p and $0.742/s at 1080p.
- **Audio changes the price** on Kling 3.0 Pro, Kling 3.0 Standard, Veo 3.1, Veo 3.1 Fast and PixVerse V6 (Veo 3.1: $0.400/s with audio, $0.200/s without). It is free on the Seedance models, Wan 3.0, Wan 3.0 Prime, Vidu Q3 Pro and LTX 2.5 Pro.
- **720p to 1080p** multiplies the price by 1.00x (Veo 3.1) to 4.00x (Luma Ray 3.2), depending on the model.

## Method

For each model we send a text-to-video request body to Atlas Cloud's calculate endpoint (`POST https://api.atlascloud.ai/api/v1/model/calculate`). It prices a request **without running it**, so nothing is generated or billed. Every quote uses the same prompt ("A lighthouse on a cliff at dusk, waves below."), a 16:9 aspect ratio and the clip length shown (10 seconds, or 8 seconds for Veo, whose lengths are 4, 6 and 8). Models that take an audio switch are quoted with it on and off. We record the **list price** (`origin_price`) the endpoint returns and divide by the clip length to get USD per second. Seedance is billed by video tokens, which scale linearly with length, so per-second figures hold across lengths. Model IDs are the ones in Atlas Cloud's public [model catalog](https://www.atlascloud.ai/models).

**Caveats**

- These are list prices from one provider. Atlas offers account-level discounts on some models, and other providers (the model makers' own APIs, fal, Replicate and others) charge differently. If a number here disagrees with the provider's own page, the provider's page wins.
- Image-to-video and reference-to-video can price differently from text-to-video. For example, our own account's reference-to-video quote for Seedance 2.0 Fast at 720p, 9:16, was about $0.058/s on 2026-10-16; see the [Seedance prompt guide](https://github.com/Katechon-Technology/seedance-prompt-guide/blob/main/guides/seedance-prompting-field-guide.md#prices-we-measured).
- Cheaper models exist at lower resolutions and outside this index.

## Columns

| Column | Meaning |
|---|---|
| `as_of` | Quote date (YYYY-MM-DD) |
| `model`, `maker` | Display name and model maker |
| `atlas_model_id` | Model ID in Atlas Cloud's catalog |
| `resolution` | Requested resolution, or `fixed` when the model takes none |
| `quoted_seconds` | Clip length that was quoted |
| `usd_quoted_clip` / `usd_quoted_clip_audio_off` | List price for the whole clip, with audio on (or the only price) and off; empty when there is no audio switch |
| `usd_per_second` / `usd_per_second_audio_off` | The clip price divided by `quoted_seconds` |
| `has_audio_switch` | Whether the model takes an audio on/off parameter |
| `mode`, `aspect_ratio`, `price_type`, `provider` | Constant for this snapshot: text-to-video, 16:9, list price, Atlas Cloud |

## Refresh schedule

The index is re-quoted at least once a month and whenever a listed model changes price. Each refresh adds a new `data/raw-YYYY-MM-DD.json` and rewrites the CSV and JSON, so the git history is the price history.

## Cite

Katechon, *AI video price index* (2026-10-17), <https://arc.katechon.technology/ai-video-price-index>, CC BY 4.0. See [CITATION.cff](CITATION.cff).

## About

Published by [Katechon](https://katechon.technology), which makes [Katechon Arc](https://arc.katechon.technology) (an AI studio for short dramas and video ads) and [Cast](https://cast.katechon.technology) (an AI character video app). Both run on models in this index; we publish the numbers because we needed them ourselves.
