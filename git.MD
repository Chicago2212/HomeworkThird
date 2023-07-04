#### Распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано


*Задание имени и емейла*<br>
git config --global user.name "My Name"<br>
git config --global user.email myEmail@example.com<br>

Для того, чтобы посмотреть все настройки системы, используйте команду:<br>
git config --list<br>

Создание нового репозитория<br>
git init<br>

Определение состояния<br>
git status<br>

Подготовка файлов<br>
git add filename.ext<br>

Если нам нужно добавить все, что находится в директории, мы можем использовать<br>
git add -A<br>
Если же такое произошло изъять оттуда ошибочный файл можно при помощи команды<br>
git reset filename.ext<br>

Фиксация изменений<br>
git commit -m 'Add some code'<br>

Как посмотреть коммиты<br>
git log<br>
git log --graph<br>

Переделать сообщение последнего коммита<br>
git commit --amend -m 'Новый комментарий'<br>

Создание новой ветки<br>
git branch branch_name<br>

Переключение между ветками<br>
git branch branch_name<br>

Слияние веток<br>
git merge branch_name - вливает branch_name в текущую ветку<br>

Удаление ветки<br>
git branch -d local_branch_name<br>