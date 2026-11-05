2026-11-04

- Anonymous GET /recipes → 200 OK, returned full recipe list (all data readable without login).
- Anonymous POST /recipes → 200 OK, created "Evil Test Cake" (new recipe added without login).
- Anonymous DELETE /recipes/4 → 204 No Content, recipe removed from list (data deleted without login).