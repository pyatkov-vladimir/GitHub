GitHub. HW_2
1. На локальном репозитории сделать ветки для: -git branch br_name
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing

2. Запушить все ветки на внешний репозиторий - git add . , git status, git commit , git push origin br_name. 
3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта - git checkout Bug_Reports, cat > BugReports.txt.
4. Запушить структуру багрепорта на внешний репозиторий - git add Bug_Reports, git status, git commit -m "Структура баг репорта", git push. 
5. Вмержить ветку Bug Reports в Main - git checkout main, git branch, git merge Bug_Reports.
6. Запушить main на внешний репозиторий - git push.
7. В ветке CheckLists набросать структуру чек листа - git checkout CheckLists, cat > CheckList.txt.
8. Запушить структуру на внешний репозиторий - git add CheckList.txt, git status, git commit -m "Структура чеклиста"
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.
10. Синхронизировать Внешнюю и Локальную ветки Main - git pull (тянем с внешней ветки на локальную) , git push (пушим с локалки на внешний)
