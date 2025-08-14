Создаёт ресурс (**create**). Не idempotent, имеет тело.

```bash
curl -X POST http://localhost:3000/users -H "Content-Type: application/json" -d '{"name":"Alice","age":25,"city":"London"}'  
```

На сервере: INSERT INTO users (name, age, city) VALUES ('Alice', 25, 'London').