### План по тестированию и автоматизации формы записи на обучение профессии «Тестировщик ПО»:

**Объект тестирования:** https://netology.ru

**Цели тестирования:**
- Автоматизация тестирования сценария перехода к форме записи на курс «Тестировщик  ПО»
- Автоматизация тестирования сценария заполнения формы записи на курс «Тестировщик  ПО»

**1.	Перечень автоматизируемых сценариев:**

**1.1. Сценарии перехода к форме записи на курс Тестировщик ПО»:**

**Тест-кейс 1: Переход на страницу формы заявки на курс "Тестировщик ПО" через каталог курсов**

Шаг 1: Зайти на страницу по ссылке https://netology.ru

Шаг 2: В левом верхнем углу кликнуть правой кнопкой мыши на кнопку «Каталог курсов»

Шаг 3: Из выпадающего списка «Направления обучения» кликнуть правой кнопкой мыши на  кнопку «Программирование»

Шаг 4: После того, как осуществится переход на страницу «Программирование», скролить страницу вниз до  блока «Тестировщик ПО», затем кликнуть правой кнопкой мыши по 
данному блоку

Шаг 5: Нажать на кнопку «Записаться»

*__Ожидаемый результат:__* Открылась страница для заполнения формы записи на курс «Тестировщик ПО»

**Тест-кейс 2: Переход на страницу формы заявки на курс "Тестировщик ПО" через прямую ссылку**

Шаг 1: Набрать в адресной строке браузера  https://netology.ru/programs/qa

Шаг 2: После того, как осуществится переход на страницу записи на курс, нажать на кнопку «Записаться»

*__Ожидаемый результат:__* Открылась страница для заполнения формы записи на курс «Тестировщик ПО»

**Тест-кейс 3: Переход на страницу формы заявки на курс "Тестировщик ПО" через главную страницу**

Шаг 1: Зайти на страницу по ссылке https://netology.ru

Шаг 2: Скроллить страницу вниз до блока «Направления обучения»

Шаг 3: В блоке «Направление обучения» кликнуть правой кнопкой мыши на блок «Программирование» 

Шаг 4: После того, как осуществится переход на страницу «Программирование», скролить страницу вниз до  блока «Тестировщик ПО», затем кликнуть правой кнопкой мыши по данному блоку

Шаг 5: Нажать на кнопку «Записаться»

*__Ожидаемый результат:__* Открылась страница для заполнения формы записи на курс «Тестировщик ПО»

**Тест-кейс 4: Переход на страницу формы заявки на курс "Тестировщик ПО" через поисковую систему**

Шаг 1: Зайти на страницу по ссылке https://netology.ru

Шаг 2: В левом верхнем углу кликнуть правой кнопкой мыши на кнопку «Каталог курсов»

Шаг 3: В строке поиска набрать слово «Тестировщик»

Шаг 4: Кликнуть появившуюся карточку профессии «Тестировщик ПО»

Шаг 5: Нажать на кнопку «Записаться»

*__Ожидаемый результат:__* Открылась страница для заполнения формы записи на курс «Тестировщик ПО»

**1.2	Сценарии заполнения формы записи на курс «Тестировщик  ПО»:**

*__Предусловие:__*  *Открыта страница https://netology.ru/programs/qa#/order*

**Тест-кейс 1: Позитивный сценарий (Happy Path), когда все требуемые данные введены корректно**

Шаг 1: Ввести в поля «Имя» валидное имя *Мария*

Шаг 2: Ввести в поля «Телефон» 10 значный номер с кодом +7, например *+79114774466*

Шаг 3: Ввести в поля «Электронная почта» действующую почту *mari289071@mail.ru*

Шаг 4: Нажать на  кнопку «Записаться» 

*__Ожидаемый результат:__* Появляется сообщение о том, что регистрация прошла успешно,  на email *mari289071@mail.ru* приходит письмо «Заявка на курс «Тестировщик ПО» оформлена» 

**Тест-кейс 2: Отправка формы заявки с незаполненными полями**

Шаг 1: Оставить все поля незаполненными

Шаг 2: Нажать на  кнопку «Записаться» 

