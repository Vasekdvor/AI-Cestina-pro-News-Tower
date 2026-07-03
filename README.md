# 🗞️ Čeština pro News Tower `1.1.123.r`

Neoficiální fanouškovský **český překlad** hry [**News Tower**](https://store.steampowered.com/app/1649950/) (Sparrow Night).

Přeložené je **celé uživatelské rozhraní i obsah hry** včetně procedurálně generovaných novinových titulků — dohromady přes **35 000 textových řetězců** ve 41 tabulkách. Součástí je i **oprava fontů**, aby se správně zobrazovaly české znaky s háčky a čárkami (ě, š, č, ř, ž, ů, …).

> ⚠️ Překlad byl z velké části vytvořen pomocí **umělé inteligence (AI)**. Není proto dokonalý — přečti si prosím [Než začneš](#-než-začneš) a [Známé nedostatky](#-známé-nedostatky).

---

## 📥 Instalace

1. Stáhni si **`NewsTower_Cestina_Setup.exe`** z [**záložky Releases**](../../releases).
2. Ukonči hru News Tower.
3. Spusť instalátor a proklikej se jím.
   - Instalátor se **sám pokusí najít složku s hrou** (přes Steam) a předvyplní ji. Když sedí, jen pokračuj. Pokud ne, klikni na **Procházet** a vyber kořenovou složku hry (tu, kde je `News Tower.exe`).
   - Před instalací musíš odsouhlasit podmínky (viz níže).
4. Spusť hru a v **Nastavení → Jazyk** zvol **„Polski"**. 🇨🇿

> 💡 Čeština nahrazuje **polský** jazyk hry. Ve hře se tedy přepneš na „Polski" a uvidíš češtinu.

### 🗑️ Odinstalace
Odinstaluj přes **Ovládací panely → Programy a funkce** (nebo **Nastavení → Aplikace**), položka **„News Tower - Čeština"**. Odinstalace **vrátí původní soubory hry** ze záloh.

---

## ⚠️ Než začneš

Instalací a používáním této češtiny **souhlasíš s následujícím**:

- **Instaluješ a používáš vše zcela na VLASTNÍ RIZIKO.**
- Autor (**Vasekdvor**) **nijak neručí** za jakékoli poškození dat, hry ani **uložených pozic (savů)**, které by mohlo instalací nebo používáním vzniknout.
- **Doporučuji si před instalací zálohovat uložené hry.**
- Instalátor vytvoří zálohu původních souborů (přípona `.orig`) a lze ho odinstalovat.

### 🔄 Aktualizace hry
Při **aktualizaci hry přes Steam** (i po funkci **„Ověřit integritu souborů hry"**) se přeložené soubory přepíšou původními a **čeština zmizí**. Po každé aktualizaci prostě **spusť instalátor znovu**.

### 🎯 Kompatibilita verzí
Tato čeština byla vytvořena pro **konkrétní verzi hry** (Steam build `23146725`, otestováno na verzi hry `1.1.123.r`). Instalátor verzi zkontroluje:
- **Sedí** → nainstaluje se bez varování.
- **Nesedí** → zobrazí varování. Instalace na jinou verzi může hru **rozbít** (nemusí jít spustit, poškozené texty) a je pak čistě na tvoje riziko.

---

## 🐛 Známé nedostatky

- **Pády v novinových titulcích.** Titulky ve hře vznikají **procedurálně skládáním jednotlivých slov**. Slova v seznamu (WordList) jsou v **1. pádě**, takže ve vygenerovaných titulcích **nemusí vždy sedět pád, rod ani shoda**. Jde o vlastnost hry, ne o chybu překladu, a nelze to plně odstranit.
- **AI překlad.** Mohou se objevit nepřesnosti, kostrbaté formulace nebo překlepy. Nahlaš je prosím v [Issues](../../issues) — díky!

---

## 📦 Co instalátor dělá

Instalátor je postavený na **Inno Setup** a je plně v češtině. Konkrétně:

- **Automaticky najde hru** (čte cestu Steamu z registru a knihovny Steamu), ale nechá tě cíl **kdykoli změnit**.
- **Zkontroluje verzi hry** (podle kontrolního součtu herního katalogu) a upozorní, pokud nesedí.
- **Zálohuje** původní soubory (přípona `.orig`) — pokud ještě záloha neexistuje.
- Nahradí **3 soubory** hry ve složce `News Tower_Data\StreamingAssets\aa\`:
  | Soubor | Co obsahuje |
  |---|---|
  | `catalog.json` | úprava, aby hra přijala změněné balíčky |
  | `…\StandaloneWindows64\fonts_…​.bundle` | fonty s doplněnými českými znaky |
  | `…\StandaloneWindows64\localization-…​polish(pl)…​.bundle` | přeložené texty (v polském slotu) |
- Zaregistruje **odinstalátor**, který vše vrátí do původního stavu.

Nic jiného do počítače nezapisuje, neběží na pozadí a nepotřebuje administrátorská práva (pokud je složka hry zapisovatelná).

---

## 🔁 Sdílení

Pokud tuto češtinu nebo její soubory dále **šíříš** nebo je **použiješ do vlastního překladu**, vždy prosím **uveď autora: Vasekdvor**. Díky!

---

## ❤️ Poděkování

- **News Tower** © [Sparrow Night](https://store.steampowered.com/app/1649950/) — jde o neoficiální fanouškovský počin, nijak nesouvisející s tvůrci hry.
- Překlad: **Vasekdvor**

---

<sub>Neoficiální fanouškovská lokalizace. Všechny ochranné známky náleží jejich vlastníkům.</sub>
