# XML

1. Создать внешний репозиторий c названием XML. `Repositories --> New`
2. Клонировать репозиторий XML на локальный компьютер. `git clone `
3. Внутри локального XML создать файл “new.xml”. `cd XML && touch new.xml`
4. Добавить файл под гит. `git add new.xml`
5. Закоммитить файл. `git commit -m "XML"`
6. Отправить файл на внешний GitHub репозиторий. `git push`
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.vim new.xml
  <pre><?xml version="1.0" encoding="UTF-8" ?>
<person>
	<First name>Lena</First name>
	<Middle name>Mikhailovna</Middle name>
	<Last name>Chadushkina</Last name>
	<Age>32</Age>
	<Pet>1</Pet>
	<Salary>1000$</Salary>
</person></pre>
9. Отправить изменения на внешний репозиторий. `git add new.xml`-->`git commit -m "XML new"`-->` git push `
10. Создать файл preferences.xml `touch preferences.xml`
11. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. `vim preferences.xml`--> i
<pre><?xml version="1.0" encoding="UTF-8" ?>
<root>
	<Favorite_movie>The_Pursuit of Happyness</Favorite_movie>
	<Favorite_series>Game of Thrones</Favorite_series>
	<Favorite_food>kebab</Favorite_food>
	<Favorite_food>pizza</Favorite_food>
	<Favorite_food>grilled cheese</Favorite_food>
	<Favorite_time_year>Summer</Favorite_time_year>
	<Country>Indonesia</Country>
</root></pre>
`Esc` --> `:wq `
12. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML `vim sklls.xml`--> `i`
<?xml version="1.0" encoding="UTF-8" ?>
<root>
	<Basic_testing_theory>What is testing</Basic_testing_theory>
	<Basic_testing_theory>Bug reports</Basic_testing_theory>
	<Basic_testing_theory>Test documentation</Basic_testing_theory>
	<Basic_testing_theory>SDLC</Basic_testing_theory>
	<Basic_testing_theory>STLC</Basic_testing_theory>
	<Basic_testing_theory>Design Test Techniques</Basic_testing_theory>
	<HTTP>Methods</HTTP>
	<HTTP>Status code</HTTP>
	<HTTP>Structure of requests and responses</HTTP>
	<Data_exchange_formats>JSON</Data_exchange_formats>
	<Data_exchange_formats>XML</Data_exchange_formats>
	<API_testing>Postman</API_testing>
	<API_testing>JS</API_testing>
	<API_testing>Autotests API</API_testing>
	<Traffic_sniffing>Charles</Traffic_sniffing>
	<Traffic_sniffing>Fiddler</Traffic_sniffing>
	<Dev_Tools>Google Chrome</Dev_Tools>
	<Dev_Tools>Firefox</Dev_Tools>
	<VPN>How it works</VPN>
	<VPN>How to use it</VPN>
	<VPN>Tool options</VPN>
	<Mobile_testing>iOS</Mobile_testing>
	<Mobile_testing>Android</Mobile_testing>
	<Mobile_testing>Guidelines</Mobile_testing>
	<Mobile_testing>XCode</Mobile_testing>
	<Mobile_testing>Android Studio</Mobile_testing>
	<Mobile_testing>ADB</Mobile_testing>
	<Terminal>GitBash</Terminal>
	<SQL>The basics</SQL>
	<SQL>Postgres</SQL>
	<SQL>Redis</SQL>
	<Load_testing>Jmeter</Load_testing>
	<Python>The basics</Python>
	<Python>Creating a client server application</Python>
<root>
`Esc` --> `:wq`
13. Сделать коммит в одну строку. ` git add . && git commit -m "prefernces and skills"`
14. Отправить сразу 2 файла на внешний репозиторий. `git push`
15. На веб интерфейсе создать файл bug_report.xml. `Add file`--> `Create new file`
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.`Commit changes`
17. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<?xml version="1.0" encoding="UTF-8" ?>
<root>
	<Bug-ID>01</Bug-ID>
	<Title>Ошибка авторизации пользователя при вводе валидного логина и пароля</Title>
	<Project>Сайт Форум Хомячки</Project>
	<STR>1. Открыть страницу авторизации https://forumhomyachki.com/authorization</STR>
	<STR>2. Ввести валидный логин и пароль (test@com.ru, 123456)</STR>
	<STR>3. Нажать кнопку 'Войти'</STR>
	<Actual result>Система отображает сообщение об ошибке 'При входе произошла ошибка, попробуйте позднее' </Actual result>
	<Expected result>Авторизация прошла успешно, произошел переход в раздел 'Мой профиль'</Expected result>
	<Environment>
		<OS>Windows 10 PRO 64-bit operating system, x64 processor</OS>
		<Browser>Microsoft Edge Версия 115.0.1901.200 (Официальная сборка) (64-разрядная версия)</Browser>
	</Environment>
	<Severity>Critical</Severity>
	<Priority>High</Priority>
	<Status>New</Status>
	<Author>Чадушкина Елена</Author>
</root>
18. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `Commit changes`
19. Синхронизировать внешний и локальный репозиторий XML `git pull`
