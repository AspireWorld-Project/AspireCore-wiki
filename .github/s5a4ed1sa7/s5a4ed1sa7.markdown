# Фиксы ядра от s5a4ed1sa7

**Первый фикс:**
* **Убрана проверка ForgeVersion**
  * **Причины:**
    * Мёртвая ссылка Forge Maven.
  * Включить всё же можно, в **server.yml**

**Второй фикс:**
* **Фикс рестартера**
  * **Что было не так:**
    * До этого рестартер просто выключал сервер.
    * Сейчас же, он адекватно закрывает + включает сервер.
  * **Найденные баги:**
    * **Рестартер после первого рестарта перестаёт закрывать старую консоль.**