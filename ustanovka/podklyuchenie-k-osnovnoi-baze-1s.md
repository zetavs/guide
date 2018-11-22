---
description: Релиз 3.0.1.1
---

# Подключение к основной базе 1С

## Подключение к основной базе 1С

{% hint style="warning" %}
Актуально только при использовании Виртуального склада совместно с [Zeta Web](https://www.zetasoft.ru/products-zetaweb/)
{% endhint %}

Настройки подключения к основной базе 1С необходимы для получения данных через web-сервис ExchangeRMM и http-сервис Zeta API на стороне 1С.

### Публикация сервисов в основной базе

{% hint style="info" %}
Web-сервис ExchangeRMM поставляется в рамках отдельной конфигурации на поддержке. Порядок объединения конфигураций и публикации web-сервиса ExchangeRMM описаны в [базе знаний RMM](https://help-rmm.zetasoft.ru/ustanovka/izmenenie-osnovnoi-1s).
{% endhint %}

{% hint style="info" %}
Http-сервис Zeta API поставляется в рамках конфигурации Zeta Web. Процесс публикации htpp-сервиса Zeta API описан в [базе знаний Zeta Web](https://help-zetaweb.zetasoft.ru/ustanovka-i-obnovlenie/publikaciya-servisov-1s).
{% endhint %}

### Настройка подключения к основной базе

После публикации сервисов в основной базе необходимо ввести путь публикации, а также указать пользователя и пароль, под которым будет осуществляться доступ.

{% hint style="info" %}
Мы рекомендуем создать отдельного пользователя в основной базе 1С с необходимыми для доступа к сервисам правами.
{% endhint %}

Для перехода к настройкам в правой области на начальной странице выберите "Настройки виртуального склада" в разделе "Настройки".

![](../.gitbook/assets/image%20%2817%29.png)

![&#x424;&#x43E;&#x440;&#x43C;&#x430; &quot;&#x41D;&#x430;&#x441;&#x442;&#x440;&#x43E;&#x439;&#x43A;&#x438; &#x432;&#x438;&#x440;&#x442;&#x443;&#x430;&#x43B;&#x44C;&#x43D;&#x43E;&#x433;&#x43E; &#x441;&#x43A;&#x43B;&#x430;&#x434;&#x430;&quot;](../.gitbook/assets/image%20%2884%29.png)

  
Выберите вид своей базы: База на платформе "1С:8.х" с установленным модулем "ЗетаСофт:Веб-сервисы"

![](../.gitbook/assets/image%20%2858%29.png)

Заполните данные для подключения и нажмите "Проверить подключение к своей базе".

![](../.gitbook/assets/image%20%2894%29.png)

Если все предыдущие действия были выполнены правильно, то проверка подключения пройдет успешно, о чем будет соответствующее уведомление.

![](../.gitbook/assets/image%20%2847%29.png)


