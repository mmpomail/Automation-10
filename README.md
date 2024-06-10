# План по тестированию записи на обучение по профессии "Инженер по тестированию" на сайте "Нетологии". 

## Тестовые сценарии.

Предварительное условие - в браузере открыта страница netology.ru.

### Пользовательские сценарии навигации к форме записи на курс "Инженер по тестированию".

#### Сценарий 1. 

 - на главной странице сайта "Нетология" нажать кнопку "Каталог курсов".
 - в выпавшем списке нажать на кнопку "Программирование". 
 - на открывшейся странице перейти в раздел "Инженер по тестированию". 
 - нажать кнопку "Записаться". 
 
 Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".
 
##### Сценарий 2. 
 
 - на главной странице сайта "Нетология" нажать кнопку "Каталог курсов".
 - в выпавшем списке нажать на кнопку "Программирование". 
 - на открывшейся странице перейти в раздел "Инженер по тестированию". 
 - прокрутить вниз страницу в браузере до появления формы записи на курс. 
 
Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".
 
#### Сценарий 3.
 
 - в разделе "Направления обучения" главной страницы сайта "Нетология" нажать на кнопку "Программирование". 
 - на открывшейся странице перейти в раздел "Инженер по тестированию". 
 - нажать кнопку "Записаться". 
 
 Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".
 
#### Сценарий 4. 
 
 - в разделе "Направления обучения" главной страницы сайта "Нетология" нажать на кнопку "Программирование". 
 - на открывшейся странице перейти в раздел "Инженер по тестированию". 
 - прокрутить вниз страницу в браузере до появления формы записи на курс.  
 
 Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".
 
#### Сценарий 5.
  
 - в разделе "Направления обучения" главной страницы сайта "Нетология" нажать на кнопку "Полный каталог". 
 - на открывшейся странице перейти в раздел "Инженер по тестированию". 
 - нажать кнопку "Записаться". 

 Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".

#### Сценарий 6. 

- в разделе "Направления обучения" главной страницы сайта "Нетология" нажать на кнопку "Полный каталог". 
- на открывшейся странице перейти в раздел "Инженер по тестированию". 
- прокрутить вниз страницу в браузере до появления формы записи на курс.  

 Ожидаемый результат: пользователь увидит форму записи на курс "Инженер по тестированию".

### Пользовательские сценарии заполнения формы записи на курс "Инженер по тестированию". 

Предварительное условие - в браузере открыта страница https://netology.ru/programs/qa#/
 
 #### Сценарий 1.
 
 - на странице специальности "Инженер по тестированию" нажать кнопку "Записаться". 
 - в поле "Имя" формы ввода ввести значение, состоящее из любых символов, кроме букв.
 - в поле "Телефон" формы ввода ввести номер телефона, состоящий из 11 цифр.
 - Нажать кнопку "Записаться".
 
 Ожидаемый результат: форма записи на курс "Инженер по тестированию" не примет данные, введённые в поле "Имя". 
 
 
 #### Сценарий 2.

 - на странице специальности "Инженер по тестированию" нажать кнопку "Записаться". 
 - в поле "Имя" формы ввода ввести значение, состоящее из любых букв.
 - в поле "Телефон" формы ввода ввести значение из любых символов, кроме цифр.
 - Нажать кнопку "Записаться".
 
 Ожидаемый результат: форма записи на курс "Инженер по тестированию" не примет данные, введённые в поле "Телефон".

 #### Сценарий 3.

 - на странице специальности "Инженер по тестированию" нажать кнопку "Записаться". 
 - в поле "Имя" формы ввода ввести значение, состоящее из любых букв.
 - в поле "Телефон" формы ввода ввести номер телефона, состоящий из 11 цифр.
 - Нажать кнопку "Записаться".

 Ожидаемый результат: будет произведена запись пользователя на курс "Инженер по тестированию". 
 

# Используемые инструменты. 

- IDE IntelliJ IDEA (для написания кода автотестов на Java)
- фреймворк Junit5 (для написания автотестов)
- фреймворк Selenide, подключенный в сборке Gradle ( для реализации автотестов)
- фреймворк JavaFaker (для генерации тестовых данных)
- браузер Google Chrome: DevTools для анализа кода сайта "Нетологии", сам браузер для проверки автотестов. 


# Необходимые разрешения, данные и доступы.

 - Доступ к сайту "Нетологии", возможность просмотра кода сайта через DevTools в GoogleChrome.

# Возможные риски. 

- Селекторы, используемые на сайте "Нетологии", могут быть неоптимальными для использования в автоматизированном тестировании.
- Возможное изменение структуры и наполнения сайта.
- Необходимость постоянно следить за актуальным состоянием сайта. 

# Необходимые специалисты. 

- Специлист автоматизированного тестирования со знанием языка программирования Java и фреймворков Junit 5, Selenide, JavaFaker.



# Оценка времени с учётом рисков.

- Необходимое время - порядка 1 - 1,5 часов. 
