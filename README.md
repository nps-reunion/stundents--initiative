# NPS Reconnect

A small website built by three students of the 10th batch (2023–24) at Nalgonda Public School, before everyone went their separate ways for higher studies. The idea was simple — a lot of classmates had left over the years, and nobody had a complete list of contacts. This was our attempt to fix that before it got too late.

---

## What it does

Visitors can submit their own contact number, and optionally add contacts of old classmates they've stayed in touch with. All submissions go into a Firebase Firestore database. The admin team then reviews them, verifies where possible, and builds a WhatsApp reunion group.

No accounts. No sign-ups. Just fill the form and submit.

---

## Pages / Sections

- **Hero** — landing with live stats (total contacts shared, number of contributors)
- **How It Works** — three-step explainer
- **Share a Contact** — the main submission form
- **About** — the story behind why this was built
- **Contact** — reach the team directly via WhatsApp, Telegram, or Instagram
- **Admin** — password-protected panel, restricted to the core team

---

## Tech used

- Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step
- **Firebase Firestore** (compat SDK v10.12.2) for storing submissions and reading live stats
- **Google Fonts** — DM Sans + Playfair Display

---

## Running it

No installation needed. Just open `index.html` in a browser.

If you want to host it, drop `index.html` on any static host — GitHub Pages, Netlify, Cloudflare Pages, whatever works.

---

## Project structure

```
index.html   ← the whole thing, self-contained
README.md    ← you're reading it
```

---

## The team

| Name | Role | Contact |
|---|---|---|
| Manikanta | Admin | [WhatsApp](https://wa.me/918328060866) · [@xliptan](https://instagram.com/xliptan) |
| Sspankco | Moderator | [Telegram](https://t.me/sspankcoreddy) · [@sspankcoreddy](https://instagram.com/sspankcoreddy) |
| Srikar | Moderator | [WhatsApp](https://wa.me/917670845855) · [@peruri_srikar](https://instagram.com/peruri_srikar) |

All data collected has full parental consent.

---

## Notes

- Submissions are private and only accessible to the admin team
- Friends' contacts are optional — submitting your own number alone is perfectly fine
- This is a one-time initiative tied to the 10th batch of 2023–24
