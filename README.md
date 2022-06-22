# HW_GitHub
## TXT

 1. Создать внешний репозиторий c названием TXT.
 2. Клонировать репозиторий TXT на локальный компьютер.
 
	`git clone https://github.com/setter-getter/TXT.git`
 3. Внутри локального TXT создать файл “new.txt”
 
	`touch new.txt`
 4. Добавить файл под гит.
 
    `git add new.txt`
  
 5. Закоммитить файл.
 
	 `git commit -m "add new.txt"`
   
 6. Отправить файл на внешний GitHub репозиторий.
 
	 `git push`
    
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
  vim new.txt
  i
	
  Firs name: Dmitry,
  Last name: Bondarenko,
  Patronymic: Anatolevich,
  Age: 33,
  Number of pets: 1,
  Desired salary: 350
	
  Esc
  :wq
  ```
  
 8. Отправить изменения на внешний репозиторий.
 ```
	git add new.txt
	git commit -m "update new.txt"
	git push
 ```
 9. Создать файл preferences.txt
 
	`touch preferences.txt`
  
 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
  vim preferences.txt
  i

  Favorite movie: 1+1,
  Favorite TV series: Friends,
  Favorite food: Borsch,
  Favorit time of the year: summer,
  Country I would like to visit: Iceland

  Esc
  :wq
```
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 ```
	touch skills.txt
	
	vim skills.txt
	i
	
   Testing theory: bug report, test documentation, SDLC, STLS;
   Skills of working whith: Git, bash, SQL, Fidler, Postman
	
	Esc
	:wq
```
 12. Отправить сразу 2 файла на внешний репозиторий.
 ```
	git add preferences.txt skills.txt
	git commit -m "add preferences.txt skills.txt"
	git push
 ``` 
 13. На веб интерфейсе создать файл bug_report.txt.
 ```
	Add file -> create new file -> bug_report.txt
```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`	"create bug_report.txt" -> commit new file`

 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
	
  `	"Edit this file"`
```
  ID: ID
  Summary: Summary
  Steps to reproduce: Steps to reproduce
  Actual result: Actual result
  Expected result: Expected result
  Severity: Блокирующий
  Priority: Высокий
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 ` "update bug_report.txt" -> commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON
 
 `git pull`
