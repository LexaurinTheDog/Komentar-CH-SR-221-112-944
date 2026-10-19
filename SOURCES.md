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
