# Παιδικές Εκδηλώσεις

Αυτό το repo περιέχει **μόνο** τα δημοσιευμένα αρχεία που σερβίρει το GitHub Pages
(https://glogiotatidis.github.io/kids-events/). Παράγονται αυτόματα από το pipeline των
πηγών — μην τα επεξεργάζεσαι με το χέρι εδώ.

- `index.html` — η σελίδα (αυτόνομη· κουβαλά και inline τα δεδομένα)
- `data.json` — ολόκληρο το dataset σε JSON (schema v1): `generated_at`, `counts`,
  `sources[]`, `programs[]` με `sessions[]`, ηλικίες, τιμές και συνδέσμους κρατήσεων

## Για scripts και AI agents

Διάβασε το **https://glogiotatidis.github.io/kids-events/data.json** — δεν χρειάζεται
scraping του HTML. Η σελίδα το δηλώνει στο `<head>` (`<link rel="alternate"
type="application/json">` + schema.org `Dataset`) και στο footer.
