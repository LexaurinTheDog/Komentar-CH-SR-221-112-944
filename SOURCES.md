# Quellen und tatsächliches Rechercheprotokoll

## Gesetz und Versionsprüfung

- Amtliche Rohquelle: https://www.fedlex.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/1993/3122_3122_3122/20100701/de/html/fedlex-data-admin-ch-eli-cc-1993-3122_3122_3122-20100701-de-html-7.html
- [Abruf, SHA-256 und Versionsevidenz](sources/verification.json)
- [Rohes HTML](sources/official.html), [kanonische Extraktion](sources/canonical.md), [sämtliche amtlichen Anmerkungen](sources/official-notes.md)
- [Mitgliedschaften aller Fassungen](sources/versions.json), [Anwendungsdaten](sources/version-details.json), [Queries](sources/versions-query.json)
- [Unveränderter ursprünglicher Intake als Sicherung](sources/intake-original.md), [Änderungs-/Auswahlkarte](sources/change-map.json)
- [Normabdeckung](coverage-evidence.json); eigenständige Rohstruktur-Inventur mit `_coverage.py`.

## Tatsächlich ausgeführte Suchabfragen

- `site:search.bger.ch Produktehaftpflicht BGE 133 III 81`: [originale Suchantwort](sources/search.json).

Die Suchantworten dienten nur der Fundstellenermittlung. Verwendet wurden die tatsächlichen amtlich publizierten Entscheidungsgründe, nicht allein Treffertexte. Die Recherche fand am 19.10.2026 statt und ist selektiv. Eine lokale schweizerische Urteilssammlung wurde nicht für eine vollständige Recherche ausgewertet. Für die übrigen Einheiten wird kein Nichtvorhandensein von Rechtsprechung behauptet.

Ein erster Abruf über search.bger.ch lieferte eine leere Kurzantwort trotz HTTP 200; er ist als verworfene Antwort gesichert. Erst der Direktabruf über den amtlichen relevancy.bger.ch-Endpunkt lieferte den verwerteten Entscheidungsauszug. Die verworfene Metadaten-HTML-Antwort ist ebenfalls ausdrücklich keine Versionsevidenz.

- [Bundesgericht, 19.12.2006 – 4C.298/2006, BGE 133 III 81](judikatur/BGE-133-III-81.md): E. 3.1–3.3, 4.1–4.2.3; zu Art. 1 und 4.

## Offene Grenzen

Keine erschöpfende Rechtsprechungs-, Literatur- oder Verordnungsrecherche. Externe Verweisungsnormen werden nur im aus dem verifizierten Gesetz ersichtlichen Umfang behandelt; ihre Detailanwendung ist gesondert zu prüfen. Insbesondere wurde eine eigenständige vollständige Prüfung möglicher Anpassungsverordnungen zum Selbstbehalt nicht durchgeführt; das Rechenbeispiel bezieht sich ausdrücklich auf den Gesetzesbetrag.

## Ergänzende Prüfung im zweiten Prozess – 19.10.2026

- [Erneuter Rohabruf, Versionsinventur und Anwendungsdaten](sources/review-fetch-verification.json); die aktuelle HTML-Antwort ist bytegleich mit der Autorenquelle. Die abweichend geratenen historischen HTML-Pfade lieferten Anwendungshüllen und wurden verworfen. Eine gezielte Manifestationsabfrage lieferte keine HTML-Fundstellen; daraus wird keine Aussage über das Nichtvorhandensein historischer amtlicher Fassungen abgeleitet.
- [Suchlog und lokale nationale Fundstellen](sources/review-search-log.json). Ergänzend erfolgte eine gezielte Textsuche in den lokalen Beständen BGer/BGE 2025–2026; keine vollständige Bestandsrecherche.
- [Vollständiges Urteil 4C.298/2006](sources/review-full-case.html), einschliesslich E. 1–5 und Dispositiv geprüft. Die frühere Beschränkung auf den publizierten Auszug wurde für diese Fallkarte aufgehoben.
- [Bundesgericht 30.01.2026 – 4A_648/2024](judikatur/4A-648-2024.md), E. 5.3.1–5.3.7, insbesondere 5.3.5: Fristsicherung durch unbezifferte Klage; Kontext und zeitliche Grenzen gesondert dokumentiert. [Amtliche Abrufbelege](sources/review-extra-verification.json).
- [AS 2010 2573, PrSG vom 12. Juni 2009](sources/review-prsg-as2010.pdf), Titelblatt und S. 2580 (Art. 20 Abs. 2 Ziff. 1) gelesen und visuell geprüft. [PDF-Nachweis](sources/review-prsg-pdf-verification.json), [amtliche Metadaten](sources/review-prsg-metadata.json), [lesbarer PDF-Text](sources/review-prsg-as2010.txt). Das Datum 12. Juni 2010 in Fussnote 5 des PrHG-HTML weicht von der veröffentlichten AS-Fassung ab; das Zitat bleibt erhalten und erhält eine ausdrückliche Berichtigung im Kommentar.

Die in 4A_648/2024 besprochenen weiteren Gerichtsentscheidungen sind keine eigenständig vollständig verifizierten zusätzlichen Autoritäten dieser Ausgabe. Die ursprünglichen Recherchegrenzen, insbesondere zu Anpassungsverordnungen nach Art. 6, bleiben bestehen.
