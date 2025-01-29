# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Gál Levente Máté  
**A mérés tárgya:** Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése  
**A mérés száma:** Mikro mérés  
**A mérés dátuma:** 2025. 01. 29.  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1  
**Helyszín:** V3 Labor  

---

## Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése

---

## 1. Hálózat tesztelés lényege: A tesztelés lényege, hogy a **Mikrotik LHG18 LTE antennába** bele helyezünk egy **SIM** kártyán, azon azntánnán keresztül internetet hosszabítunk meg egy routeren keresztül a **Mikrotik nRay 60GHz mikrohullámú antennákra**. Majd egy laptoppal teszteljük hogy a jel forrás hosszabbítása sikeres.

## 2. Alkalmazott eszközök

- **Mikrotik LHG18 LTE antenna** (alapértelmezett IP: `192.168.188.1`)

<img src="https://github.com/user-attachments/assets/3415919b-850d-4f92-bef9-1d0ceaee6b54" alt="lhg18lte" style="width:250px;"/>

- **Mikrotik nRay 60GHz mikrohullámú antenna szett** (eszközök IP-címei: `192.168.88.2` és `192.168.88.3`)   

<img src="https://github.com/user-attachments/assets/a18697ea-6d66-4376-b491-c55dc37fadfb" alt="nray60" style="width:250px;"/>  

- **D-LINK vagy TP-LINK vagy ASUS SOHO router** (AP módban)

<img src="https://github.com/user-attachments/assets/9f853286-1b82-49cf-9312-1420ff7472b2" alt="asus" style="width:250px;"/>  

- **HP switch** (opcionálisan felhasználható)
- **Laptop vagy PC** a konfigurációkhoz és mérésekhez
- **iperf szoftver** a sávszélesség mérésekhez

**Laptop bejelentkezési adatok:**  
- Felhasználónév: `V3-XX\admin` (XX - az aktuális laptop száma)  
- Jelszó: `mzKvsd`  

---

## 3. Eszközök előkésztése és telepítése

### 3.1 Előkészítés és tervezés

### 3.2 Eszközök gyári beállításainak visszaállítása (Factory Reset)

- A vizsga kezdetén minden eszköz gyári alaphelyzetbe állítása kötelező. Az alábbi lépések végrehajtása szükséges:

### 3.3 Mikrotik LHG18 LTE antenna resetelése:

1. Az eszközt áramtalanítani kell.
2. A reset gombot lenyomva kell tartani.
3. A tápellátás visszacsatlakoztatása mellett továbbra is nyomva kell tartani a reset gombot.
4. A status LED villogásának megkezdésekor (kb. 5 másodperc) a reset gombot fel kell engedni.
5. Az eszköz ezzel visszaáll a gyári beállításokra.

### 3.4 Mikrotik nRay 60GHz antennák resetelése:

1. A fent leírt resetelési eljárást kell alkalmazni mindkét antennán (192.168.88.2 és 192.168.88.3 IP-címekkel).

### 3.5 SOHO router (D-LINK, TP-LINK vagy ASUS) resetelése:

1. A reset gomb helyének beazonosítása után az eszközt áramtalanítani kell.
2. Rövid várakozás után a reset gombot meg kell nyomni és lenyomva tartani.
3. Az eszköz visszakapcsolása után a reset gombot legalább 10 másodpercig lenyomva kell tartani, amíg a gyári visszaállítás befejeződik.

# 3.2.1 Hálózati topológia tervezése

A hálózat tervezése során egy diagramot kell készíteni, amely tartalmazza az összes eszközt és azok kapcsolatait. Ehhez javasolt a Draw.io használata.

### 3.2.2 IP-cím kiosztás:

1. Mikrotik LHG18 LTE: 192.168.88.1
2. Mikrotik nRay 60GHz Master: 192.168.88.2
3. Mikrotik nRay 60GHz Slave: 192.168.88.3
4. Router (AP mód): 192.168.88.4
5. Switch (ha szükséges): 192.168.88.254
6. Kliens laptop: 192.168.88.100-250 (DHCP-ből)

A hálózat kialakítása során kiemelten figyelni kell az IP-cím ütközések elkerülésére, valamint az alhálózati maszk helyes beállítására (255.255.255.0).


<img src="https://github.com/user-attachments/assets/551bf396-1a37-4d77-9239-2ffc241c70e6" alt="kep"/>  

## 4. Telepítési adatok

|     Készülékek     |       RSSI       |   Távolság   |     |         |
| ------------------ | ---------------- | ------------ | --- | ------- |
| **nRAy 1**         | -49dBm           |    2,18 m    |     |         |
| **nRAy 2**         | -49dBm           |    2,18 m    |     |         |
| **LHG_LTE18**      | -51dBm           |  ----------  |     |         |
