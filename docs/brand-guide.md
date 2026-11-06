# Brand Hannah Kodad

Zkrácená veřejná verze brand dokumentu (listopad 2026): positioning, architektura značky, jazyky a struktura webu.

## Positioning

| Jazyk | Hlavní věta | Podtitul |
| --- | --- | --- |
| švédsky | Hannah Kodad – Hemma i norr | Teknik, natur, skapande. |
| česky | Hannah Kodad – Doma na severu | Technologie, příroda, tvorba. |
| anglicky | Hannah Kodad – At home in the North | Technology, nature, creation. |

Švédsko je můj domov a zvu ostatní k sobě. Půlka mé práce je online ve světě dat, systémů a AI, půlka offline v přírodě. Obojí dělám naplno, protože to sama žiju.

**Tón:** klidný, opravdový, s humorem. Švédské *lagom*. Radost, kompetence a odvaha.

**Nosná nit:** odvaha ke změně.

## Architektura značky

```
HANNAH KODAD – Hemma i norr (sv → cs → en)
Teknik, natur, skapande
│
├── Venku / Ute
│     Průvodkyně a organizátorka
│     Treky a Objevuj Švédsko s Babičkou na treku
│
├── Smartflow AI
│     Datová a AI architektura a správa pro malé firmy
│     One-to-one mentoring: technologie + osobní růst
│
└── Tvořím / Skapar
      Zpravodaj odvážné ženy / Nyhetsbrev av en modig kvinna
      Haiku
      My Sweden Style
      Zahrada
```

Smartflow AI je vlastní pod-značka s vlastním názvem a vizuálem. Babička na treku je partnerská značka.

## Jazyky

Web přibývá postupně: **švédština → čeština → angličtina**. Jazykové verze nejsou doslovné překlady; menu je stejné, důrazy se liší.

- **Švédská verze:** důraz na Smartflow AI a život ve Švédsku.
- **Česká verze:** důraz na Venku a Smartflow AI pro české klienty.
- **Anglická verze:** stručně, kdo jsem, Venku pro zahraniční turisty, kontakt.

## Struktura webu

**Menu (sv / cs):** Start · Om mig / O mně · Ute / Venku · Smartflow AI · Skapar / Tvořím · Kontakt

| Stránka | Obsah |
| --- | --- |
| Start | jméno + Hemma i norr, obrázek, dveře Venku · Smartflow AI · Tvořím, dole poslední článek nebo haiku |
| Om mig / O mně | příběh jako korálky na šňůrce |
| Ute / Venku | treky, Objevuj Švédsko s Babičkou na treku |
| Smartflow AI | architektura a správa · one-to-one mentoring, odkaz na web Smartflow AI |
| Skapar / Tvořím | Zpravodaj · Nyhetsbrev · Haiku · My Sweden Style · Zahrada |
| Kontakt | kontaktní údaje, odkazy na sítě |

### Struktura repozitáře

```
personal-website/
├── index.html        švédsky (výchozí)
├── om-mig.html ...
├── cs/
│   ├── index.html    česky
│   └── o-mne.html ...
├── en/               později
├── css/styles.css    společné pro všechny jazyky
├── images/           společné
└── docs/             dokumentace (tento soubor)
```

Každá stránka má `lang="sv"`, `lang="cs"` nebo `lang="en"`. Přepínač jazyka vede na protějšek téže stránky, ne na úvod.

### Barvy

`#fac396` · `#dbafc2` · `#bac696` · `#1d5c42` · `#ebdd9c` · `#da487e` · `#72b5cc`
