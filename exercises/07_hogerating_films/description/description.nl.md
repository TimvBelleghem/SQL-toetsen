# Oefening 7 - High rating


Je werkt op de databank **films.sqlite**.  
Deze bevat één tabel **Films** met volgende kolommen:

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

Toon **Titel**, **Jaar** en **Rating**
voor films die na **2010** zijn uitgebracht
en een **Rating groter dan 8** hebben.

Sorteer het resultaat **aflopend** op `Rating`.