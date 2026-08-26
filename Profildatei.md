# Profildatei — Personalisierter News-Reader

Version: v1.6 · Letzte Änderung: 19. August 2026
Versionslogik: Erste Ziffer erhöht sich nur bei größeren, strukturellen Änderungen; jede sonstige Änderung erhöht nur die zweite Zahl.

Diese Datei ist die operative Datengrundlage für die Kuration (Whitelist/Blacklist, Wildcard-Verhältnis, Feedback-Historie). Für Projektkontext, Ziele und Roadmap siehe Kontext.md.

## 1. Wildcard-Verhältnis (Profil-basiert vs. explorativ)
- Standard: 80/20
- Ausnahme (höherer explorativer Anteil): Sport, Rezepte, Gesundheit & Fitness: 60/40
- Sonstiges: 10/90 (bewusst sehr hoher explorativer Anteil — Ziel: Blick über die eigene Bubble hinaus; siehe Abschnitt 2)

## 2. Kategorien & Quellen-Whitelist

### Basisliste "Welt" (wird von mehreren Kategorien referenziert)
Süddeutsche.de, Tagesschau/ARD, Zeit Online, Reuters, dpa, NZZ, Der Spiegel, Handelsblatt, Die Welt, BBC News, The Times, The Guardian, The Economist, Le Monde, France 24, NPR, NY Times, The Atlantic, AP News, Wall Street Journal, Al Jazeera English*, The Japan Times, Nikkei Asia, South China Morning Post*, Xinhua/Global Times/China Daily*, The Straits Times*, Channel News Asia

*siehe Abschnitt 5 (redaktionelle Einordnung)

### Welt
= Basisliste Welt

### Europa
= Basisliste Welt + Politico Europe, Euronews, EUobserver, El País, Corriere della Sera/La Repubblica, Notes from Poland, Balkan Insight, Kyiv Independent/Kyiv Post

### Deutschland
= Basisliste Welt (deutschsprachiger Teil: Süddeutsche.de, Der Spiegel, Handelsblatt, Die Welt, Zeit Online, Tagesschau/ARD, dpa) + FAZ, taz, BR24, Münchner Merkur, Abendzeitung München, SZ-Regionalteil, B304.de, Grasbrunn-aktuell.de, grasbrunn.de/nachrichten
Lokale Priorität: München, Grasbrunn (siehe Kontext.md 3.2)

### Wirtschaft
= Basisliste Welt (insb. Handelsblatt, FT, Economist, WSJ, Reuters, Nikkei Asia, SCMP) + Wirtschaftswoche, brand eins, Manager Magazin, Bloomberg, CNBC, Forbes, Fortune, Business Punk

### Finanzen
= Basisliste Welt (insb. Handelsblatt, FT, Bloomberg, Reuters, Economist) + Finanzfluss, Finanztip, Extra-ETF, Finanz-Szene, Morningstar, MarketWatch, Motley Fool, Seeking Alpha

### Tech News — KI
MIT Technology Review, TechCrunch, The Information, Anthropic-Blog, OpenAI-Blog, Google AI/DeepMind-Blog, Meta AI Blog, Import AI/AI Snake Oil, Stratechery, The Verge, Wired, Ars Technica

### Tech News — Gadgets
Heise.de, Golem.de, 9to5mac, 9to5Google, The Verge, Engadget, MacRumors, Android Authority, Notebookcheck, Wired, Ars Technica

### Sport
**Themen-Präferenz:** Fußball als Hauptfokus — Bundesliga (insb. FC Bayern München, Borussia Dortmund, VfB Stuttgart) sowie international Premier League und La Liga. Zusätzlich Großevents anderer Sportarten (Olympia, WM, EM, NBA Playoffs, Super Bowl). Motorsport: kein Interesse (siehe Themen-Blacklist).
**Quellen:** SZ, Kicker, Sky Sport/Sport1, Sportschau, Bundesliga.com, Transfermarkt, fcbayern.com, bvb.de, vfb.de, The Athletic, Marca/AS, BBC Sport, Goal.com, ESPN

