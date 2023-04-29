# TXT репозиторий

**1. _Создаем внешний репозиторий c названием TXT_**

`Repositories -> New -> Repos Name:TXT -> Check "Add a README file" -> Press "Create repository"`

**2. _Клонировать репозиторий TXT на локальный компьютер_**

`git clone <repository HTTPS>`

**3. _Внутри локального TXT создать файл "new.txt"_**

`touch new.txt`

**4. _Добавить файл под гит_**

`git add .` или `git add new.txt`

**5. _Закоммитить файл_**

`git commit -m "любой комментарий"`

**6. _Отправить файл на внешний GitHub репозиторий_**

`git push`

**7. _Отредактировать содержание файла “new.txt” написать информацию о себе в формате TXT (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)_**

`vim new.txt -> input data -> esc -> enter ":wq"`

**8. _Отправить изменения на внешний репозиторий_**

`git add . && git commit -m "любой комментарий"`

`git push`

**9. _Создать файл preferences.txt_**

`touch preferences.xml`

**10. _В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT_**

`vim preferences.txt -> insert data -> esc -> enter ":wq"`

**11. _Создать файл skills.txt. Добавить информацию о скиллах которые будут изучены на курсе в формате TXT_**

`touch skills.txt`

**12. _Отправить сразу 2 файла на внешний репозиторий_**

`git commit -a -m "любой комментарий" && git push`

**13. _На веб интерфейсе создать файл bug_report.txt_**

`Add file -> Create new file -> Name: bug_report.txt`

**14. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_**

`Commit New File`

**15. _На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT_**

`Choose bug_report.txt -> Edit this file`

**16. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_**

`Commit changes`

**17. _Синхронизировать внешний и локальный репозиторий TXT_**

`git pull`
