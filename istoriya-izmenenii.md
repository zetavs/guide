# История изменений

## Версия 3.0.1.20 от 06.08.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Добавлен менеджер заданий для обмена с УТ с гарантированой доставкой.
* Добавлена возможность автоматически завершать зависшие обмены с сайтом.
* Добавлена возможность поиска, фиксации и отправки сообщений для тех предложений, цены на которые сильно отличаются друг от друга.

### Изменено:

* Нет.

### Исправлено:

* Обмен с сайта в форме списка обменов всегда помечался как ошибочный.
* Ошибка чтения пустой цены из файлов xls95

### Удалено:

* Нет.

## Версия 3.0.1.18 от 21.06.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет.

### Изменено:

* Нет.

### Исправлено:

* Ошибка разбора адреса электронной почты, если он указан как адрес и как имя отправителя.

### Удалено:

* Нет.

## Версия 3.0.1.17 от 03.06.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Возможнсть ручной синхронизации с УТ 10.3 по поставщику.
* Возможность получения файлов по http
* Возможность отказа от загрузки новых данных, если изменения превысили заданный порог.
* Отправка уведомления о получении файла, в котором слишком много изменений.
* Возможность ручной регистрации предложения для обмена с сайтом.
* Возможность пометить загрузку как неразобранную.

### Изменено:

* В веб-сервис получения предложений из виртуального склада добавлена информация о просроченных и исключенных позициях и датах изменений.
* Улучшена очистка сырых данных.

### Исправлено:

* Запись исключенных позиций при разборе остатков.
* Отборы по кроссировкам брендов при настройке пропускаемых и исключаемых позиций.
* При выборе варианта получения файлов через http нужно было обязательно указать адрес эл. почты.

### Удалено:

* Нет.

## Версия 3.0.1.16 от 28.04.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Добавлена возможность фильтрации прайсов перед загрузкой.

  Стало можно пропускать некоторые позиции по достаточно сложным настраиваемым фильтрам или помечать их как исключаемые.

* В форму настройки загрузки и в формы списков остатков добавлены переключатели с фильтрами актуальных, просроченных, исключенных предложений.
* Добавлена возможность синхронизации с УТ 10.3 \(для того, чтобы эти функции работали, на стороне УТ 10.3 должна быть обеспечена их поддержка\)
* Добавлена возможность использования COM-объекта Excel для загрузки файлов прайсов.

### Изменено:

* Улучшена система удаления старых данных.

### Исправлено:

* Нет.

### Удалено:

* Функциональность кроссировки брендов полностью перенесена в продукт Zeta Web.

## Версия 3.0.1.15 от 31.03.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет.

### Изменено:

* Обновлен внешний разархиватор для поддержки фомата RAR 5.

### Исправлено:

* Ошибки сопоставления брендов, если имя бренда было слишком длинным.

### Удалено:

* Нет.

## Версия 3.0.1.14 от 29.03.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Проверка подключения ADO из настройки загрузки.
* Проверка маски из настройки загрузки.
* Ручное переключение актуальности остатков из настройки загрузки.

### Изменено:

* Нет.

### Исправлено:

* Нет.

### Удалено:

* Нет.

## Версия 3.0.1.13 от 23.03.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет.

### Изменено:

* Нет.

### Исправлено:

* Определение изменений при загрузке остатков, когда различаются основные бренды и бренды поставщика.

### Удалено:

* Нет.

## Версия 3.0.1.12 от 05.02.2021

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

Кроссировка брендов из основной конфигурации 1С в Виртуальный склад \(при использовании Zeta Web\): версия Zeta Web должна быть не ниже 2.5.0.0 HTTP сервис ZetaApi должен быть опубликован и доступен в Виртуальном складе в Виртуальном складе регламентное задание "Обновление кроссировок брендов" должно выполняться по расписанию \(расписание задается в соответствии с частотой изменения брендов и кроссировок брендов в основной базе\) улучшена регистрация изменений для обмена с Zeta Web