*__Ожидаемый результат:__* Заявка не отправляется, отображаются ошибки под полями ввода *«Обязательное поле»*

**Тест-кейс 3: Отправка формы заявки с незаполненным полем «Имя»**

Шаг 1: Оставить поле «Имя» незаполненным

Шаг 2: Ввести в поля «Телефон» номер телефона *+79114771618*

Шаг 3: Ввести в поля «Электронная почта» *mari289071@mail.ru*

Шаг 4: Нажать на кнопку «Записаться»

*__Ожидаемый результат:__* Заявка не отправляется, отображается ошибка под полем «Имя»: *«Обязательное поле»*

**Тест-кейс 4: Отправка формы заявки с незаполненным полем «Телефон»**

Шаг 1: Ввести в поля «Имя» имя на латинице, например *Maria* 

Шаг 2: Оставить поле «Телефон» незаполненным 

Шаг 3: Ввести в поле «Электронная почта» *mari289071@mail.ru*

Шаг 4: Нажать на  кнопку «Записаться»

*__Ожидаемый результат:__* Заявка не отправляется, отображается ошибка под полем «Телефон»: *«Обязательное поле»*

**Тест-кейс 5: Отправка формы заявки с незаполненным полем «Электронная почта»**

Шаг 1: Ввести в поля «Имя» валидное имя, например *Мария*

Шаг 2: Ввести в поля «Телефон» 10 значный номер с кодом +7, например *+79114774466*

Шаг 3: Оставить поле «Электронная почта» незаполненным 

Шаг 4: Нажать на  кнопку «Записаться»

*__Ожидаемый результат:__* Заявка не отправляется, отображается ошибка под полем  «Электронная почта»: *«Обязательное поле»*

**Тест-кейс 6: Ввод валидных значений в поле "Имя"**

Шаг 1: Ввести в поле на кириллице популярное имя *Иван*

Шаг 2: Ввести в поле на кириллице имя с использованием буквы "ё" *Фёкла*

Шаг 3: Ввести в поле имя на кириллице через дефис *Анна-Мария*

Шаг 4: Ввести в поле на латинице *Maria*

*__Ожидаемый результат:__* Поле заполняется, сообщений об ошибках нет

**Тест-кейс 7: Ввод невалидных значений в поле "Имя"**

Шаг 1: Ввести данные в поле на кириллице + цифры *Инна79*

Шаг 2: Ввести данные в поле спецсимволами  *Мария%!*

Шаг 3: Ввести данные в поле пробелом 

Шаг 4: Ввести данные в поле иероглифами *異體字*

*__Ожидаемый результат:__* Отображается ошибка *«Должно состоять из букв»*

**Тест-кейс 8: Ввод граничных значений в поле "Имя"**

Шаг 1: Ввести данные в поле на кириллице 1 символа *A*

Шаг 2: Ввести  в поле имя на кириллице состоящее из 2 символов *Ян*

Шаг 3: Ввести  в поле имя на кириллице состоящее из 3 символов *Ира*

Шаг 4: Ввести  в поле имя на кириллице состоящее из 15 символов *Абдурахмангаджи*

*__Ожидаемый результат:__* Невозможно ввести имя, состоящее из 1 символа, в остальных случаяз поле заполняется, сообщений об ошибках нет

**Тест-кейс 9: Ввод валидных значений в поле "Телефон"**

Шаг 1: Ввести в поле 10 цифр от 0 до 9 цифры, код +7 (на первом месте) *+79114771618*

Шаг 2: Ввести в поле  телефон с цифрой 8 вместо кода «+7» *89114771618*

Шаг 3: Ввести в поле номер телефона с кодом другой страны *+96550600334*

*__Ожидаемый результат:__*  Поле заполняется, сообщений об ошибках нет

**Тест-кейс 10: Ввод граничных значений в поле "Телефон"**

Шаг 1: Ввести в поле 9 цифр от 0 до 9 *+791147716*

*__Ожидаемый результат:__* Отображается ошибка *«Номер в формате +9 (999) 999-99-99»*

**Тест-кейс 11: Ввод валидных значений в поле «Электронная почта»**

