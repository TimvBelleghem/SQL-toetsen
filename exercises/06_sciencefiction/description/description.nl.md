# Oefening 6 — Sciencefictionfilms

Je werkt op de databank **Films.sqlite**.

| Kolom | Type | Beschrijving |
|--------|-------|--------------|
| FilmID | INTEGER | Uniek ID van de film |
| Titel | TEXT | Naam van de film |
| Genre | TEXT | Filmgenre |
| Regisseur | TEXT | Naam van de regisseur |
| Jaar | INTEGER | Jaar van uitgave |
| Duur | INTEGER | Duur in minuten |
| Taal | TEXT | Hoofdt taal van de film |
| Land | TEXT | Productieland |
| Rating | REAL | IMDb-score |
| Beschikbaar | INTEGER | 1 = ja, 0 = nee |

## Opdracht

Toon **Titel**, **Regisseur**, **Jaar** en **Rating**
voor alle films waarvan het genre gelijk is aan `'Science Fiction'`.
