# Дипломный проект профессии «1C-программист: с нуля до middle»
 
## Кастомизация конфигурации «Управление IT-фирмой для компании «Ваш компьютерный мастер»

### Цель дипломного проекта

Разработать и подготовить к эксплуатации новый функциональный блок в конфигурации «Управление IT-фирмой».

Необходимо:

- реализовать новые подсистемы «Работа с заявками клиентов» и «Расчёт управленческой зарплаты» в соответствии с требованиями заказчика,
- подготовить отчёты по новой функциональности,
- оформить инструкцию по начальной настройке,
- подготовить автотест для проверки корректности работы подсистемы «Работа с заявками клиентов»,
- загрузить результат работы в новый репозиторий на GitHub.

------

### Описание задания

Компания «Ваш компьютерный мастер» использует конфигурацию «Управление IT-фирмой» от стороннего поставщика. Необходимо добавить в конфигурацию модуль для работы с заявками на обслуживание клиентов и модуль для расчёта управленческой заработной платы.

Для доработки конфигурации нужно использовать 1C:EDT. При доработке конфигурации максимально задействовать функциональность библиотеки стандартных подсистем.

Для добавленных объектов, реквизитов, методов используется префикс ВКМ_. Если меняется программный код существующих методов, изменения выделены комментариями.

Все добавленные объекты размещены в новой служебной подсистеме ВКМ_ДобавленныеОбъекты. В добавленных объектах не должно быть ошибок, выявляемых встроенным механизмом проверки 1C:EDT.

Вместе с результатами работы должны быть переданы инструкция по начальной настройке новой подсистемы и сценарий для автоматизированного тестирования модуля работы с заявками клиентов.

В блок Releases репозитория должен быть добавлен dt-файл демонстрационной базы с введёнными тестовыми данными, которые показывают работу всех механизмов системы.

------

### Подробные требования к подсистемам

- [Работа с заявками клиентов](https://github.com/MaryanaSl/Diplom/blob/main/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%B7%D0%B0%D1%8F%D0%B2%D0%BA%D0%B0%D0%BC%D0%B8%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.md).
- [Расчёт управленческой зарплаты](https://github.com/MaryanaSl/Diplom/blob/main/%D0%A0%D0%B0%D1%81%D1%87%D1%91%D1%82%20%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9%20%D0%B7%D0%B0%D1%80%D0%BF%D0%BB%D0%B0%D1%82%D1%8B.md).
- [Отчёты](https://github.com/MaryanaSl/Diplom/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%D1%8B.md).
- [Инструкция по начальной настройке](https://github.com/MaryanaSl/Diplom/blob/main/%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F%20%D0%BF%D0%BE%20%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B5.md).
- [Тестирование](https://github.com/MaryanaSl/Diplom/blob/main/%D0%A2%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.md).
