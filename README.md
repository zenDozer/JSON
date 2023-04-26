# JSON

***1. Создать внешний репозиторий c названием JSON***

`github.com -> Repositories -> New -> "JSON" -> Create repository`

***2. Клонировать репозиторий JSON на локальный компьютер***

```
Enter to repo JSON -> "<>Code" -> SSH -> Copy url -> go to Terminal:
git clone git@github.com:zenDozer/JSON.git
```

***3. Внутри локального JSON создать файл “new.json”***

```
cd JSON
touch new.json
```

***4. Добавить файл под гит***

`git add .`

***5. Закоммитить файл***

`git commit - m "Add new.json file`

***6. Отправить файл на внешний GitHub репозиторий***

`git push`

***7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON***

```
vim new.json

{
	"fio" : "Malko Oleksandr",
	"age" : 42,
	"pet" : 1,
	"salary" : 750
}
```
***8. Отправить изменения на внешний репозиторий***

```
git add .
git commit -m "Update new.json"
git push
```

***9. Создать файл preferences.json***
***10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON***

```
vim preferences.json

{
	"Film" : "The Social Network",
	"TV series" : "Silicon Valley",
	"Favorite food" : "Borsch",
	"Favorite season" : "Spring",
	"Country" : "USA"
}
```

***11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON***

```
vim sklls.json

{
	"skills" : [
	"Basic theory",
	"client-server architecture",
	"HTTP",
	"JSON/XML",
	"Postman",
	"Charles",
	"Fidler",
	"Dev Tools",
	"VPN",
	"Mobile testing",
	"Android Studio",
	"Terminal",
	"Git",
	"SQL basic",
	"Jmeter",
	"Scrum",
	"Python basic"
	]
}
```

***12. Отправить сразу 2 файла на внешний репозиторий***

```
git add .
git commit -m "Add 2 files"
git push
```

***13. На веб интерфейсе создать файл bug_report.json***

`Enter to repo JSON -> Add file -> Create new file ->  bug_report.json`

***14. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

`Commit changes -> Commit message: "Add bug_report.json" -> Commit changes`

***15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON***

```
Select bug_report.json file -> add changes:

{
  "ID" : "LF-001",
  "Summary" : "The Login button should be blue - not red",
  "Severity" : "Minor",
  "Priority" : "Low",
  "Environment" : "PC, Windows 11, Chrome",
  "Steps to reproduce" : "Open example_site.com, click on sign in button",
  "Expected result" : "Login button is blue",
  "Actual result" : "Login button is red",
  "Attachments" : "Screenshot.jpg",
  "Reported By" : "Oleksandr Malko"
}
```

***16. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

`Commit changes -> Commit message: "Update bug_report.json" -> Commit changes`

***17. Синхронизировать внешний и локальный репозиторий JSON***

```
Go to Terminal and type:

git pull
```
