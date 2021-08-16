## План автоматизации тестирования отправки формы записи на курс ["Тестировщик ПО"](https://netology.ru/programs/qa) сайта [Netology.ru](https://netology.ru/)

## 1. Сценарии тестирования

Настоящий план автоматизации предполагает проведение функционального тестирования методом серого ящика.

В ходе тестирования планируется провести:

- **Тестирование пользовательского интерфейса и юзабилити**
  
  Будут написаны авто-тесты, имитирующие возможные способы перехода пользователями с главной страницы сайта 
  к форме отправки данных для записи на курс. Также будет произведена проверка видимости и работоспособности 
  существующих элементов страниц, которые для этого необходимы.
  
  
- **Тестирование формы отправки данных для записи на курс**  
  
  Будет произведена проверка формы отправки данных, включающая в себя позитивные и негативные сценарии 
  для существующих и незарегистрированных пользователей, а также проверка валидации заполняемых полей согласно известной 
  информации о данной форме. 

Набор тестовых сценариев представлен в [отдельном документе](https://github.com/evgsemenov/6.4-Automation-Plan/blob/master/test_suit.md).

## 2. Инструментарий

- **IntelliJ IDEA** - интегрированная среда разработки программного обеспечения
- **Java JDK 11** - язык программирования общего назначения 
- **Gradle** - проект-менеджер автоматической сборки
- **JUnit5 v5.7.2**- тестовый фреймворк
- **Selenide v5.23.2** - реализация взаимодействия с UI
- **Cucumber JVM: JUnit v6.11.0** - интеграция ручных тестов с автоматическими и их поддержка
- **Allure JUnit 5 v2.14.0** - отчетность и аналитика
- **Git** - система контроля версий ПО
- **Github Actions** - непрерывная интеграция с автоматической проверкой публикуемых билдов
- **JavaFaker** - плагин для генерации тестовых данных
- **Lombok** - плагин для замещения значительного объема функциональных строк кода, не содержащих бизнес-логики, краткими аннотациями
- **DBeaver** - клиент для мониторинга и администрирования базы данных

## 3. Перечень необходимых разрешений/данных/доступов

- Разрешение на проведение автоматизированного тестирования сайта [Netology.ru](https://netology.ru/)
- Доступ к базе данных сайта [Netology.ru](https://netology.ru/)
- Доступ к API сайта [Netology.ru](https://netology.ru/)

## 4. Перечень и описание возможных рисков при автоматизации

- Возможные затруднения с поиском корректных CSS-селекторов элементов сайта
- Возможное изменение структуры сайта и его отдельных страниц при проведении тестирования
- Возможна обработка отделом продаж "ложных" заявок, отправленных в ходе тестирования
- Увеличение расходов на дальнейшую поддержку написанных авто-тестов

## 5. Перечень необходимых специалистов для автоматизации

Инженер по автоматическому тестированию - 1 человек

## 6. Интервальная оценка с учётом рисков (в часах)

- 8-12 часов - подготовка тестовой среды, написание кода авто-тестов
- 2-4 часа - составление отчетности о проведении тестирования, заведение выявленных дефектов
- 8 часов - наступление рисков при автоматизации
  
  **Итого:** 24 часа

