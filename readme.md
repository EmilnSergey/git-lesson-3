# Инструкция для работы с Git и удалёнными репозиториями

## -Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка терминала

Для начала работы необходимо единоразово выполнить две команды для обьявления глобальных переменных Git

### git config --global user.name "Your name"

### git config --global user.email yourname@example.com

## Подготовка репозитория

### git init

Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Просмотр состояния репозитория

### git status

Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов

### git commit - m "Имя коммита"

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями

### git checkout

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

### git log

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

## Создание ветки

### git branch "Имя ветки"

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

### git merge "Имя ветки"

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток

### git branch -d "Имя ветки"

Для удаления ветки ввести команду "git branch -d 'name branch'"

Локальные изменения