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

* `cs_CZ` - Česky
* `en_US` - English
* `it_IT` - Italiano
* `ru_RU` - Русский

For example

* !lang `ru_RU`

![](../.gitbook/assets/lang.png)

Now all responses to commands will be in Russian language

{% hint style="info" %}
If Minerea on join detect that your server region setted to Russian, ru\_RU language will be setted automatically

You still can set English language through !lang `en_US`
{% endhint %}

## Setting track announce

Track announce setting showing info about current playing music when it starting

Here example how to turn on or turn off this feature

{% tabs %}
{% tab title="Turn on" %}
!config `track_announce true`
{% endtab %}

{% tab title="Turn off" %}
!config `track_announce false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/trackannounce.png)

## Setting auto resume

Auto resume setting does what the title says, it automatically resuming current music when someone is joining channel where bot

Here example how to turn on or turn off this feature

{% tabs %}
{% tab title="Turn on" %}
!config `auto_resume true`
{% endtab %}

{% tab title="Turn off" %}
!config `auto_resume false`
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/autoresume%20%281%29.png)



