# Autókereskedés Nyilvántartó és Elemző Rendszer

**Projektfeladat a 12.D osztály számára**  
**Tantárgyak:** Asztali alkalmazások, Adatbázis-kezelés és IKT projekt  
**Témavezetők:** Dobrocsi Róbertné és Szemán Zita  



## A csoport tagjai
* **Csajkás Olivér**
* **Kerner Mátyás**
* **Bodnár Attila**



## Projekt leírása
A projekt célja egy autókereskedés gépjárműparkját kezelő konzolos C# alkalmazás és a hozzá tartozó egytáblás MySQL/SQLite adatbázis megvalósítása. 
A program egy strukturált `.txt` állományból (`adatok.txt`) olvassa be az autók adatait, majd különböző programozási tételeket (összegzés, maximumkeresés, megszámlálás, kiválogatás) alkalmazva végzi el az elemzéseket.



## Alkalmazott technológiák
* **Fejlesztői környezet:** Visual Studio / Visual Studio Code
* **Nyelv:** C# (.NET)
* **Adatbázis:** MySQL / SQLite
* **Projektmenedzsment & Dokumentáció:** Trello, Microsoft Word



## Repository tartalma
* `Autokereskedes.zip` - A teljes C# konzolos alkalmazás Visual Studio projektje tömörítve.
* `Autónyilvántartó projekt dokumentáció.docx` - A projekt részletes Word dokumentációja (UML diagram, képernyőképek, irodalomjegyzék).
* `adatok.txt` - A gépjárművek adatait tartalmazó pontosvesszővel elválasztott szöveges állomány.
* `projektmunka.txt` - Az adatbázis létrehozásához, az adatok feltöltéséhez és a lekérdezésekhez használt SQL szkript.



## Adatbázis szerkezete (`Autok` tábla)
* **Rendszam** (VARCHAR) - *Elsődleges kulcs (Primary Key)*
* **Marka** (VARCHAR)
* **Modell** (VARCHAR)
* **GyartasiEv** (INT)
* **KmAllas** (INT)
* **Ar** (INT)
* **Uzemanyag** (VARCHAR)

## Projektmenedzsment (Trello)
A projekt feladatainak felosztását és nyomon követését Trello táblán végeztük:
*  **Trello Tábla Link:** https://trello.com/invite/b/6acde5f5fe315939eb376a2e/ATTI26908e592bbfea3d00e2c8d504b6ad4cB0189C9E/projekt
