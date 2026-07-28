---
description: Звуки в майнкрафте вау
icon: compact-disc
---

# Кастомные пластинки

[\*ссылка на плагин\*](https://modrinth.com/plugin/customdiscs-plugin)

### Как создать кастомную пластинку?

1. Скачать аудиофайл (поддерживаются только mp3/wav/flac) с ютуба или спотифая или чем вы там пользуетесь
2. Загрузить аудиофайл на облачный диск и использовать прямую ссылку на файл (объяснение с гугл диском находится в [#skachivanie-audiofaila](kastomnye-plastinki.md#skachivanie-audiofaila "mention"))
3. Скачать аудиофайл на сам сервер ([#skachivanie-audiofaila](kastomnye-plastinki.md#skachivanie-audiofaila "mention"))
4. Взять платинку в руки и записать аудиофайл на неё ([#zapis-audiofaila-na-plastinku](kastomnye-plastinki.md#zapis-audiofaila-na-plastinku "mention"))

Если у вас возникнут какие-то проблемы, то обращайтесь в тикет

### Скачивание аудиофайла

Для этого нужно использовать команду: `/cd download url filename.extension`

> _Пример 1:_ `/cd download "https://example.com/mysong.mp3" example.mp3`&#x20;
>
> _Пример 2:_ `/cd download "https://drive.google.com/uc?export=view&id=1HUZtPcSScay3lIOuOo-fXXpt62zF4wWO" UNDO_UNDO.mp3`

#### `url - ссылка на аудиофайл`

> Должно быть в двойных кавычках (т.е. "url") и должна быть прямая ссылка на аудиофайл.
>
> Можно использовать гугл диск для загрузки файла, т.е. его нужно загрузить к себе на гугл диск, после открыть доступ по ссылке и ссылку на файл нужно загрузить сюда: [https://lonedev6.github.io/gddl/](https://lonedev6.github.io/gddl/)
>
> Оттуда скопируйте ссылку ниже в команду и всё должно работать (если не работает - пишите в тикет).
>
> _Пример 1:_ `"https://example.com/mysong.mp3"`
>
> _Пример 2:_ `"https://drive.google.com/uc?export=view&id=1HUZtPcSScay3lIOuOo-fXXpt62zF4wWO"`

#### `filename.extension - название аудиофайла`

> Имеется в виду, что между filename и extension нужно поставить точку.
>
> extension - это mp3/wav/flac, другие расширения файлов нельзя.
>
> _Пример 1:_ `example.mp3`
>
> _Пример 2:_ `UNDO_UNDO.mp3`

### Запись аудиофайла на пластинку

Для этого нужно сначала скачать файл и после использовать команду, держа в руках пластинку: `/cd create filename.extension name`

> _Пример 1:_ `/cd create example.mp3 "Example"`
>
> _Пример 2:_ `/cd create UNDO_UNDO.mp3 "UNDO UNDO"`

#### `name - название трека`

> Название трека на пластинке в двойных ковычках (т.е. "name").
>
> _Пример 1:_ `"Example"`
>
> _Пример 2:_ `"UNDO UNDO"`

### Сбросить пластинку

Возьмите в руку пластинку и используйте команду: `/cd revert`

### Кастомные рога/звуки голов

Помимо пластинок эти все команды можно применить и к рогам/головам.
