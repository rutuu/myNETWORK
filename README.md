# myNETWORK — LinkedIn Connection Journal

> A private, local-first CRM for your professional network. No accounts. No servers. Just a single HTML file.

[![Ko-fi](https://img.shields.io/badge/support%20this%20project-ko--fi-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/rutuenso9)
[![License: MIT](https://img.shields.io/badge/license-MIT-111111)](LICENSE)

[☕ Support on Ko-fi](https://ko-fi.com/rutuenso9) · [MIT License](LICENSE)

---

## What it does

LinkedIn connections are a black box — you can't search them, annotate them, or remember how you met half of them. myNETWORK fixes that.

- **Import** your LinkedIn `Connections.csv` — deduplication is automatic, notes are never overwritten on re-import
- **Write** how you met each person, add tags, and track context
- **Star** connections for seasonal greetings (New Year, Thanksgiving, Winter Holidays) and track outreach
- **Your data never leaves your device** — everything lives in a JSON file you download and reload

---

## How to use

1. Download [`linkedin-connections.html`](linkedin-connections.html)
2. Open it in any browser — no install, no build step
3. Import your LinkedIn CSV or add contacts manually
4. Hit **Save JSON** after each session to keep your data

**To get your LinkedIn CSV:**
Settings → Data Privacy → Get a copy of your data → Download larger data archive → Request archive

LinkedIn emails you a download link (can take up to 24 hours). Unzip and upload only `Connections.csv`.

---

## Try it first

Drop [`sample-connections.csv`](sample-connections.csv) into the import to see how it works before connecting your real data.

---

## Stack

Zero dependencies. One file. Vanilla HTML, CSS, and JavaScript.

Data persists via download/upload of a local `my-network.json` — nothing is stored in the browser.

---

## Built by

[Rutu Upadhyaya](https://www.linkedin.com/in/rutuupadhyaya/) · [enso9](https://enso9.com)

If this is useful to you, [buy me a coffee ☕](https://ko-fi.com/rutuenso9)

---

## License

MIT
