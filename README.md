# XO
Xoritonova zdractвуйте
```
git config --global user.name
git config --global user.email
```
> логинимся
```
cd (путь к папке)
```
> указываем путь к папке в гите (можно проверить в какой мы папке командой "pwd")
```
git init
```
> создаем локальный репозиторий
```
git add .
```
>добавляет файлы из репозитория в индекс
```
git commit -m "commit`"
```
>сохраняет текущие изменения
```
git status
```
>показывает состояние репозитория
```
git log
```
>показывает историю коммитов
## Перенос репозитория на удаленный
git remote add origin
```
>подключает к локальному репозиторию удаленный
```
git push -u origin main
```
>переносит локальный репозиторий
```
 git remote -v
```
>чтобы посмотреть какой удаленный репозиторий подключен
```
## Работа с ветками
```
git branch new_branch_name
```
>создание новой ветки
```
git branch -M main
```
>создает основную ветку
```
git checkout -b new_branch_name
```
>автоматический переход в ветку
```
git branch
```
>просмотр списка веток
```
git branch -d existing_branch_name
```
>удаление ветки
```
git merge existing_branch_name
```
>слияние двух веток
