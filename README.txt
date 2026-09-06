# Acute Medicine PWA

This package converts the supplied **Acute Medicine Master Exact Prompt Library** into an installable Progressive Web App while preserving the curriculum/prompt text.

## Included
- Full Parts 0–28 exact prompt library
- Micro-bite completion tracking stored locally on the device
- Progress percentage and remaining count
- Continue from the last/next incomplete micro-bite
- Search across topics and prompts
- Copy Prompt and Copy + Open ChatGPT buttons
- Offline cache after first successful load
- iPhone/Android/desktop install support

## Important
A PWA must be served from **HTTPS** (or localhost during testing). Opening `index.html` directly as a local `file://` page will not enable installation/service-worker offline behavior.

## iPhone installation
1. Host this folder on an HTTPS website.
2. Open the URL in **Safari**.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Open **Acute Medicine** from the Home Screen thereafter.

Progress is stored in that installed app/browser profile on that device.
