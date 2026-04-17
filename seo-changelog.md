# SEO Changelog — vetes-ai.de

---

## 2026-04-17 — Phase 1–3 & Deliverables

### Phase 0 — Audit (keine Änderungen)
- `seo-audit.md` erstellt: Inventur aller HTML-Seiten, Meta-Tag-Analyse, technische Checkliste
- Top-5-Konkurrenten recherchiert (n8n-agentur.de, digitaleheimat.de, press-ki.de, frankfurt-ai.de, 2moove.de)

### Phase 1 — On-Page Basics
Geänderte Dateien: `index.html`, `ueber-uns.html`, `leistungen/automatisierung.html`, `leistungen/ai-agents.html`, `leistungen/voice-ai.html`, `termin.html`

| Seite | Neuer Title | Description-Länge |
|---|---|---|
| index.html | Sahit Luma – KI Automation Fulda \| Vetes AI | 151 Zeichen |
| ueber-uns.html | Sahit Luma – KI-Experte & Gründer von Vetes AI Fulda | 155 Zeichen |
| leistungen/automatisierung.html | Workflow Automation Fulda \| n8n & Make Berater \| Vetes AI | 152 Zeichen |
| leistungen/ai-agents.html | AI Agents Fulda \| Autonome KI-Systeme für KMU \| Vetes AI | 152 Zeichen |
| leistungen/voice-ai.html | Voice AI Fulda \| KI-Telefonie & Sprachassistent \| Vetes AI | 146 Zeichen |
| termin.html | Kostenloses KI-Erstgespräch \| Sahit Luma – Vetes AI Fulda | 155 Zeichen |

Alle Seiten erhalten zusätzlich:
- `<link rel="canonical">` mit absoluter HTTPS-URL
- `og:url` (absolut)
- `og:image` absolut (`https://vetes-ai.de/og-image.png`)
- `twitter:card = summary_large_image`
- `twitter:title`, `twitter:description`, `twitter:image`

### Phase 2 — Schema.org JSON-LD
- `index.html`: Person (Sahit Luma) + LocalBusiness (Vetes AI, Fulda) + WebSite mit SearchAction
- `ueber-uns.html`: vollständiges Person-Schema mit `sameAs` LinkedIn
- `leistungen/automatisierung.html`: Service-Schema, areaServed Fulda/Hessen
- `leistungen/ai-agents.html`: Service-Schema, areaServed Fulda/Hessen
- `leistungen/voice-ai.html`: Service-Schema, areaServed Fulda/Hessen

### Phase 3 — Technical SEO
- `robots.txt` erstellt: Allow /, Disallow node_modules + outputs, Sitemap-URL eingetragen
- `sitemap.xml` erstellt: 6 URLs, Homepage priority 1.0, Leistungen 0.9, Rest 0.7–0.8

### Phase 5 — Keyword-Map
- `seo-keyword-map.md` erstellt: 6 URLs mit Primary/Secondary/LSI-Keywords, Kannibalisierungs-Check

### Phase 6 — Competitor Plan
- `seo-competitor-plan.md` erstellt: 5 Vergleichs-/Alternativseiten vorgeschlagen, wartet auf Freigabe

---

## TODO — Noch offen
- [ ] Google Search Console: Property einrichten, sitemap.xml einreichen (`https://vetes-ai.de/sitemap.xml`)
- [ ] Bing Webmaster Tools: Property verifizieren, sitemap einreichen
- [ ] Google Business Profile: "Vetes AI" in Fulda anlegen oder beanspruchen
- [ ] DSGVO-konforme Analytics einrichten (Empfehlung: Plausible oder Umami, keine Cookies)
- [ ] og:image Maße prüfen (soll exakt 1200×630 px sein)
- [ ] Phase 6 Seiten umsetzen nach Freigabe
- [ ] Backlink-Strategie starten (Fulda IHK, lokale Netzwerke, LinkedIn-Artikel)
