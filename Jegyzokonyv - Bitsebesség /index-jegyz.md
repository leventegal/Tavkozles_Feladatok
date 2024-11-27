
# MÉRÉSI JEGYZŐKÖNYV

**Kandó Kálmán Informatikai Technikum**  
**Miskolc Palóczy u. 3.**

**A mérést végző neve:** Gál Levente Máté  
**A mérés tárgya:** A különböző bitsebesség milyen hatással van a jelminőségre.  
**A mérés száma:** 5. mérés  
**A mérés dátuma:** 2024. 11. 13.  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1 
**Helyszín:** V3 Labor  

---

## 1. Mérés célja
A hallgatók megismerjék a Johansson 8202 DVB-T modulátor további képességeit, különös tekintettel a többcsatornás jel generálásra. A mérés során a résztvevők két programot állítanak be és mérik a jel minőségét különböző bitsebességek mellett.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Programozható antennaerősítő-szűrő  | Johansson   | 8202          |
| Programozható antennaerősítő-szűrő  | Johansson   | 8202          |
| Spectrum Analizátor                 | Metek       | HDD           |

---

### 3. Előkészületek
A mérés menete során a Johansson 8202 DVB-T modulátorokat összekötöttük, majd az egyik modulátor **RF-out** pontjára csatlakoztattuk a spektrumanalizátort. Az eszközök megfelelő beállítását követően megkezdtük a mérést.

---

## 4. Különböző bitsebességen mért adatok.

| Frekvencia (MHz) | Johansson        | Jelszint (dBm) | MER (dB) | Bitsebesség (Mbps) |
| ---------------- | ---------------- | -------------- | -------- | ------------------ |
| **674 MHz**      | Tv1              | -30.2          | 37.0     | 10.8 – 14.5        |
| **682 MHz**      | Tv2              | -32.1          | 33.2     | 7.2 – 8.3          |
| **682 MHz**      | Tv2              | -32.5          | 40.0     | 15.2 – 18.4        |

---

### 5. Mérési folyamat apránként
1. A mérőeszközök megfelelően lettek összekapcsolva és beállítva a mérés előtt.   
2. A Johansson 8202 DVB-T modulátor különböző bitsebességeken tesztelve lett a jelminőség mérve.   
3. A jelanalizátorral minden beállításhoz tartozó jelminőség mérését elvégeztük.   

### 6. Mért képek:

<details>
    <summary>Grafikus ábrázolás</summary>
    <img src="https://raw.githubusercontent.com/leventegal/Tavkozeles/refs/heads/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/d553cce9-92d5-4cbb-8faa-159b6424967b.jpg">
</details>

<details>
    <summary>Spektrum Analizátor Kép: TV1</summary>
    <img src="https://github.com/leventegal/Tavkozeles/blob/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/its_snapshot_0025.bmp">
</details>

<details>
    <summary>Spektrum Analizátor Kép: TV1</summary>
    <img src="https://github.com/leventegal/Tavkozeles/blob/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/its_snapshot_0026.bmp">
    
</details>

<details>
    <summary>Spektrum Analizátor Kép: TV2</summary>
    <img src="https://github.com/leventegal/Tavkozeles/blob/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/its_snapshot_0027.bmp">
</details>

<details>
    <summary>Spektrum Analizátor Kép: TV2</summary>
    <img src="https://github.com/leventegal/Tavkozeles/blob/main/Jegyzokonyv%20-%20Bitsebess%C3%A9g%20/images/its_snapshot_0028.bmp">
</details>

---

## 7. Konklúzió

 - A mérések során kezünkbe került a **Johansson 8202 DVB-T modulátor**, és pontos adatokat kaptunk a bitsebességről és jelminőségről. A mérési eredmények alapján a modulátor megfelelő teljesítményt nyújtott, a jelszint, bitsebesség, valamint a MER értékek a prímán alakultak.

 - Azonnal láthatóvá válik, hogy a TV1 magasabb bitsebességgel és erősebb teljesítménnyel dolgozik, míg a TV2 jobb MER értékkel rendelkezik.

- A mérések alapján megfigyelhető, hogy a bitsebesség növekedésével a jelminőség lassacskán csökken. A legmagasabb jelminőséget alacsonyabb bitsebességnél értük el, ahol a zaj mértéke még elfogadható szinten maradt.

---

#### 8. További mérések javaslata:
1. **Különfajta bitsebesség**: Vizsgáljuk meg, hogy különfajta bitsebességek hogyan azonosulnak a jelszintel.
2. **Hőmérséklet és környezeti feltételek hatása**: Érdemes a méréseket különböző környezeti feltételek mellett (pl. hőmérséklet-ingadozás) is elvégezni, hogy megismerjük, hogyan változik a jelminőség extrém körülmények között.

---

### 9. Összegzés

A jegyzőkönyvben rögzített mérés célja a **Johansson 8202 DVB-T** modulátor által előállított jelminőség vizsgálata volt különböző bitsebességek mellett. Az eredmények rámutattak, hogy a nagyobb bitsebességek negatívan befolyásolják a jelminőséget, amit a zajszint (SNR) csökkenése is igazolt. A vizsgált bitsebességek közül a 10 Mbps körüli érték nyújtotta a legjobb kompromisszumot a jelminőség és a sebesség között, így elfogadható teljesítményt eredményezett.

További vizsgálatok, például különböző antennák tesztelése, zajforrások hatásának elemzése, valamint eltérő környezeti feltételek figyelembevétele révén még pontosabban feltárható a bitsebesség és a jelminőség közötti összefüggés. A jegyzőkönyv összességében értékes betekintést nyújt a DVB-T technológia alapvető működésébe, és fontos alapot szolgáltat az optimális beállítások megtalálásának folyamatához.


---


**Aláírás:** Gál Levente Máté

**Dátum:** 2024. 11. 13.
