# Анализ репозитория RADAR: Список компонентов для закупки

## 1. Плата синтезатора частот (Frequency Synthesizer Board)
**Основные активные компоненты:**
* AD9523BCPZ (PLL Clock Driver) — 1 шт.
* ADF4382ABCCZ (Synthesizer) — 2 шт.
* MTX2-143+ (Mixer) — 4 шт.
* CVHD-950-50.000 (Кварц 50 МГц) — 2 шт.
* ECOC-2522-100.000-3HC (Кварц 100 МГц) — 1 шт.
* ATS1005-3DB-FD-T05 (Резистор высокой точности) — 4 шт.
* FBMH1608HL601-T (Ферритовая бусина) — 4 шт.

**Пассивные компоненты и разъемы:**
* 142-0731-211 (SMA Connector Jack, Female) — 11 шт.
* 22-23-2021 (Разъем Header 2-pin) — 6 шт.
* CJT-T-P-HH-ST-TH1 (Разъем Twinax Samtec) — 2 шт.
* Конденсаторы 0.1 мкФ (0201) — 26 шт.
* Конденсаторы 10 пФ (0201) — 6 шт.
* Конденсаторы 10 мкФ (1210) — 5 шт.
* Конденсаторы 22 мкФ (1210) — 6 шт.
* Индуктивности 1.3 нГн (0201) — 8 шт.
* Резисторы 1 кОм (0201) — 6 шт.
* Резисторы 200 кОм (0201) — 8 шт.

## 2. Основная плата (Main Board)
**Основные активные компоненты:**
* XC7A50T-2FTG256I (FPGA Artix-7) — 1 шт.
* STM32F746ZGT7 (MCU) — 1 шт.
* AD9484BCPZ-500 (ADC 500 MSPS) — 1 шт.
* AD9708AR (DAC) — 1 шт.
* ADAR1000ACCZN (RF Switch/Attenuator) — 4 шт.
* ADTR1107ACCZ (RF Switch) — 16 шт.
* FT2232HQ (USB-to-UART/FIFO) — 1 шт.
* DAC5578SRGET (Octal DAC) — 2 шт.
* INA241A3IDGKR (Current Sense Amp) — 16 шт.
* LTC5552IUDB#TRMPBF (Mixer) — 2 шт.
* M3SWA2-34DR+ (RF Switch) — 17 шт.
* ADS7830IPWR (ADC 8-ch) — 3 шт.
* OPA4703EA/250 (Quad Op-Amp) — 4 шт.
* AT93C46DN-SH-B (EEPROM) — 1 шт.
* MT25QL01GBBB8E12-0AUT (Flash Memory) — 1 шт.
* SZMMSZ5232BT1G (Zener Diode) — 34 шт.

**Разъемы и прочее:**
* 142-0731-211 (SMA Connector Jack, Female) — 37 шт.
* 22-23-2021 (Header 2-pin) — 40 шт.
* 22-23-2031 (Header 3-pin) — 16 шт.
* MINI-USB-32005-201 (Mini USB-B) — 2 шт.
* Конденсаторы 0.1 мкФ (0201) — 71 шт.
* Конденсаторы 100 нФ (0402) — 28 шт.
* Конденсаторы 100 пФ (0201) — 34 шт.
* Резисторы 1 кОм (0201) — 49 шт.
* Резисторы 4.7 кОм (0201) — 27 шт.

## 3. Плата питания (Power Board)
**Основные активные компоненты:**
* TPS562208DDCT (Step-down Converter) — 21 шт.
* ADM7151ACPZ-04-R7 (LDO Regulator) — 6 шт.
* LM2662MX/NOPB (Voltage Regulator) — 5 шт.
* TPS7A8300RGRR (Ultra-low noise LDO) — 2 шт.
* T521W476M020ATE045 (Polymer Tantalum Cap 47мкФ) — 10 шт.

**Разъемы и пассивы:**
* 22-23-2021 (Header 2-pin) — 35 шт.
* Индуктивности силовые (TDK VLP8040T) — 21 шт.
* Конденсаторы 10 мкФ (0805) — 60 шт.
* Конденсаторы 22 мкФ (0603) — 52 шт.
* Резисторы 10 кОм (0805) — 27 шт.

## 4. Плата усилителя мощности (PA Board)
*Необходима проверка файла BOM.xlsx в папке Gerber_PA. Ключевые компоненты согласно даташитам:*
* QPA1013D / QPA2962
* QPM1021
* PMA2-123LNW+ / PMA5_123_3W
* LTC6419fa / LTC5552f
* SMIQ-5143H+ / MMIQA-0218HPSM
* TGA2623

## Сводная таблица основных IC
| Маркировка | Описание | Кол-во (всего) |
| :--- | :--- | :--- |
| XC7A50T-2FTG256I | FPGA Artix-7 | 1 |
| STM32F746ZGT7 | MCU STM32 | 1 |
| AD9484BCPZ-500 | ADC | 1 |
| AD9523BCPZ | Clock Driver | 1 |
| ADF4382ABCCZ | Synthesizer | 2 |
| ADAR1000ACCZN | RF Switch | 4 |
| ADTR1107ACCZ | RF Switch | 16 |
| M3SWA2-34DR+ | RF Switch | 17 |
| TPS562208DDCT | DC-DC | 21 |
| FT2232HQ | USB-UART | 1 |
| 142-0731-211 | SMA Connector | 48+ |
