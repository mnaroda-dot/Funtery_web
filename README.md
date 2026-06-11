# Funtery web

Staticky webovy navrh pro firmu Funtery, zamereny na B2B prezentaci zakazkoveho siti technickeho a firemniho textilu.

Web je pripraveny jako jednoducha vicestrankova staticka prezentace bez build procesu. Lze ho otevrit primo v prohlizeci nebo nasadit na Netlify.

## Struktura

- `index.html` - uvodni stranka a rozcestnik
- `sluzby.html` - prehled sluzeb
- `materialy.html` - materialy, vlastnosti a dokumentace
- `realizace.html` - galerie realizaci a referencni karty
- `kontakt.html` - kontaktni a poptavkova stranka
- `styles.css` - sdilene styly
- `assets/hero-technical-textiles.png` - hlavni vizual

## Lokalni nahled

Nejjednodussi spusteni:

```bash
python3 -m http.server 4173
```

Potom otevrit:

```text
http://localhost:4173
```

## Nasazeni

Projekt je napojen na GitHub repozitar:

```text
https://github.com/mnaroda-dot/Funtery_web
```

Aktualni Netlify projekt:

```text
https://funteryweb.netlify.app
```

Po pushi do vetve `main` se zmeny nasazuji pres Netlify.

## Poznamky k obsahu

Texty a struktura jsou pripravene pro profesionalni prezentaci pred vetsimi firmami a dopravci. Sekce Realizace a Materialy jsou navrzene tak, aby se daly postupne doplnovat realnymi fotografiemi, materialovymi listy, referencemi a presnymi technickymi podklady.
