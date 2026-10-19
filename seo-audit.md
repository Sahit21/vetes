# SEO-Audit — vetes-ai.de
**Erstellt:** 2026-04-17  
**Auditor:** Phase 0 – Inventur (keine Änderungen)

---

## 1. Datei-Inventur (indexierbare Seiten)

| Datei | Seiten-Typ |
|---|---|
| `index.html` | Homepage |
| `ueber-uns.html` | Über-uns / Founder-Seite |
| `leistungen/automatisierung.html` | Leistung: Workflow Automation |
| `leistungen/ai-agents.html` | Leistung: AI Agents |
| `leistungen/voice-ai.html` | Leistung: Voice AI |
| `termin.html` | Buchungsseite |
| `impressum.html` | Impressum (noindex ✓) |
| `datenschutz.html` | Datenschutz (noindex ✓) |
| `agb.html` | AGB (noindex ✓) |

---

## 2. On-Page Audit pro Seite

### index.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | VETES — Individuelle KI- & Automationslösungen für den Mittelstand | 67 | ❌ Zu lang (>60), fehlt "Sahit Luma", fehlt "Fulda" |
| `<meta description>` | VETES entwickelt maßgeschneiderte KI-Lösungen, Voice AI, AI Agents und Automatisierungen für mittelständische Unternehmen in Deutschland. Keine Standardsoftware — individuelle Systeme, die wirklich funktionieren. | 213 | ❌ Zu lang (>158) |
| `<h1>` | Systeme, die Ihr Unternehmen wirklich entlasten. | 48 | ❌ Kein Keyword, kein "Fulda", kein "Sahit Luma" |
| Canonical | — | — | ❌ Fehlt |
| `<html lang>` | `de` | — | ✅ |
| `og:title` | VETES — Individuelle KI- & Automationslösungen | — | ⚠️ Kein "Sahit Luma" |
| `og:description` | Maßgeschneiderte KI-Systeme für mittelständische Unternehmen. Voice AI, AI Agents und Automatisierung — individuell entwickelt, nahtlos integriert. | — | ⚠️ OK aber kein CTA |
| `og:url` | — | — | ❌ Fehlt |
| `og:image` | `og-image.png` (relativ) | — | ⚠️ Sollte absolut sein |
| `og:locale` | `de_DE` | — | ✅ |
| `twitter:card` | `summary` | — | ❌ Sollte `summary_large_image` sein |
| Schema.org | — | — | ❌ Fehlt komplett |

**H2s (Auswahl):** "Vertrauen entsteht durch Substanz", "Unsere Kernbereiche. Ihr Vorteil.", "Kein System von der Stange. Nie.", "Häufige Fragen."

---

### ueber-uns.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | Über uns — VETES | 17 | ❌ Zu kurz, kein Keyword, kein "Sahit Luma" |
| `<meta description>` | VETES ist ein spezialisiertes KI-Studio für individuelle Sprach-, Agenten- und Automationslösungen. Erfahren Sie mehr über unsere Mission, Werte und Arbeitsweise. | 157 | ✅ Länge OK, aber kein "Sahit Luma" |
| `<h1>` | Dein Partner für nachhaltiges Wachstum. | 40 | ❌ Kein Keyword, kein "Sahit Luma" |
| Canonical | — | — | ❌ Fehlt |
| `og:url` | — | — | ❌ Fehlt |
| `twitter:card` | — | — | ❌ Fehlt |
| Schema.org | — | — | ❌ Fehlt (Person-Schema für Sahit Luma wäre hier ideal) |

**Positiv:** Sahit Luma wird auf dieser Seite als Gründer mit Foto vorgestellt. Adresse (Flemingstr. 18, 36041 Fulda) und Kontaktdaten im Footer vorhanden.

---

### leistungen/automatisierung.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | Automatisierung — Prozesse & Workflows \| VETES | 46 | ⚠️ Kein "Fulda", kein Longtail-Keyword |
| `<meta description>` | VETES automatisiert operative Prozesse, verbindet Systeme und beseitigt manuelle Zwischenschritte. Individuelle Lösungen für mittelständische Unternehmen. | 151 | ✅ Länge OK, kein CTA |
| `<h1>` | Weniger Handarbeit. Mehr System. | 32 | ❌ Kein Keyword |
| Canonical | — | — | ❌ Fehlt |
| `og:url` | — | — | ❌ Fehlt |
| `twitter:card` | — | — | ❌ Fehlt |
| Schema.org | — | — | ❌ Fehlt |

---

### leistungen/ai-agents.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | AI Agents — Autonome KI-Systeme \| VETES | 40 | ⚠️ Kein "Fulda", kein Longtail |
| `<meta description>` | VETES entwickelt individuelle AI Agents, die Aufgaben eigenständig übernehmen, Prozesse koordinieren und Ihr Team von repetitiver Arbeit entlasten. | 148 | ✅ Länge OK, kein CTA |
| `<h1>` | Systeme, die arbeiten – ohne Pause. | 35 | ❌ Kein Keyword |
| Canonical | — | — | ❌ Fehlt |
| `og:url` | — | — | ❌ Fehlt |
| `twitter:card` | — | — | ❌ Fehlt |
| Schema.org | — | — | ❌ Fehlt |

