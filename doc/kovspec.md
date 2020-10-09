# Igényelt üzleti folyamatok

## Bevezető

Jelenlegi rendszerünkben a nyilvántartás és a könyvelés papír alapú. Az egyes
autók szervizintervallumait és a bérlési dátumokat ezzel a rendszerrel követni
nehéz. A kéréseink alább vannak listázva és azt taglalják, hogy mit várunk el a
rendszertől, hogy a munkánkat egyszerűbbé tudja tenni.

A pontok gyakoriság szerint csökkenő sorrendben vannak.

## Felhasználókezelés

### Vendégek

A vendégek (értsd nem regisztrált tagok) az oldalon látják a jelenleg
kikölcsönözhető autók listáját, képpel, márkanév és típus, illetve üzemanyag
megjelölésével.

### Regisztrált felhasználók

Az új rendszernek tudnia kell kezelni az ügyfeleket. Az elsődleges célközönség
a magánszemélyek, nem pedig cégek. Magánszemély felhasználót készíthet magának a
weboldalra, és belépés után kikölcsönözhet egy adott autót. A kölcsönzés
időtartamát 10 napban szeretnénk maximalizálni.

## Kölcsönzés

Szeretnénk, ha a kölcsönzés menete folyékonyabb lenne, és szeretnénk
minimalizálni a szükséges emberi kontaktust az autókölcsönzés során. Szeretnénk,
ha kölcsönzésenként mindössze két találkozás történne, amikor az autó kulcsait
és dokumentumait az ügyfél megkapja, majd pedig visszahozza (személyes
szerződéskötés).

A kölcsönzés menete a következő lenne:

1. A felhasználó kiválasztja a neki szükséges autót, majd a kölcsönzés gombra
   kattint.
2. A felhasználó kitölti a kölcsönzéshes szükséges információkat, mint például
   a kölcsönzés kezdete és vége. A kölcsönzés kezdete a jelenlegi dátumtól
   maximum 3 nappal térhet el a pozitív irányba, a kölcsönzés vége pedig
   a kölcsönzés kezdetétől számított 10 napban kell legyen.
3. A kölcsönzött autó felkerül a felhasználó profiljára, később az oldal
   ügyintéztője tudja levenni innen. A jelenleg kikölcsönzött autókat az oldalon
   nem kell megjeleníteni.


## Karbantartás

Az egyes autók rendelkeznek szükségletekkel, ilyen például az első kötelező
szerviz, a kopó-fogyó alkatrészek cseréje, valamint az esetleges kár utáni
javítás. Ezt a rendszernek tudnia kell kezelni, minden autóhoz szeretnénk, ha
társulna egy karbantartási lap, ahol az ügyintéző nyilván tudja tartani a fent
felsorolt tényezőket.

## Autóbeszerzés

Időnként szükség van arra, hogy a flottát új autókkal bővítsük. Az új autók
felvitele gördülékeny kell, hogy legyen, és automatikusan el kell hozzá
készülnie a karbantartási lapnak, amint az előző fejezetben kértünk.

## Céges kapcsolattartás

Az első fejezetben említettük, hogy az oldal elsődleges célközönsége
a magánszemélyek. Cég esetében egyéni egyeztetésre van szükség, amelyhez
a szükséges elérhetőségeket az oldalnak tartalmaznia kell.

## Cégek felhasználói (tervezett funkcionalitás, később)

Tervben van, hogy a cégeknek is online felületet biztosítsunk később, azonban
erre csak később tartanánk igényt.

## Automatizált autó értékesítés (tervezett funkcionalitás, későbbre)

A flotta már elhasználódott vagy elöregedett tagjait automatikusan értékesítésre
kínálnánk egy külső cégen keresztül, azonban egyelőre ez is csak tervezet.

## Összegzés

A fentiek alapján szeretnénk hogy elkészüljön az oldal felhasználói és
adminisztrátori része. Az adminisztrátor résznek egyszerűnek kell lennie, hogy
minél kevesebb betanulást igényeljen a használata.

# Követelménylista

- A weboldal legyen intuitív, egyszerűen használható.
- A weboldal felhasználói felülete legyen reszponzív.
- A weboldal legyen reaktív.
- A szerver képes legyen futni bármilyen népszerű operációs rendszeren
(GNU+Linux, MacOS, Windows).