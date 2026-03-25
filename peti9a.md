# Tanulmányi összefoglaló – 9.A évfolyam

Ez a dokumentum az idei tanév főbb témaköreit és a megszerzett ismereteket foglalja össze rendszerezett formában.

---

## 1. Projektmenedzsment és agilis módszertanok

A modern szoftverfejlesztés nem csupán kódolásból, hanem szigorú folyamatok menedzseléséből is áll. Az alábbi keretrendszereket sajátítottuk el:

### **Scrum**
A legnépszerűbb agilis keretrendszer, amely rövid ciklusokra (**sprintekre**) bontja a munkát.
* **Szerepkörök:** Scrum Master, Product Owner, Fejlesztői csapat.
* **Események:** Daily Scrum (napi állomány), Sprint Planning (tervezés), Sprint Review (bemutató).

### **Kanban**
A munka vizualizálására fókuszál. Egy Kanban táblán követjük a feladatok útját (pl. **To Do** $\rightarrow$ **In Progress** $\rightarrow$ **Done**). Fő célja a folyamatos munkaáramlás biztosítása és a szűk keresztmetszetek kiiktatása.

### **Extreme Programming (XP)**
Elsősorban a kód minőségére és a technikai kiválóságra helyezi a hangsúlyt:
* **Páros programozás:** Két fejlesztő dolgozik egy gépen (egyik ír, a másik ellenőriz).
* **Tesztvezérelt fejlesztés (TDD):** Előbb írjuk meg a tesztet, és csak utána a kódot, ami átmegy rajta.

### **Crystal Method**
Egy rugalmas módszercsalád (pl. Crystal Clear, Crystal Orange), amely a csapat létszámától és a projekt kritikus jellegétől függően változtatja a szigorúságát.

---

## 2. Python programozás

A Python egy magas szintű, könnyen olvasható nyelv. Az alábbi alapvető építőelemekkel ismerkedtünk meg:

* **Változók:** Adatok tárolására szolgáló névvel ellátott helyek (pl. `nev = "Béla"`, `kor = 15`).
* **Adattípusok:**
    * `int`: Egész számok.
    * `float`: Lebegőpontos (tizedes) számok.
    * `str`: Karakterláncok (szövegek).
* **Függvények:** Alapvető műveletek, mint a `print()` (kiíratás) vagy az `input()` (adatbekérés).

---

## 3. Számítógép hardver

A szoftver futtatásához elengedhetetlen a fizikai alkatrészek ismerete:

| Alkatrész | Funkció |
| :--- | :--- |
| **Processzor (CPU)** | A gép "agya", a számítási műveletek végrehajtója. |
| **Memória (RAM)** | Gyors, ideiglenes tároló a futó programok adatai számára. |
| **Alaplap** | A központi egység, amely fizikailag és elektronikusan összeköti az alkatrészeket. |
| **Háttértár (SSD/HDD)** | Az adatok hosszú távú, tartós tárolására szolgál. |

---

## 4. Matematika

### **Halmazok**
A halmaz elemek gyűjteménye, ahol a sorrend nem számít, és minden elem egyedi.

**Műveletek:**
* **Unió ($A \cup B$):** Azon elemek, amik legalább az egyik halmazban benne vannak.
* **Metszet ($A \cap B$):** Azon elemek, amik mindkét halmazban benne vannak.
* **Különbség ($A \setminus B$):** Azon elemek, amik $A$-ban benne vannak, de $B$-ben nem.

### **Egyenletek és szöveges feladatok**
A matematikai modellezés alapja a szöveges problémák egyenletté alakítása.

**Példa egyenletrendszerre:**
$$\begin{cases} 
3x + 4y = 14 \\ 
5x - 2y = 10 
\end{cases}$$

**Példa egyismeretlenes egyenletre:**
A példád alapján nézzük meg ezt a feladatot:
$$15x \cdot (8-9) + 12 = 3x - 9$$
$$-15x + 12 = 3x - 9$$
$$21 = 18x \implies x = \frac{21}{18} = \frac{7}{6}$$