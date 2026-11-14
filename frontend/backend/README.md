# Backend

Ο server της εφαρμογής: δέχεται τα αιτήματα από το frontend, μιλάει με τη βάση και με το Europeana API, και παρέχει το δικό μας REST API.

**Τεχνολογίες:** Node.js, Express

## Δομή
- `routes/` – τα endpoints του API
- `controllers/` – η λογική κάθε endpoint
- `models/` – οι κλάσεις που αντιστοιχούν στους πίνακες της βάσης
- `services/` – επικοινωνία με εξωτερικά APIs (Europeana)
