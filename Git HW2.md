# GitHub. Homework #2
1. На локальном репозитории сделать ветки для: 
- [Postman](https://github.com/pyatkov-vladimir/study/tree/Postman)
- [Jmeter](https://github.com/pyatkov-vladimir/study/tree/Jmeter)
- [CheckLists](https://github.com/pyatkov-vladimir/study/tree/CheckLists)
- [Bug Reports](https://github.com/pyatkov-vladimir/study/tree/Bug_reports)
- [SQL](https://github.com/pyatkov-vladimir/study/tree/SQL)
- [Charles](https://github.com/pyatkov-vladimir/study/tree/Charles)
- [Mobile testing](https://github.com/pyatkov-vladimir/study/tree/Mobile_Testing)
  
`git branch <branch_name>`

2. Запушить все ветки на внешний репозиторий

`git push origin <branch_name>`

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта

`git checkout Bug_Reports`
`cat > BugReports.txt`

4. Запушить структуру багрепорта на внешний репозиторий

`git add BugReports.txt`
`git commit -m "Структура баг репорта"`
`git push`

8. Вмержить ветку Bug Reports в Main

`git checkout main`
`git merge Bug_Reports`

10. Запушить main на внешний репозиторий

`git push`

12. В ветке CheckLists набросать структуру чек листа

`git checkout CheckLists`
`cat > CheckList.txt`

14. Запушить структуру на внешний репозиторий

`git add CheckList.txt`
`git commit -m "Структура чеклиста"`

16. На внешнем репозитории сделать Pull Request ветки CheckLists в main.
17. Синхронизировать Внешнюю и Локальную ветки Main -
18. `git pull`
`git push`
