# Kompass — Decision Intelligence

> Software, die teure Entscheidungen wie ein System durchrechnet — und eine begründete Empfehlung gibt.

Dies ist kein weiteres SaaS-Tool. Es ist der Wedge in eine neue Kategorie: **Decision Intelligence**.

---

## 1. Das Problem (warum es überhaupt existiert)
Die teuersten Entscheidungen im Leben von Menschen und Unternehmen — eine Immobilie kaufen, Kapital allokieren, einen Standort wählen, ein Unternehmen übernehmen — werden mit **Bauchgefühl + einem chaotischen Excel** getroffen.

Der Grund: Diese Entscheidungen sind **Systeme**, keine Rechnungen. Sie hängen von Dutzenden gekoppelten Variablen ab (Zins, Miete, Leerstand, Wertentwicklung, Steuer, Liquidität), von **Second-Order-Effekten** und von **Unsicherheit über 10+ Jahre**. Ein Mensch kann das nicht im Kopf simulieren. Bisherige Tools zeigen eine Zahl — aber keine *Begründung*, keine *Szenarien*, kein *Risiko*.

## 2. Warum jetzt (die Wette)
Zum ersten Mal können Maschinen nicht nur *rechnen*, sondern *begründen und einordnen*:
- **Rechenkern:** deterministische Finanz- und Systemmodelle (Cashflow, Monte-Carlo, Sensitivität).
- **Reasoning-Layer:** ein LLM übersetzt Zahlen in Kontext ("Warum ist dieser Deal riskant? Was müsste passieren, damit er kippt?").
- **Daten-Layer:** reale Markt-, Miet- und Zinsdaten fließen automatisch ein.

Diese drei Schichten zusammen gab es vor 2024 nicht.

## 3. Der Moat (warum es verteidigbar ist)
Das Modell ist **kein** Moat — das hat jeder. Der Moat ist ein **Daten-Schwungrad**:

```
Mehr Entscheidungen  →  mehr Ergebnis-Daten (was ging wie aus?)
        ↑                          ↓
  bessere Empfehlungen   ←   besseres Kalibrierungsmodell
```

Wer als Erster **longitudinal misst, welche Entscheidungen wie ausgingen**, baut ein proprietäres Kalibrierungsmodell, das mit jedem Nutzer besser wird und von Wettbewerbern nicht kopiert werden kann. Hohe Eintrittsbarriere, wachsend über Zeit.

## 4. Der Wedge → die Kategorie
- **Wedge (jetzt):** Immobilien-Investment-Entscheidungen. Harte Zahlen, hohe Zahlungsbereitschaft, klarer ROI, messbare Ergebnisse.
- **Expansion:** Dasselbe Engine (Modell + Reasoning + Daten) skaliert auf jede hochriskante Entscheidung — Kapitalanlage, Firmenkauf, Standortwahl, Großanschaffungen.
- **Endzustand:** Ein **Decision Operating System**, das Menschen bei jeder wichtigen Entscheidung entlastet — mit einem persönlichen Modell der eigenen Ziele, Risikotoleranz und Historie.

## 5. Geschäftsmodell
- **B2C Prosumer:** private Kapitalanleger, Abo (z. B. pro Analyse / Flatrate).
- **B2B:** Makler, Bauträger, Family Offices, Banken — White-Label & API.
- **Daten:** anonymisierte Markt-Insights als eigenständiges Produkt.

## 6. Was der Prototyp zeigt (`kompass.html`)
Ein voll funktionsfähiger Kern des Rechen-Layers — **echte Mathematik, kein Mockup**:
- Vollständiges Cashflow-Underwriting einer Mietimmobilie (Rendite, Cashflow, Tilgung, Kaufpreisfaktor)
- **Monte-Carlo-Simulation** über 10 Jahre (Miete, Leerstand, Wertentwicklung) → Verteilung möglicher Ergebnisse (p10/p50/p90)
- **Risiko-Radar** über 6 Dimensionen
- **Sensitivitäts-Analyse** ("Was, wenn der Zins +1 % macht?")
- **Klare Empfehlung** BUY / PRÜFEN / PASS mit Begründung und Leverage-Points

Der fehlende Teil — der **Reasoning-Layer (LLM)** und der **Daten-Layer (Live-Marktdaten)** — ist der Teil, der das Ganze zu einem Produkt mit Moat macht. Der Prototyp beweist, dass der harte Kern real und heute baubar ist.
