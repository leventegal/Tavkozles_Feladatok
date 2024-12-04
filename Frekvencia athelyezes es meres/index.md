# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Gál Levente Máté  
**A mérés tárgya:** Programozható Antennaerősítő-szűrő használata  
**A mérés száma:** 7. mérés  
**A mérés dátuma:** 2024. 11. 27.  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1 
**Helyszín:** V3 Labor 

---

## 1. Mérés Célja

A **Johansson 6700 Profiler** antennaerősítő-szűrő megismerése és beállítása, különböző antennák jeleinek kezelése.
Ez az eszköz a rádiófrekvenciás jelek szűrésére és erősítésére szolgál, mely különösen hasznos, ha különböző frekvenciasávokat szeretnénk célzottan feldolgozni, illetve javítani az átvitel minőségét.
Feladata, hogy egy antenna segítségével először befogjuk az **Avasi adó toronyból** sugárzott adásokat. Majd a helyes sorrendben lévő csatornákat és helyen lévő frekvencián a **Johansson eszközzel** áthelyezzük a csatornákat úgy, hogy a régen kiépített rövid UTP kábeles rendszerben is zavartalanul lehessen TV-t nézni.

---

## 2. Helyszín

- **Antenna Típus:** Iskra P-20  
- **Antenna magassága:** 1.5m  
- **Környezet:** V3 labor
- **Adó Távolsága:** 780m  

<details>   
  <summary> ADÓTORONY - VÉTELI HELY távolság </summary>
  
  <img src="https://erosbence27.github.io/jegyzokonyv/image/map.png" alt="TVtorony" />
  
</details>

<br>


---

## 3. Alkalmazott Mérőeszközök és Készülékek

| Műszer neve                         | Típus           | Gyártási szám         |
| ----------------------------------- | ---------       | -------------------   |
| Programozható antennaerősítő-szűrő  | Johansson 6700  |                       |
| Antenna                             | Iskra P-20      | 38331002931507        |
| Spektrum Analizátor                 | Metek  HDD      |                       |

---

## 4. Blokkvázlat

---

## 5. Mérési Adatok és Eredmények

### Mért adatok

Az alábbi táblázat a különböző frekvenciasávokhoz tartozó mért jelerősségeket hasonlítja össze a Johansson 6700 Profiler alkalmazása nélkül és annak használatával.

| Beérkező Csatornák (CH) | Frekvencia (MHz) | Jelszint (dBu) | Átrendezett Csatornák (CH) |  Frekvencia (MHz) | Jelszint (dBuV) |
|---------------|------------------|----------------|--------------------------|----------------------------|----------------------------|
| 28            | 530              | 63             | 40                       | 624                        | 100.5                      |
| 31            | 554              | 61             | 41                       | 632                        | 100.7                      |
| 35            | 586              | 61             | 42                       | 640                        | 100.9                      |
| 41            | 634              | 58             | 46                       | 660                        | 100.7                      |
| 45            | 666              | 58             | 49                       | 652                        | 100.3                      |
| 48            | 690              | 57             | 44                       | 663                        | 100.5                      |

### Eredmények értelmezése

A mérések során a Johansson 6700 Profiler a kiválasztott frekvenciasávokban egyenletes, 30 dB-es erősítést nyújtott. Az eredmények alapján a készülék hatékonyan növelte a bemeneti jelerősséget az adott frekvenciasávokban, ami elősegíti a gyenge jelek stabil vételét és további feldolgozását. A mérések megfeleltek az elvárásoknak, az erősítés stabilnak bizonyult, és az eltérések elhanyagolhatóak voltak.

---

## 6. Elemzés és Értékelés

Az eredmények elemzése alapján a Johansson 6700 Profiler stabil és megbízható teljesítményt nyújtott a mérések során. Az eszköz hatékonyan erősítette a jelerősséget a kiválasztott frekvenciasávokban, elősegítve a gyenge RF jelek minőségének javítását. A kalibrációs beállításai pontosnak bizonyultak, és az eltérések minimálisak voltak. Városi környezetben jól működött, bár az alacsonyabb frekvenciákon némi interferencia jelentkezett. Az eszköz sikeresen áthelyezte a csatornákat és stabil jelet biztosított.

