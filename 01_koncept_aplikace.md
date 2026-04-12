# Koncept projektu

Tento dokument popisuje laboratorní sestavu, základní koncepty a rozdělení uživatelského rozhraní. Aplikace slouží k psychofyzikálním měřením a kalibraci monitorů v laboratorním prostředí.

## Laboratorní sestava

Sestava obsahuje laboratorní PC, primární monitor (60 Hz) a externí monitor (240 Hz). K systému jsou připojeny externí měřicí přístroje (kamera, fotodioda). Celá sestava je řízena pomocí aplikace.

<p align="center">
  <img src="screenshots/experiment_sestava.png" alt="Experimentální sestava">
  <br>
  <em>Obrázek 1: Experimentální sestava.</em>
</p>

---

## Uživatelské rozhraní (UI)

Vidíte hlavní okno aplikace rozdělené na tři klíčové části:

- **Část A:** Zde inicializujte systém a nastavte globální parametry.
- **Část B:** Zde konfigurujte měření a spouštějte testovací podněty.
- **Část C:** Zde sledujte výpis logů a průběh probíhajícího měření.

<p align="center">
  <img src="screenshots/koncept.png" alt="Celkový koncept UI">
  <br>
  <em>Obrázek 2: Hlavní okno aplikace (části A, B a C).</em>
</p>

---

## Hlavní moduly

### Modul pro měření
Tento modul slouží k ovládání hardwaru (kamera, fotodioda) a sběru dat pro tvorbu LUT (Look-Up Table) tabulek.

<p align="center">
  <img src="screenshots/measure.png" alt="Rozhraní měření">
  <br>
  <em>Obrázek 3: Diagram zapojení pro měření.</em>
</p>

### Modul pro stimuly
Tento modul slouží ke konfiguraci a vykreslování vizuálních podnětů na externím monitoru.

<p align="center">
  <img src="screenshots/psych.png" alt="Rozhraní stimulů">
  <br>
  <em>Obrázek 4: Schéma zapojení pro spouštění stimulů.</em>
</p>

---
[Zpět na README](README.md)