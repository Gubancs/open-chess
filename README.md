# Open Chess
Ez a szoftver lehetőséget biztosít FIDE versenyek lebonyolítására, majd az eredmények közzétételére.
FIDE által elfogadott verseny rendező programok listája:
https://www.fide.com/FIDE/handbook/C04Annex3_EPLIST.pdf

# Támogatott verseny rendszerek
- Dutch System
- Lim System
- Dubov System
- Burstein System

# SWIFT 3 
Swift programozás alapok
- Konstans változó deklarációjára a <code>let</code> kulcsszót haszhnáljuk.
- A típusokat nem kötelező implicit megadni, de explicit típusos nyelv.
- String műveletnél a <code>\()</code> operátort használhatjuk egyébt változók kiértékelésére.
- A tömb típus elemei (<code>array</code>, <code>dictionary</code>) kulcs és index alapján is elérhetőek.
- A nyelv támogatja az opcionális értékeket amelyhez a kérdőjelet kell alkalmaznunk. pl. <code>var fruit:String? = 'Apple'</code>
- Swich case szerkezetnél nem kötelező a <code>break</code> használata de kötelező a <code>default</code> case megadása!
- A függvények egymásba ágyazhatóak, növelve ezzel a nagyobb függvények olvashatóságát.
- Egy függvény visszatérési értéke lehet egy másik függvény!
- Varargs támogatott a függvények paraméterében. pl.: <code>func sumOf(numbers: Int...) -> Int</code>
- Az osztályok constructora az <code>init()</code> függvény.
- A Java-ban megszokott <code>this</code> helyett SWIFT-ben a <code>self</code> kucsszóval hivatkozhatunk az osztály változóira függvényeire.
- Egy példány létrehozáshoz az osztály neve után rakjuk zárojelet. pl.: <code>var apple = Furit(name:"Apple")</code>
- Osztály származtatásnál a Java-ban megszokott <code>extends</code> kulcsszó helyett SWIFT-ben  egy sima kettősponttal jelöjük az öröklődést. 
- Az ősosztály-ben definiált változókat metódusokat a <code>super</code> kulcszóval érjük el.
- Viselkedés felülírásánál az <code>override</code> kulcsszó használata kötelező.
- A megszokott <code>null</code> helyet itt <code>nil</code> kulcsszóval hivatkozunk a NULL referenciára.
- Nested property eléréshez használhatjuk a NULL safe kérdőjel operátort. pl.: <code>triangleAndSquare?.triangle?.sideLength</code>
- Enum típusnál a <code>case</code> kulcsszó után kell felsorolnunk az enumeráció elemeit.
- Enum is egy osztály, lehet tulajdonsága és viselkedése, a self itt is működik.
