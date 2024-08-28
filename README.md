# php-interview

# OPCACHE

Улучшает производительность PHP путём сохранения скомпилированного байт-кода скриптов в разделяемой памяти, тем самым избавляя PHP от необходимости загружать и анализировать скрипты при каждом запросе.


# OOP
Наследование – это свойство позволяющее описать новый класс на основе уже существующего функциональностью

Полиморфизм - изменение решение проблемы разными способами в child классах

Инкапсуляция – позволяет объединить данные и методы, работающие с ними, в классе и скрыть детали
реализации от пользователей


# Абстрактный класс и интерфейс

Абстрактный класс и интерфейс - это два ключевых концепта объектно-ориентированного программирования, используемых для реализации полиморфизма. Вот основные различия между ними:

Реализация методов:

Абстрактный класс: Может содержать как абстрактные методы (методы без тела), так и конкретные методы (методы с телом).
Интерфейс: Может содержать только абстрактные методы, которые не имеют реализации.

Наследование:
Абстрактный класс: От него можно наследовать только один класс, так как поддерживается одиночное наследование.
Интерфейс: Может быть реализовано несколькими классами, так как поддерживается множественное наследование.

Поля класса:
Абстрактный класс: Может содержать поля, которые могут быть как абстрактными, так и конкретными.
Интерфейс: Не может содержать переменных, кроме констант.

Пример использования:
Абстрактный класс: Используется, когда необходимо предоставить базовую реализацию для группы связанных классов.
Интерфейс: Используется, когда требуется, чтобы несколько различных классов обеспечивали одинаковый набор методов, но с различной реализацией.

В целом, выбор между абстрактным классом и интерфейсом зависит от конкретной ситуации и требований вашего проекта.

# SOLID

Вот как расшифровывается акроним SOLID:

S: Single Responsibility Principle (Принцип единственной ответственности).
User, Email

O: Open-Closed Principle (Принцип открытости-закрытости).
поведение класса должно быть изменяемым без изменения самого класса.

L: Liskov Substitution Principle (Принцип подстановки Барбары Лисков).

класс B является подклассом класса A, то объекты класса A могут быть заменены объектами класса B без изменения правильности программы. Проще говоря, подкласс должен дополнять, а не нарушать поведение базового класса

I: Interface Segregation Principle (Принцип разделения интерфейса).
Интерфейсы должны быть разделены на более мелкие, специфичные интерфейсы, предназначенные для конкретных клиентов.

D: Dependency Inversion Principle (Принцип инверсии зависимостей).
классы должны зависеть от абстракций, а не от конкретных реализаций

1. Высокоуровневые модули не должны зависеть от низкоуровневых модулей. Оба типа модулей должны зависеть от абстракций.
2. Абстракции не должны зависеть от деталей. Детали должны зависеть от абстракций.

# KISS 
это принцип проектирования и программирования, при котором простота системы декларируется в качестве основной цели или ценности. Есть два варианта расшифровки аббревиатуры: «keep it simple, stupid» и более корректный «keep it short and simple»

KISS – keep it short simple – делайте вещи проще. Порой наиболее правильное решение – это наиболее простая реализация задачи, в которой нет ничего лишнего.

# DRY
Don't repeat yourself (DRY; с англ. — «не повторяйся») — это принцип разработки программного обеспечения, нацеленный на снижение повторения информации различного рода, особенно в системах со множеством слоёв абстрагирования.

DRY – Don’t repeat yourself – принцип призывает Вас не повторяться при написании кода. Все что Вы пишите в проекте, должно быть определено только один раз.


# Индексы
Существуют следующие типы индексов:

Уникальный (Unique index) — все значения встречаются только один раз. Если в столбец с уникальным индексом попробовать добавить неуникальное значение, то возникнет
ошибка.

Неуникальный (Non-unique index) — индекс, при котором значения могут повторяться.

Простой (Simple index) — индекс, состоящий из одного поля.

Составной (Composite Index) — индекс, который строится по нескольким столбцам таблицы. В данном типе индекса расположение полей является важным.

Древовидный (B-tree index) — индекс, который представлен в виде корневой вершины и узлов.

Частичный (Partial Indexes) — индекс, который состоит из подмножеств строк таблицы по определенному выражению.

# Дополнить -----------------------------

mysql explain

ООП
SOLID
PHP
Redis (как кэш и очередь) (почему нельзя хранить данные деген сурагы бар, потому что после рестарта данные пропадают деп айтасын. Но если настроить хранилище то можно сделать так чтобы не удалялись после рестарта деп айтсан хуеть етип калады и уже 1.500 деп сурай берсен болады)
Laravel
Другие фреймворки и их разница
Индексы
Составные индексы обязательно сурайды
Абстракция интерфейс

RabbitMQ/Kafka
ElasticSearch
Git

Структура данных 
разница php fpm  от  php cli
yeld return
depende (деп инжекшн деп инвершн
singleton
макросы