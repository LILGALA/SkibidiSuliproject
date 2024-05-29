# Epres Attila
1. Galavics Gergő Balázs
2. Hustikker Szabolcs
3. Jäger Máté

**Készítsetek egy autókereskedést szimuláló alkalmazást, a főoldalon az elérhető autók adatai jelenjenek meg ahol egy sor tartalmazza az autó nevét, üzemanyag típusát, évjáratát és állapotát (ez lehet “újszerű”, “használt”, ”kiváló”).
Készítsetek egy gombot amivel lehet rögzíteni egy új autót, ahol csak a megfelelő adatok megadásával lehet  hozzáadni adatot.
Legyen egy gomb a törlésre is!**

## Követelmények

Általános információk
A feladat során 2-3 fős csapatokban kell megoldanotok a lejjebb felsorolt témák egyikét. Szabadon is
választhatók témák, de előtte egyeztetni kell róla egy oktatóval! A projektben egy teljes értékű JavaFX

alkalmazást kell implementálni, teszteléseket végezni, dokumentálni, végül prezentálni. Ebből kifo-
lyólag a projektre 3 tárgyból is kaptok értékelést: Asztali alkalmazás fejlesztés 2, Szoftvertesztelés,

#### IKT projektmunka.

Mindegyik csapattagnak részt kell vennie a kódolási, tesztelési, dokumentációs és prezentációs folya-
matokban! Ajánlott, hogy mindenki a saját maga által implementált funkciókat tesztelje, dokumen-
tálja és prezentálja! Minden csapatban lehetőleg azonos képességű tagok legyenek!

Elvárások
#### Asztali alkalmazás fejlesztés 2

    - Teljes értékű JavaFX alkalmazás: A hangsúly a funkcionalitáson van, a design másodla-
    gos! Félkész funkciók ne legyenek az alkalmazásban! Ha megakadtok egy funkció fej-
    lesztése közben, az órákon megbeszéljük. A projektben az MVC struktúrát kell alkal-
    mazni (tehát külön-külön fájlokban és osztályokban legyen a nézet, a modell és a kont-
    roller). Az alkalmazásban a nagyon eltérő funkciókat külön-külön Pane-en kell megje-
    leníteni. Ezeken kívül JDK17-et és Maven csomagolót kell használni!

    - Kivétel- és hibakezelés: Az alkalmazásban minden előforduló kivételt és hibát le kell
    kezelni, ennek előfordulásakor adj vissza hibaüzenetet piros betűszínnel egy Label-be!
    Ha nem történt hiba és sikeresen lefutott egy funkció, adj vissza fekete / zöld betű-
    színnel egy tájékoztató üzenetet ugyanabban a Label-ben!

    - Adatbázis használata JDBC-vel: Az adatbázis funkciókat külön, erre a célra kialakított
    osztályban kell implementálni. Adatbázishoz való csatlakozás után érdemes rávizs-
    gálni, hogy létezik-e a kívánt adatbázis és táblák. Így ha nem létezik, akkor az alkalma-
    zásból létre is tudjuk hozni őket. Célszerű Derby-t használni, viszont egyéb MySQL
    megvalósítás is elfogadott.

    - Clean code alapelvek használata: A kód legyen letisztult, a különböző részek megfele-
    lően tagolva, indentálva! Figyelni kell, hogy a különböző funkciók külön-külön metó-
    dusokba / függvényekbe legyenek tagolva, ne egybe ömlesztve (+ újra felhasználható-
    ság)! Értelmes változó neveket kell használni, legyenek beszédesek, hogy kitalálható
    legyen, mire is jók. Célszerű kommentelni is, melyik részegység mire való.

    - Szoftver ergonómia: A feliratok jól láthatóak legyenek, a gombok megfelelően kattint-
    hatóak legyenek (ne túl kicsi, ne túl nagy)!

