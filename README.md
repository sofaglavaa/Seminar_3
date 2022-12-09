# Seminar_3

Работа на семинаре

# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создатся репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория, используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status* и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

---
## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

### Удаление веток

Для удаления ветки ввести команду "git branch -d 'name branch'"

---

## Добавление картинок
Для того, чтобы добавить **картинку**, надо:

![картинка](https://moskeram.ru/upload/iblock/fe6/fe66c63e25ea9f4f73e490fe41ae1409.jpg)

## Добавление ссылки

Для того, чтобы добавить **ссылку**, надо:
[работа с текстом .md](https://gist.github.com/Jekins/2bf2d0638163f1294637)

## Добавление цитат и списков
 
Чтобы добавить *одиночную* цитату, надо поставить знак ">":
>Земля в иллюминаторе

Чтобы добавить *вторую цитату*, надо поставить знак ">>":
>Земля в иллюминаторе
>>Россия - родина слонов
---
Для добавления *маркированного списка* надо поставить знак * перед позицией:

* Первая строка
* Вторая строка
* Третья строка

Для добавления *нумерованного списка* надо ставить цифру номера позиции: 1.:

1. Первая строка

2. Вторая строка

3. Третья строка








