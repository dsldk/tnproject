# Tekstnets projektskabelon

En klar katalogstruktur gør det lettere at finde de filer, et udgivelsesprojekt
producerer.

Kataloget `project-layout` udgør en projektskabelon som kan kopieres til brug i nye
projekter. Det kan gøres ved at klone eller downloade dette repositorium. 

Når du har fået fat i arkivet, kopierer du det til det sted på din computer,
hvor du skal bruge det. For eksempel:  

```
cp -r project-layout /sti/til/mappe/projektnavn
```

## Indhold

Skabelonen er struktureret på følgende måde:

```
project-layout/
├── data/
│   ├── processed/
│   │   ├── accounts/
│   │   │   └── nn-n_example-text/
│   │   │       └── index.md
│   │   ├── introductions/
│   │   │   └── nn-n_example-text/
│   │   │       └── index.md
│   │   ├── notes/
│   │   │   └── nn-n_example-text.toml
│   │   ├── persons/
│   │   │   └── persons.toml
│   │   └── texts/
│   │       └── nn-n_example-text/
│   │           └── nn-n_example-text.xml
│   └── raw/
│       ├── accounts/
│       │   └── nn-n_example-text/
│       │       └── index.md
│       ├── introductions/
│       │   └── nn-n_example-text/
│       │       └── index.md
│       ├── notes/
│       │   └── nn-n_example-text.toml
│       ├── persons/
│       │   └── persons.toml
│       └── texts/
│           └── nn-n_example-text/
│               └── nn-n_example-text.xml
├── docs/
├── .gitignore
├── LICENSE
└── README.md
```

## Filer og regler for navngivning

Fordi filers funktion på Tekstnet er afhængig af navngivning, er det nødvendigt
at iagttage nogle regler. Filnavne er en blanding af

- snake_case og kebab-case. Filnavnet `nexoe-ma_ditte-menneskebarn-1` er
  sammensat af
  - forfatterkoden `nexoe-ma`, kort for _Martin Andersen Nexø_
  - underscore `_`, adskiller forfatterkode og værktitel
  - værktitlen `ditte-menneskebarn-1`, kort for _Ditte Menneskebarn_, 1. del

## Kontakt

Spørgsmål til Tekstnets projektskabelon kan rettes til [Thomas Hansen](mailto:th@dsl.dk)
