1. git status
2. git add [files] или все то git add .
   - добавляет файлы в stage(промежуточная область)
3. git commit -m "comment"
4. git log - показывает подробную инфо о наших записях commit
5. git log --oneline - показывает краткую инфо о commit
6. git push - добавляет изменения на удаленный репозиторий [rep_link]-ссылка на удаленный репозиторий, и через пробел нужно указать ветку [branch_name]
7. [rep_link] - можно узнать с помощью команды 'git remote -v'
8. [branch_name] - можно узнать с помощью команды 'git branch'
9. [rep_link] можно заменить на origin, [branch_name] можно заменить на master
10. git push origin master