#### Szoftvertesztelés

    o Készítsd el a projekted dokumentációjához az osztály diagramot! A diagram tartal-
    mazza a megoldás összes osztályát, az osztályok adattagjait és metódusait továbbá a

    (ha van) jelöld nyilakkal az öröklődéseket (minta).
    o A program gyenge pontjain (ahol felhasználótól kérünk adatot), kezelje megfelelően
    egy tanult módzserrel úgy, hogy ne okozhasson hibát a felhasználó!
    o A programban valahol használjon legalább egy saját készítésű kivételt!

    o Készítsen tesztelési útmutatót a projektjéhez! Ez egy reademe.md (segédlet) fájl le-
    gyen, amiben lépésről lépésre bemutatja az alkalmazás felhasználását. Figyeljen arra,

    hogy a program minden funkcióját bemutassa vele! Például:
    ▪ 1. Indítsuk el az alkalmazást a yxz.java futtatásával.
    ▪ 2. Kattintsunk a “hozzáadás” gombra egy új elem hozzáadásához.
    ● 2/a. Adjunk meg egy nevet a ... mezőbe, ez lesz a ... neve
    ● 2/b Adjunk meg egy évszámot a ... mezőbe, ami a ... lesz
    ▪ ....
    o Készítsen Unit teszteket a programhoz! Válasszon ki legalább 2 függvényt, amelyhez
    elkészíti a Unit teszteteket. Minden függvényhez készítsen egy egyenlőség vizsgálatot
    legalább 3 opcióval
    ▪ Szám esetén:
    ● “Nem egyenlő” vizsgálat: túl kicsi opció
    ● “Egyenlő” vizsgálat: megfelelő opció
    ● “Nem szám” vizsgálat: rossz bemenet
    ▪ Szöveg esetén:
    ● “Üres” vizsgálat: üres bemeneti mező
    ● “Megfelelő” vizsgálat: jó bemenő adat
    ● “Hibás” vizsgálat: nem megfelelő adat

#### IKT projektmunka
##### Bemutató készítése az elkészített szoftverhez.

##### A bemutatónak legalább 15 diát kell tartalmaznia, mely az alábbi felépítést tartalmazza:

- A szoftver céljának rövid bemutatása
- A szoftver felépítése (menürendszer, képernyőképek, stb.)
- A szoftver használatának bemutatása
- Az elkészített szoftver továbbfejlesztési lehetőségei
##### A diákon maximum 28-as betűméret alkalmazható

##### Figyelni kell a helyesírásra, nyelvhelyességre (zavaró elírások, helyesírási hibák, stb.
    PONTLEVONÁST fog jelenteni)
##### Az elkészített bemutató előadása

### Téma ajánlások
1. Kiadás-kezelő alkalmazás

A feladat során egy olyan alkalmazást kell elkészíteni, ahol a felhasználó figyelni tudja a kiadá-
sait és bevételeit kategóriákra bontva. Funkciók: külön-külön Pane-en lehessen felvinni bank-
számlákat, kategóriákat, bevételeket és kiadásokat. Kiadás kategóriák lehetnek pl vásárlás,
szabadidő, rezsi, egyéb. Bevétel kategóriák lehetnek pl fizetés, maszekolás. Egy tranzakció
rögzítésekor (bevétel / kiadás felvitelekor) menteni kell a tranzakció dátumát is! A tranzakci-
ókról lehessen pdf formátumban jelentést készíteni egy meghatározott időszakra!

2. Call Center alkalmazás

A feladat során egy olyan alkalmazást kell elkészíteni, ahol egy call centeres operátor rögzíteni
tudja a bejövő és kimenő hívásait. Minden hívásnak rögzíteni kell a pontos időpontját, hívó és
hívott számot / melléket, ill. a hívás típusát. Egy hívás típus szerint lehet support (pl egy ügyfél
panasz), config (pl egy új szolgáltatás rendelés), ill other (pl két kolléga beszélgetése egy ügy
kapcsán). A bejövő és kimenő hívások külön-külön pane-eken legyenek megvalósítva! A hívá-
sokról lehessen pdf formátumban jelentést készíteni egy meghatározott időszakra!

3. Osztályzat-követő alkalmazás

A feladat során egy olyan alkalmazást kell elkészíteni, ahol egy tanuló tudja rögzíteni a jegyeit
tárgyanként. Egy külön pane-en lehessen új tárgyat felvinni. A fő pane-en lenyíló listával le-
hessen szűrni tárgyakat. A jegyek táblázata alatt jelenjen meg az adott tárgy átlaga. Az adat-
bázis táblájában minden bejegyzéshez rögzítésre kerüljön a tárgy, időpont, jegy, témakör (pl
mire kapta a diák az adott jegyet). A jegyekről lehessen pdf formátumban jelentést készíteni
egy meghatározott időszakra és egy vagy több meghatározott tárgyra.

4. ToDo list alkalmazás (Gyengébb csapatnak)

