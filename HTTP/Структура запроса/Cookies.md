Специальный заголовок для хранения состояний (**session**). Cookie — строка, устанавливаемая сервером в Set-Cookie (ответ) и отправляемая клиентом в Cookie (запрос). Полезны для аутентификации (например, JWT в cookie). В Postgres: cookie может хранить user_id для сессии.  

Пример запроса с cookie:
![[Pasted image 20250810224115.png]]

На сервере: Проверить cookie, затем SELECT * FROM users WHERE id = decode(session_id).