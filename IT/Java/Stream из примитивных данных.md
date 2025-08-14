
Для работы с примитивными типами **(int, double, long**) используются специализированные потоки, чтобы избежать авто упаковки.

- **IntStream.range(int start, int end)**
	Генерирует последовательность целых чисел от start до end - 1.

**Пример:**
![[Pasted image 20250409222847.png]]


- **IntStream.rangeClosed(int start, int end)**
	Включает конечное значение end.

**Пример:**
![[Pasted image 20250409222951.png]]
