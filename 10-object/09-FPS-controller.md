# Режим от первого лица
Режим от первого лица (first-person mode).

Персонажа, чтобы смотреть от первого лица, можно создать самому для этого нам понадобятся камера и капсула.

`GameObject > 3D Object > Capsule`

Капсула:
* По-умолчанию она 2 метра в высоту.
* Поднимите капсулу на 10 см от пола.
* Удаляем компонент: `Capsule Collider`
* Добавляем компонент: `Physics > Character Controller`

Камера:
* В Иерархии перетаскиваем камеру на капсулу.
* Position: 0, 0.5, 0
* Rotation: 0, 0, 0

Скрипт:
* Скрипт прикрепляем к капсуле

## Пак Standart Assets
* Перемещаем на сцену: `Standart Assets > Characters > FirstPersonCharacter > Prefabs > FPSController`
* Жмём кнопку `Play` сверху по середине.
* Перемещение: `W, A, S, D`, Прыгать: `Пробел`, Обзор: `Мышь`, Выход: `Ctrl + P` или `Esc`.

## PS:
* Отключите аудио компонент на камере в свойствах, чтобы в консоли не выдавало сообщений.