### Изменено:

* Нет.

### Исправлено:

* Проблема с получением писем без вложений.

### Удалено:

* Нет.

## Версия 3.0.0.7 от 02.03.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет. 

### Изменено:

* Нет.

### Исправлено:

* Проблема с получением писем без вложений.

### Удалено:

* Нет.

## Версия 3.0.0.6 от 21.02.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет. 

### Изменено:

* Нет.

### Исправлено:

* Восстановлена возможность очистить остатки виртуального склада по поставщику из списка поставщиков и из карточки поставщика.

### Удалено:

* Нет.

## Версия 3.0.0.5 от 19.02.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Экспорт данных о складах поставщиков в 1С-часть конфигурации Zeta Web \(для корректной работы требуются веб-сервисы РММ версии 1.2.2.0 и младше и Zeta Web версии 2.4.4.41 и младше. Для работы в ВС должен быть опубликован http-сервис ExchangeVS\). 

### Изменено:

* Обновлена версия библиотеки обмена с сайтом.

### Исправлено:

* Нет.

### Удалено:

* Нет.

## Версия 3.0.0.4 от 19.01.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет. 

### Изменено:

* Нет.

### Исправлено:

* Автоматическое удаление было недоступно в клиент-серверном варианте в том случае, если тонкий клиент был запущен не на сервере.
* При поиске из внешней системы в результат попадали лишние строки, когда бренды поставщика, эталонной и собственной базы различались.

### Удалено:

* Нет.

## Версия 3.0.0.3 от 18.01.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Нет. 

### Изменено:

* Эталонный бренд в остатках виртуальных складов перенесен в измерение для обмена с сайтом.
* Поиск из внешней системы выполняется по бренду поставщика, эталонному бренду и бренду основной базы.

### Исправлено:

* Эталонные бренды всегда сохраняются в верхнем регистре.
* Существование артикула для записи проверяется по очищенному артикулу, а не по артикулу поставщика.

### Удалено:

* Нет.

## Версия 3.0.0.2 от 18.01.2018

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Добавлена подсистема автоматического получения обновлений \(ссылка на начальной странице и пункт "Установка обновлений" в меню "Администрирование".
* На начальной странице указывается полный номер версии конфигурации.
* В настройке загрузки прайс-листа добавлена возможность явного указания кодировки для полученных текстовых файлов.

### Изменено:

* Нет.

### Исправлено:

* Ошибка получения данных виртуального склада при получении данных в конфигурации "ЗетаСофт: Рабочее место менеджера".

### Удалено:

* Нет.

## Версия 3.0.0.1 от 09.10.2017

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* На начальную страницу добавлена информация о выполнении регламентных заданий виртуального склада.
* Добавлена возможность отправить файл прайса разработчику из любой загрузки \(например, при возникновении ошибки\). 

### Изменено:

* Получение файлов, разбор файлов и запись изменений теперь выполняются не в одном потоке, а в отдельных, т.е. вместо одного регламентного задания "Обработка данных виртуального склада" теперь есть три отдельных регламентных задания:
  * Виртуальный склад: 01. Получение данных.
  * Виртуальный склад: 02. Разбор полученных данных.
  * Виртуальный склад: 03. Запись изменений.

### Исправлено:

* Если при разборе полученного файла происходит ошибка, приводящая к падению платформы, то загрузка с таким файлом будет помечена как ошибочная и больше не будет обрабатываться. В списке загрузок такая загрузка будет выделена флагом "Ошибка" и красным цветом.

### Удалено:

* Нет.

## Версия 3.0.0.0 от 28.12.2017

**Минимальная версия для обновления: 3.0.0.0**

### Добавлено:

* Выпущена первая релизная версия 

### Изменено:

* Нет.

### Исправлено:

* Нет.

### Удалено:

* Нет.

