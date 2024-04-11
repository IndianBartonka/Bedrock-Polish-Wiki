<div align="center">

# Jak wyłączyć WatchDog

Znajdziesz tu informacje na temat jak wyłączyć WatchDog
</div>


## Wyłączanie z poziomu skryptów
```js
import {system} from "@minecraft/server"

system.beforeEvents.watchdogTerminate.subscribe((eventData) => {
eventData.cancel = true;
});
```

## Wyłączanie z poziomu BDS

Musisz w [Server.properties](..%2F..%2F..%2Fserver%2Fsoftwares%2Fvanilla%2FBDS.MD#script-watchdog-enable)
ustawić `script-watchdog-enable` na `false`<br>
Dodając poprostu linię `script-watchdog-enable=false`