# Spinozos „Etika"

Benedikto Spinozos „Etikos", įrodytos geometrijos metodu, elektroninis leidimas. Kūrinys išdėstytas kaip tarpusavyje susietų apibrėžimų, aksiomų ir teoremų tinklas, paremtas priežastine logika.

## Svetainė

Svetainė prieinama: [4arturas.github.io/spinoza-vault](https://4arturas.github.io/spinoza-vault/)

## Struktūra

- **content/** — visos Markdown bylos (371 failas) su YAML frontmatter
  - `index.md` — pagrindinis puslapis su turiniu
  - `I dalis - Apie Dievą.md` – `V dalis - Apie intelekto galią...md` — penkios dalys
  - `Priedėlis` — išankstinių nuostatų aptarimas
- **quartz.config.yaml** — Quartz svetainės konfigūracija

## Technologijos

- [Quartz v5](https://quartz.jzhao.xyz/) — statinių svetainių generatorius
- [Obsidian](https://obsidian.md/) — Markdown redaktorius (naudotas turiniui kurti)
- GitHub Actions — automatinis deplojimas į GitHub Pages

## Paleidimas vietoje

```bash
npm install
npx quartz build --serve
```

Svetainė bus prieinama `http://localhost:8080`.

## Deplojimas

Deplojimas vyksta automatiškai kiekvieną kartą atlikus `git push` į `main` šaką. GitHub Actions workflow pastato svetainę ir paskelbia ją GitHub Pages.

Licencija: turinys yra viešosios sferos kūrinys.
