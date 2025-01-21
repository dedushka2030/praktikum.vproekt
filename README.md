# Проект: Анализ оттока клиентов из Метанпромбанка
## Задача:
Проанализируйте клиентов регионального банка и выделите сегменты клиентов, которые склонны уходить из банка.
Проведите исследовательский анализ данных, определите все значимые признаки отточности (интервалы значений характеристик, которые связаны с повышенным оттоком, сравните портреты типичных клиентов, которые склонны и не склонны уходить из банка и т.д)
Сформулируйте и проверьте статистические гипотезы.
Проверьте гипотезу различия дохода между теми клиентами, которые ушли и теми, которые остались.
Сформулируйте и проверьте статистическую гипотезу относительно представленных данных, которая поможет внести ясность в исследование.
Объединяя признаки отточности, сформируйте сегменты, отберите из них лучшие и дайте по ним рекомендации.
По итогам исследования подготовьте презентацию. Для создания презентации используйте любой удобный инструмент, но отправить презентацию нужно обязательно в формате pdf, прикрепив ссылку на файл в основном проекте.

## Проведена работа: 
Проведен анализ данных, проведена сегментация клиентов по разным признакам, выделены портреты "ушедших" клиентов, проверены гипотезы.

## Описание данных

/datasets/bank_scrooge.csv

Датасет содержит данные о клиентах банка «Метанпром». Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск.

USERID — идентификатор пользователя,
score — баллы кредитного скоринга,
city — город,
gender — пол,
age — возраст,
equity — количество баллов собственности
balance — баланс на счёте,
products — количество продуктов, которыми пользуется клиент,
credit_card — есть ли кредитная карта,
last_activity — активный клиент,
EST_SALARY — оценочный доход клиента,
сhurn — признак оттока.
Декомпозиция проекта

### Шаг 1. Загрузка данных и изучение общей информации

### Шаг 2. Подготовка данных

2.1 Приведение названия столбцов к нижнему и "змеинному" регистру
2.2 Проверка наличия дубликатов
2.3 Проверка на наличие пропусков в данных
2.4 Проверка значений на наличие выбросов и аномалий
2.5 Преобразование данных к нужному типу
### Шаг 3. Исследовательский анализ данных

3.1 Какой общий процент оттока клиентов у банка
3.2 Какой процент оттока клиентов в разных городах
3.3 Общий портрет клиентов в разных городах по средним значениям
3.4 Выяснить влияет ли наличие кредитной карты, активности клиентов или пол на отток клиентов
### Шаг 4. Выделение категорий ушедших клиентов

4.1 Сегментирование клиентов по признакам
4.2 Составление портретов клиентов по нескольким сегментам
4.3 Выделение трех групп клиентов из выделенных сегментов, которые чаще всего уходят
### Шаг 5. Проверка гипотез

5.1 Формулирование и проверка гипотезы №1
5.2 Формулирование и проверка гипотезы №2
5.3 Формулирование и проверка гипотезы №3
### Шаг 6. Общий вывод и рекомендации
