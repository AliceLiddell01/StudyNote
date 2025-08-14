
- **put(K key, V value)**
Добавляет пару "ключ-значение" или обновляет значение, если ключ уже существует. Возвращает предыдущее значение или **null**, если ключа не было.
![[Pasted image 20250408234616.png]]

- **get(Object key)**
Возвращает значение по ключу или **null**, если ключ не найден.
![[Pasted image 20250408234649.png]]

- **remove(Object key)**
Удаляет пару по ключу и возвращает удаленное значение или null, если ключа не было.
![[Pasted image 20250408234806.png]]

- **containsKey(Object key)**
Проверяет, есть ли указанный ключ в карте.
![[Pasted image 20250408234901.png]]

- **containsValue(Object value)**
Проверяет, есть ли указанное значение в карте.
![[Pasted image 20250408234950.png]]

- **size()**
Возвращает количество пар "ключ-значение" в карте.
![[Pasted image 20250408235055.png]]

- **isEmpty()**
Проверяет, пуста ли карта.
![[Pasted image 20250408235149.png]]

- **clear()**
Удаляет все пары из карты.
![[Pasted image 20250408235225.png]]

- **keySet()**
Возвращает множество (Set) всех ключей.
![[Pasted image 20250408235341.png]]

- **values()**
Возвращает коллекцию (Collection) всех значений. 
![[Pasted image 20250408235431.png]]

- **entrySet()**
Возвращает множество (Set) всех пар "ключ-значение" в виде объектов Map.Entry.
![[Pasted image 20250409000037.png]]

- **putIfAbsent(K key, V value)**
Добавляет пару "ключ-значение", если ключа нет. Возвращает **null** или существующее значение.
![[Pasted image 20250409000216.png]]

- **compute(K key, BiFunction< ? super K, ? super V, ? extends V> remappingFunction)**
Вычисляет новое значение для ключа с помощью переданной функции.
![[Pasted image 20250409000337.png]]

- **merge(K key, V value, BiFunction< ? super V, ? super V, ? extends V > remappingFunction)**
Объединяет значение для ключа с существующим значением через функцию (например, суммирование).
![[Pasted image 20250409000419.png]]