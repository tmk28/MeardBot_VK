# MeardBot_VK
Название: Бот ВКонтакте
Автор: Трифонов Михаил

Файловая структура проекта:
- Bot.py - "тело" бота, обработка и отправка сообщений
- Hello_ans.py - варианты сообщений, которыми бот здоровается с пользователем
- Bye_ans.py - варианты сообщений, которыми бот прощается с пользователем
- Crafts.py - словарь крафтов блоков, инструментов, брони, предметов
- Mobs.py - словарь информации о мобах
- Help.py - текст для команды "help"
- TegComms.py - список с элементами типа tuple, в нем хранятся внутриигровые команды и их описание
- Comms.py - формирование страницы с игровыми командами

Библиотеки Python:
- vk_api
- vk_api.longpoll
- random

Проект представляет собой бота для социальной сети ВКонтакте.
Предназначен для предоставления информации про различные элементы игры Minecraft. Доступны следующие команды: help, !бот крафт [предмет], !бот моб [моб], !бот игровые команды.
При обращении к боту в беседе сообщества необходимо писать "!бот " перед непосредственно самой командой. Это сделано для того, чтобы бот не реагировал на каждое сообщение и пользователи имели возможность пообщаться между собой. При обращении к боту в личных сообщениях писать "!бот " не надо.