---

### leistungen/voice-ai.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | Voice AI — Intelligente Sprachsysteme \| VETES | 45 | ⚠️ OK Länge, kein "Fulda" |
| `<meta description>` | VETES entwickelt individuelle Voice-AI-Systeme für Terminvereinbarung, Erstgespräche und telefonischen Kundenservice – 24/7, skalierbar, nahtlos integriert. | 155 | ✅ |
| `<h1>` | Ihr Telefon arbeitet jetzt für Sie. | 35 | ❌ Kein Keyword |
| Canonical | — | — | ❌ Fehlt |
| `og:url` | — | — | ❌ Fehlt |
| `twitter:card` | — | — | ❌ Fehlt |
| Schema.org | — | — | ❌ Fehlt |

---

### termin.html
| Feld | Aktueller Wert | Länge | Status |
|---|---|---|---|
| `<title>` | Termin vereinbaren — VETES | 25 | ❌ Zu kurz |
| `<meta description>` | Vereinbaren Sie jetzt Ihr kostenloses Erstgespräch mit VETES. Wählen Sie einfach einen passenden Termin aus unserem Kalender. | 124 | ⚠️ Kein "KI Beratung", kein "Fulda" |
| Canonical | — | — | ❌ Fehlt |
| `og:url` | — | — | ❌ Fehlt |
| Schema.org | — | — | ❌ Fehlt |

---

## 3. Technische Checkliste

| Element | Status | Details |
|---|---|---|
| `robots.txt` | ❌ FEHLT | Muss erstellt werden |
| `sitemap.xml` | ❌ FEHLT | Muss erstellt werden |
| Canonical-Tags | ❌ Fehlt auf ALLEN Seiten | Höchste Priorität |
| Schema.org JSON-LD | ❌ Fehlt auf ALLEN Seiten | |
| `og:url` | ❌ Fehlt auf allen Seiten | |
| `twitter:card` | ⚠️ Nur index.html, falscher Wert (`summary`) | Sollte `summary_large_image` |
| `og:image` (absolut) | ⚠️ Relative Pfade | Sollte `https://vetes-ai.de/og-image.png` |
| `favicon.svg` | ✅ Vorhanden | |
| `apple-touch-icon.png` | ✅ Vorhanden | |
| `og-image.png` | ✅ Vorhanden | Maße unbekannt (sollte 1200×630) |
| Google Fonts Preconnect | ✅ Vorhanden auf allen Seiten | |
| `lang="de"` | ✅ Auf allen Seiten | |
| `<meta name="viewport">` | ✅ Auf allen Seiten | |
| 404-Seite | ❌ Nicht gefunden | |
| `.htaccess` | — | Nicht relevant (Vercel-Hosting) |
| `vercel.json` | ✅ Vorhanden (`cleanUrls`) | |

---

## 4. Bekannte Services (aus Seiteninhalt)

| Service | Stichwörter aus dem Content |
|---|---|
| Workflow-Automatisierung | n8n, Systeme verbinden, API-Integration, Prozessautomatisierung, manuelle Zwischenschritte |
| AI Agents | Autonome Agenten, eigenständige Aufgabenübernahme, multi-step tasks |
| Voice AI | Terminvereinbarung automatisieren, KI-Telefonie, 24/7 Kundenservice, Sprachassistent |

---

## 5. Kritische Lücken (Priorität)

1. **Kein "Sahit Luma" in einem einzigen Title-Tag** — Personal Brand ist unsichtbar
2. **Kein "Fulda" oder "Hessen" in Meta-Tags oder H1s** — Lokale Sichtbarkeit = 0
3. **Kein Canonical-Tag überall** — Duplicate-Content-Risiko
4. **Kein Schema.org** — Kein Rich Snippet-Potenzial
5. **Kein robots.txt + sitemap.xml** — Google crawlt blind
6. **H1s sind alle kreativ, aber keyword-leer** — Missed opportunity
7. **twitter:card = "summary"** statt `summary_large_image`
8. **og:image ist relativ** — Social Shares broken auf anderen Domains

---

## 6. Adress- und Kontaktdaten (aus Footer ueber-uns.html)
- **Adresse:** Flemingstraße 18, 36041 Fulda
- **Telefon:** 0661 97423950
- **E-Mail:** info@vetes.de
- **LinkedIn:** https://www.linkedin.com/company/vetes
- → Physische Adresse vorhanden → `LocalBusiness`-Schema ist berechtigt ✅

---

*Nächster Schritt: Freigabe durch Sahit Luma → dann Phase 1 starten.*
