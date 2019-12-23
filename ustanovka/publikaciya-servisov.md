---
description: Релиз 3.0.1.1
---

# Публикация сервисов

## Публикация web-сервиса ExchangeVS и http-сервиса ExchangeVS <a id="publikaciya-veb-servisa"></a>

В зависимости от того, какой программой вы будете пользоваться для публикации веб-сервиса, воспользуйтесь соответствующей инструкцией.

{% hint style="info" %}
Дистрибутив Apache - [https://drive.google.com/open?id=0B1XBNSCvmVxwcUxwTFpMejRXTjg](https://drive.google.com/open?id=0B1XBNSCvmVxwcUxwTFpMejRXTjg)​
{% endhint %}

### Apache или IIS <a id="apache-ili-iis"></a>

{% hint style="info" %}
Для публикации веб-сервиса необходимо запускать 1С в режиме **Конфигуратор** с правами администратора.
{% endhint %}

![](../.gitbook/assets/image%20%2826%29.png)

* После объединения и обновления необходимо опубликовать веб-сервис. Для этого переходим в Администрирование – Публикация на веб-сервере

![](../.gitbook/assets/image%20%2828%29.png)

* В открывшемся окне необходимо указать имя базы \(только латинские буквы, также можно использовать символ «-» и «\_»\), каталог и выставить галки как показано на рисунке. Нажмите «Опубликовать»

{% hint style="info" %}
Web-сервис ExchangeVS и http-сервис ExchangeVS необходимы для взаимодействия с решениями [Zeta РММ](https://www.zetasoft.ru/products-zeta-rmm/) и [Zeta Web](https://www.zetasoft.ru/products-zetaweb/).
{% endhint %}

![](../.gitbook/assets/image-21.png)

![Http-&#x441;&#x435;&#x440;&#x432;&#x438;&#x441;](../.gitbook/assets/image%20%2868%29.png)

### 1С Публикатор <a id="1s-publikator"></a>

* Скачайте 1С Публикатор \(по ссылке [https://drive.google.com/open?id=0B1XBNSCvmVxwbXhTc045Nk5JakE](https://drive.google.com/open?id=0B1XBNSCvmVxwbXhTc045Nk5JakE)\) и извлеките из архива.
* Путь к папке, в которой находится 1С Публикатор, должен содержать только латинские символы, желательно расположить в корневой папке диска С \(например C:\Publicator\)

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2FARo7OegrJ4tfY8%2Fimage.png?alt=media&token=919d8178-b2ab-43ab-a017-66afad87985f)

* Запустите приложение publicator.exe
* После успешного запуска вы увидите сообщение

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2K0UlRFNl372loV1%2Fimage.png?alt=media&token=4786cf29-f33c-4891-aa58-8246db91601b)

* Нажмите на сообщение или правой кнопкой на появившийся ярлык в области уведомлений и выберите “Панель управления”

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2OtDWJ44qVhnaBiq%2Fimage.png?alt=media&token=053377c1-0ebf-4bd1-ba74-01d8f1739f51)

* В браузере откроется страница управления 1С Публикатором, для начала работы необходимо принять Лицензионное соглашение
* Нажмите “Опубликовать” или “1С: Публикатор”, для того чтобы перейти к списку баз

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2T5vtTxy3Ac9KXyk%2Fimage.png?alt=media&token=500c6cd7-070d-4117-9c85-5a8e5ab87c03)

* В появившемся списке баз выберите необходимую базу, для которой вы хотите опубликовать веб-сервисы и нажмите на переключатель рядом с ней

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2Xn8YM8yCEHZC2Hv%2Fimage.png?alt=media&token=13ebd033-ae56-4b48-bbf5-bf64fbd7bde0)

* В открывшемся окне выберите версию платформы, под которой необходимо выполнить публикацию и нажмите “Опубликовать”. Если вы планируете работать в локальной сети, то выберите IP адреса для публикации.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2bHdNwAU9uzy4phf%2Fimage.png?alt=media&token=e9d3b079-e85f-4c08-af24-7c0c61e7bae6)

* После успешной публикации скопируйте адрес публикации выбранной базы, для того чтобы увидеть список адресов нажмите на ярлык справа от названия базы

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LDkZZ4KLHlNn6g8TQlV%2F-LLA--y7J_NlZQ9l4rwh%2F-LLA2gkiaNF5e1BVWdKO%2Fimage.png?alt=media&token=6801692b-11b5-4c50-a2cd-6b24b155aa8d)

* Используйте данный адрес для дальнейших настроек

После произведения публикации рекомендуется также произвести _**проверку текста публикации vrd:**_

```text
<?xml version="1.0" encoding="UTF-8"?>
<point xmlns="http://v8.1c.ru/8.2/virtual-resource-system"
  xmlns:xs="http://www.w3.org/2001/XMLSchema"
  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  base="/vs-to"
  ib="Srvr=&quot;mars&quot;;Ref=&quot;vs-to&quot;;">
 <httpServices publishByDefault="false">
  <service name="ExchangeVS"
    rootUrl="ExchangeVS"
    enable="true"
    reuseSessions="dontuse"
    sessionMaxAge="20"
    poolSize="10"
    poolTimeout="5"/>
 </httpServices>
 <standardOdata enable="true"
   reuseSessions="autouse"
   sessionMaxAge="20"
   poolSize="10"
   poolTimeout="5"/>
 <ws>
  <point name="InterfaceVersion"
    alias="InterfaceVersion.1cws"
    enable="false"
    reuseSessions="dontuse"
    sessionMaxAge="20"
    poolSize="10"
    poolTimeout="5"/>
  <point name="ExchangeVS"
    alias="ExchangeVS.1cws"
    enable="true"
    reuseSessions="dontuse"
    sessionMaxAge="20"
    poolSize="10"
    poolTimeout="5"/>
 </ws>
</point>
```

