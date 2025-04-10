# MikroTik telepítési útmutató

## Telepítés

- A telepítéshez nyomd meg az `i` betűt.
- Igen, szeretnéd folytatni *(Angol billentyűzet van beállítva alapértelmezetten a MikroTik-en, ezért a `z` betűt kell a magyar billentyűzeten megnyomni)*.
- Nyomj egy `Enter`-t, hogy újrainduljon.

## Belépés

- Az alapértelmezett felhasználónév: `admin`.
- Alapértelmezetten **nincs jelszó** beállítva, szóval csak egy `Enter`-t kell nyomni.
- A licencszerződést **NE olvasd végig**, ezért az `n` billentyűt nyomd meg.

## Jelszó beállítása

- Állíts be új jelszót.
- Ismételd meg a jelszó megadását.

## Interfészek ellenőrzése

- Nézd meg, megvan-e minden interface a routeren.

## IP-cím beállítások

- Adj **DHCP-vel IP-t** a NAT-os kártyának, és **kapcsold fel az interfészt**.
- Szintén **DHCP-vel adj IP-t** az interfésznek, és **kapcsold fel az interfészt**.
- Adj **statikus IP-t** az interfésznek, és **kapcsold fel**.  
  *(Az IP-nél a `/24`-et úgy tudod beírni, hogy az IP-cím végén az egyesnél nyomsz egy `TAB`-ot.)*

- Nézd meg, hogy **minden interfész megfelelően kapott-e IP-t**.

## Tűzfal beállítások

- Állítsd be a tűzfalon, hogy **elérd az internetet**.
- Állítsd be a tűzfalon, hogy ha **távoli asztalon próbálod meg elérni a szervert**, akkor **irányítsa át a megfelelő IP-re**.
