Состав и описание
=================

privoxy-bl-upd.pl - скрипт, предназначенный для добавления блоклистов AdBlock в Privoxy

adblock.action - блэклист, сгенерированный скриптом privoxy-bl-upd.pl

rpft.action - блэклист от RPFTeam

rpft.filter - фильтры от RPFTeam


Установка privoxy-bl-upd.pl (Linux):
====================================

 1. Копируете скрипт в любую понравившуюся папку.
 2. Изменяете необходимые параметры в скрипте ($cfg, $tmp)
 3. Делаем скрипт исполняемым.
 4. Делаете изменения в конфиге Privoxy в секции "actionsfile":
 	после строки:
		actionsfile default.action
 	ставите строку:
 		actionsfile adblock.action
 5. Запускаете его вручную (из под sudo) или с помощью cron'а
 6. При необходимости производите рестарт Privoxy



Установка дополнительного actionsfile
=====================================

Делаете изменения в конфиге Privoxy в секции "actionsfile":
 	перед строкой:
		actionsfile user.action
 	ставите строку: 
		actionsfile rpft.action


Установка дополнительных filterfile
===================================

Делаете изменения в конфиге Privoxy в секции "filterfile":
 	после строки:
		filterfile default.filter
 	ставите строки: 
 		filterfile rpft.filter


По всем вопросам обращайтесь на https://groups.google.com/d/forum/rpfteam

Arcady N. Shpak (telegram: Greignar; e-mail/jabber: arcady.shpak@gmail.com)
