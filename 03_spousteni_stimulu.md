# Návod pro spouštění stimulů

Aplikace umožňuje generovat vizuální stimuly pro psychofyzikální experimenty, jako je testování viditelnosti blikání (flicker) nebo kontrastní citlivosti.

## Postup spuštění

Nejprve je nutné přepnout aplikaci do režimu stimulů a nakonfigurovat požadované parametry.

![Postup spuštění](screenshots/postup_spusteni.png)
*Obrázek 1: Průvodce spuštěním stimulu krok za krokem.*

---

## Typy stimulů

### Sinusový signál (Sine)

Generuje plynulé změny jasu v čase podle sinusové křivky. Používá se pro studium časové kontrastní citlivosti (TCSF).

![Sinusový stimul](screenshots/sine.png)
*Obrázek 2: Náhled generovaného sinusového podnětu na obrazovce.*

![Sinusový kontrast](screenshots/sine_contrast.png)
*Obrázek 3: Ukázka nastavení kontrastu pro sinusový stimul.*

### Obdélníkový signál (Rectangular)

Jas se skokově mění mezi dvěma úrovněmi. Tento typ je vhodný pro stanovení kritické frekvence splývání (CFF).

![Obdélníkový stimul](screenshots/rect_doc.png)
*Obrázek 4: Konfigurace obdélníkového signálu a jeho vykreslení.*

### Textový kontrast (Text Contrast)

Testování schopnosti rozlišit textové prvky při různých úrovních kontrastu vůči pozadí.

![Textový kontrast](screenshots/text_contrast.png)
*Obrázek 5: Testovací vzor pro měření kontrastní citlivosti oka na textu.*

---

## Parametry a jejich význam

U každého stimulu je možné měnit následující hodnoty:

- **Frekvence [Hz]:** Jak rychle se jas mění. Vyšší frekvence se používají k určení CFF.
- **Amplituda / Kontrast [%]:** Rozdíl mezi maximálním a minimálním jasem.
- **Střední jas (Mean Luminance):** Průměrná hodnota jasu, kolem které signál osciluje.
- **Pozice a Velikost:** Nastavení, kde přesně na monitoru se má stimul zobrazit.

Tyto parametry se mění v ovládacím panelu aplikace před stisknutím tlačítka "Start".

---
[Zpět na README](README.md)