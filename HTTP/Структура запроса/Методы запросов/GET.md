Получает данные (**read**). Безопасный, idempotent (повтор не меняет состояние), нет тела.  

Пример (получить всех пользователей из Postgres):
![[Pasted image 20250810222453.png]]

Ответ: JSON вроде [{"id":1,"name":"John","age":28,"city":"New York"}]. На сервере: SELECT * FROM users.