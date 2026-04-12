# Návod pro měření LUT tabulek

Tento dokument popisuje postup při vytváření LUT (Look-Up Table) tabulek, které zajišťují správnou kalibraci barev a jasů monitoru pro experimentální účely.

## Příprava a kalibrace monitoru

Před začátkem měření proveďte základní nastavení monitoru.

1. Spusťte testovací podnět (viz Obrázek 1).
2. Manuálně nakalibrujte jas monitoru na požadovanou výchozí hodnotu.

![Kalibrace monitoru](screenshots/kalibrace_monitoru.png)
*Obrázek 1: Spuštění testovacího podnětu.*

> [!IMPORTANT]
> **Zatemněte místnost.** Jakékoli okolní světlo zkresluje výsledky měření jasu.
---

## Postup měření LUT

Měření probíhá automatizovaně na základě zvolených úrovní signálu.

### Měření jasu (Luminance)

Měření jasu probíhá pro celou škálu šedi (0–255). K měření použijte kalibrovanou kameru.

1. Připravte a zapněte kameru.
2. Zaostřete kameru na středovou oblast monitoru, kde se vykresluje podnět.
3. Spusťte automatické měření jasu (viz Obrázek 2).

Měření trvá přibližně 45 minut. Průběh měření sledujte v části C uživatelského rozhraní.

![Měření jasu](screenshots/mereni_lum.png)
*Obrázek 2: Rozhraní pro měření jasu.*

### Měření napětí fotodiody

V případě použití fotodiody měřte napětí přímo na výstupu čidla.

1. Připojte fotodiodu k systému.
2. Spusťte měření napětí (viz Obrázek 3).

Měření trvá přibližně 10 minut. Průběh měření sledujte v části C uživatelského rozhraní.

![Měření napětí](screenshots/mereni_volt.png)
*Obrázek 3: Rozhraní pro sledování napětí.*

---
[Zpět na README](README.md)
