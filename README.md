# ag-spiel_analytics

## Intro
Das Fan-Projekt *ag-spiel_analytics* nutzt die Daten-API aus dem AG-Spiel (https://www.ag-spiel.de/).
Wir verwenden vorrangig html/css/js damit die APP einfach im Browser funktioniert.

## Installationsanleitung
Download der Datei ag-spiel_adhoc_analytics.html und anschließend im Brower öffnen.
Die Kompatibilität wird ausschließlich für den Chrome-Brower getestet.

## Feature-Requests
Bitte lasst mich eure Wünsche wissen, welche Daten wollt ihr sehen, kombinieren, auswerten, visualisieren.
Macht bitte einfach einen Issue hier in github auf (https://github.com/SpekulantAC/ag-spiel_analytics/issues)

## Change Log
### v0.8 Aktiendepot der Systembank
- veröffentlicht: 19.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Der Report *Aktiendepot der Systembank* hält was er verspricht, er gewährt Einblick an welchen AGs die Systembank beteiligt ist und wie hoch der Anteil am Kapital der jeweiligen AG ist. Wenig überraschend ist die (fast) vollständige Kontrolle der Userprojekt-AGs. 


### v0.7 Top 10 AGs high Valuation + Liabilities Maturity Report
- veröffentlicht: 17.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Im neuen high Valuation Bericht sind die 10 AGs aufgeführt, bei denen das Verhältnis von Marktkapitalisierung ohne cash/bonds/loans zu Marktkapitalisierunga am höchsten ist. Hierbei wird auch der Zinsertrag/Zinsaufwand miteingerechnet. Ist die Ratio >1, so wird helfig Fremdkapital eingesetzt.
Der Liability-Report zeigt die Fälligkeiten des Fremdkapitals an, also an welchen Tagen dem Markt durch Rückzahlung von Kapital und Zinsen Bargeld entzogen wird.

### v0.6 Top 10 AGs low Valuation
- veröffentlicht: 15.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Im neuen Bericht sind die 10 AGs aufgeführt, bei denen das Verhältnis von Marktkapitalisierung net cash/bonds/loans zu Marktkapitalisierunga am gerinsten ist. Hierbei wird auch der Zinsertrag/Zinsaufwand miteingerechnet. Ist der Ratio <0, so lag der letzte Kurs unterhalb der "sicheren" Inneren Wertes. ACHTUNG: Keine blende Kaufentscheidung treffe, meist liegt der Briefkurs deutlich uber dem d KAUFEMPFEHLUNG

### v0.5 Code refactoring
- veröffentlicht: 14.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Inhaltlich keine Änderungen. CSS für Formatierung im Head ergänzt. Berichte in eigene Funktionen gekapselt für bessere Wartbarkeit. Format der Beträge in € vereinheitlicht.

### v0.4 Top 20 AGs mit geringsten Spreads
- veröffentlicht: 13.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Der Bericht *TOP 20 AGs with lowest Spreads* zeigt die 20 AGs mit dem aktuell geringsten Spreads zwischen Brief- und Geldkurs. Geringe Spreads sprechen für vergleichsweise hohes Vertrauen des Marktes in diese AGs. Möglicherweise ein Qualitätsmerkmal?   

### v0.3 Anleihebuch der Systembank
- veröffentlicht: 13.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Der Bericht *Anleihebuch der Systembank* zeigt die Bargeldzuflüsse aus dem Anleihegeschäft pro Tag. Dieser kann zur Schätzung der künftigen Zinsentwicklung herangezogen werden und gegenenfalls zur Optimierung von Investitionen in Anleihen (Timing) beitragen.  

### v0.2 Total Market
- veröffentlicht: 08.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Zusätzlich werden nun die Informationen zu den AGs aggregiert:
 Marktbewertung (Anzahl Aktien\*Kurs),
 Bargeldbestände,
 Anleihen,
 künfitge Zinserträge aus Anleihen,
 Kredite,
 Kreditkosten

### v0.1 Hello World
- veröffentlicht: 06.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Die erste Version läde das data.json von https://www.ag-spiel.de/api/get/data.php und zeigt die allgemeinen Informationen an (timestamp, Anzahl AGs, Anzahl Orders 24h, Volumen Orders 24h)

