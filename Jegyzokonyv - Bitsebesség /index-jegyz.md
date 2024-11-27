
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

### Mért képek:

<details>
    <summary>Grafikus ábrázolás</summary>
    (https://github.com/user-attachments/assets/a11ae35c-6dd2-4b7b-90b2-abf48ac75a9b)

</details>

---

## 5. Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:
- **Jelszint (dBm)**:
- **MER (Modulation Error Ratio)**: 
- **Bitsebesség**: 
---

## 6. Konklúzió

 - A mérések során kezünkbe került a **Johansson 8202 DVB-T modulátor**, és pontos adatokat kaptunk a bitsebességről és jelminőségről. A mérési eredmények alapján a modulátor megfelelő teljesítményt nyújtott, és a jelszint, bitsebesség, valamint a MER értékek a várakozásoknak megfelelően alakultak.

 - Azonnal láthatóvá válik, hogy a TV1 Pongo magasabb bitsebességgel és erősebb teljesítménnyel dolgozik, míg a TV2 Erős jobb MER értékkel bír.

- A mérések alapján megfigyelhető, hogy a bitsebesség növekedésével a jelminőség fokozatosan csökkent. A legmagasabb jelminőséget alacsony bitsebességnél értük el, ahol a zaj mértéke még elfogadható szinten maradt. Az eredmények alapján javasolható, hogy nagyobb stabilitás érdekében a rendszer optimális működése alacsonyabb bitsebességeken biztosított.

---

## 7. Mérési nehézségek és eltérések


---
