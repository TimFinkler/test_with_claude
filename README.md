# RechnungsPro 🧾

Ein schlanker, professioneller **Rechnungs-Generator** – eine einzige HTML-Datei, läuft komplett offline im Browser (auch mobil). Kein Build, keine Server, keine Abhängigkeiten.

> Gebaut als "damit lässt sich Geld verdienen"-Prototyp: Tools wie dieses werden als Micro-SaaS für 10–30 €/Monat verkauft.

## Features
- 📝 Firmen- & Kundendaten, Rechnungsnummer, Datum, Fälligkeit, Leistungszeitraum
- ➕ Beliebig viele Positionen mit Menge, Einzelpreis und individuellem MwSt-Satz
- 🧮 Automatische Berechnung von Netto, MwSt (pro Satz aufgeschlüsselt) und Gesamtbetrag
- 👀 Live-Vorschau der fertigen Rechnung
- 📄 Ein Klick → als PDF drucken/speichern
- 💾 Automatisches Speichern im Browser (localStorage) – nichts verlässt dein Gerät
- 📱 Responsive, funktioniert auf Handy, Tablet und Desktop

## Nutzung
Einfach `index.html` im Browser öffnen. Fertig.

- **"Beispiel laden"** füllt eine Demo-Rechnung
- **"Als PDF drucken"** öffnet den Druckdialog (dort "Als PDF speichern" wählen)

## Ideen für die Monetarisierung
- Als Web-App hosten (Netlify/Vercel) und hinter eine Bezahlschranke / Login setzen
- Vorlagen & Branding (eigenes Logo, Farben) als Premium-Feature
- Kundenverwaltung, wiederkehrende Rechnungen, E-Mail-Versand ergänzen
- Als White-Label-Lösung an Agenturen verkaufen
