<div align="center">

# hello-micro-tools

**A 90-day challenge: ship one small tool at a time, one commit every day.**

<img alt="Challenge" src="https://img.shields.io/badge/challenge-90%20days-black?style=flat-square">
<img alt="Started" src="https://img.shields.io/badge/started-2026--10--01-blue?style=flat-square">
<img alt="Streak" src="https://img.shields.io/badge/streak-16%20days%20unbroken-22c55e?style=flat-square">
<img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-blue?style=flat-square">

</div>

---

## The challenge

Started **2026-10-01**, running for **90 days** until **2026-12-29**.

**The rules I set for myself:**

1. One commit every day, for 90 days straight.
2. Each project must actually deploy — a public URL, not a local build.
3. Keep the scope small enough to finish. A finished small thing beats an unfinished big one.
4. Write down what broke, not just what worked.

This repository is the **hub**. Each day's real work lives in its own repository, linked below.

> **A note on the day numbers.** Day *N* is the *N*-th calendar day since 2026-10-01 (so
> Day 16 is 2026-10-16). An earlier version of this table counted by "ship" instead of by
> date, which put Day 8 on 2026-10-09 and left 2026-10-08 unlisted — even though that day
> had a commit. The rows below are now keyed to the actual commit dates, so a reader can
> check any row against `git log`.

## What has shipped

| Project | What it is | Live |
| --- | --- | --- |
| [my-first-tool](https://github.com/anhaoXie/my-first-tool) | The first Next.js app — built to prove the write → build → deploy loop end to end | [demo](https://my-first-tool-six.vercel.app) |
| [visa-photo-tool](https://github.com/anhaoXie/visa-photo-tool) | Crops a selfie into a pixel-exact, officially-sized visa / passport photo, entirely in the browser | [demo](https://visa.anhaoxie.com) |
| [may-first-website](https://github.com/anhaoXie/may-first-website) | The first web page I ever wrote — one HTML file, CSS in a `<style>` tag, zero dependencies | [Pages](https://anhaoxie.github.io/may-first-website/) |
| [kaggle-journey](https://github.com/anhaoXie/kaggle-journey) | A Kaggle log written the same day, including a full data-leakage post-mortem | — |
| [dsh-client-ui-zero-friction](https://github.com/anhaoXie/dsh-client-ui-zero-friction) | A single-input, zero-friction client plugin for DeepSeek Harness | — |
| [ai-frontier](https://github.com/anhaoXie/ai-frontier) | Daily AI radar: 20 public sources, deduped and scored, into an Excel sheet plus a written digest. No API keys | — |
| [hr-radar](https://github.com/anhaoXie/hr-radar) | Industry demand radar for students: real postings → skill demand, pay bands, gaps, and what to learn first | — |
| [videonote](https://github.com/anhaoXie/videonote) | Offline video-study workbench: ASR → scene analysis → notes → subtitles, plus sentence-by-sentence pronunciation scoring | — |
| [3dgs-cpu-port](https://github.com/anhaoXie/3dgs-cpu-port) | 3D Gaussian Splatting reproduced end-to-end on a machine with no NVIDIA GPU — official code byte-for-byte unchanged | — |
| [airllm-lab](https://github.com/anhaoXie/airllm-lab) | Running AirLLM on a Windows laptop with no discrete GPU: how it works, what it actually measures, and the cloud fallback | — |

## Progress log

Every row below corresponds to a real commit. Dates are the actual commit dates.

| Day | Date | Shipped |
| --- | --- | --- |
| 1 | 2026-10-01 | Challenge starts — this repository is created |
| 2 | 2026-10-02 | [my-first-tool](https://github.com/anhaoXie/my-first-tool) — first Next.js app, deployed to Vercel |
| 3 | 2026-10-03 | Rest day — README polish, kept the streak alive |
| 4 | 2026-10-04 | [visa-photo-tool](https://github.com/anhaoXie/visa-photo-tool) — product draft v0.1 + homepage skeleton |
| 5 | 2026-10-05 | Visa photo tool — working canvas crop and download |
| 6 | 2026-10-06 | Visa photo tool — bound the custom domain `visa.anhaoxie.com` |
| 7 | 2026-10-07 | Visa photo tool — face-alignment oval guide |
| 8 | 2026-10-08 | Groundwork on the software-testing contest, then caught in it — see Day 11 |
| 9 | 2026-10-09 | Visa photo tool — client-side background removal spike (`@imgly/background-removal`) |
| 10 | 2026-10-10 | Visa photo tool — AI background removal integrated into the main tool (beta) |
| 11 | 2026-10-11 | Contest prep on R006 / R007 — **and I got stuck.** Two commits, both saying so |
| 12 | 2026-10-12 | Contest prep, R007 practice — still unfinished. Logged rather than hidden |
| 13 | 2026-10-13 | [dsh-client-ui-zero-friction](https://github.com/anhaoXie/dsh-client-ui-zero-friction) and [ai-frontier](https://github.com/anhaoXie/ai-frontier); plus a README / LICENSE / metadata pass across the six repos that existed then |
| 14 | 2026-10-14 | [hr-radar](https://github.com/anhaoXie/hr-radar) v1.0. Also 9 commits on a God's Eye View fork: five-language UI, a global hazard layer (GDACS / USGS / NWS / NASA EONET), event cards, weather-tile sharpness, and a marker-occlusion fix |
| 15 | 2026-10-15 | [videonote](https://github.com/anhaoXie/videonote) v0.3.0 → v0.4.0 — unified SM-2 review queue (sentence + word cards), speaker-aware sentence splitting, three reported UI bugs fixed, MIT license |
| 16 | 2026-10-16 | [3dgs-cpu-port](https://github.com/anhaoXie/3dgs-cpu-port) — 3DGS reproduced with no GPU, official code unchanged — and [airllm-lab](https://github.com/anhaoXie/airllm-lab) |

## What I've learned so far

- **Deploying on day 2 instead of day 20 was the right call.** The deploy loop is the scary
  part; once it is boring, the building gets easier.
- **A hard scope cut is a feature.** `visa-photo-tool`'s v1 deliberately excludes accounts,
  payments, printing and batch processing. The draft that says so is committed in
  [`PRODUCT.md`](https://github.com/anhaoXie/visa-photo-tool/blob/main/PRODUCT.md).
- **"Works on my machine" is not the milestone.** A public URL is.
- **Some days you get stuck, and the log should say so.** Days 11 and 12 are stuck days and
  they are still in the table. A streak of clean days would mean I was only writing down the
  wins.
- **A constraint can be the interesting part.** The most valuable thing I built was built
  *because* this laptop has no NVIDIA GPU — not in spite of it.

## Follow along

The streak is still running. Watch this repository, or check the
[commit history](https://github.com/anhaoXie/hello-micro-tools/commits/main).

## License

[MIT](LICENSE) © anhaoXie
