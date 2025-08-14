Частично обновляет ресурс (**update**). Idempotent, тело — только изменения.

```bash
curl -X PATCH http://localhost:3000/users/1 -H "Content-Type: application/json" -d '{"age":30}'  
```

На сервере: UPDATE users SET age = 30 WHERE id = 1.