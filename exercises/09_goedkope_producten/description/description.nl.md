# Oefening 9 — Actieve producten

Je werkt op de databank **Producten.sqlite**.  
Deze bevat één tabel **Producten** met volgende kolommen:

| Kolom | Type | Beschrijving |
|--------|-------|--------------|
| ProductID | INTEGER | Uniek ID van het product |
| Naam | TEXT | Naam van het product |
| Categorie | TEXT | Soort product (bv. drank, voeding, elektronica) |
| Prijs | REAL | Verkoopprijs in euro |
| Voorraad | INTEGER | Aantal stuks in voorraad |
| Leverancier | TEXT | Naam van de leverancier |
| Actief | INTEGER | 1 = actief, 0 = niet actief |
| Land | TEXT | Land van herkomst |
| Korting | REAL | Korting in procent |
| DatumToegevoegd | TEXT | Datum waarop product werd toegevoegd |

---

## Opdracht

Toon **Naam**, **Prijs** en **Categorie**
voor producten die **minder dan €10** kosten.

Sorteer oplopend op `Prijs`.