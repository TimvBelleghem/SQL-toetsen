# Oefening 2 — Studenten met een hoog gemiddelde

Je werkt op de databank **studenten.sqlite**.  
Deze bevat de tabel **Studenten** met volgende kolommen:

| Kolom | Omschrijving |
|-------|---------------|
| StudentID | Uniek identificatienummer |
| Voornaam | Voornaam van de student |
| Achternaam | Achternaam van de student |
| Geslacht | 'M' of 'V' |
| Geboortedatum | Datum in de vorm YYYY-MM-DD |
| Stad | Woonplaats |
| Studierichting | Richting waarin de student studeert |
| Jaar | Huidig leerjaar (4, 5 of 6) |
| Gemiddelde | Gemiddelde score van de student |
| Credits | Aantal behaalde studiepunten |

---

## Opdracht

Toon **alle studenten met een gemiddelde score hoger dan 16**.  
Geef alle kolommen weer (`SELECT *`).

De tabel moet dus enkel die studenten bevatten waarvan `Gemiddelde > 16`.
