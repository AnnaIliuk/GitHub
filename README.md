# GitHub

1. Создать внешний репозиторий c названием JSON


2.  Клонировать репозиторий JSON на локальный компьютер
```
git clone https://github.com/AnnaIliuk/JSON.git
```

3. Внутри локального JSON создать файл “new.json”
```
cd JSON
touch new.json
```

4. Добавить файл под гит
```
git add new.json
```

5. Закоммитить файл
```
git commit -m "Add the new.json"
```

6. Отправить файл на внешний GitHub репозиторий
```
git push
```

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, 
будущая желаемая зарплата). Всё написать в формате JSON
```
vim new.json
{
   "person":{
        "first_name":"Anna",
        "middle_name":"Serveegna",
        "last_name":"Iliuk",
        "age":28,
        "pets":{

                "dog":1
        },
        "salary":"1000$"
   }

}

```


8. Отправить изменения на внешний репозиторий
```
git commit -am "New information added"
git push
```

9. Создать файл preferences.json
```
touch preferences.json
```

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
```
vim prefereces.json

{
   "favorite_movie": "Black Swan",
       "favorite_TV_series": "American housewife",
       "favorite_food": [
               "sushi",
               "burger",
               "lasagne"
       ],
       "favorite_time_year": "summer",
       "country": "Russia"
}
```

11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```
vim skills.json
{
   "skills":{
    "basic testing theory":[
        "testing",
        "bug reports",
        "documentation",
        "SDLC",
        "STLC"
    ],
    "HTTP":[
        "client-server architecture",
        "HTTP methods of requests to the server",
        "HTTP server response codes",
        "HTTP request and Response structures"
    ],
    "data exchange format":[
        "XML",
        "JSON"
    ],
    "database":[
        "SQL",
        "Postgres"
    ],
    "API":"JS",
        
    "sniffing":[
        "Charles",
        "Fidler"
    ],
    "DevTools:"GoogleChrome",

    "mobiletesting":[
        "iOS",
        "Android"
    ],
    "buildingapplications":[
        "AndroidStudio",
        "XCode"
    ],
    "workingintheterminal":[
        "GitBush",
        "GitHub"
    ],
    "loadtesting": "Jmeter",
    "methodology": "SCRUM"
   }
}
```

12. Отправить сразу 2 файла на внешний репозиторий
```
git add . && git commit -m "correct slills,json" && git push

```

13. На веб-интерфейсе создать файл bug_report.json

14. Сделать Commit changes (сохранить) изменения на веб-интерфейсе


15. На веб-интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON


16. Сделать Commit changes (сохранить) изменения на веб-интерфейсе


17. Синхронизировать внешний и локальный репозиторий JSON
```
git pull
```

18. 



