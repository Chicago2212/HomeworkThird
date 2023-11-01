# HomeworkThird
Git commands
git config --global user.name "your_name" - создание имени, под которым будет сохраняться авторстко всех коммитов git config --global user.email "your@e-mail.com" - будет отображать ваш имейл вл всех коммитах
git init - создание, инициализация репозитория
git add - добавление файла
git status - проверка статуса репозитория
git commit -m "You comment" - создание коммита (сохранения), в котором хранятся изменения репозитория
git log - вывод истории коммитов.
cd "directory" - переход в указанную папку.
git checkout - переход в указанный коммит или ветку
git branch - показ всех существующих веток в репозитории
git diff - показывает разницу между коммитами.
git branch -D "existing_branch_name" - удалить указанную ветку
git merge "existing_branch_name" - производит слияние указанной ветки с текущей
Working with remote repository
git remote add https://github.com/someurl... - добавляет удаленный репозиторий

git push origin main - отправляяет изменения в удаленный репозиторий.

git pull - подтягивает изменения из удаленного репозитория.

git merge origin - Слияние удалённого репозитория с локальным выполняется параметром merge с указанием имени удалённого репозитория.

Fork request
Fork
clone Fork
cd fork_name
Create branch_new
checkout branch_new
add-commit-puch (git push --set-upstream original branch_new)
---

Данный репозиторий был создан с целью выполнения домашнего задания № 3 для студентов GeekBrains.
