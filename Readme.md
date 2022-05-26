# Инструкция по работе с GIT

## Что такое GIT?

## Подготовка репозитория
Для того, чтобы создать репозиторий, используется команда *git init*. Для этого необходимо написать в терминале в папке будущего репозитория *git init*.
## Создание “сохранений”

### Добавление файла к коммиту
Для добавления файла к коммиту используется команда *git add*. Пишется она следующим образом:  *git add <имя файла>* в терминале в папке с созданным репозиторием.

### Создание коммита
Для создания нового "сохранения" используется команда *git commit*. Используется она следующим образом: в терминале с папкой-репозиторием пишется *git commit -m “сообщение к коммиту на английском”* Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**!!!

## Журнал изменений

## Перемещение между коммитами
Для перемещения между сохранениями используется команда *git checkout*. Для того, чтобы переместиться на указанный комит в терминале в папке с репозиторием пишем *git checkout <номер коммита>*. **Номер коммита** берется из журнала изменений, о котором сказано выше. После перемещения на указанный коммит мы попадаем в состояние *detached head*. Чтобы вернуться к обычной работе, нужно ввести команду *git checkout master*.


## Ветки в GIT

## Слияние веток и разрешение конфликтов

## Удаление веток
