# HTTP Stoic Statuses

**`http-stoic-statuses`** is a metaphysical error-handling layer for APIs, websites, and machines that deserve better than a mere number. Instead of dry HTTP responses, this project returns meaningful, philosophical Latin reflections depending on the status code – all from the point of view of a chosen ancient thinker.

> Because sometimes, *404 Not Found* just isn't enough.

---

## Philosophers

Choose your responder:

- **Seneca (the Younger)** — Stoic calm, sorrow-tinged reason.
- **Diogenes** — Cynical, mocking, sharp-tongued truth.
- **Plotinus** — Mystical abstraction and cosmic vibes.

(*Nietzsche plugin currently in testing — handle with care.*)

---

## Supported Status Codes

Each status has unique responses per philosopher:

- `200 OK` — *Actum est.* / *It is done.*
- `403 Forbidden` – *Scimus te. Et tamen: non.* / *We know you. And yet: no.*
- `404 Not Found` – *Inquiris quod non est.* / *You seek what is not.*
- `418 I'm a Teapot` – *Amphora sum, non machina.* / *I am a jug, not a machine.*
- `500 Internal Server Error` - *Chaos regnat intra.* / *Chaos reigns within.*

See all in the [json file](./statuses.json)...

---

## Format

All definitions are stored in a single eternal `json` file:

- Structured by philosopher, code, and tone
- Ready for use in:
  - API middleware
  - Static site error handling
  - DevOps status dashboards
  - Marble engraving tools (experimental)

---

## Usage Ideas

- `curl -i --philosopher=diogenes https://your.api/endpoint`
- `fortune | http-stoic-statuses`
- Custom error pages in Latin with full philosophical context
- Poster printing, tattoo planning, daily contemplation

---

## Blessing

> **miraculum operatur**

If it works — and you don't know why — it belongs here.

---

## License

Open-source, obviously. But engraved in stone, spiritually.

---

Happy requesting. May your packets find meaning.

