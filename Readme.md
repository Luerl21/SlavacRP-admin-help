# Инструкция по использования админ комманд SlavacRP - IP: 45.136.204.27:27015

## Правила сервер SlavacRP
https://docs.google.com/document/d/10ip8LQkliGBWYJKjxR6ugSIcHtC76QwK

# Можно обойтись без всех этих комманд и использовать удобства сервера:

## При принятии жалобы:
Вы можете воздействовать на игрока в меню самой жалобы нажав на соответствующую кнопку, также вы можете написать игркоку сообщение, передать жалобы либо же закрыть.

Чтобы войти в админмод достаточно взять профу админа и в 'C - context menu' навестить на кнопку 'Админмод' и нажать включить, а для выхода нажать выключить.

Чтобы открыть меню логов, в 'C - context menu' нажмите на кнопку 'Логи'

Чтобы просмотреть метки с положениями жертвы и атакущего, в 'C - context menu' нажмите на кнопку 'Пт меню'
# Сами комманды:
## Телепорты
!goto 'steamid или nickname' - тп к игроку

!bring 'steamid или nickname' - тп игрока к себе

!return 'steamid или nickname' - возврат игрока на место до телепортации

## Комманды для разборок
!logs - открыть меню логов

!screengrab 'steamid или nickname' - Получить скриншот экрана игрока

## Ban
!ban 'steamid или nickname' 'время(1,2,3...)' '(y(лет),w(недель),d(дней),h(часов),m(минут),s(секунд))' 'причина'

Если игрок ливнул с сервера, использовать эту комманду:

!banid 'steamid' 'время(1,2,3...)' '(y(лет),w(недель),d(дней),h(часов),m(минут),s(секунд))' 'причина'

## Jail
!jail 'steamid или nickname' 'время в минутах(1,2,3...)' 'причина'

## Команды наказания чатов
!gag 'steamid или nickname' 'время в минутах(1,2,3...)' 'причина' - мут голосового чата

!ungag 'steamid или nickname' - снятие мута голосового чата

!mute 'steamid или nickname' 'время в минутах(1,2,3...)' 'причина' - мут текстового чата

!unmute 'steamid или nickname' - снятие мута текстового чата

## Прочее
!slap 'steamid или nickname' 'урон(1,2,3...)' - ударить игрока на определённое количество урона

!slay 'steamid или nickname' - Убить игрока

!hp 'steamid или nickname' 'хп(1,2,3...)' - выдать определённое количество хп игроку

!armor 'steamid или nickname' 'броня(1,2,3...)' - выдать определённое количество брони игроку

!ignite 'steamid или nickname' 'время в секундах(1,2,3...)' - поджечь игрока на определённое время в секундах

!god 'steamid или nickname' - выдача игроку режима бога

!ungod 'steamid или nickname' - снятие игроку режима бога

!freeze 'steamid или nickname' - заморозить игрока

!unfreeze 'steamid или nickname' - разморозить игрока

!cloak 'steamid или nickname' - выдача игроку невидимости

!uncloak 'steamid или nickname' - снятие игроку невидимости

!strip 'steamid или nickname' - забрать всё оружие у игрока

!respawn 'steamid или nickname' - возродить игрока

!noclip 'steamid или nickname' - включить/выключить игроку noclip

!unarrest 'steamid или nickname' - Разарестить игрока

!setjob 'steamid или nickname' 'профессия' - Принудительно выдать игроку профессю

!forcename 'steamid или nickname' 'имя' - Установить игроку рп имя


## Полезные бинды

Файл с парой команд для облегчения входа/выхода из админ мода и cloak("[" - вход/выход из админ мода, ноклипа, клоака и профы админа; "b" - выход и вход в клоак) Закидывать в папку \GarrysMod\garrysmod\cfg\ , конфиг сам подтянется после перезахода в игру или пишите в консоль exec autoexec

https://cdn.discordapp.com/attachments/462827054556119041/1097271263447240736/autoexec.cfg

# Create by Luerl(Вильгельм Рихард STEAM_0:0:94363213)

## При неточностях писать в Discord: Luerl#0100