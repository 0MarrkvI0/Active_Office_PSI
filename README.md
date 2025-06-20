# ActiveOffice – PSI FIIT STU LS 2024/25

**Autori:**  
Šimon Ištván  
Martin Kvietok  
Ľubomír Ligocký  
Monika Tomová  
**Predmet:** Principles of Software Engineering  
**Fakulta:** Fakulta informatiky a informačných technológií, STU Bratislava

---

## Popis projektu

ActiveOffice je návrh inteligentného systému pre podporu zdravého životného štýlu v kanceláriách. Spája ergonomický smart nábytok, senzory a softvérové rozhranie do jednotného systému pre zvýšenie pohody a produktivity zamestnancov. 

---

## Ciele projektu

- Znížiť sťažnosti na bolesti chrbtice o 80 % do 6 mesiacov  
- Zvýšiť psychickú pohodu zamestnancov o 31 % do 3 mesiacov  
- Dosiahnuť 70 % pracovného času v zdravej polohe  
- Podporovať hydratáciu a pravidelný pohyb cez inteligentné pripomienky

---

## Funkcionalita systému

### Smart nábytok
- **Inteligentná stolička** – monitorovanie držania tela, haptická spätná väzba
- **Výškovo nastaviteľný stôl** – podpora Pomodoro režimu (automatické prepínanie medzi sedením/státím)

### Inteligentné prostredie
- **Svetelná optimalizácia** – adaptívne osvetlenie, redukcia modrého svetla
- **Monitoring pitného režimu** – váženie fľaše, pripomienky na doplnenie tekutín
- **Ochrana zraku** – pripomienky na zmenu pohľadu podľa 20-20-20 pravidla

### Softvérová aplikácia
- Monitoring v reálnom čase
- Personalizované odporúčania
- Integrácia so smart zariadeniami (Garmin, Fitbit, Apple Health)
- Export štatistík do PDF/CSV

---

## Architektúra

### Doménový model
- Triedy ako `Účet`, `Štatistiky`, `Záznam`, `Udalosť`, `Pripomienka`, `Zariadenie`, `Senzor` a `Časovač`
- Podpora pre personalizované aj anonymné dáta

### Procesy
- Automatické pripomienky a sledovanie:
  - **P01:** Správa osvetlenia
  - **P02:** Pitný režim
  - **P03:** Telesná poloha
  - **P04:** Pomodoro režim
  - **P05:** Sledovanie pohľadu

---

## Požiadavky

### Biznisové požiadavky
- Zníženie bolesti, podpora zdravia, zvýšenie efektivity

### Používateľské požiadavky
- Pomodoro režim, analytika aktivity, pripomienky, reporty, gamifikácia

### Funkčné požiadavky
- Automatické osvetlenie, úprava stola, inteligentné pripomienky, REST API

### Ne-funkčné požiadavky
- GDPR, šifrovanie (AES-256), škálovateľnosť, dostupnosť 99.9 %, multiplatformová podpora

---

## Prípady použitia

- UC01: Prezeraj štatistiky  
- UC02: Nastav preferencie  
- UC03: Odpovedaj na pripomienku

---

## UI Návrhy

- **Štatistiky:** prehľad dennej aktivity  
- **Preferencie:** nastavenie režimov a pripomienok  
- **Pripomienky:** interakcia v reálnom čase  
