### Python for network engineers (https://github.com/pyneng)


---

**11. Модулі**

Різновиди модулів:
- скріпти
- модулі стандартної бібліотеки
	- один файл на python
	- один файл на іншій мові програмування
	- група файлів та каталогів які об'єднані у вигляді одного модуля із використання python package (`файл __init__.py` - спосіб організації)
- соторонні модулі
	- практично завжди не один файл

Правила найменування python файлів:
- розширення файлу - .py
- назва файлу:
	- нижній регістр
	- початок не із цифри
	- слова розділяти нижніми підкресленням

Структура python файла: 
1. Ше-банг `/usr/bin/python3`
2. Кодировка
3. doc-string `''' ... '''`
4. Імпорт із стандартної бібліотеки
5. Імпорт сторонніх модулів
6. Імпорт власних скриптів
