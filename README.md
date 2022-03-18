#план автоматизации тестирования сценария перехода и заполнения формы записи на обучение профессии "Тестировщик ПО" на сайте [НЕТОЛОГИЯ](https://netology.ru/)



##1. Перечень автоматизируемых сценариев
## Переход на форму записи возможен следующими способами:
* с главной страницы через "каталог курсов" - програмирование 
https://netology.ru/ - https://netology.ru/development - https://netology.ru/programs/qa -нажать "записаться"
или при скролиннге вниз - https://netology.ru/programs/qa#/ - нажать "записаться"


* с главной страницы через "нео для начинающих"
https://netology.ru - https://netology.ru/neo - https://netology.ru/programs/qa -нажать "записаться"
или при скролиннге вниз -  https://netology.ru/programs/qa#/ - нажать "записаться"; 
последняя страница при прокрутке вниз - https://netology.ru/programs/qa#/order - нажать "записаться"


* футор главной страницы - каталог курсов 
https://netology.ru/#/courses - https://netology.ru/navigation - https://netology.ru/programs/qa#/ - нажать "записаться"
или при скролиннге вниз -  https://netology.ru/programs/qa#/ - нажать "записаться" ; 
последняя страница при прокрутке вниз - https://netology.ru/programs/qa#/order - нажать "записаться"


* футор главной страницы - популярные курсы
https://netology.ru/#/courses - https://netology.ru/popular -https://netology.ru/programs/qa#/- нажать "записаться"




##2. Перечень используемых инструментов с обоснованием выбора
###- В качестве языка программирования выбираем Java - проще найти специалистов
###- В качестве тестового фреймворка JUnit(@BeforeEach, @Override ), Docker для запуска автотестов,  фреймворк Selenium WebDriver для автоматизации действий браузера
###- для запросов к API используется REST Assured
###- FAKER или для подготовки тестовых данных ( генерация имени, телефона, эл. почты)
###- Cucumber чтобы уменьшить расходы проекта на тестирование
###- Allure для отчетности
##3. Перечень необходимых разрешений/данных/доступов
###Желателен доступ к тестовым данным ( БД реальных посетителей для использования в автотестах).

##4. Перечень и описание возможных рисков при автоматизации
###- экономическая выгода от автоматизации (окупается при частых релизах, в условиях одновременной работы с большим количеством данных и пользователей);
###- есть риск при использовании сгенерированных входных данных ;
###- необходимо учитывать время на поддержку (актуализацию) автотестов.
##5. Перечень необходимых специалистов для автоматизации
###тестировщик-автоматизатор 
##6. Интервальная оценка с учётом рисков (в часах) - 6, включая:
* ### анализ требований и данных;
* ### написание автотестов;
* ###прогон тестов;
* ###анализ результатов


