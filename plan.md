# План курса “Профессиональная разработка ПО”

Лекция 1. Введение в языки программирования

1. Компилируемые и интерпретируемые
1. Статически и динамически типизируемые
1. Обзор наиболее популярных сегодня ЯП 

ДЗ: Установить среду разработки, написать и запустить простейший “Hello, World”

Лекция 2. Базовые понятия

1. Типы данных
1. Операции над примитивами
1. Ветвления
1. Циклы
1. Функции
1. Рекурсия

ДЗ: 20 простых алгоритмических задач, 10 решить на Java, 10 на JavaScript

Лекция 3. Введение в ООП

1. Конструкторы, поля и методы
1. Инкапсуляция
1. Полиморфизм (ситуативный, включения, параметрический)
1. Наследование
1. Интерфейсы и абстрактные классы

ДЗ: Написать реализацию бинарного дерева с возможностью добавлять и удалять элементы, а также поиском в глубину и в ширину

Лекция 4. Инструменты контроля версия, сборки и тестирования

1. Централизованные и распределённые VCS
1. Процесс сборки
1. Ant, Maven
1. Принципы юнит тестирования
1. Признаки хороших тестов
1. Моки
1. Покрытие тестами

ДЗ: Создать Maven-проект для своей реализаии дерева, написать тесты, проверить покрытие, залить на github.

Лекция 5. Коллекции

1. Нотация “О большое”
1. Списки
1. Множества
1. Ассоциативные массивы

ДЗ: Написать свою реализацию одного из типов коллекций и реализовать там методы map, filter, foldLeft

Лекция 6. Продвинутый ООП

1. Принципы SOLID
1. Шаблоны проектирования (Factory method, Builder, Singleton, Observer, Visitor)

ДЗ: Реализовать калькулятор “обратной польской нотации”. На входе - список токенов (числа, операции, функции). На выходе - результат вычисления.

Лекция 7. Среда выполнения

1. Виртуальная машина
1. Позднее связывание
1. Garbage collection
1. Структура heap’а
1. Особенности среды выполнения JavaScript в браузерах

ДЗ: продолжение предыдущей работы. Реализовать преобразование строки, содержащей математическое выражение, в список токенов.

Лекция 8. Многопоточность

1. Процессы и потоки
1. Создание потоков
1. Блок synchronize
1. Пулы потоков

ДЗ: решить задачу “обедающих философов”

Лекция 9. Введение в клинет-серверное программирование

1. Понятия клиента и сервера
1. Протоколы взаимодействия
1. Протокол HTTP (структура URL, загаловки и тело запроса, GET и POST)
2. Ajax

ДЗ: провести несколько операций с API VK.com используя cURL или другой HTTP-клиент

Лекция 10. Серверные технологии стека Java EE

1. Servlet
1. Filter
1. Listener
1. Application server

ДЗ: Написать приложение, предоставляющее HTTP API для получения данных в виде текста и файла, и для записи данных в виде текста, параметров и файлов

Лекция 11. Серверная инфраструктура проекта

1. SaaS, PaaS, IaaS
2. Базовые принципы работы с клаудами на примере Amazon
3. Введение в Linux

ДЗ: Задеплоить на AWS приложение, написанное в рамках предыдущей ДЗ.

Лекция 12. Введение в базы данных

1. Принципы работы RDBMS.
2. Quering, DML, DDL.
3. Constraints
4. Indexes
5. JDBC
6. DAO

ДЗ: Развернуть на AWS одну из RDBMS, спроектировать БД для приложения, разработанного для ДЗ 10, реализовать слой DAO для этого приложения.

Лекция 13. Клиентская веб-разработка

1. HTML и шаблонизаторы
2. CSS, LESS, SASS
3. jQuery
4. Twitter Bootstrap

ДЗ: сверстать страничку и предоставить >1 CSS разметки, которые можно переключать для полного изменения внешнего вида 

Лекция 14. Клиентская веб-разработка (часть 2)

1. RequireJS
2. BackboneJS

ДЗ: сделать Todo-list с возможность добавлять, удалять, выполнять задачи, добавлять в избранное и выводить только избранные. Опциональо - написать бэкенд для хранения данных на сервере.

Лекция 15. Введение в процессы разработки ПО

1. Водопадный процесс, его достоинтсва и недостатки
1. Современные подходы к организации процесса проектирования
1. Роли на проекте и кроссфункциональная команда
1. Коротко про Scrum и Kanban

ДЗ: подготовить backlog
