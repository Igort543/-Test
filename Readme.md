# Инструкция по работе с Git

## Что такое Git
Git - это одна из реализаций распределённых систем контроля версий, что позволяет иметь версионность как в локальном репозитории, так и в удалённом репозитории(общем для всех). Git является на данный момент самой популярной системой контроля версий. 
## Подготовка репозитория
Для создания репозитория используется команда *git init*. В терминале в папке с будущим репозиторием достаточно написать *git init*, и эта папка станет репозиторием.

## Создание фиксаций 
Перед тем как сделать создать новую фиксацию необходимо сохранить изменения в файле, а после добавить его в исходную папку.

### Просмотр состояния репозитория
Здесь текст про *git status*.

### Добавление файла к сохранению
Для добавления файла в текущий коммит используется команда *git add*. Для этого достаточно в терминале с папкой текущего репозитория написать *git add <название файла>*

### Сохранение коммита
Для сохранения коммита используется команда *git commit*. Для этого в терминале с папкой репозитория необходимо написать команду *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Журнал изменений

Для просмотра истории коммитов, то есть истории наших изменений используется команда *git log*. Для этого необходимо в терминале с папкой-репозиторием написать *git log*.

## Перемещение между коммитами

Для того, чтобы перемещаться между коммитами необходимо использовать команду *git checkout*. Для этого в терминале с папкой репозиторием необходимо написать *git checkout <номер коммита>*. Номер коммита берётся из истории изменений. После такого "перемещения" мы попадаем в состояние *Detached head*. Для возвращения в обычное состояние используется команда *git checkout master*.

## Сравнения коммитов

## Ветки в Git

## Слияние веток и решение конфликтов

## Удаление веток
Для удаления ветки используется команда *git branch -d <имя ветки>* Если в удаляемой ветке есть не объединённые изменения, то Git выдаст сообщение об ошибке. Чтобы удалить ветку принудительно используется команда *git branch -D <имя ветки>*