---
description: Релиз 3.0.1.0
---

# Основные параметры загрузки

Для создания новой настройки на начальной странице выберите соответствующий пункт в правой области.

![](../.gitbook/assets/image%20%2810%29.png)

После чего откроется форма создания новой настройки.

![](../.gitbook/assets/image%20%284%29.png)

В шапке настройки необходимо заполнить 3 обязательных реквизита:

1. Поставщик
2. Наименование настройки
3. Валюта

## Основные параметры загрузки

### Поставщик

Нажмите на выпадающий список в поле выбора поставщика.

![](../.gitbook/assets/image%20%2814%29.png)

Выберите из списка или создайте нового поставщика. Для добавления поставщика нажмите на кнопку "+".

{% hint style="info" %}
В списке выбора отображаются последние поставщики, которые использовались в настройках прайс-листов. Для того, чтобы увидеть всех поставщиков нажмите "Показать все"
{% endhint %}

### Создание поставщика

При нажатии на "+" откроется форма создания поставщика.

![](../.gitbook/assets/image.png)

Введите наименование поставщика \(как он будет отображаться в Виртуальном складе\).

{% hint style="info" %}
Если Виртуальный склад подключен к основной базе 1С, то необходимо выбрать поставщика из основной базы.
{% endhint %}

Для выбора поставщика из основной базы нажмите на "..." в поле ввода идентификатора поставщика.

![](../.gitbook/assets/image%20%2828%29.png)

В открывшейся форме найдите необходимого поставщика и выберите его.

![](../.gitbook/assets/image%20%2811%29.png)

В результате в поле "Идентификатор поставщика" подставится уникальный код этого поставщика, а также необходимо убедиться, что установлена галка "Поставщик из основной базы"

![](../.gitbook/assets/image%20%2827%29.png)

### Наименование загрузки

Наименование загрузки может быть любым и носит информационный характер. Например, если от одного поставщика приходит несколько прайс-листов с остатками на разных складах, то мы можем указать это в названии настройки, для удобства идентификации и выбора.

![](../.gitbook/assets/image%20%2821%29.png)

### Валюта прайс-листа

Выберите валюту из выпадающего списка.

![](../.gitbook/assets/image%20%283%29.png)

### Добавление валюты

Для добавления валюты необходимо перейти в справочник "Валюты" с помощью меню.

![](../.gitbook/assets/image%20%286%29.png)

В открывшемся справочнике нажмите "Создать" и выберите "По классификатору".

![](../.gitbook/assets/image%20%2812%29.png)

![](../.gitbook/assets/image%20%288%29.png)

Найдите в списке нужную валюту и выберите ее.

После добавления валюта будет доступна для выбора в настройке загрузки.

## Параметры получения файлов

Следующим этапом является настройка источника.

![](../.gitbook/assets/image%20%2831%29.png)

В зависимости от выбранного варианта получения файлов доступны соответствующие маски.

### Инструкция по использованию маски

Следующие символы в строке шаблона являются служебными и имеют смысл, отличный от символа строки:

* **% \(процент\)**: последовательность, содержащая любое количество произвольных символов
* **\_ \(подчеркивание\)**: один произвольный символ
* **\[…\] \(в квадратных скобках один или несколько символов\)**: любой одиночный символ из перечисленных внутри квадратных скобок В перечислении могут встречаться диапазоны, например a-z, означающие произвольный символ, входящий в диапазон, включая концы диапазона. 
* **\[^...\]\(в квадратных скобках значок отрицания, за которым следует один или несколько символов\)**: любой одиночный символ, кроме тех, которые перечислены следом за значком отрицания

Любой другой символ означает сам себя и не несет никакой дополнительной нагрузки.

Если в качестве самого себя необходимо записать один из перечисленных символов, то ему должен предшествовать &lt;Спецсимвол&gt;. Сам &lt;Спецсимвол&gt; \(любой подходящий символ\) определяется в этом же операторе после ключевого слова СПЕЦСИМВОЛ.

