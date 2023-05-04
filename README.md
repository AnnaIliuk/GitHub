# GitHub

##HW_1 

1. Создать внешний репозиторий c названием JSON
```
- перейти во вкладку [Repositories]
- клик по [New]
- ввести имя репозитория [JSON]
- поставить radio button [Public] и [Add a README file]
- клик по [Create repository]
```

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
```
- зайти в репозиторий JSON
- клип по кнопке  [Add file] 
- клик по [Appload files]
- клик по [Choose your file]
- клик по кнопке [Commit changes]

```

14. Сделать Commit changes (сохранить) изменения на веб-интерфейсе
```
- клик по названию файла
- клик по [Edit file]
- внести изменения 
- клик по [Commit changes]
```

15. На веб-интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
```
- клик по названию файла [bug_report.json]
- клик по [Edit file]
- внести изменения 
- клик по [Commit changes]
```

16. Синхронизировать внешний и локальный репозиторий JSON
```
git pull
```

17. Создать внешний репозиторий c названием XML
```
- перейти во вкладку [Repositories]
- клик по [New]
- ввести имя репозитория [JSON]
- поставить radio button [Public] и [Add a README file]
- клик по [Create repository]
```

18. Клонировать репозиторий XML на локальный компьютер
```
git clone https://github.com/AnnaIliuk/XML.git

```

19. Внутри локального XML создать файл “new.xml”
```
touch new.xml
```

20. Добавить файл под гит
```
git add new.xml
```

21. Закоммитить файл
```
git commit -m "Add the new.xml"
```

22. Отправить файл на внешний GitHub репозиторий
```
git push
```

23. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, 
будущая желаемая зарплата). Всё написать в формате XML
```
vim new.xml
<?xml version="1.0" encoding="UTF-8" ?>
<person>
 <first_name>Anna</first_name>
 <middle_name>Sergeevna</middle_name>
 <last_name>Iliuk</last_name>
 <age>28</age>
 <pet>
   <dog>1</dog>
 </pet>
 <salary>1000$</salary>
</person>

```

24. Отправить изменения на внешний репозиторий
```
git commit -am "new information added"
```

25. Создать файл preferences.xml
```
touch preferences.xml
```

26. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
```
vim preferences.xml

<?xml version="1.0" encoding="UTF-8" ?>
<root>
 <favorite_movie>Black Swan</favorite_movie>
 <favorite_TV_series>American housewife</favorite_TV_series>
 <favorite_food>sushi</favorite_food>
  <favorite_food>burger</favorite_food>
 <favorite_food>lasagne</favorite_food>
 <favorite_time_year>summer</favorite_time_year>
 <country>Russia</country>
</root>

```

27. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
touch skills.xml
vim skills.xml

```

28. Сделать коммит в одну строку
```
git add . && git commit -m "Added preferences.xml and skills.xml files"
```

29. Отправить сразу 2 файла на внешний репозиторий
```
git push
```

30. На веб-интерфейсе создать файл bug_report.xml
```
- зайти в репозиторий [XML]
- клип по кнопке  [Add file] 
- клик по [Appload files]
- клик по [Choose your file]
- клик по кнопке [Commit changes]
```

31. Сделать Commit changes (сохранить) изменения на веб интерфейсе
```
- клик по названию файла [bug_report.xml]
- клик по [Edit file]
- внести изменения 
- клик по [Commit changes]
```

32. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
```
<?xml version="1.0" encoding="UTF-8" ?>
<root>
 <Bug-ID>1</Bug-ID>
 <Title>"Карточка продукта "MAKEUP REVOLUTION Conceal and Define Full Coverage Concealer" находится во вкладке для другого типа продукта"</Title>
 <Project>tint.com</Project>
 <STR>1. Открыть страницу входа</STR>
 <STR>2. Клик по кнопке [Live camera] </STR>
 <STR>3. Пройти Face analysis</STR>
 <AR>MAKEUP REVOLUTION Conceal and Define Full Coverage Concealer" находится во вкладке [Contour]</AR>
 <ER>Карточка продукта "MAKEUP REVOLUTION
Conceal and Define Full Coverage Concealer" находится во вкладке [Concealer]</ER>
 <Environment>
   <OS>Windows 10 PRO 64-bit operating system, x64 processor</OS>
   <Browser>Google Chrome Version 102.0.5005.63 (Official build), (64 bit)</Browser>
 </Environment>
 <Severity>Major</Severity>
 <Priority>Medium</Priority>
 <Status>New</Status>
 <Author>No name</Author>
</root>
```

33. Сделать Commit changes (сохранить) изменения на веб интерфейсе
```
- клик по названию файла [bug_report.xml]
- клик по [Edit file]
- внести изменения 
- клик по [Commit changes]
```

34. Синхронизировать внешний и локальный репозиторий XML
```
git pull
```
