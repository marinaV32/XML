# XML HW
 21. Создать внешний репозиторий c названием XML.
New - имя репозитории XML - галочка - ok
 
22. Клонировать репозиторий XML на локальный компьютер.
git clone git clone https://github.com/marinaV32/XML.git (ссылка из репозитории раздел https)
 
23. Внутри локального XML создать файл “new.xml”.
touch new.xml
 
24. Добавить файл под гит.
git add new.xml
 
25. Закоммитить файл.
git commit -m "new"
 
26. Отправить файл на внешний GitHub репозиторий.
git push
 
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
vim new.xml
жмем а на клавиатуре (команда дляя записи текста в редакторе)
(пишем текст внутри)
 
<?xml version="1.0" encoding="UTF-8"?> 
 <xml>
          <fullname> "Prokopovich Marina" </fullname>
          <age> "26" </age>
          <numberofpets> "no" </numberofpets>
          <futuredesiredsalary> "2000$" </futuredesiredsalary>
               </xml>
жмем Esc и  :wq(сохранить и выйти) 

28. Отправить изменения на внешний репозиторий.
git commit -am "get"
git push

29. Создать файл preferences.xml
touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
vim preferences.xml
жмем а на клавиатуре (команда дляя записи текста в редакторе)

<?xml version="1.0" encoding="UTF-8"?> 
 <xml>
        <favoritemovie> "oath" </favoritemovie>
        <favoriteseries> "from outside" </favoriteseries>
        <favoritefood> "pasta" </favoritefood>
        <favoriteseason> "spring" </favoriteseason>
        <travelcountry> "Greece" </travelcountry>
 </xml>
жмем Esc и  :wq(сохранить и выйти) 

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
vim sklls.xml

<?xml version="1.0" encoding="UTF-8"?> 
<xml>
        <courseQA> "soft skills,hard skills" </courseQA>
</xml>
 32. Сделать коммит в одну строку.
git add . | git commit -m "create new files"
 
33. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -m "new"
git push
 
34. На веб интерфейсе создать файл bug_report.xml.
В Гите заходим на наш репозиторий XML, жмем "Создать новый файл", даем имя файлу - сохраняем
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
Редактируем - добавляем екст - сохраняем

<?xml version="1.0" encoding="UTF-8"?> 
<bugreport>
<Name> structure bug report </Name>
<IssueTitle> Pop-up window does not disappear until the date is not changed </IssueTitle> 
<IssueType> Bug </IssueType>
<Priority> Low </Priority>
<IssueStatus> Blocked </IssueStatus>
<Author> Marina Prokopovich </Author>
<Severity> " " </Severity>
<Build> " " </Build>
<Environment> " " </Environment>
<Name2> Issue Description, Steps to reproduce </Name2>
<step1> Select any dish </step1>
<step2> Go to the basket </step2> 
<step3> Select a date next to the last delivery date in the menu(e.x. menu 8-11 Nov, select 15 Nov) </step3>
<step4> After the pop-up 'Delivery up t 14.11'appears click on the 'Change a date' button </step4>
<step5> Look at the pop-up </step5>

<Expectedresult> The pop-up 'Delivery up to 14.11' does not appear </Expectedresult>
<Actualresult> The Pop-up remains until the date is not changed to the suitable one </Actualresult>
</bugreport>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML
++++++на 34-38: создала новый файл в репозитории, затем через консоль гид синхронизировала с локальным и внешним репозиторием: 
git fetch   проверила
git pull    синхронизировала
Редактировала: добавила текст 
git fetch   
git pull
