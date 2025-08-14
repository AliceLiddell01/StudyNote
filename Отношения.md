Hibernate превосходно управляет связями между таблицами. Для этого используются аннотации отношений.

- **`@OneToOne`**: Связь "один к одному" (напр., `User` и `UserProfile`).
- **`@OneToMany`** / **`@ManyToOne`**: Связь "один ко многим" / "многие к одному".
User имеет много Orders (OneToMany), Order ссылается на User (ManyToOne).
- **`@ManyToMany`**: Связь "многие ко многим" (напр., `Student` и `Course`).

![[Pasted image 20250811231037.png]]

![[Pasted image 20250811231458.png]]