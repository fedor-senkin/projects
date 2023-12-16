# Портфолио: инженер по тестированию

## Обо мне 

Привет! Меня зовут Федор, я - начинающий тестировщик. <br>
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время стажировок, обучения и практики.
<br>

## Навыки и технологии
``Jira``, ``qase.io``, ``SQL``, `` Postman``, ``Swagger``, ``Trello``, <br>
``SoapUI``, ``Mockoon``, ``Chrome DevTools``, ``Miro``,  ``Android Studio``,   <br>
``Charles Proxy``
## Проекты
<p> </p>

### Тестирование веб-приложения для учителей от Skyeng
<p> </p>
<p>Что нужно было сделать: протестировать новую функциональность - добавление личных событий.<p>
  <li>Задача № 1. Тестирование требований.</li>
  <li>Задача № 2. Декомпозиция новой функциональности.</li> 
  <li>Задача № 3. Smoke-тестирование.</li> 
  <li>Задача № 4. Функциональное тестирование на уровне компонентов (GUI, API).</li> 
  <li>Задача № 5. Приемочное тестирование.</li> 
  <li>Задача № 6. Регрессионное тестирование.</li>
<p>
<p>Как решал: 
<li> Тестирование требований: несоответствующие критериям хороших требований формулировки и вопросы, возникшие по ним, объединены в <a href="skyeng/requirment testing.pdf">таблицу</a>.</li>
<li><a href="skyeng/декомпозиция.jpg">Декомпозиция</a> выполнена в Miro.</li>
<li><a href="skyeng/skyeng_smoke TC.pdf">Smoke</a>, <a href="skyeng/acceptance TC.pdf">приемочные</a> и функциональные <a href="skyeng/skyeng_API TC.pdf">API</a>-тесты оформлены в виде тест-кейсов.
<li>API тест-кейсы выполнены в Postman (пример: <a href="skyeng/Postman.jpg">запросы на создание, просмотр и удаление нового события в расписании</a>).
<li><a href="skyeng/functional tests.pdf">Функциональные (GUI)</a> и <a href="skyeng/regress test.pdf">регрессионные тесты</a> оформлены в виде чек-листов.</li>
<li>По выявленным в ходе тестирования дефектам составлены отчеты о дефектах (<a href="skyeng/bugreport1.pdf">пример 1</a>, <a href="skyeng/bugreport2.pdf">пример 2</a>).</li>
<p>
 <p>Итоги:<p>
<ol>
  <li>Научился составлять тест-план в Confluence.</li>
  <li>Умею работать в TMS qase.io: составлять функциональные (GUI, API) тест-кейсы, формировать тест-сьюты, выполнять тест-раны и анализировать их результаты.</li>
  <li>Научился составлять низкоуровневые чек-листы.</li> 
  <li>Знаю, как оформлять отчеты о дефектах и заводить их в BTS Jira.</li>
  <li>Умею работать в Postman: создавать коллекции API-тестов, составлять запросы и анализировать полученные ответы, пользоваться переменными, писать простые тесты при помощи сниппетов.</li>
  <li>Научился работать с Chrome DevTools: анализировать отправляемые запросы и полученные ответы (URL, метод, статус, заголовки, полезная нагрузка), извлекать токен из файлов cookie, записывать и сохранять log-файлы.</li>
  <li>Знаю, как выполнять декомпозицию системы.</li>
</ol>
<p> </p>

### Тестовая документация для тестирования главной страницы сайта <a href="https://cloud.ru/ru">Cloud.ru</a>
<p> </p>
<p>Что нужно было сделать: составить низкоуровневые чек-листы для проверки функциональности главной страницы.<p>
  <p>Как решал: 
<li> Провел исследовательское тестирование веб-страницы, по результатам которого составил <a href="Cloud.ru/Cloud.ru_main page check lists.pdf">чек-листы</a>.</li>
<p>
 <p>Итоги:<p>
<ol>
  <li>Научился составлять низкоуровневые чек-листы, отталкиваясь от уже реализованной функциональности.</li>
  </ol>
<p> </p>

