������ � ��������
=================

privoxy-bl-upd.pl - ������, ��������������� ��� ���������� ���������� AdBlock � Privoxy

adblock.action - ��������, ��������������� �������� privoxy-bl-upd.pl

rpft.action - �������� �� RPFTeam

rpft.filter - ������� �� RPFTeam


��������� privoxy-bl-upd.pl (Linux):
====================================

 1. ��������� ������ � ����� ������������� �����.
 2. ��������� ����������� ��������� � ������� ($cfg, $tmp)
 3. ������ ������ �����������.
 4. ������� ��������� � ������� Privoxy � ������ "actionsfile":
 	����� ������:
		actionsfile default.action
 	������� ������:
 		actionsfile adblock.action
 5. ���������� ��� ������� (�� ��� sudo) ��� � ������� cron'�
 6. ��� ������������� ����������� ������� Privoxy



��������� ��������������� actionsfile
=====================================

������� ��������� � ������� Privoxy � ������ "actionsfile":
 	����� �������:
		actionsfile user.action
 	������� ������: 
		actionsfile rpft.action


��������� �������������� filterfile
===================================

������� ��������� � ������� Privoxy � ������ "filterfile":
 	����� ������:
		filterfile default.filter
 	������� ������: 
 		filterfile rpft.filter


�� ���� �������� ����������� �� https://groups.google.com/d/forum/rpfteam

Arcady N. Shpak (telegram: Greignar; e-mail/jabber: arcady.shpak@gmail.com)
