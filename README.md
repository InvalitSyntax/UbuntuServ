# UbuntuServ

1) Шёл по https://info-comp.ru/install-linux-ubuntu-20-04

Прогрузил убунту, пробовал установить

2) Первое что встретилось - при установки просит отключить Intel RST, но как вариант удалить WIndows, судя по всему изза неё проблемы.

3) https://meshok-sovetov.ru/kak-otklyuchit-intel-rapid-storage-technology-windows-10/
Кратко:
-заходим в windows, WIN+X - Device Manager
-ищем драйвер, удаляем *RST_DEL.JPG*

Результат - не помогло, сломал Windows

1) Помогло сменить тип boot установщика в биосе на Legasy External ( НЕ UEFI )

2) *настройка установки_.jpg*

3) пароль - 7151 (для входа не нужен)

Перезагрузил, убунта не загрузилась, сменил на UEFI bootloader, пробую заново

1) всё же отключил в биосе RST

2) установилось

В первый раз скорее всего была проблема что не извлек флешку установщика

[installServer](installServer.md)