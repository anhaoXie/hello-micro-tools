<div align="center">

# hello-micro-tools

**A 90-day challenge: ship one small tool at a time, one commit every day.**

<img alt="Challenge" src="https://img.shields.io/badge/challenge-90%20days-black?style=flat-square">
<img alt="Started" src="https://img.shields.io/badge/started-2026--10--01-blue?style=flat-square">
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

## What has shipped

| Project | What it is | Live |
| --- | --- | --- |
| [my-first-tool](https://github.com/anhaoXie/my-first-tool) | The first Next.js app — built to prove the write → build → deploy loop end to end | [demo](https://my-first-tool-six.vercel.app) |
| [visa-photo-tool](https://github.com/anhaoXie/visa-photo-tool) | Crops a selfie into a pixel-exact, officially-sized visa / passport photo, entirely in the browser | [demo](https://visa.anhaoxie.com) |

## Progress log

Every row below corresponds to a real commit. Dates are the actual commit dates.

| Day | Date | Shipped |
| --- | --- | --- |
| 1 | 2026-10-01 | Challenge starts — this repository is created |
| 2 | 2026-10-02 | [my-first-tool](https://github.com/anhaoXie/my-first-tool) — first Next.js app, deployed to Vercel |
| 3 | 2026-10-03 | Rest day — kept the streak alive |
| 4 | 2026-10-04 | [visa-photo-tool](https://github.com/anhaoXie/visa-photo-tool) — product draft v0.1 + homepage skeleton |
| 5 | 2026-10-05 | Visa photo tool — working canvas crop and download |
| 6 | 2026-10-06 | Visa photo tool — bound the custom domain `visa.anhaoxie.com` |
| 7 | 2026-10-07 | Visa photo tool — face-alignment oval guide |
| 8 | 2026-10-09 | Visa photo tool — client-side background removal spike (`@imgly/background-removal`) |
| 9 | 2026-10-10 | Visa photo tool — AI background removal integrated into the main tool (beta) |

## What I've learned so far

- **Deploying on day 2 instead of day 20 was the right call.** The deploy loop is the scary
  part; once it is boring, the building gets easier.
- **A hard scope cut is a feature.** `visa-photo-tool`'s v1 deliberately excludes accounts,
  payments, printing and batch processing. The draft that says so is committed in
  [`PRODUCT.md`](https://github.com/anhaoXie/visa-photo-tool/blob/main/PRODUCT.md).
- **"Works on my machine" is not the milestone.** A public URL is.

## Follow along

The streak is still running. Watch this repository, or check the
[commit history](https://github.com/anhaoXie/hello-micro-tools/commits/main).

## License

[MIT](LICENSE) © anhaoXie
