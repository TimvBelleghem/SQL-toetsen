# Oefening 3 — Producten sorteren op prijs

Je werkt op de databank **producten.sqlite**.  
Deze bevat één tabel **Producten** met volgende kolommen:

| Kolom | Omschrijving |
|-------|---------------|
| ProductID | Uniek productnummer |
| Naam | Naam van het product |
| Categorie | Soort product (Voeding, Drank, Elektronica, ...) |
| Prijs | Verkoopprijs in euro |
| Voorraad | Aantal stuks op voorraad |
| Leverancier | Naam van de leverancier |
| Actief | 1 = te koop, 0 = niet meer beschikbaar |
| Land | Land van oorsprong |
| Korting | Percentage korting |
| DatumToegevoegd | Datum waarop het product werd toegevoegd |

---

## Opdracht

Toon alle producten en sorteer de resultaten **van duur naar goedkoop**.  
Geef enkel de kolommen: `Naam`, `Categorie`, `Prijs`, `Voorraad` en `Leverancier`.

Gebruik een SQL-query met `ORDER BY`.
