Полностью заменяет ресурс (update или create). Idempotent, тело — полный объект.

```bash
curl -X PUT http://localhost:3000/users/1 -H "Content-Type: application/json" -d '{"name":"Bob","age":35,"city":"Paris"}'  
```

На сервере: UPDATE users SET name='Bob', age=35, city='Paris' WHERE id=1 (или INSERT если нет).