### Тестирование мобильного приложения для изучения английского языка от Skyeng
<p> </p>
<p>Что нужно было сделать: провести функциональное тестирование разделов "Ситуации" и "Видеопрактика".<p>
  <li>Задача № 1. Тестирование требований.</li>
  <li>Задача № 2. Выбрать окружение для тестирования.</li> 
  <li>Задача № 3. Составить чек-листы.</li> 
  <li>Задача № 4. Провести тестирование по составленной документации.</li> 
  <li>Задача № 5. Выполнить подмену ответа от сервера на запрос отображения новых ситуаций.</li> 
  <li>Задача № 6. Написать отчет о тестировании.</li> 
 <p>
<p>Как решал: 
<li> Тестирование требований: несоответствующие критериям хороших требований формулировки и вопросы, возникшие по ним, объединены в <a href="Skyeng mobile/Requirement testing.pdf">таблицу</a>.</li>
<li>Выбор окружения для тестирования проведен на основании предоставленных статистических данных и оформлен в виде <a href="Skyeng mobile/Test environment.pdf">таблицы</a>.</li>
<li>Подготовлены <a href="Skyeng mobile/Checklists_mobile.pdf">чек-листы</a> на основании предоставленной документации.</li>
<li>Тестирование проведено на <a href="Skyeng mobile/Android Studio.png">эмуляторе</a> в Android Studio.</li>
<li>Подмена ответа выполнена при помощи сниффера трафика Charles Proxy с использованием функции Breakpoints (<a href="Skyeng mobile/Response breakpoint.pdf">пример использования инструмента</a>).</li>
<li>По результатам тестирования составлен <a href="Skyeng mobile/Test report_mobile.pdf">отчет</a> (<a href="Skyeng mobile/Bag reports_example.pdf">примеры баг-репортов</a>).</li>
<p>
 <p>Итоги:<p>
<ol>
  <li>Научился работать в Android Studio: выбирать и настраивать эмулятор, проводить функциональное тестирование мобильного приложения, выполнять специальные проверки для мобильных приложений.</li>
  <li>Умею устанавливать APK файлы на эмуляторы в Android Studio.</li>
  <li>Научился работать со сниффером трафика Charles Proxy: умею анализировать трафик, перехватывать запросы и подменять их.</li>
  </ol>
  <p> </p>
  
### Инвестиционная платформа <a href="https://zorko-exchange.ru/">Zorko</a> 
<p>Работал фулл-тайм в составе команды тестирования: тимлид + 4 тестировщика.</p>
<p> </p>
<p>Что нужно было сделать: протестировать сайт инвестиционной платформы Zorko.<p>
  <li>Задача № 1. Составить чек-листы проверок.<p>Как решал: <a href="Zorko/Zorko_checklist.jpg">чек-листы</a> составлял в Miro.</p></li>
  <li>Задача № 2. Выполнить тестирование верстки сайта (мобильная и веб-версии) с точки зрения UX/UI. <p>Как решал: отвечал за тестирование верстки в веб-версии на устройстве Windows в браузере Chrome, мобильной версии - на устройстве Android в браузере Firefox на соответствие макетам в Figma.</p></li> 
  <li>Задача № 3. Протестировать функционал регистрации нового пользователя и присвоения ему подтвержденного статуса инвестора (KYC). <p>Как решал: зарегистрировал двух новых тестовых пользователей в системе, которым через админку был присовен статус KYC.</p></li> 
  <li>Задача № 4. Протестировать функциональность продажи/покупки акций. <p>Как решал: от имени первого тестового пользователя разместил акции на маркете на продажу, от имени второго - разместил заявку на покупку акций на маркете.</p></li> 
  <p>
<p>Итоги:<p>
<ol>
  <li>Нашел 12 багов (из них 2 блокера).</li>
  <li>По каждому дефкту завел баг-репорт в ClickUp.</li>
  <li>Добавил 1 предложение по улучшению UI.</li> 
  <li>Результат работы передавал разработчику на созвоне в Google Meet.</li>
  </ol>
<p> </p>

## Контактная информация
- Email: f_senkin@mail.ru
