# Лабораторная работа 2 по дисциплине "Технологии программирования". 
## Постановка задачи
**Цели:**
1. Познакомиться c моделью MVC, ее сущностью и основными фреймворками на ее основе.
2. Разобраться с сущностями «модель», «контроллер», «представление», их функциональным
назначением.
3. Получить навыки разработки веб-приложений с использованием MVC-фреймворков.

### Индивидуальное задание: Вариант 9.
**Тип магазина:** Магазин канцелярских товаров  
**Функциональность приложения:** Покупателю должна быть предоставлена скидка в 10% на любой товар в его день рождения.
### Краткое описание проекта:
Разработанное приложение позволяет авторизироваться и регистрироваться пользователям, а так же добавлять, удалять и покупать товары. У каждого пользователя при регистрации вводится дата его рождения. При авторизации осуществляется проверка даты рождения пользователя с текущей, у именинника появляется скидка в 10% на все.

**Было разработано:**
* 3 модели: Product, User, Basket.
* 1 контроллер: HomeController .
* 6 представлений: Basket, CreateProduct, Index, Products, Profile, Registration.  

### Используемые языки / библиотеки / технологии
Язык проекта - C#  
Язык разметки - HTML  
Дополнительные библиотеки:
* *EntityFrameworkCore* - Для работы с базой данных
* *AspNetCore.Mvc* - Для работы с MVC

# Лабораторная работа 3 по дисциплине "Технологии программирования"
## Постановка задачи
**Цели:**
* Изучение модульного тестирования приложений.

### Индивидуальное задание:
* Написание тестов к лабораторной работе № 2.
### Краткое описание проекта:
Разработанное приложение позволяет осуществлять модульное тестирование методов контроллера(т.к. логика работы приложения содержится в нем) проекта лабораторной работы № 2.

**Было разработано:**
* HomeControllerTest - класс для тестирования основных методов контроллера лабораторной работы № 2.
* AddDbContext - класс для получения БД, созданной в лабораторной работы № 2.

### Используемые языки / библиотеки / технологии
Язык проекта - C#
  
Дополнительные библиотеки:
* *EntityFrameworkCore* - Для работы с БД
* *AspNetCore.Mvc* - Для работы с MVC
* *Moq* - Для имитации БД
  
Технологии:
* *xunit* - Инструмент модульного тестирования 