# myNETWORK — LinkedIn Connection Journal

> A private, local-first CRM for your professional network. No accounts. No servers. Just a single HTML file.

[![Ko-fi](https://img.shields.io/badge/support%20this%20project-ko--fi-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/rutuenso9)
[![License: MIT](https://img.shields.io/badge/license-MIT-111111)](LICENSE)

[☕ Support on Ko-fi](https://ko-fi.com/rutuenso9) · [MIT License](LICENSE)

---

## What it does

LinkedIn connections are a black box. You can't search them, annotate them, or remember how you met half of them. myNETWORK fixes that.

- **Import** your LinkedIn `Connections.csv` — deduplication is automatic, notes are never overwritten on re-import
- **Write** how you met each person, add tags, and track context
- **Star** connections for seasonal greetings (New Year, Thanksgiving, Winter Holidays) and track outreach
- **Your data never leaves your device** — everything lives in a JSON file you download and reload

---

## How to use

**First time**

1. Download [`linkedin-connections.html`](linkedin-connections.html)
2. Open it in any browser — no install, no build step
3. Click **Import CSV** and upload your `Connections.csv` from LinkedIn
4. Add notes and tags to your contacts
5. Hit **Save JSON** before closing — this downloads `my-network.json` with all your data

**Returning**

1. Open the app and click **Load JSON** to restore your contacts, notes, and tags
2. Pick up where you left off

**Adding new connections later**

Click **Add New CSV** after loading your JSON. Only new contacts are added. Your existing notes and tags are never overwritten.

**To get your LinkedIn CSV:**
LinkedIn Settings → Data Privacy → Download your data → Download larger data archive → Request archive

LinkedIn emails you a download link (can take up to 24 hours). Unzip and upload only `Connections.csv`.

---

## Try it first

Drop [`sample-connections.csv`](sample-connections.csv) into the import to see how it works before connecting your real data.

---

## Stack

Zero dependencies. One file. Vanilla HTML, CSS, and JavaScript.

Data persists via download/upload of a local `my-network.json`. Nothing is stored in the browser.

---

## Built by

[Rutu Upadhyaya](https://www.linkedin.com/in/rutuupadhyaya/) · [enso9](https://enso9.com)

If this is useful to you, [buy me a coffee ☕](https://ko-fi.com/rutuenso9)

---

## License

MIT
