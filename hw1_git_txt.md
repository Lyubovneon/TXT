### 👉 *START part 3* 💙💛
### *TXT*
***
### *1. Создать внешний репозиторий c названием TXT.*
- **github.com --> section Repositories --> click on the NEW button --> write TXT in the Repository name field --> mark as Public --> click on the Create repository button**

*** 
### * 2. Клонировать репозиторий TXT на локальный компьютер.*
- **git clone** git@github.com:Lyubovneon/TXT.git

***
### * 3. Внутри локального TXT создать файл “new.txt”.*
- **cd TXT**
- **touch new.txt**
- **ls -la**  -  to see TXT content 

***
### *4. Добавить файл под гит.*
- **add new.txt**

***
### *5. Закоммитить файл.*
- **git commit -m** "add new.txt"

***
### *6. Отправить файл на внешний GitHub репозиторий.*
- **git push**

***
### *7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.*
- **vim new.txt**
- **insert**

Person first name: Lyubov

Person last name: Nekroyenko

Age: 30

Pets: 2

Salary: 3000

- **Esc:wq**

- **cat new.txt**  - to see the new.txt content in gitbash

***
### *8. Отправить изменения на внешний репозиторий.*
- **git add .**
- **git commit -m** "modify new.txt"
- **git push**

***
### *9. Создать файл preferences.txt*
- **touch preferences.txt**
- **ls -la**  -  to see TXT content 

***
### *10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.*
- **vim preferences.txt**
- **insert**

Movie: The Bodyguard
Serial: My Software Testing Manual Journey
Food: Apples
Season: Spring
Country: USA

- **Esc:wq**

- **cat preferences.txt**  - to see the preferences.txt content in gitbash

***
### *11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT*
- **touch skills.txt**
- **ls -la**  -  to see TXT content 
- **vim skills.txt**
- **insert**

1. Bug Tracker JIRA, Mantis
	
2. Test Tracker TestLink 
	
3. Test documentations Test Plan, Test case, Test Suite, Check list, Bug report
        
4. Testing Methods, Types of Testing, Software Test Design Techniques, SDLS(System Development Life Cycle), STLC
	
5. Agile methodology SCRUM, KANBAN
	
6. Client-Server Architecture Basics
	
7. SQL DML, DDL
	
8. HTTP methods
	
9. Response STATUS codes
	
10. API REST, SOAP
	
11. POSTMAN
	
12. Devtools Chrome
	
13. GITHUB, GITBASH
	
14. JSON, XML basic, structure 
	
15. Google Sheets
	
16. Visual Studio code basics
	
17. Mobile testing
	
18. SNAGIT, Lightshot, Bandicam
	
19. html, css, JavaScript basics
	
20. Taking, uploading and reading Logs 
	
- **Esc:wq**

- **cat skills.txt**  - to see the skills.txt content in gitbash

***
### *12. Сделать коммит в одну строку.*
- **git add .** 
- **git commit -m** "add preferences.txt skills.txt"

***
### *13. Отправить сразу 2 файла на внешний репозиторий.*
- **git push**

***
### *14. На веб интерфейсе создать файл bug_report.txt.*
- **github.com --> drop down menu --> Your Repositories --> click on the TXT Repository --> click on add file dropbox --> Create new file --> write bug_report.txt in the name field**

***
### *15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*
- **--> write the title in the Commite new file field --> click on the Commit new file button**

***
### *16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.*
- **click on the dropbox--> edit this file -->**

ID: 110920221

Title: Fields are shown without required identification

Invironment: Microsoft EdgeVersion 105.0.1343.27 (64-bit) OS Windows OS Version 10x64

STR: 1. Open the http://itcareer.pythonanywhere.com

     2. Pay attention to the browser tab
    
AR: Fields are shown without required identification

ER: Required fields are shown marked *(asterisk)

Severity: major

Priority: high

Attachments: link_video, link_screenshort

***
### *17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*
- **--> write the title in the Commite changes field --> click on the Commit changes button**

***
### *38. Синхронизировать внешний и локальный репозиторий TXT*
- **git pull**

###  *F I N I S H_part 3* 👈









