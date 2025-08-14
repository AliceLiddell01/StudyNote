#Метод #Массивы 

```Java
int[] copyOfRange(int[] original, int from, int to)
```
Создает  массив и копирует в него элементы массива **original** с индекса **from** до индекса **to** (как обычно, не включая этот элемент). Аналогично методу [[Arrays.copyOf()]] существуют перегрузки для различных типов элементов массива.

Пример:
```Java
int[] mas = {1, 2, -3, 4, 25, 6, 17, -1, 9, 6};
int[] d = Arrays.copyOfRange(mas, 4,8); System.out.println(Arrays.toString(d));
```
Получаем на консоли:
**[25, 6, 17, -1]**