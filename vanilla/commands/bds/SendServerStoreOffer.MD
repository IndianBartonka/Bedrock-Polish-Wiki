<div align="center">

# sendshowstoreoffer

Komenda która wyświetla graczowi ofertę z sklepu
</div>

## Użycje
`/sendshowstoreoffer <player: target> <redirectType: RedirectLocation> <offerId: string>` <br>
`/sendshowstoreoffer <player: target> server` <br>

* `player` - Nazwa gracza 
* `redirectType` - Co ma zostać pokazane 
  *  `character` - skin
  *  `marketplace` - oferta z sklepu
  * `server` - Prawdopodobnie wyświetla sklep aktualnego serveru, nie wiemy dokładnie

### Wykonanie
#### character
Nie mamy pojęcia jak pozyskać ID danego skina z marketplace

#### marketplace
ID oferty idzie pozyskać z [rynku](https://www.minecraft.net/pl-pl/marketplace), url danej zawartości posiada w sobie ID <br>
`/sendshowstoreoffer JndjanBartonka marketplace 6317347f-94f5-4752-8141-aca8a48b38f8`

### server
Nie mamy pojęcia jak zrobić aby to działało , to jedyne co wiemy <br>
`/sendshowstoreoffer JndjanBartonka server`

---
## Wymagany poziom permisji operatorów
Aby wykonać je jako gracz potrzebujesz prawdopodobnie `4` poziomu permisji, w konsoli BDS wystarczy domyślny lvl