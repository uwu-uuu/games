
**guild wars 2** -  https://github.com/uwu-uuu/games/issues/1#issuecomment-3697620129 / / / [zapret_gw2.zip](https://github.com/user-attachments/files/24374878/zapret_gw2.zip) / / / pastebin-версия: https://pastebin.com/pt778hQy *обновлено 30.12*


перед запуском нужно выполнить в **cmd** ```netsh interface tcp set global timestamps=enabled``` и убедиться, что в ярлыке игры **нет** нестандартных настроек соединения [(wiki.guildwars2)](https://wiki.guildwars2.com/wiki/Command_line_arguments)
```
gw2_6112.cmd                 ; вход в локацию  / этот cmd используем в первую очередь

gw2_6112_80.cmd              ; вход в локацию+обновление

gw2_6112_443_80.cmd          ; вход в локацию+обновление+лаунчер+аукцион
```

**Snowbreak: Containment zone** - https://github.com/uwu-uuu/games/issues/3#issuecomment-3679097385 / / / [zapret_snowbreak.zip](https://github.com/user-attachments/files/24297283/zapret_snowbreak.zip) / / / pastebin-версия: https://pastebin.com/hPRGgFV4

!!перед запуском нужно выполнить в **cmd** ```netsh interface tcp set global timestamps=enabled``` иначе будет бан в игре, и убедиться, что у вас обновленный лаунчер
```
snowbreak_v1_1.cmd           ; исправление ошибки "определение полномочий"
```

*также принимаются запросы и на другие игры* 

команда timestamps=enabled выполняется 1 раз, для последующих запусков zapret это не требуется

как сделать лог wireshark https://github.com/uwu-uuu/games/wiki/%D0%9A%D0%B0%D0%BA-%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C-%D0%BB%D0%BE%D0%B3-wireshark

оригинальный инструментарий https://github.com/bol-van/zapret
