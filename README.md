# Om brukermanualen

## Brukermanual for Prosjektportalen 365

Brukermanualen vil til enhver tid gjenspeile siste gjeldende versjon av Prosjektportalen 365 som du finner på Github.

Prosjektportalen for Microsoft 365 er et prosjektstyringsverktøy for Microsoft 365 basert på <a href="http://prosjektveiviseren.digdir.no">Prosjektveiviseren</a>. <a href="https://crayonconsulting.no/teknologi-og-partnere/prosjektstyring-og-verktoy/prosjektportalen/">Mer informasjon på Crayon Consultings nettsider.</a>

## Hva er Prosjektportalen for Microsoft 365?

Prosjektportalen for Microsoft 365 er bygget av Puzzlepart AS og videreutviklet av <a href="https://crayonconsulting.no/">Crayon Consulting</a>. Løsningen inneholder Microsoft 365 og SharePoint-tilpasninger som til sammen utgjør et prosjektstyringsverktøy. Det blir satt opp en porteføljeside der en får en oversikt over prosjekter og kan opprette nye prosjektrom. Hvert prosjektområde opprettes som en Microsoft 365 gruppe og det settes opp en del lister, en del standardelementer og logikk for å gjennomføre et prosjekt etter prosjektveiviserens modell. Prosjektveiviseren er Difis anbefalte prosjektmodell for gjennomføring av digitaliseringsprosjekter i offentlige virksomheter.

Prosjektportalen ble i sin tid utviklet for Asker kommune og Kommit. Versjonen som her foreligger er utviklet av Puzzlepart basert på de samme prinsippene som den opprinnelige versjonen.

## For nedlasting og installasjon av produktet

All nødvendig informasjon finner du på Prosjektportalen 365 sine sider på [GitHub](http://github.com/Puzzlepart/prosjektportalen365)

## Markdown Linting

Dette prosjektet bruker [markdownlint](https://github.com/DavidAnson/markdownlint) for å sikre konsistent formatering og struktur i dokumentasjonen.

### Kjøre linting lokalt

For å sjekke alle Markdown-filer i prosjektet:

```bash
npm install
npm run lint
```

For å automatisk fikse enkle linting-feil:

```bash
npm run lint:fix
```

### Konfigurasjon

Linting-reglene er definert i `.markdownlint.json` i prosjektets rotmappe. Følgende regler er deaktivert for å passe prosjektets dokumentasjonsstil:

- `MD013` (line-length): Ingen begrensning på linjelengde
- `no-inline-html`: Tillater bruk av inline HTML (nødvendig for Jekyll)
- `MD025` (single-title): Tillater H1 i innhold når front matter har title
- `MD045` (no-alt-text): Ikke krav om alt-tekst på alle bilder
- `MD003` (heading-style): Tillater blanding av setext og atx heading-stiler
- `MD029` (ol-prefix): Tillater fleksible nummereringer i ordnede lister
