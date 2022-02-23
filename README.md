# UbuntuServ

+ Шёл по https://info-comp.ru/install-linux-ubuntu-20-04

## Прогрузил убунту, пробовал установить

+ Первое что встретилось - при установки просит отключить Intel RST, но как вариант удалить WIndows, судя по всему изза неё проблемы.

+ https://meshok-sovetov.ru/kak-otklyuchit-intel-rapid-storage-technology-windows-10/
Кратко:
-заходим в windows, WIN+X - Device Manager
-ищем драйвер, удаляем *RST_DEL.JPG*

### Результат - не помогло, сломал Windows

+ Помогло сменить тип boot установщика в биосе на Legasy External ( НЕ UEFI )

+ *настройка установки_.jpg*

+ пароль - 7151 (для входа не нужен)

### Перезагрузил, убунта не загрузилась, сменил на UEFI bootloader, пробую заново

+ всё же отключил в биосе RST
	> установилось

В первый раз скорее всего была проблема что не извлек флешку установщика

# Инструкция к Серверу
[Что делал при установки](installServer.md)

### Фиксы:

+ Пробуем установить [chromium браузер](https://losst.ru/ustanovka-chromium-ubuntu-16-04)
	> `sudo apt update`
	> `sudo apt install chromium-browser`

Не помогло
---