### Rezepte
**Themen-Präferenz:** überwiegend vegetarisch + Fisch; gesunde, ausgewogene Ernährung; bevorzugt schnelle/einfache statt aufwändige Zubereitung.
**Explizit ausgeschlossen:** Chefkoch (siehe Abschnitt 6)
**Quellen:** SZ, Essen und Trinken, Küchengötter, Serious Eats, BBC Good Food, NYT Cooking, Smitten Kitchen, Minimalist Baker, EAT SMARTER, Green Kitchen Stories, Ottolenghi (via Guardian), simply-cookit.com, Chiemseeblog (Cookit-Beratung), EatingWell

### Gesundheit & Fitness
**Themen-Präferenz:** undogmatisch, evidenzbasiert, kein Hype/Verkaufsinteresse.
**Explizit ausgeschlossen:** Fit for Fun (siehe Abschnitt 6)
**Quellen:** NDR Ratgeber Gesundheit, Apotheken Umschau, Quarks, Harvard Health Publishing, NHS-Website/-Blog, Examine.com, Nerd Fitness/StrongFirst, Stronger by Science, Fit&Well

### Social Media
Keine feste Quellen-Whitelist — plattform- statt domain-getrieben. Ansatz: Websuche nach viralen Themen + Durchsickern aus anderen Kategorien, da keine direkten Trending-APIs verfügbar sind.
**Zeitfenster:** explizit nicht auf "brandaktuell/letzte Stunden" beschränkt — auch Trends der letzten Tage bis Wochen sind relevant.

### Sonstiges
Whitelist-Einträge: Spektrum.de (Wissenschaftsmagazin, thematisch breit — Physik, Biologie, Medizin, Psychologie, Astronomie u. a. — passt in keine der übrigen Kategorien; bewusst hier statt in eigener „Wissenschaft"-Kategorie geführt, siehe Kontext.md, Entscheidungen vom 16.08.2026), Utopia.de (Nachhaltigkeit, ethischer Konsum, Umwelt-Lifestyle — passt ebenfalls in keine der übrigen Kategorien). Wegen der bewusst schmalen Whitelist entsprechend hoher Wildcard-Anteil (10/90, siehe Abschnitt 1) — Ziel: Blick über die eigene Bubble hinaus (siehe Kontext.md 3.2). Whitelist kann bei Bedarf um weitere Quellen erweitert werden; das Wildcard-Verhältnis wäre dann ggf. neu zu bewerten.

## 3. Quellen-Blacklist
Aktuell leer.

## 4. Themen-Blacklist
- Motorsport (z. B. Formel 1) — kein Interesse
- Horoskope, Sternzeichen o. Ä. — kein Interesse

## 5. Redaktionelle Einordnungen (nicht ausschließend, nur zur Kalibrierung bei Kuration und Kernaussage)
- Al Jazeera English: staatsnah (Katar)
- South China Morning Post: zunehmende Nähe zu Peking
- Xinhua / Global Times / China Daily: staatlich kontrolliert, spiegeln offizielle Regierungslinie
- The Straits Times: regierungsnah (Singapur)

## 6. Explizit ausgeschlossene Quellen (mit Begründung)
- Chefkoch: Community-Plattform, keine redaktionell kuratierten Empfehlungen — passt nicht zum Anspruch dieser Kategorie
- Fit for Fun: massenmarkt-/trendorientiert, teils Clickbait/Sponsored Content — passt nicht zum gewünschten evidenzbasierten, undogmatischen Ansatz

## 7. Feedback-Historie
*(wird ab Nutzung der App laufend befüllt)*

### Daumen hoch/runter
— noch leer —

### Mute-Liste (24h)
— noch leer —

### Freitext-Feedback
— noch leer —

## 8. Eingereichte Links
*(vom Nutzer geschickte, interessante Artikel-Links als zusätzliches Feedback-Signal)*
— noch leer —
