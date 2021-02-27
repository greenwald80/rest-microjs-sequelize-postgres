Node.js REST сервер c вэб сервером на micro.js и ORM мэппингом к postgres на Sequelize.

JavaScript давно уже вышел за пределы "чисто браузерного языка" и на нём иногда реализуют микроприложения и микросервисы, не требующие большой нагрузки на процессор. Из-за особенностей реализации виртуальной машины и сборщика мусора node.js очень хорошо подходит для задач, активно использующих ввод-вывод. Таким образом построить сервер для раздачи фронтенда или для обработки активного пользовательского ввода через webSocket или большого количества http сообщений вполне можно на легковесной node.js. (НО всегда надо помнить и о минусах платформы, ввиде однопоточности и неудовлетворительной производительности в алгоритмах, требовательных к процессорным мощностям)

В данном видео мы реализуем простейший REST сервер, обслуживающий только добавление новой сущности и её раздачу. Для упрощения web взаимодействия я выбрал легковесный фреймворк micro.js, а для удобного взаимодействия с БД выбрал популярный ORM фреймворк Sequelize

Код из видео:
https://github.com/drucoder/microjs-s...​

Видео про установку Node.js:
https://www.youtube.com/watch?v=ZNjnM...​

Видео по NPM менеджеру пакетов для node.js:
https://www.youtube.com/watch?v=TsM4M...​

Видео про отладку кода в браузере и в целом про инструментарий web разработчика:
https://youtu.be/8ZKgsdxSdTc​

Стрим с разработкой простейшего плагина для Gradle:
https://youtu.be/WXAQ0r9vt2w​

Репозиторий фреймворка micro:
https://github.com/zeit/micro​

Репозиторий девелоперской версии фреймворка micro:
https://github.com/zeit/micro-dev​

Репозиторий со ссылками на разные фреймворки и библиотеки из инфраструктуры micro.js:
https://github.com/amio/awesome-micro​

Репозиторий роутера для micro.js:
https://github.com/pedronauck/micro-r...​

Документация про парсинг тела POST запроса:
https://github.com/zeit/micro#body-pa...​

Документация по Sequelize:
https://sequelize.org/v5/​

Документация по настройке разных диалектов в Sequelize:
https://sequelize.org/v5/manual/diale...​

Определение моделей (мэппингов) в Sequelize:
https://sequelize.org/v5/manual/model...​

Документация по построению запросов в Sequelize:
https://sequelize.org/v5/manual/query...​
https://sequelize.org/v5/manual/model...​

Отличный учебник по JavaScript на русском языке (бесплатный и активно обновляемый):
https://learn.javascript.ru/+

https://www.youtube.com/watch?v=PS_vWDxwATM&t=394s