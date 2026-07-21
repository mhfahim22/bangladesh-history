# Heritage of Bengal — বাংলাদেশের ঐতিহাসিক স্থান

A web application showcasing 8 historical places of Bangladesh, built with the **Aurora** programming language as the backend server.

## Languages & Technologies Used

| Language/Tech | Purpose |
|--------------|---------|
| **Aurora** | Backend HTTP server, routing, template compilation & rendering |
| **HTML** | 12 page templates (index, places, 8 detail pages, about, base) |
| **CSS** | Inline styles with custom design system (Playfair Display + Inter fonts) |

## Architecture

- **`server.aura`** — Aurora backend: compiles templates, registers 11 GET routes, runs on port 8080
- **`templates/`** — 12 self-contained HTML files with inline CSS (no external dependencies)
- **`static/css/style.css`** — Source CSS reference (content inlined into templates)

## How to Run

```bash
aurorac.exe server.aura
```

Server starts at `http://localhost:8080`

## Historical Places Covered

1. Sixty Dome Mosque (UNESCO) — Bagerhat
2. Somapura Mahavihara (UNESCO) — Paharpur
3. Lalbagh Fort — Dhaka
4. Ahsan Manzil — Dhaka
5. Mahasthangarh — Bogura
6. Mainamati — Cumilla
7. Kantajew Temple — Dinajpur
8. Panam City — Sonargaon
