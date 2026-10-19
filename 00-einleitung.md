# Einleitung zum PrHG

## Gegenstand und Systematik

Die Produktehaftpflicht verbindet einen verschuldensunabhängigen Haftungsgrund mit einem spezifischen Sicherheitsbegriff. Herstellerrolle, Fehler, erfasster Schaden und Kausalität müssen getrennt ermittelt werden. Entlastung, Selbstbehalt, Solidarität und Fristen schliessen sich als eigenständige Prüfungsschritte an. Andere Anspruchsgrundlagen werden durch das Gesetz nicht pauschal ausgeschlossen.

## Nachgewiesener Rechtsstand

Prüftag und entscheidender Stichtag: 19.10.2026. Die amtliche Fassung vom 2010-07-01 wurde nicht allein wegen ihres Abrufdatums als aktuell behandelt. Über den amtlichen Fedlex-SPARQL-Endpunkt wurden alle zum Werk gehörenden Konsolidierungen und die Anwendungsdaten der einschlägigen Fassung abgefragt. Die ermittelten Daten 19940101, 20070701 und 20100701 ergeben am Prüftag die Auswahl 20100701. Die erneute Versionsabfrage im zweiten Prüfprozess ergab dieselbe Auswahl; eine zusätzliche jüngere Konsolidierung wurde nicht gefunden.

Die Rohantworten und Queries sind unter `sources` archiviert. Die erste probeweise falsche Metadatenadresse lieferte eine HTML-Anwendung und wurde ausdrücklich als untaugliche Metadatenantwort ausgesondert; entscheidend ist der tatsächlich validierte SPARQL-Endpunkt. Eine erfolgreiche HTTP-Antwort ohne erwarteten Inhalt gilt nicht als Quellenprüfung.

## Extraktion und Vollständigkeit

Der Parser verarbeitet die Artikelsektionen des amtlichen HTML, erhält Absätze, Buchstaben und Verweise auf amtliche Fussnoten. Alle Fussnoten einschliesslich Präambel und Abschnittsanmerkungen sind zusätzlich separat vollständig archiviert. Die historische Änderungsposition Art. 12 bleibt mit ihrer Auslassung und dem AS-Verweis erhalten. Die erwarteten Kennungen werden mit einem zweiten, unabhängigen HTMLParser direkt aus den Roh-Attributen inventarisiert; sie werden nicht aus der fertigen JSONL kopiert. `coverage-evidence.json` legt erwartete und extrahierte Kennungen, Gruppenbehandlung und tatsächlichen Anhangsbefund offen.

## Autoritäten und Grenzen

Die Erläuterungen sind eigene Auslegung; Beispiele sind keine Berichte über entschiedene Mandate. Die Quellenkarten ordnen einzelne Aussagen präzisen Erwägungen zu und halten Kontext und Grenzen fest. Für technische oder institutionelle Bestimmungen ohne in dieser Recherche belegten passenden Entscheid wird keine Rechtsprechung erfunden. Keine flächendeckende Einzelnormsuche, keine vollständige Nachfolgerecherche und keine eigenständige Verifikation sämtlicher Verordnungen oder externer Normen. Historische Sachverhalte benötigen eine eigene zeitliche Prüfung. Technische Länge und Wortlautübereinstimmung beweisen keine materielle Richtigkeit. Die in einem eigenständigen zweiten Prozess durchgeführte Prüfung aller 14 Einheiten ist in [REVIEW.md](REVIEW.md) dokumentiert. Sie ist keine externe professionelle Freigabe. Der vollständige amtliche Text von 4C.298/2006 wurde nachgelesen; ein weiterer amtlich verifizierter Entscheid vom 30.01.2026 ergänzt Art. 10. Die im Quellenhinweis zu Art. 3 erklärte Abweichung beim Erlassjahr der amtlichen HTML-Anmerkung wurde anhand der AS-Veröffentlichung aufgelöst.
