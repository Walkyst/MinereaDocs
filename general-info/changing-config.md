---
description: >-
  This page include all what you can change in Minerea settings and how to do it
  right
---

# Changing config

## Setting prefix

Default prefix in Minerea is `!` you can always change it to any other

For example

* !prefix `m!`

![](../.gitbook/assets/settingprefix.png)

Now all commands works with `m!` prefix

{% hint style="info" %}
You can mention Minerea and it show current prefix in your server
{% endhint %}

{% hint style="info" %}
Help command always can be called through default `!` prefix
{% endhint %}

## Setting language

Minerea can speak on many languages, here list of currently supported

* `en_US` - English \(Default language if server region is not setted to Russia\)
* `ru_RU` - Русский
* `cs_CZ` - Česky
* `it_IT` - Italiano

For example

* !lang `en_US`

![](../.gitbook/assets/lang%20%281%29.png)

Now all responses to commands will be in English language

## Setting Live♪Player

Live♪Player provide new way to interact with bot, you can control it through reactions

{% tabs %}
{% tab title="Turn on" %}
!config `live player true`
{% endtab %}

{% tab title="Turn off" %}
!config `live player false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/liveplayer%20%281%29.png)

## Setting track announce

Track announce setting showing info about current playing music when it starting

{% tabs %}
{% tab title="Turn on" %}
!config `track announce true`
{% endtab %}

{% tab title="Turn off" %}
!config `track announce false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/trackannounce%20%281%29.png)

## Setting auto resume

Auto resume setting does what the title says, it automatically resuming current music when someone is joining channel where bot

{% tabs %}
{% tab title="Turn on" %}
!config `auto resume true`
{% endtab %}

{% tab title="Turn off" %}
!config `auto resume false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/autoresume.png)