A feladat során egy olyan alkalmazást kell elkészíteni, ahol a felhasználó rögzíteni tudja a te-
endőit. Minden teendőhöz lehessen napot és prioritást rendelni, ill minden teendőt késznek
lehessen jelölni! A teendőkről lehessen pdf formátumban jelentést készíteni egy meghatáro-
zott időszakra!


5. Teniszpálya foglaló alkalmazás

Ebben a feladatban egy olyan alkalmazást kell készítenie amiben a felhasználó képes foglalást
leadni különböző pályákra.
A főoldalon egy lista fogadjon a meglévő foglalásokról ami mutatja hogy melyik pályán, ki és
mikor foglalta a pályát. Egy foglalás minden esetben 1 órára szól!
Az adatokat tetszőleges módon lehet tárolni (adatbázis, fájl, lista)!
Lehessen törölni adatokat a táblázatból, azonban ehhez jelenjen meg egy üzenet, hogy bizto-
san szeretnéd-e törölni és csak az igen válasz esetén törölje!
Legyen lehetőség hozzáadni foglalást, ehhez szükség van a foglaló nevére, egy pályára ami
egy legördülő listából választható (ebben fixen az 1. pálya, 2. pálya, 3. pálya és Center pályák
vannak) és egy időpontra amit hh:00 (csak az órát kell kérni) formátumban kell megadni (in-
nentől 1 óra a foglalás).

A program itt figyeljen a következőkre:

● Ne engedjen rögzíteni és adjon hibajelzést ha bármelyik mező üres vagy nem megfe-
lelő (pl 25 óra, -1 óra)

● Figyelje, hogy van-e már erre az időpontra foglalás, ha van ne engedje rögzíteni és
dobjon hibát!

### Jegyek kialakítása
#### Asztali alkalmazás fejlesztés 2
- Első jegy: Maga az alkalmazás funkcionalitása kerül értékelésre, kódolási technikák, ill
clean code 200%-os súlyozással.
- Második jegy: Szoftver ergonómia és design értékelése 50%-os súlyozással.

- Egyéb fontos infók: Az alkalmazás futtatható legyen az iskolai gépeken, de saját lapto-
pon is bemutatható. Értékeléskor be kell mutatni az alkalmazást futás közben, ill. ma-
gát a kódot is! Ha az alkalmazás nem fordítható buildelési hiba miatt, akkor mindkét
jegyre 1-es jegy jár. Ha valamilyen hibát / kivételt nem kezeltél le, akkor egy jegy levo-
nás kerül az első jegyből! Ezek elkerülésére adott a lehetőség az órákon való segítség
kérésre! Amennyiben egy csapat semmit nem adna le, úgy a második jegy is 200%-os
súlyozással kerül beírásra!

#### Szoftvertesztelés

- Első jegy: A kód értékelése, szerepelnek-e benne a szoftvertesztelés gyakorlati felada-
tai (100%-os jegy)

- Második jegy: A dokumentáció diagram és readme értékelése (200%-os jegy)

- Az alkalmazás ezen részeit egy konzultáció során be kell mutatni (ez lehet saját gépen
vagy iskolai gépen is). Itt elbeszélve születik meg a jegy. A jegy lehet eltérő a csapatta-
gok között amennyiben feltűnő az egyes csapattagokban a plágium/nem dolgozás gya-
núja.

#### IKT projektmunka 2
##### 1 db 100%-os jegy, melynek részei:
- A bemutató designja, a design egységessége a képkockákon - 10%
- Helyesírás, nyelvhelyesség - 10%
- A diák tartalma, értelmezhetősége 30%
- A bemutató szóbeli előadása, előadásmódja - 50%

### Munkamegosztás
##### Hustikker Szabolcs
- Adatbázis beolvasás
- PPT

##### Galavics Gergő Balázs
- Hibakezelés
- Tesztelés

##### Jäger Máté
- GUI
- Java

### Megvalósítás

##### Táblázat a megjelenítéshez
- Név
- Üzemanyag típus
- Évjárat
- Állapot
    - Újszerű
    - Használt
    - Kiváló
##### Gomb a hozzáadáshos
- Név
- Üzemanyag típus
- Évjárat
- Állapot
    - Újszerű
    - Használt
    - Kiváló
##### Gomb a törléshez
##### Adatok tárolása táblázatban
- Név
- Üzemanyag típus
- Évjárat
- Állapot
    - Újszerű
    - Használt
    - Kiváló
##### Adatok tárolása adatbázisban