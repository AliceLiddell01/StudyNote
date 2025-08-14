
- **readAllLines(Path path)**  
	Читает все строки из файла и возвращает их в виде списка **List< String >**.  
**Пример:**
![[Pasted image 20250328173908.png]]

- **readAllBytes(Path path)**  
	Читает все байты из файла и возвращает их как массив **byte[ ]**.
**Пример:**
![[Pasted image 20250328174120.png]]

- **write(Path path, byte[] bytes, OpenOption... options)**
	Записывает массив байтов в файл. Перезаписывает файл, если он существует.
**Пример:**
![[Pasted image 20250328174835.png]]

- **newBufferedReader(Path path)**  
	Возвращает BufferedReader для чтения файла построчно.
**Пример:**
![[Pasted image 20250328175200.png]]

- **newBufferedWriter(Path path, OpenOption... options)**  
Возвращает BufferedWriter для записи в файл.  
**Пример:**
![[Pasted image 20250328175323.png]]