# Oefening 1 — Studenten uit Brugge

Je werkt op de databank **Studenten.db**.  
Deze bevat één tabel **Studenten** met volgende structuur:

| Kolom | Omschrijving |
|-------|---------------|
| StudentID | Uniek identificatienummer |
| Voornaam | Voornaam van de student |
| Achternaam | Achternaam van de student |
| Geslacht | 'M' of 'V' |
| Geboortedatum | Datum in de vorm YYYY-MM-DD |
| Stad | Woonplaats van de student |
| Studierichting | Richting waarin de student studeert |
| Jaar | Huidig leerjaar (4, 5 of 6) |
| Gemiddelde | Gemiddelde score van de student |
| Credits | Aantal behaalde studiepunten |

---

## Opdracht

Toon **alle studenten die in Brugge wonen**.

Gebruik een SQL-query die alle kolommen van deze studenten weergeeft.

### Verwachte uitvoer

De tabel moet dus enkel de studenten tonen waarvoor de kolom `Stad` gelijk is aan `'Brugge'`.
