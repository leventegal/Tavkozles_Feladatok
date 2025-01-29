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

<img src="https://github.com/user-attachments/assets/3415919b-850d-4f92-bef9-1d0ceaee6b54" alt="nray60" style="width:250px;"/>

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