---

## 7. Hibák és Korlátozások

A mérés során az alábbi problémák kerülhetnek felmerülőbe:

- **Környezeti tényezők**: Az épületek közelsége, valamint a laborban található egyéb elektromos eszközök interferenciát generáltak, különösen az alacsonyabb frekvenciatartományban.
- **Antenna elhelyezése**: A viszonylag alacsony antennamagasság (1,5 méter) miatt a vétel nem volt optimális. Az antennát magasabb helyre kellene telepíteni, hogy javítsuk a jelerősséget és csökkentsük a zavarokat.
- **Interferencia**: A vétel nem volt megfelelő a viszonylag alacsony, 1,5 méteres antennamagasság miatt. Az antenna magasabb helyre történő telepítése javíthatná a jelerősséget és mérsékelhetné a zavarokat.

---

## 8. Következtetések és Javaslatok

- A mérés sikeresen demonstrálta a Johansson 6700 Profiler képességeit. A kapott eredmények azt mutatják, hogy a készülék megbízhatóan teljesíti a kívánt erősítési feladatokat.
- Javasolt további méréseket végezni eltérő környezeti feltételek mellett, hogy megismerjük az esetleges befolyásoló tényezőket.
- Fontos lenne a méréseket nagyobb spektrális sávban is elvégezni, hogy felmérjük az eszköz széleskörű alkalmazhatóságát.
- A mérések eredményei összességében megfelelnek az elvárásoknak.
- A rendszer zavartalanul működött a rövid UTP kábeles rendszeren keresztül is.
- A mérés célja teljesült, de további finomítások szükségesek a vétel minőségének javítása érdekében.

---

## 9. További mérési javaslatok a jobb vétel és minőség érdekében 

- **Antenna elhelyezése**: Javasolt az antennát magasabb pozícióba telepíteni a jobb jelerősség érdekében, különösen az alacsonyabb frekvenciák esetében.
- **Környezeti hatások minimalizálása**: További mérések során érdemes lenne tesztelni, hogyan befolyásolják a különböző környezeti feltételek (pl. időjárás, építészeti akadályok) a vételt.
- **További tesztek**: Érdemes más antennatípusokat is tesztelni és összehasonlítani a jelenlegi Iskra P-20 antennával.

---

## 10. Felhasznált Források

1. **Johansson 6700 felhasználói kézikönyv** - A gyártó által biztosított dokumentáció az eszköz beállításairól.
2. **Iskra P-20 antenna műszaki leírás** - Az antenna specifikációi és teljesítménye különböző frekvenciákon.
3. **Műholdas és földi adóállomások jellemzői** - Általános útmutató a városi adótornyok és sugárzott frekvenciák jellemzőiről.

---

## 11. Magyarázatok és Lábtanulmányok

- **SNR (Signal-to-Noise Ratio)**: A jel és a zaj viszonya decibelben (dB). Minél magasabb az érték, annál tisztább a jel. Általában 30 dB feletti SNR szükséges a stabil vételhez.
- **QPSK**: Kvadratúra fáziseltolásos moduláció (Quadrature Phase Shift Keying), amely hatékony adatátviteli technika, gyakran használják digitális televízióadásoknál.

---

## 12. Jelerősség diagram


---

## 13. Záró Összegzés

A viszonylag alacsony, 1,5 méteres antennamagasság következtében a vétel nem volt kielégítő. Az antenna magasabbra helyezése elősegítené a jelerősség növelését és a zavarok csökkentését.

A mérés legfontosabb tanulságai:
- Az antennák helyes pozicionálása kulcsfontosságú a vétel optimalizálása érdekében.
- A környezeti hatások jelentős szerepet játszanak a jelerősség és minőség tekintetében.
- A Johansson 6700 egyszerűen konfigurálható, és a mért eredmények alapján hatékonyan működik.

Az összesített mérések és következtetések alapján a Johansson 6700 Profiler hatékony eszköz a városi antennarendszerek kezelésére, azonban a vétel optimalizálása érdekében további mérések elvégzése javasolt.

---

## 14. Mért Képek


**Aláírás:** Gál Levente Máté

**Dátum:** 2024. 11. 27.
