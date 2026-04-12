# Koncept projektu

Tento dokument popisuje laboratorní sestavu, základní koncepty a rozdělení uživatelského rozhraní. Aplikace slouží k psychofyzikálním měřením a kalibraci monitorů v laboratorním prostředí.

## Laboratorní sestava

Sestava obsahuje laboratorní PC, primární monitor (60 Hz) a externí monitor (240 Hz). K systému jsou připojeny externí měřicí přístroje (kamera, fotodioda). Celá sestava je řízena pomocí aplikace.

![Experimentální sestava](screenshots/experiment_sestava.png)
*Obrázek 1: Experimentální sestava.*

---

## Uživatelské rozhraní (UI)

Vidíte hlavní okno aplikace rozdělené na tři klíčové části:

- **Část A:** Zde inicializujte systém a nastavte globální parametry.
- **Část B:** Zde konfigurujte měření a spouštějte testovací podněty.
- **Část C:** Zde sledujte výpis logů a průběh probíhajícího měření.

![Celkový koncept UI](screenshots/koncept.png)
*Obrázek 2: Hlavní okno aplikace (části A, B a C).*

---

## Hlavní moduly

### Modul pro měření
Tento modul slouží k ovládání hardwaru (kamera, fotodioda) a sběru dat pro tvorbu LUT (Look-Up Table) tabulek.

![Rozhraní měření](screenshots/measure.png)
*Obrázek 3: Rozhraní pro konfiguraci měření.*

### Modul pro stimuly
Tento modul slouží ke konfiguraci a vykreslování vizuálních podnětů na externím monitoru.

![Rozhraní stimulů](screenshots/psych.png)
*Obrázek 4: Schema zapojení pro spouštění stimulů.*

---
[Zpět na README](README.md)