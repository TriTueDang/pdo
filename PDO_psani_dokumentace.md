# NTI/PDO – Psaní dokumentace

Produkt je výstup bakalářské práce, což je rozšíření stávajícího programu v laboratornim počítači TUL. Program je napsán v jazyce **C# (.NET Framework)** s využitím technologie Windows Forms.

---

## 1. Produkt

Produkt je součástí většího systému na TUL. Moje část se zaměřuje na:

- **Kalibraci monitoru:** Tvorba LUT tabulek na základě reálného měření jasu.
- **Generování stimulů:** Vykreslování vizuálních podnětů pro vizuální experimenty.
- **Uživatelské rozhraní:** Vytvoření intuitivního prostředí ve Windows Forms pro správu těchto úloh.

---

## Cílové skupiny

Dokumentace je určena pro odborníky a studenty TUL, kteří budou systém využívat nebo dále rozvíjet.

### Kalibrační technici
*Zaměření na technickou přípravu a údržbu systému.*
- Kalibrace laboratorních monitorů.
- Měření jasů (kamerou) a napětí (fotodiodou) pro tvorbu LUT tabulek.
- [Přejít k manuálu měření](02_kalibrace_a_mereni.md)

### Experimentální pracovníci
*Zaměření na provádění vědeckých měření a sběr dat.*
- Spouštění vizuálních stimulů (Sinus, Obdélník).
- Konfigurace parametrů jako frekvence a jas.
- [Přejít k manuálu stimulů](03_spousteni_stimulu.md)

---

## 3. Typy a struktura dokumentace

Dokumentace je pro lepší přehlednost rozdělena do tří specializovaných souborů, které jsou propojeny odkazy:

### [3.1 Koncept](01_koncept_aplikace.md)

- **Rozsah:** Popis celkové architektury aplikace, rozložení uživatelského rozhraní a shrnutí hardwarové sestavy.
- **Účel:** Slouží k pochopení fungování aplikace.

### [3.2 Návod pro měření LUT tabulek](02_kalibrace_a_mereni.md)

- **Rozsah:** Kroky pro kalibraci monitoru, provádění měření jasu (luminance) pomocí kamery, měření napětí pomocí fotodiody.
- **Účel:** Poskytnout návod pro kalibraci laboratorního monitoru.

### [3.3 Návod pro spouštění stimulů](03_spousteni_stimulu.md)

- **Rozsah:** Popis dostupných podnětů (Sinus, Rectangular, Contrast), seznam jejich parametrů a postup jejich spuštění.
- **Účel:** Manuál pro experimentátory definující parametry vizuálních testů.

---

## Shrnutí

Cílem této dokumentace je zajistit hladké předání technických znalostí a umožnit další akademické využití projektu.

- Strukturovaný text
- Obrázky z reálného prostředí aplikace s popisky
- Technické parametry a postupy

---

