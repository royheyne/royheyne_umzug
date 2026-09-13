# royheyne.com — Umzugsseite

Eine einzige statische Seite. Sie wird unter **royheyne.com** ausgeliefert und
verweist auf **royheyne.de**, die gepflegte Seite.

## Was hier liegt

    index.html   die Seite. Eine Datei, kein Bau, keine Abhaengigkeiten.
    CNAME        die Domain fuer GitHub Pages. Muss "royheyne.com" enthalten.

## Wie es ausgeliefert wird

GitHub Pages, aus dem Standardzweig, Ordner `/` (root).
Ein `git push` ist die Auslieferung — es gibt keinen Bauschritt.

## DNS

    A      royheyne.com      185.199.108.153
                             185.199.109.153
                             185.199.110.153
                             185.199.111.153
    CNAME  www.royheyne.com  <benutzer>.github.io

Die Zone liegt weiterhin bei Wix (die Nameserver einer Wix-Domain lassen sich
nicht aendern), die Eintraege zeigen aber nach GitHub. Das ist von Wix
ausdruecklich vorgesehen: "This allows you to connect domains that you've
registered through Wix to non-Wix websites."

MX- und TXT-Eintraege gibt es auf dieser Domain keine — es wurde also nichts
ueberschrieben. Stand der Messung: 13.9.2026.

## Warum diese Seite ueberhaupt existiert

royheyne.com war von 2020 bis 2026 Roy Heynes Website (Wix) und stand in der
Suche VOR royheyne.de. Zwei Seiten desselben Mannes teilen sich die Wertung.

Diese Seite beendet das: Sie traegt ein `canonical` auf royheyne.de, nennt den
Umzug in Titel und Beschreibung und fuehrt sechs Wege in die neue Seite. Sie hat
bewusst Substanz — eine nackte Umzugsnotiz wuerde das Canonical schwaechen.

Das Impressum ist vollstaendig: eine Seite ohne ladungsfaehige Anschrift waere
nach Paragraph 5 DDG mangelhaft. Die Anschrift ist Roys veroeffentlichte
Dienstadresse und steht ebenso auf royheyne.de.

## Spaeter

Sobald die Domain von Wix weg transferiert ist, kann daraus eine echte
301-Weiterleitung werden. Bis dahin ist diese Seite die beste verfuegbare
Loesung.
