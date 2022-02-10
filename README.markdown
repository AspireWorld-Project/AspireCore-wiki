**Внимание! Не рекомендуется к использованию в продакшине! Текущая версия ядра - 0.2.8-stable. ПОЖАЛУЙСТА, ХОРОШО ПОДУМАЙТЕ, ПЕРЕД ТЕМ КАК ИСПОЛЬЗОВАТЬ ЭТО!**

Ядро UltraMine - это **реализация Minecraft сервера на основе MinecraftForge**, действительно пригодное для промышленного использования на высоконагруженных серверах с сотнями модов.


**До версии от zaxar163 && fixer s5a4ed1sa7. Проще говоря, по ванилле ядра UltraMine, это никак не используется и не реализуется.**
```yaml
В отличии от Cauldron, Не реализует Bukkit API и не поддерживает плагины.
```
**В нашей версии:**
```yaml
Имплементирован Cauldron вглубь ядра.
Реализует собой из коробки Bukkit API && Базовый Spigot API, поддерживает 99.90% плагинов,
реализовано общение мод <-> плагин.

Конечно же, не всё так прекрасно, как может казаться.

Всего ивентов в Bukkit API: 158.
Имплементированно нами: 147.
Не имплементированно ещё: 11.
Прогресс ивентов: 93%

ОБЩИЙ ПРОЦЕНТ ИМПЛЕМЕНТИРОВАНИЯ BUKKIT API В ЯДРО: 80%
```

Нигде в этих статьях вы не найдете ни описания ядра, ни чем оно отличается от MinecraftForge. Здесь только прикладная часть: конфигурация, использование, обслуживание. Никакого маркетинга.

* Фиксы ядра от s5a4ed1sa7.
  * [Фиксы](.github/s5a4ed1sa7/s5a4ed1sa7.markdown)
  * [Даты фиксов](.github/s5a4ed1sa7/FixDate.markdown)
  * [ChangeLog](.github/s5a4ed1sa7/ChangeLog.markdown)
* [Быстрый старт](.github/Quickstart.markdown)
* Конфигурация сервера
  * Базовая настройка сервера - [server.yml](.github/server.yml)
  * Настройка миров - [worlds.yml](.github/worlds.yml)
  * Пояснение за права (Permissions) - [Permissions](.github/Permissions.markdown)
  * Блокировка предметов - [itemblocker.yml](.github/itemblocker.yml)
* [Спавн мобов в UltraMine](.github/MobSpawn.markdown)

Прочие ссылки:
* [Исходники ядра](https://github.com/AspireWorld-Project/AspireCore)
* [Maven репозиторий (UltraMine based)](https://maven.ultramine.ru/org/ultramine/core)

Известные несовместимости (моды):
* FastCraft
* ServerTools
* ForgeEssentials
* DragonAPI
* zzzzzcustomconfigs
* NEID
Известные несовместимости (плагины):
* Пока таковых нет, но они могут появиться.
* Дабы сразу попытаться всё исправить, рекомендую не умалчивать,
* и сразу писать об этом.