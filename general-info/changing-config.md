---
description: >-
  На этой странице вы найдете всё, что вы можете изменить в настройках Minerea,
  и как это сделать правильно
---

# Изменение конфигурации

## Изменение префикса

Префикс по умолчанию в Minerea `!` вы всегда можете поменять его на любой другой

Например

* !prefix `m!`

![](../.gitbook/assets/rusettingprefix.png)

Теперь все команды работают с `m!`префиксом

{% hint style="info" %}
Вы можете упомянуть Minerea и она покажет текущий префикс на вашем сервере
{% endhint %}

{% hint style="info" %}
Команда help всегда может быть вызвана стандартным `!` префиксом
{% endhint %}

## Настройка языка

Minerea может говорить на многих языках, вот список поддерживаемых в настоящее время

* `en_US` — English \(Язык по умолчанию, если регион сервера не Россия\)
* `ru_RU` — Русский
* `cs_CZ` — Česky
* `it_IT` — Italiano

Например

* !lang `ru_RU`

![](../.gitbook/assets/lang.png)

Теперь все ответы на команды будут на Русском языке

## Настройка Live♪Player

Live♪Player предоставляют новый способ взаимодействия с ботом, вы можете управлять им с помощью реакций

{% tabs %}
{% tab title="Вкл." %}
!config `live player true`
{% endtab %}

{% tab title="Выкл." %}
!config `live player false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/ruliveplayer.png)

## Настройка объявления трека

Объявление трека, показывает информацию о текущей воспроизводимой музыке при ее запуске

{% tabs %}
{% tab title="Вкл." %}
!config `track announce true`
{% endtab %}

{% tab title="Выкл." %}
!config `track announce false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/rutrackannounce%20%281%29.png)

## Настройка автоматического возобновления

Автоматическое возобновление делает то что написано в названии, автоматически возобновляет текущий трек, когда кто-то присоединяется к каналу в котором бот

{% tabs %}
{% tab title="Вкл." %}
!config `auto resume true`
{% endtab %}

{% tab title="Выкл." %}
!config `auto resume false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/ruautoresume%20%281%29.png)



