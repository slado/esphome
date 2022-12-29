# esphome

- install python ```choco install python```
- install pip ```choco install pip```
- install esphome ```pip install esphome```

build ```esphome run file.yaml```

- Ak nejde build, tak treba zmazat .platformio alebo aspon packages kde to vypisuje chybu
- i2c piny na S2 mini musia byt 33 a 35 aby to bolo kompatibilne s d1 mini shields. OLED caka i2c na pinoch D1 a D2
- powershell ansi colors https://github.com/dialex/JColor/issues/54#issuecomment-787108773 
```reg add HKCU\Console /v VirtualTerminalLevel /t REG_DWORD /d 1```
- ak build pada s OSError access denied, nainstalovat packages rucne cez pip. Daju sa instalovat hromadne, treba ich nazvy oddelit ciarkou
- ak build pada s tym, ze nenasiel idf_component_manager 
```pip install idf_component_manager```
- platformio/platform-espressif32 5.2.0 podporuje najnovsi esphome (od decembra 2022). Treba targetovat nan. https://github.com/platformio/platform-espressif32
