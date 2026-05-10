# Návod pro spouštění stimulů

Aplikace umožňuje generovat vizuální stimuly pro psychofyzikální experimenty, jako je testování viditelnosti blikání (flicker) nebo kontrastní citlivosti.

## Postup spuštění stimulu

1. Klikněte na záložku **Dang BP**.

<p align="center">
  <img src="screenshots/zalozkaBp.png" alt="Záložka Dang BP">
  <br>
  <em>Obrázek 1: Záložka pro bakalářskou práci.</em>
</p>

> [!IMPORTANT]
> **Příprava před spuštěním:**
> - Zapněte externí monitor.
> - Klikněte na tlačítka pro inicializaci **MATLABu** v části A a **Psychtoolboxu** v části B.
> - Změřte a vytvořte **LUT tabulky** pro připojený monitor. Viz [Kalibrace a měření](02_kalibrace_a_mereni.md).

> [!TIP]
> Pokud záložku v horní liště nevidíte, klikněte 2x na šipku vpravo u přepínače záložek.

2. Inicializujte Psychtoolbox. Vyberte typ stimulu a nastavte jeho parametry. Obrázek 2 ukazuje tyto kroky.
3. Stiskněte tlačítko **"Run"** u typu stimulu, který jste vybrali.
4. Podle parametrů muže stimul na externím monitoru vypadat například jako Obrázek 3:

<p align="center">
  <img src="screenshots/postup_spusteni.png" alt="Konfigurace a spuštění stimulu">
  <br>
  <em>Obrázek 2: Postup spuštění stimulu.</em>
</p>


<p align="center">
  <img src="screenshots/2circles.png" alt="Sinusový stimul">
  <br>
  <em>Obrázek 3: Sinusový stimul - náhled na monitoru.</em>
</p>

---

## Typy stimulů a parametry

### 1. Sinusový stimul (Sine Wave)
Slouží ke studiu viditelnosti flikru. Jas se mění plynule podle sinusové křivky.

**Nastavte parametry:**
- **Frekvence [Hz]:** Rychlost změn jasu.
- **Amplituda / Kontrast [%]:** Rozsah mezi maximálním a minimálním jasem.
- **Minimální jas [cd/m²]:** Spodní úroveň jasu.
- **Čas [ms]:** Doba trvání stimulu.
- **Segment & Mask:** Oblast monitoru a tvar stimulu.

<p align="center">
  <img src="screenshots/sine.png" alt="Sine Wave">
  <br>
  <em>Obrázek 4: Konfigurace sinusového stimulu.</em>
</p>

### 2. Obdélníkový stimul (Rectangular)
Slouží ke stanovení kritické frekvence splývání (CFF). Jas skokově přechází mezi dvěma úrovněmi.

**Nastavte parametry:**
- **Frekvence [Hz]:** Rychlost změn jasu.
- **Amplituda / Kontrast [%]:** Rozsah mezi maximálním a minimálním jasem.
- **Minimální jas [cd/m²]:** Spodní úroveň jasu.
- **Čas [ms]:** Doba trvání stimulu.
- **Segment & Mask:** Oblast monitoru a tvar stimulu.

<p align="center">
  <img src="screenshots/rect_doc.png" alt="Rectangular">
  <br>
  <em>Obrázek 5: Konfigurace obdélníkového stimulu.</em>
</p>

### 3. Sinusová mřížka (Grating)
Slouží ke studiu kontrastní citlivosti (TCSF).

**Nastavte parametry:**
- **Spatial Frequency [cyc/deg]:** Hustota mřížky.
- **Kontrast [%]:** Michelsonův kontrast.
- **Minimální jas [cd/m²]:** Jas pozadí.
- **Distance [cm]:** Pozorovací vzdálenost od monitoru.
- **Orientation:** Natočení mřížky.
- **Čas [ms]:** Doba trvání stimulu.

<p align="center">
  <img src="screenshots/sine_contrast.png" alt="Grating">
  <br>
  <em>Obrázek 6: Konfigurace sinusové mřížky.</em>
</p>

### 4. Textový kontrast (Text Contrast)
Slouží k testování čitelnosti textu.

**Nastavte parametry:**
- **Text:** Obsah textu.
- **Minimální jas [cd/m²]:** Jas pozadí.
- **Kontrast [%]:** Weberův kontrast textu vůči pozadí.
- **Čas [ms]:** Doba trvání stimulu.

<p align="center">
  <img src="screenshots/text_contrast.png" alt="Text Contrast">
  <br>
  <em>Obrázek 7: Konfigurace textu.</em>
</p>

---
[Zpět na README](README.md)
