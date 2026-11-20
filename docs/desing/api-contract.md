# API-szerződés

| Művelet | Javasolt API | Metódus | Sikeres válasz | Megjegyzés |
|---|---|---|---|---|
| Feladatok lekérése | /api/tasks | GET | 200 OK | Összes feladat lekérése |
| Új feladat létrehozása | /api/tasks | POST | 201 Created | Új feladat mentése |
| Feladat módosítása | /api/tasks/{id} | PUT | 200 OK | Meglévő feladat módosítása |
| Feladat törlése | /api/tasks/{id} | DELETE | 204 No Content | Feladat törlése |
| Feladat teljesítettnek jelölése | /api/tasks/{id}/complete | PATCH | 200 OK | A feladat állapotának módosítása |