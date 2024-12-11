# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Gál Levente Máté
**A mérés tárgya:** Antennák teljesítményének és jelminőségének összehasonlítása  
**A mérés száma:** 6. mérés  
**A mérés dátuma:** 2024. 12. 04.  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1  
**Helyszín:** V3 Labor  

---

## 1. Mérés célja
A mérés célja három különböző típusú antenna, az **Iskra P20**, az **ISKRA P2845** és az **IKUSI FLASHD C48** teljesítményének összehasonlítása, valamint a jelszint és jelminőség (MER - Modulation Error Ratio) vizsgálata három különböző frekvencián (746, 762).

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Programozható antennaerősítő-szűrő  | Johansson   | 6700          |
| Antenna                             | Iskra       | P20, P2845    |
| Antenna                             | IKUSI       | FLASHD C48    |
| Spectrum Analizátor                 | Metek       | HDD           |

---

### 3. **Mérési helyszín és környezet**
- **Antenna magassága**: 2 m
- **Környezet jellemzői**: V3 labor

---

## 4. Antennák teljesítménye különböző frekvenciákon

| Frekvencia (MHz) | Antenna          | Jelszint (dBm) | MER (dB) | Bitsebesség (Mbps) |
| ---------------- | ---------------- | -------------- | -------- | ------------------ |
| **762 MHz**      | Iskra P20        | -57.7          | 24.9     | 12.2 – 12.6        |
|                  | ISKRA P2845      | -58.8          | 26.3     | 13.6 – 13.6        |
|                  | IKUSI FLASHD C48 | -51.6          | 27.0     | 12.4 – 12.2        |
| **746 MHz**      | Iskra P20        | -59.2          | 25.6     | 14.2 – 14.5        |
|                  | ISKRA P2845      | -56.9          | 33.2     | 14.3 – 14.8        |
|                  | IKUSI FLASHD C48 | -51.3          | 31.9     | 12.2 – 12.8        |

---

## 5. Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:
- **Jelszint (dBm)**: Az ISKRA P2845 és az IKUSI FLASHD C48 antennák jellemzően jobb jelszintet biztosítottak, különösen a 746 MHz-es frekvencián. Ezzel szemben az ISKRA P20 antenna mindhárom frekvencián magasabb jelszintet ért el.
- **MER (Modulation Error Ratio)**: A MER értékek alapján az ISKRA P20 antenna bizonyult a legjobbnak, különösen a középső, 570 MHz-es frekvencián, ahol a MER értéke 25,6 dB volt. Az IKUSI P2845 antenna szintén magas MER értékeket produkált, míg az ISKRA P20 némileg gyengébben teljesített.
- **Bitsebesség**: A bitsebesség szintén magasabb volt az ISKRA P2845 és az IKUSI FLASHD C48 esetében, míg az ISKRA P20 antennánál kicsit alacsonyabb értékeket tapasztaltunk. A legmagasabb bitsebességet 746 MHz-en az ISKRA P2845 érte el (14.8 Mbps).

---

## 6. Konklúzió
A mérések alapján az ISKRA P20 antenna érte el a legjobb eredményeket mind jelszintben, mind MER-ben és bitsebességben. Az ISKRA P2845 szintén kedvezően teljesített, míg az IKUSI FLASHD C48 gyengébb értékeket produkált. Az antennák közötti eltérések különösen a 746 MHz-es frekvencián váltak szembetűnővé, ahol a legnagyobb teljesítménykülönbség volt megfigyelhető.

---

## 7. Mérési nehézségek és eltérések
A mérések során a laboratóriumi környezetben előforduló zajok és interferenciák hatással lehettek a jelszintek pontos mérésére. Továbbá, az antennák pozíciójának változásai is kisebb eltéréseket okozhattak a mérési eredményekben.

---

## 8. Grafikus ábrázolás
A jelszint és MER értékek vizuális ábrázolását az alábbi diagramok mutatják be:


---

## 9. Javaslatok
Az **ISKRA P2845** antenna javasolt elsődleges használatra, mivel minden frekvencián magasabb jelszintet és jobb jelminőséget biztosított. Amennyiben költséghatékonyabb megoldás szükséges, az **IKUSI FLASHD C48** is megfelelő választás lehet. Az **Iskra P20** csak alacsonyabb frekvenciákon javasolt, ahol még kielégítő teljesítményt nyújt.

---

## 10. P-20 Képek:
<details>
<summary>Kattins a részletekért</summary>

**474Mhz Mért Képek:**

<img src="(https://github.com/leventegal/Tavkozeles/blob/main/Antenna%20teljes%C3%ADtm%C3%A9ny%20%C3%A9s%20jelszint/images/its_snapshot_0001.bmp)">
---

**570MHz Mért Képek**

<img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">
---

</details>

<br>

## 11. P-2845 Képek:
<details>

<summary>Kattins a részletekért</summary>

**474Mhz Mért Képek:**

<img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">

---

**570MHz Mért Képek**

<img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">

---

</details>

<br>

## 12. FlashHD C-48 Képek:
<details>
<summary>Kattins a részletekért</summary>

**474Mhz Mért Képek:**

<img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">
---

**570MHz Mért Képek**

<img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">
---

</details>


<br>

**Aláírás:** Gál Levente Máté

**Dátum:** 2024. 12. 04.
