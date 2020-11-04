---
description: All information that you need about perms system in Minerea
---

# Permission system

## Introduction

Minerea is focused on easy using in small servers where everyone is friends and not want to wasting time for dealing with setting right permissions, but if you owner of big server or just want prohibit annoying user from using bot in your server, permission system at your service

### Admin permission

* [x] Add track to queue
* [x] Voteskip command
* [x] Skip own track
* [x] Skip other users tracks
* [x] Repeat, reshuffle, pause, unpause, leave, stop, volume commands
* [x] Change permissions, language, prefix of guild and access to config command
* [x] Destroy command

{% hint style="info" %}
Server owner **always** have Admin permission
{% endhint %}

### DJ permission

* [x] Add track to queue
* [x] Voteskip command
* [x] Skip own track
* [x] Skip other users tracks
* [x] Repeat, reshuffle, pause, unpause, leave, stop, volume commands
* [ ] Change permissions, language, prefix of guild and access to config command
* [ ] Destroy command

{% hint style="info" %}
By default @everyone has DJ permission
{% endhint %}

### User permission

* [x] Add track to queue, but can't add it to top of queue
* [x] Voteskip command
* [x] Skip own track
* [ ] Skip other users tracks
* [ ] Repeat, reshuffle, pause, unpause, leave, stop, volume commands
* [ ] Change permissions, language, prefix of guild and access to config command
* [ ] Destroy command

{% hint style="info" %}
By defauly @everyone has User permission
{% endhint %}

## Setting permissions

Any user or role can be added to any permission

For example

* !admin `add w.st#8014`

{% hint style="info" %}
If user or role has all DJ, Admin and User permission only the highest one take account of on command execution
{% endhint %}

Also you can denied someone from any permission

For example

* !admin `remove w.st#8014`

{% hint style="warning" %}
You can't remove yourself from Admin permission if you don't have Administrator rights on server itself, this action will leave you without any permissions at all!
{% endhint %}

{% hint style="info" %}
To remove @everyone from any permission you don't need ping it, just write everyone without @

  
For example 

* !dj `remove everyone`
{% endhint %}

