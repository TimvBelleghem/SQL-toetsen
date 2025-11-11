# Oefening 4 — Boeken van Dan Brown

Je werkt op de databank **boeken.sqlite**.  
Deze bevat één tabel **Boeken** met volgende kolommen:

| Kolom | Omschrijving |
|-------|---------------|
| BoekID | Uniek boeknummer |
| Titel | Naam van het boek |
| Auteur | Auteur van het boek |
| Genre | Genre van het boek |
| Jaar | Publicatiejaar |
| Paginas | Aantal pagina’s |
| Taal | Taal van het boek |
| Prijs | Verkoopprijs in euro |
| Beschikbaar | 1 = beschikbaar, 0 = niet beschikbaar |

---

## Opdracht

Toon **alle boeken geschreven door Dan Brown**.  
Geef de kolommen: `Titel`, `Auteur`, `Genre`, `Jaar`, `Prijs`.

Gebruik een `WHERE`-voorwaarde om enkel zijn boeken te selecteren.
