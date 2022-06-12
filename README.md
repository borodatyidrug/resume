# РОМАН ЗЫРЯНОВ
**тел.:** +79002743163<br>
**email:** borodatyidrug@yandex.ru<br>
**tg:** @borodatyidrug<br>
**портфолио:** https://github.com/borodatyidrug
## Java-разработчик/Java developer
### Ключевые компетенции
* Программирование на Java (Java Core)
* Разработка Telegram-ботов
* Работа с GIT
* Работа с шаблонами проектирования: Builder, Singleton, Facade, Iterator и т.д.
#### Инструменты:
* Java
* GIT
* GitHub
* Maven
* Stream API
* Telegram Bot Java Library
* Quartz
* Jsoup, STaX
### Профессиональный опыт
10.2021 - настоящее время. **Учебные проекты в Нетологии**, курс "Java-разработчик" (программа курса по [ссылке](https://cat.2035.university/rall/course/11144/?orgs=1369))<br>
**Название проекта:** *Поисковая система* ([дипломный проект](https://github.com/borodatyidrug/Diplom))<br>
**Задачи:** *разработать класс поискового движка для быстрого поиска заданного слова в наборе .pdf-документов с ранжированием результатов по количествам вхождений на страницу и сервер, обслуживающий соответствующие запросы с помощью этого движка*<br>
**Используемые технологии:** *Sockets, jackson, itextpdf*<br>
**Результаты:**<br>
* Написан класс, имплементирующий интерфейс поискового движка
* В классе реализован механизм индексации. Поиск осуществляется по предвычисленному множеству вхождений. Таким образом, поиск становится очень быстрым.
* Написан сервер, отвечающий на запросы с указанием искомого слова и возвращающий в качестве результата JSON со статистикой вхождений.

**Название проекта:** *Применение принципов DRY, SOLID, magics (финальная [работа](https://github.com/borodatyidrug/DRYSOLIDTask) в блоке “Шаблоны проектирования”)*<br>
**Задачи:** *получить практический опыт в написании чистого кода в соответствии с принципами DRY, SOLID, magics; написать консольное приложение - магазин для заказа пользователями товаров в произвольной форме, с произвольной структурой и произвольным набором функций для демонстрации понимания изученных принципов чистого кода*<br>
**Используемые технологии:** *стандартная библиотека Java, консольный интерфейс*<br>
**Результаты:**<br>
* Реализован ограниченный набор основных функций пользовательского интерфейса, таких как - 	добавление товаров в корзину по артикулу и количеству, вывод на экран содержимого корзины с расчетом стоимости по позиции и общей, очистка корзины, присвоение оценки товару
* Реализована фильтрация товаров по категориям и подкатегориям, среднему рейтингу, 	диапазону цены, наименованию, ключевым словам, артикулу
* Реализован механизм последовательного уточнения выборки товаров, история выборок и 	возможность отката к предыдущим состояниям выборки
* Реализована система рейтинга товаров по шкале с изменяемыми границами интервала 	возможных значений
* Создана подсистема генерации товаров и их характеристик по заданным категориям
* Для генерации названий товаров создан простейший генератор слов на основе заданного 	множества морфем - корней, суффиксов, окончаний (в качестве интересного упражнения)
* Код содержит комментарии, объясняющие применение того или иного принципа чистого кода в 	каждом конкретном месте

04.2022 - настоящее время. **Разработчик**<br>
**Телеграм-бот “Семейный Ассистент”** (личный [pet-проект](https://github.com/borodatyidrug/Telegram-bot-Family-Assistant))<br>
**Задачи:** *создать telegram-бота, помощника с полезными для себя и семьи функциями, освоить ряд современных библиотек, фреймворков, технологий, Telegram Bot API, дополнять функционал бота по необходимости*<br>
**Используемые технологии:** *Telegram Bot API (Telegram Bot Java Library), Quartz Scheduler, Jsoup, PostgreSQL*<br>
**Результаты:**<br>
* Бот по расписанию парсит заданные информационные блоки определенного сайта и 	отправляет их в чаты, в которых данная задача была запланирована. Поддерживается разовое 	исполнение задачи по запросу, по расписанию и - периодическое
* Реализует управление задачами пользователей (органайзер), напоминаниями (разовые, периодические)
* Расписание рассылки результатов парсинга сайта хранится в локальном файле на сервере в 	формате JSON, планировщик задач - из библиотеки concurrent.
* Хранение и восстановление задач и напоминаний менеджера задач осуществляется 	средствами Quartz в СУБД PostgreSQL
* Бот функционирует как монолит локально вне сервера приложений на домашнем linux-сервере

09.2018 – настоящее время. **Инженер-технолог (удаленно)**<br>
**АО “ТВиМ”, Екатеринбург**<br>
* Создание управляющих программ для станков ЧПУ<br>

08.2015 – 07.2018 **Инженер-конструктор столярных изделий**<br>
**ООО “Атлас”, Екатеринбург**<br>
* Конструировал различные столярные изделия: корпусную мебель, классическую мебель из 	массива и не только, декоративные отделочные панели из древесных материалов и массива, 	арки, двери, поручни и т.д.
* Участвовал в замерах на объектах, оцифровке криволинейных шаблонов
* Разрабатывал большие 3D-сборки изделий и конструкторскую документацию на них в САПР 	Компас-3D, AutoCAD, SketchUp
* Разрабатывал управляющие программы (УП) для фрезерного станка с ЧПУ в ArtCAM
* Выполнял УП на фрезерном станке с ЧПУ в качестве оператора
* Участвовал в больших интересных проектах, переговорах с техническими специалистами, 	дизайнерами. Например, конструирование отделочных композитных панелей (фанера, МДФ, 	шпон дорогих пород) премиум-класса сложной формы для отделки стен, потолка большого 	офиса под 1000 кв. м в г. Нефтеюганск.

04.2012 – 07.2015 **Инженер-электроник ОАСУ, Инженер ССДТУ**
**ОАО "МРСК Урала", ПО "Западные электрические сети"**
* Обслуживал парк пользовательских ПК и офисной техники
* Собирал и настраивал рабочие места пользователей производственного отделения и РЭС
* Осуществлял техническую поддержку пользователей локально и удаленно
* Выполнял монтаж СКС
* Обслуживал сервера диспетчерского и технологического управления (телеметрия и телемеханика), устройств записи диспетчерских переговоров

08.2011 – 04.2012 **Помощник системного администратора**
**ООО Транспортная Компания "Кит"**
* Обслуживал парк пользовательских ПК и офисной техники
* Собирал и настраивал рабочие места пользователей для главного офиса и филиалов по всей 	стране
* Осуществлял техническую поддержку пользователей локально и удаленно
* Осуществлял монтаж СКС, системы видеонаблюдения
* Раскрыл характер и масштабы эпизода вирусной атаки на ИТ-инфраструктуру компании благодаря базовым познаниям в администрировании unix-подобных ОС (программный сетевой экран/маршрутизатор PfSense)

### ОБРАЗОВАНИЕ
**2010, Уральский государственный лесотехнический университет, Екатеринбург**
Лесомеханический факультет, Сервис транспортных и технологических машин и оборудования (по отраслям)<br>
Специалист (инженер-механик)

### Курсы, тренинги
* 2022, Нетология, Java-разработчик
* 2022, Нетология, Основы верстки сайта

### Дополнительная информация:
* Английский — A2 — Элементарный
* Ищу только удаленную работу, не готов к командировкам и релокации

## ОБО МНЕ
Занимаюсь программированием, окончил курс Java-разработчик в Нетологии. Имею начальный опыт в разработке web-приложений, telegram-ботов, работаю с GIT. 
Работа java-разработчиком для меня - это шанс осуществить мечту юности и стать глубоко причастным к миру ИТ, т.к. еще со студенческой поры я питал сильный интерес к автоматизации инженерных и технических расчетов, САПР, системам компьютерной алгебры и т.д. Решил развивать карьеру в этом направлении. Рассматриваю проекты в любых сферах. Быстро обучаюсь, технарь по складу ума.

### Сертификаты
![Диплом Java-разработчика](https://github.com/borodatyidrug/resume/blob/bb6ecad36916532b74333bdfef29a6d8699e0941/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%20Java-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%B0.png)
![Основы вёрстки сайта](https://github.com/borodatyidrug/resume/blob/bb6ecad36916532b74333bdfef29a6d8699e0941/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B%20%D0%B2%D0%B5%D1%80%D1%81%D1%82%D0%BA%D0%B8.png)
