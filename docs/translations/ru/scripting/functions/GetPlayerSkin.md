---
title: GetPlayerSkin
description: Возвращает скин игрока.
tags: ["player"]
---

## Описание

Возвращает значение ID скина игрока.

| Параметр | Описание                                 |
| -------- | ---------------------------------------- |
| playerid | Игрок, скин которого хотите получить.    |

## Возвращаемые данные

ID скина (0 если значение не верное)

## Примеры

```c
playerskin = GetPlayerSkin(playerid);
```

## Примечания

:::tip

Возращение нового значения ID скина после использования SetSpawnInfo будет после спавна игрока с новым скином. Возвращает старое значение скина, если игрок заспавнился при использовании функции SpawnPlayer.

:::

## Связанные функции

- [SetPlayerSkin](SetPlayerSkin.md): Устанавливает скин игрока.