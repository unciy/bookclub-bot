Telegram-бот для книжного клуба [Ботаним](https://botanim.to.digital).

Команды бота:

- `/start` — приветственное сообщение
- `/help` — справка
- `/allbooks` — все книги, который есть в нашем списке
- `/already` — прочитанные книги
- `/now` — книга, которую сейчас читаем
- `/vote` — проголосовать за следующую книгу
- `/voteresults` — текущие результаты текущего голосования

Голосование доступно только для участников Ботаним

## TODO for today

Порефачить:

- Убрать дублирование блоков кода
- Чтобы отвечать можно было только в vote режиме. Транзакцию проверь
- Чтобы голосовать могли только участники Ботаним
- Клавиатура чтобы ходить по меню — как в `@donate` боте?

Deploy

## TODO

- Refactoring
- Добавить фильтрацию голосования только для тех, кто в Ботаним
- Добавить выделение в `/allbooks` прочитанных книг
- Добавить время разборов по прочитанному
- Добавить отзывы

## Ideas

- Сделать возможность напоминаний тем, кто еще не проголосовал о том, что голосование заканчивается через N часов
- В `/vote` после вывода списка всех книг добавить текущих лидеров по баллам, ТОП-N и количество проголосовавших на данный момент
- Сделать в дополнение к командам меню, чтобы можно было жать по нему и выбирать, куда идти (как в `@donate` боте)
- Возможность поиска книг — возможно с автодополнением
- Возможность предлагать книги для добавления
- Выход из голосования
