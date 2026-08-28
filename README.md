# Testovi C / C1 kategorija — objedinjena baza pitanja

Web aplikacija za pripremu teorijskog dela vozačkog ispita za C i C1 kategoriju.

Sadrži **1902 jedinstvena pitanja** (bez duplikata), sa slikama, izvučena i deduplikovana
iz svih 45 zvaničnih testova auto škole **Euro Start** (Zrenjanin) — [eurostart.co.rs](https://www.eurostart.co.rs/).

## Funkcionalnosti

- **Interaktivni mod** — biraš odgovor, dobijaš odmah povratnu informaciju (tačno/netačno) i konačan skor
- **Pregled sa rešenjima** — tačni odgovori su odmah prikazani, bez klikanja, za brzo učenje
- Filtriranje po 7 oblasti (Pravila saobraćaja, Vozila, Saobraćajna signalizacija, Vozači, Osnove bezbednosti saobraćaja i pojmovi, Posebne mere i ovlašćenja, Posledice)
- Biranje broja pitanja u sesiji (30/50/100/sva/proizvoljno) i promešan redosled
- Pitanja sa više tačnih odgovora su posebno označena
- Automatsko čuvanje napretka (localStorage) — osvežavanje stranice ne resetuje sesiju
- "Pregledaj netačne" — ponavljanje samo pitanja na koja nije odgovoreno tačno

## Napomena o podacima

5 od 1902 pitanja (0.26%) je označeno kao "neposvrđeno" — izvorni sajt na tim mestima
nije imao pouzdano označen tačan odgovor ni u jednoj od 45 verzija tog pitanja, pa je
tačan odgovor ostavljen neoznačenim umesto da se nagađa. Ta pitanja su jasno vizuelno
označena u aplikaciji.

## Pokretanje

Aplikacija je jedan samostalan `index.html` fajl (bez servera, bez build koraka) +
folder `images/` sa slikama pitanja. Otvori `index.html` direktno u browseru, ili je
posluži preko GitHub Pages / bilo kog statičkog hostinga.

---

*Neslužbena priprema za teorijski ispit. Izvor pitanja: Auto škola Euro Start, Zrenjanin.*
