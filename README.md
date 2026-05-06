# Zoo Applikation

## Beschreibung

Dies ist die Website vom Zoo Zürich, auf welchem Besucher News, Öffnungszeiten und weitere Informationen sehen können, wie auch Tickets kaufen können.

## Branch-Struktur

```
main
└── develop
    ├── feature/<kurze-beschreibung>
    ├── bugfix/<kurze-beschreibung>
    └── hotfix/<kurze-beschreibung>
```

| Branch | Zweck |
|--------|-------|
| `main` | Nur stabile, fertig getestete Releases |
| `develop` | Alle fertigen Features laufen hier zusammen |
| `feature/*` | Neue Funktionalität, aus `develop` abgezweigt, per Pull Request zurückgemergt |
| `bugfix/*` | Fehlerbehebungen, aus `develop` abgezweigt |

## Commit-Konventionen

Format: `<type>: <kurze Beschreibung>` (lowercase, kein Punkt am Ende)

| Typ | Verwendung |
|-----|-----------|
| `feat` | neue Funktion |
| `fix` | Bugfix |
| `refactor` | Umstrukturierung ohne Verhaltensänderung |
| `test` | Tests hinzufügen oder anpassen |
| `docs` | nur Dokumentation |
| `chore` | Build, Abhängigkeiten, Konfiguration |

## Autoren

- Luca Pallagi
- Laurens Alexander Hertzer
- Tymur Arduch
- Josua Welsche
