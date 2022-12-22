# Инструкция по работе с программой Git

Git это программа для ...

## Для того чтобы создать (инициализировать) новый репозиторий в текущей папке используется команда:

    git init     

## Проверка состояния репозитория

Для того чтобы проверить состояние репозитория нужно выполнить команду

    git status  

 ## Добавление изменений к отслеживанию

 Для того чтобы добавить изменение к отслеживанию (в "индекс) нужно выполнить команду:

    git add <filename>

Homework:

    git init
    git status
    git add <filename>
    git commit
    git commit -m "message"
    git commit -a
    git commit -am "message"
    git log
    git log --oneline
    git log --all
    git log --oneline --all
    git checkout <hash>
    git diff
    git diff <hash1> <hash2>
    