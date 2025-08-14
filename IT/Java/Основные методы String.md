
- **length( )** — возвращает длину строки:
![[Pasted image 20250311214152.png]]

- **charAt(int index)** — возвращает символ по индексу:
![[Pasted image 20250311214317.png]]

- **substring(int beginIndex, int endIndex)** — извлекает подстроку
![[Pasted image 20250311214344.png]]

- **toLowerCase( )** и **toUpperCase( )** — изменяет регистр:
![[Pasted image 20250311214552.png]]

- **replace(char oldChar, char newChar)** — заменяет символы:
![[Pasted image 20250311214953.png]]

- **contains(CharSequence s)** — проверяет наличие подстроки
![[Pasted image 20250311215322.png]]

- **indexOf(String str)** — возвращает индекс первого вхождения:
![[Pasted image 20250311215126.png]]

- **lastIndexOf(String str)** — Возвращает индекс последнего вхождения подстроки в строке. Если подстрока не найдена, возвращает -1.
![[Pasted image 20250312000237.png]]

- **split(String regex)** — разделяет строку на массив
![[Pasted image 20250311215530.png]]

- **trim( )** — убирает пробелы в начале и конце
![[Pasted image 20250311215627.png]]

- **String.format( )** — создание форматированной строки
![[Pasted image 20250311233214.png]]**Спецификаторы:** %s — строка, %d — целое число, %f — число с плавающей точкой.

- **valueOf(Object obj)** — этот статический метод для конвертации примитивных типов или объектов в String.
![[Pasted image 20250311234759.png]]

- **intern( )** — добавляет строку в пул строк, если она там ещё не существует.
![[Pasted image 20250311235332.png]]

- **getChars(int srcBegin, int srcEnd, char[ ] dst, int dstBegin)** — Копирует символы из строки в указанный массив char[ ] в заданном диапазоне.
![[Pasted image 20250311235557.png]]
**srcBegin:** Начальный индекс (включительно).
**srcEnd**: Конечный индекс (исключительно).
**dst:** Массив назначения.
**dstBegin:** Начальный индекс в массиве назначения.

- **isEmpty( ) —** Проверяет, пуста ли строка (длина равна 0).
![[Pasted image 20250311235926.png]]

- **compareToIgnoreCase(String anotherString)** — сравнивает две строки лексикографически, игнорируя регистр символов.
![[Pasted image 20250312000622.png]]
0 - строки равны
0> - первая строка больше
0< - вторая строка больше

- **equalsIgnoreCase(String anotherString)** — сравнивает две строки на равенство, игнорируя регистр символов.
![[Pasted image 20250312000855.png]]

- **contentEquals( )** - сравнивает содержимое строки с объектом StringBuilder
![[Pasted image 20250312001857.png]]