Шаг 1: Ввести данные в поле  email в нижнем регистре *mari@mail.ru*

Шаг 2: Ввести данные в поле email в верхнем регистре *MARI@mail.ru*

Шаг 3: Ввести данные в поле email с цифрами в имени пользователя *mari289071@mail.ru*

Шаг 4: Ввести данные в поле email с цифрами в доменной части *mari289071@9m.com*

Шаг 5: Ввести данные в поле email с дефисом в имени пользователя *ma-ri@9m.com*

Шаг 6: Ввести данные в поле email с  несколькими точками в доменной части *mari28@mini.9m.com*

*__Ожидаемый результат:__*  Поле заполняется, сообщений об ошибках нет

**Тест-кейс 12: Ввод невалидных значений в поле «Электронная почта»**

Шаг 1: Ввести данные в поле  email без точек в доменной части *mari289071@mailru*

Шаг 2: Ввести данные в поле email с пробелами в имени пользователя *mari 289071 @mail.ru*

Шаг 3: Ввести данные в поле email без доменной части *mari289071@*

Шаг 4: Ввести данные в поле email без имени пользователя *@mail.ru*

Шаг 5: Ввести данные в поле без значка «@» в email *mari289071mail.ru*

Шаг 6: Ввести в данные поле email два знака «@@»  *mari289071@@mail.ru*

*__Ожидаемый результат:__*  Отображается ошибка *«Неверный email»*

**2. Перечень используемых инструментов с обоснованием выбора:**

- *Java JDK 11 или выше* – мощный объектно-ориентированный язык программирования с обширным набором библиотек, общепринятое базовое средство автоматизации тестирования
- *IntelliJ IDEA* - среда разработки для различных языков, совместимая с различными инструментами и возможностью их комбинирования и настройки под конкретный случай
- *JUnit5* - тестовый фреймворк, совместимый с JVM, содержит необходимые аннотации и assert’ы
- *Gradle* - система сборки проекта. Преимущества данной сборки: проще подключать зависимости, меньше кода, гибкость системы
- *Lombok* - плагин для создания аннотаций, заменяющих значительное количество однообразных конструкторов, например: getters/setters
- *Faker* - популярная библиотека-генератор данных. Позволяет создать различные данные автоматически с учетом местоположения, что позволяет экономить время, так как не надо придумывать данных и напрямую писать их в код
- *Selenide* - фреймворк для автоматизированного тестирования веб-приложений, подключение происходит автоматически, простое написание кода тестов.
- *Appveyor* - система CI. Интеграция с Github, простое подключение и настройка, бесплатное использование
- *Allure Report* - система репортинга, которая позволяет гибко строить  понятные отчеты о тестировании, а также автоматизирует сортировку тестов на баги, дефекты и сломанные тесты и отображает результат в TMS, багтрекере или в web-отчете
- *Git* - система контроля версий. Удобство, дает возможность одновременной параллельной разработки, есть интеграция с IntelliJ IDEA.
- *Docker* – платформа контейнеризации приложений, которая позволяет создавать контейнеры, автоматизировать их запуск и развертывание, управляет жизненным циклом, позволяет запускать на одной машине требуемое количество контейнеров
  
**3. Перечень необходимых разрешений, данных и доступов:**
- Разрешение от Нетологии на тестирование рабочей, активной версии сайта
- Необходим доступ к базе данных сайт Нетологии

**4. Перечень и описание возможных рисков при автоматизации:**
- Недоступность сайта netology.ru
- Недоступность страницы профессии с формой на сайте netology.ru
- Изменение дизайна сайта и/или web-элементов, задействованных в автотестах
- Некорректность тестовых данных при работе с Faker
- Дополнительная нагрузка на сайт
  
**5.	Перечень необходимых специалистов для автоматизации:** *Один AQA инженер (Java)* 

**6.	Интервальная оценка с учётом рисков в часах:**  *48 человеко-часов*, из них:
- Согласование доступа к сайту *12 часов*
- Подготовка необходимых инструментов и написание кода автотестов – *12 часов* 
- Подготовка отчетной документации и написание баг-рапортов – *8 часов* 
- Запас времени на форс-мажор - *16 часов*