Например, шаблон “%АБВ\[0-9\]\[абвг\]\абв%” СПЕЦСИМВОЛ “\” означает подстроку, состоящую из последовательности символов: буквы А; буквы Б; буквы В; одной цифры; одной из букв а, б, в или г; символа подчеркивания; буквы а; буквы б; буквы в.

Причем перед этой последовательностью может располагаться произвольный набор символов.

### Электронная почта \(e-mail\)

![](../.gitbook/assets/image%20%2813%29.png)

Обязательным для заполнения является лишь адрес электронной почты, остальные параметры позволяют выбрать нужные письма, используя маски по:

* Теме письма
* Наименованию архива
* Наименованию файла \(в письме или в архиве\)

![&#x41F;&#x440;&#x438;&#x43C;&#x435;&#x440; &#x437;&#x430;&#x43F;&#x43E;&#x43B;&#x43D;&#x435;&#x43D;&#x438;&#x44F; &#x43D;&#x430;&#x441;&#x442;&#x440;&#x43E;&#x435;&#x43A; email](../.gitbook/assets/image%20%2820%29.png)

Для получения прайс-листа в соответствии с указанными настройками нажмите "Получить файлы по электронной почте". В результате загруженные файлы появятся в табличной части.

![](../.gitbook/assets/image%20%2830%29.png)

### Каталог в файловой системе

В качестве источника можно также использовать локальный каталог.

![](../.gitbook/assets/image%20%2837%29.png)

В этом случае необходимо указать путь к каталогу и маску наименования файла.

Для получения прайс-листа в соответствии с указанными настройками нажмите "Получить файлы из каталога". В результате загруженные файлы появятся в табличной части.

![](../.gitbook/assets/image%20%281%29.png)

### Ручное добавление

Для ручного добавления необходимо выбрать необходимый файл вручную.

![](../.gitbook/assets/image%20%2833%29.png)

### Список файлов. Открытие файла в 1С

В результате выбора параметров получения файлов и после их получения, в списке в списке будут доступны файлы.

![](../.gitbook/assets/image%20%2822%29.png)

{% hint style="info" %}
Если в списке файлов нет файлов, значит указанным параметрам не соответствует ни один файл.
{% endhint %}

После загрузки файла есть возможность открыть его в 1С для того, чтобы проверить, как он открывается внутренними средствами платформы 1С. Для этого нажмите "Открыть файл в 1С"

## Общие настройки обработки файлов

После настройки параметров получения файлов необходимо проверить общие настройки обработки.

![](../.gitbook/assets/image%20%2835%29.png)

### Вариант рахархивирования файлов

Настройка используется в тех случаях, когда прайс-лист приходит в архиве без расширения, но на самом деле это zip-архив. В этом случае необходимо выбрать "Разархивировать как zip-архив".

{% hint style="info" %}
Во всех остальных случаях достаточно оставить параметр "Определять по расширению"
{% endhint %}

### Формат загрузки

Данной настройкой стоит воспользоваться в том случае, когда формат файла не соответствует его расширению.

Например, поставщик при формировании прайс-листа использует текстовый формат с разделителями \(что соответствует формату csv\), а в расширении указывает xls. В этом случае необходимо выбрать действительный формат.

![](../.gitbook/assets/image%20%2838%29.png)

{% hint style="info" %}
Во всех остальных случаях достаточно оставить параметр "Определять по расширению"
{% endhint %}

### Кодировка текста

Данной настройкой стоит воспользоваться, если системная кодировка не соответствует кодировке в файле.

{% hint style="info" %}
Во всех остальных случаях достаточно оставить параметр "Системная"
{% endhint %}

### Дополнительные параметры

* **Строка шапки** - может использоваться как отдельный параметр при настройке загрузки колонок.
* **Первая и последняя строка** - диапазон загрузи строк. \(0 - до конца документа\)
* **Первый и последний лист** - какие листы загружаем из файла.
* **Разделитель колонок** - можно указать нестандартный разделить для прайс-листов в текстовом формате \(по-умолчанию ";"\)/
* **Загружать позиции без количества** - параметр, который позволяет настроить загрузку предложений без количества \(под заказ\) из прайс-листа поставщика.


