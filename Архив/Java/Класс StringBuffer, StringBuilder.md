Классы **_StringBuilder_** и **_StringBuffer_** по своему предназначению близки к классу [[Класс String|String]]. При этом содержимое и размеры объектов классов StringBuilder и StringBuffer можно изменять.

Основное отличие этих классов в том, что StringBuffer обеспечивает потоко-безопасность, а StringBuilder – нет. При этом класс StringBuilder  дает более высокую скорость обработки. Его следует применять, если многопоточность не используется.

- [[Создание строки через StringBuilder]]
- [[Сравнение объектов StringBuilder]]


Методы:
- [[capacity()|capacity]]
- [[ensureCapacity()|ensureCapacity]]
- [[setLength()|setLength]]
- [[toString()|toString]]
- [[append()|append]]
- [[insert()|insert]]
- [[delete()|delete]] | [[deleteCharAt()|deleteCharAt]]
- [[reverse()|reverse]]
В классе StringBuilder присутствуют также методы, аналогичные методам класса String, такие как [[replace()]], [[substring()]], [[charAt()]], [[length()]], [[getChars()]], [[indexOf()]] и др.
Есть некоторые особенности использования этих методов, в отличие от класса String.