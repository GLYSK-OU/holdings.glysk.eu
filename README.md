# GLYSK Holdings — holdings.glysk.eu

Static website for **GLYSK Holdings OÜ**, the investment and holding entity of the GLYSK Group.

Deployed via [statichost.eu](https://statichost.eu) from this repository.

---

## Structure

```
/
├── index.html        — Single-page site (all sections inline)
├── statichost.yml    — Statichost deployment config
├── .gitignore
└── README.md
```

Assets (photos, documents) go in `/assets/` when added.

---

## Deployment

Hosted at **https://holdings.glysk.eu** via statichost.eu.

1. Push to `main` branch on Codeberg
2. Statichost picks up the change automatically
3. DNS: `holdings` CNAME → statichost target (managed via Infomaniak)

---

## Related

- Advisory site: [www.glysk.eu](https://www.glysk.eu) · repo: `GiuseppeLopesMe/glysk-advisory`
- Registrar: Infomaniak
- Company: GLYSK Holdings OÜ · Reg. 14772172 · Tallinn, Estonia
