iJSON
 ### 1. *Создать внешний репозиторий c названием JSON.* - 
 	**создаем новый репозитория через сайт gitHub**
 ### 2. *Клонировать репозиторий JSON на локальный компьютер.* - 
 	**на сайте gitHub копируем ссылку на репозиторий,  в терминале пишем git clone и вставляем ссылку** 
 ### 3. *Внутри локального JSON создать файл “new.json”.* - 
 	**далее в терминале смотрим, где мы находимся и переправляемся в папку Json для дальнейшей работы. Создаем новый файл new.json : touch new.json**
 ### 4. *Добавить файл под гит.* - 
 	**git add .**
 ### 5. *Закоммитить файл.* - 
 	**git commit -m «new.json»**
 ### 6. *Отправить файл на внешний GitHub репозиторий.* - 
 	**git push**
 ### 7. *Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.* - 
 	**cat > new.json**
```
"fullName": "Hanna Karsanova",
"age": 29,  
"numberOfPets": 2,
"futureDesiredSalary": 3000
```
 ### 8. *Отправить изменения на внешний репозиторий.* -
 	**git commit -a -m** 
	**Git push**
 ### 9. *Создать файл preferences.json* - 
 	**touch preferences.json**
 ### 10. *В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.*
	 **cat > preferences.json**
```
{

"favouriteFilm": "Spirit",

"favouriteSerial": "Sex and the city",

"favouriteFood": "Spaghetti",

"favouriteSeason": "winter",

"countryToVisit": "Japan"

}
```

 ### 11. *Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON* - 
 	**cat > skills.json**
```
{      
"skills": [
"Write Bash commands",
"Git Hub and Git":,
"Test disign techniques",
"Postman",
"Charles and Fiddler",
"SQL basics",
"Jmeter"
]
}
^C
```
 ### 12. *Отправить сразу 2 файла на внешний репозиторий.*  - 
 	**git add .**
	git commit -m «two files»
 ### 13. *На веб интерфейсе создать файл bug_report.json.* - 
 	**на сайте gitHub зайти в репозитория Json, и Нажать Add File > Create new file**
 ### 14. *Сделать Commit changes (сохранить) изменения на веб интерфейсе.* - 
 	**нажать commit new file**
 ### 15. *На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.* - 
 	**Нажать edit file**
```
{
"ID": "HW-2",
"Title": "What?Where?When?",
"Severity": "Medium",
"Priority": "High", 
"Precondition": "Preparation reproduce",
"Environment": "Devices",
"STR": "Steps to reproduce",
"ER": "Expected result",
"AR": "Actual Result",
"Attachment": "link"
}
```
 ### 16. *Сделать Commit changes (сохранить) изменения на веб интерфейсе.* - 
 	**нажать commit changes**
 ### 17. *Синхронизировать внешний и локальный репозиторий JSON* -  
 	**git pull**
