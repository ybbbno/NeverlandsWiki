---
description: Картинки в майнкрафте вау
icon: image
---

# Кастомные картинки

[\*ссылка на плагин\*](https://modrinth.com/plugin/imageframe)

### Как создать кастомную картинку?

1. Найти прямую ссылку на картинку (загуглить или там допустим на [imgur](https://imgur.com/) загрузить) (поддерживаются только png/jpeg/webp/gif)
2. Взять в руки карту и загрузить на неё картинку ([#zakreplenie-kartinki-na-karte](kastomnye-kartinki.md#zakreplenie-kartinki-na-karte "mention"))

Если у вас возникнут какие-то проблемы, то обращайтесь в тикет

### Закрепление картинки на карте

Для этого нужно иметь прямую ссылку на файл картинки и после использовать команду, держа в руках карту: `/imageframe create name url width height`

> _Пример 1:_ `/imageframe create Example https://example.com/example.png 1 1`
>
> _Пример 2:_ `/imageframe create cat https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQP9q8KlWl1T7bbaK4opPztjZwRoj9xKODDtW94VmiXUqymTaOH3-dkA2UM 2 2`

#### `name - название картинки`

> Название, которое будет показываться у карты в описании
>
> _Пример 1:_ `Example`
>
> _Пример 2:_ `cat`

#### `url - ссылка на картинку`

> Прямая ссылка на картинку (поддерживаются только png/jpeg/webp/gif)
>
> Можно использовать [imgur](https://imgur.com/) или подобные сервисы, если картинка не с интернета
>
> _Пример 1:_ `https://example.com/example.png`
>
> _Пример 2:_ `https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQP9q8KlWl1T7bbaK4opPztjZwRoj9xKODDtW94VmiXUqymTaOH3-dkA2UM`

#### `width и height - ширина и высота картинки`

> Картинка может быть как 1x1, так и 2x1, так и 2x3, в зависимости о того, насколько большую вы хотите. Чем больше картинка, тем больше нужно карт для её создания, т.е. для картинки 2x3 нужно 2 \* 3 = 6 карт
>
> _Пример 1:_ `1 1`
>
> _Пример 2:_ `2 2`

### Удаление картинки на карте

В любой момент вы можете использовать `/imageframe delete name` для удаления картинки со своей карты

#### `name - название картинки`

> Название, которое будет показываться у карты в описании
>
> _Пример 1:_ `Example`
>
> _Пример 2:_ `cat`
