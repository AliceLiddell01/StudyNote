**Session** управляет контекстом (cache), **транзакции** — commit/rollback. В отличие от JDBC PreparedStatement, Hibernate автоматизирует SQL.

- **Сохранение** (`persist`): Делает временный объект управляемым, планируя его сохранение в БД.
![[Pasted image 20250811224632.png]]

- **Чтение** (`get`)
![[Pasted image 20250811225034.png]]

- **Обновление** (`merge`)
![[Pasted image 20250811225142.png]]

- **Удаление** (`remove`)
![[Pasted image 20250811225215.png]]