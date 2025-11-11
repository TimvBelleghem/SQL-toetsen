# Oefening 13 — Boeken in voorraad

Je werkt op de databank **Boeken.sqlite**.  
Deze bevat één tabel **Boeken** met volgende kolommen:

| Kolom | Type | Beschrijving |
|--------|-------|--------------|
| BoekID | INTEGER | Uniek ID van het boek |
| Titel | TEXT | Titel van het boek |
| Auteur | TEXT | Naam van de auteur |
| Genre | TEXT | Soort boek |
| Jaar | INTEGER | Jaar van uitgave |
| Pagina’s | INTEGER | Aantal bladzijden |
| Taal | TEXT | Taal van het boek |
| Prijs | REAL | Verkoopprijs |
| Beschikbaar | INTEGER | 1 = ja, 0 = nee |

---

## Opdracht

Toon **Titel**, **Auteur** en **Genre**
voor boeken waarvan de **titel begint met 'De'**.