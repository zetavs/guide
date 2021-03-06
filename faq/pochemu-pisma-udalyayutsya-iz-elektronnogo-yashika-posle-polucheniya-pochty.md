# Почему письма удаляются из электронного ящика после получения почты?

Есть два режима работы \(протокола\) для получения писем из почтового ящика электронной почты:

![](../.gitbook/assets/image%20%2837%29.png)

## POP

При работе по протоколу POP \(он так же называется [POP3](https://ru.wikipedia.org/wiki/POP3)\) почтовый клиент \(в данном случае это Виртуальный склад\) скачивает все письма вместе с их вложениями при получении. После получения писем почтовый клиент работает с письмами автономно.

При настройке подключения по протоколу POP есть несколько настроек, позволяющих удалять письма с сервера, после получения почтовым клиентом:

![](../.gitbook/assets/image%20%2852%29.png)

* **Оставлять копии писем на сервере**. Если флаг не установлен, то после получения писем письма будут удалены из почтового ящика.

{% hint style="info" %}
Рекомендуем оставлять данный флаг включенным. Если письмо не подошло ни к одной настройке загрузки прайс-листов \(с учетом email и масок\), то оно будет удалено с сервера и не будет загружено в Виртуальный склад.
{% endhint %}

{% hint style="info" %}
Есть исключения в данном режиме работы. Например, почтовый сервер Яндекс не удаляет физически письма с сервера, но почтовый клиент больше не будет видеть их, т.е. для почтовых клиентов письма будут считаться удаленными \([статья на просторах интернета на эту тему](https://roem.ru/09-09-2014/109256/pochemu-yandeks-izmenil-standart-raboty-pop3-i-ne-daet-udalyat-elektronnye-pisma-iz-klienta/)\)
{% endhint %}

* **Удалять письма с сервера через**. Данная настройка позволяет удалять с сервера все письма, дата получения которых больше указанного количества дней.

{% hint style="info" %}
Как показывает практика настройка по удалению писем с сервера работает не со всеми почтовыми серверами.
{% endhint %}



## IMAP

[IMAP](https://ru.wikipedia.org/wiki/IMAP) является более современным протоколом и предоставляет почтовому клиенту различные методы по управлению письмами \(удаление, перемещение и т.д.\).

{% hint style="info" %}
На текущий момент Виртуальный склад не имеет встроенного почтового клиента и работает только в режиме получения почты из почтового ящика. Поэтому нет особой разницы по какому протоколу работать. Единственное преимущество протокола POP в том, что можно автоматически удалять письма при получении, если это позволяет почтовый сервер.
{% endhint %}



