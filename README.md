# Tekstnets projektskabelon

Mappen project-layout udgør en projektskabelon som kan kopieres til brug i nye
projekter. Det kan gøres ved at klone eller downloade dette repositorium. Når du
har fået fat i arkivet, kopierer du det til det sted på din computer, hvor du
skal bruge det. For eksempel:  

```
cp -r project-layout /sti/til/mappe/projektnavn
```

## Indhold

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
└── README.md
```

