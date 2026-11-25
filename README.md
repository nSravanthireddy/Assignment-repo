# Chromium Canary Submission — Sravanthi (@sravanthi-25-Nakka)

## 1. Loom Walkthrough Video
* **Video URL:** [Watch 5-Minute Walkthrough](https://www.loom.com/share/YOUR_VIDEO_ID)

## 2. Build Info
* **Chromium Commit ID (`git rev-parse HEAD`):** `<40-character id>`
* **Target Built:** `chrome` (or `content_shell`)
* **My Laptop OS & RAM:** `<e.g., Ubuntu 24.04, 16GB RAM>`

## 3. Architecture Notes
* **Feature A (`X-Candidate-Canary` header):** <2-3 sentences in your own words: which process runs the throttle, and how the flag value reached it from the Browser process.>
* **Feature B (`[CANARY_ACK]` console hook):** <1-2 sentences: where in Blink console.warn is caught, and which process that is.>

## 4. AI Agent Workflow
* **AI Tool & Model Used:** `<tool and model>`
* **How I Used Sub-Agents:** <2-3 sentences on how you split the codebase search.>

## Extras
* `demo.html` is a small local page used in the video to trigger `console.warn("canary-ping")` and to fetch `https://httpbin.org/headers`.
