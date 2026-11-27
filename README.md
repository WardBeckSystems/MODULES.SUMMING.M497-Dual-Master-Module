# M497 · Summing

Ward-Beck Systems M497, 1978|11. Wiki page: [M497 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M497.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 28 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 142 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 16 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [19 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M497 - Dual-Master-Module.pdf](MANUALS/1978%20-%20M497%20-%20Dual-Master-Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Frequency response | +0 -1 dB from 20 Hz to 20 kHz (tailored frequency response) |
| **Noise** | 72 dB be ]ow +8 dBm nomina 1 output level (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.25% THD from 30 Hz to 20 kHz at +24 dBm output or Tess Less than 0.1% at kHz at +24 dBm output |
| **Source impedances** | Summing Externa 30,000 ohms, balanced 600 ohms maximum, baLanced. |
| **Input impedances** | Summing Externa ] Less than 5 ohms. 30,000 ohms |
| **Input level** | Externa]: dBm nomina ] +16 dBm maximum |
| **Output impedances** |  |
| &nbsp;&nbsp;Program | Monitor Mono 600 ohms balanced 600 ohms; baLanced 75,000 ohms; baLanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Program | Monitor Mono 600 ohms baLanced Bridging balanced (5k ohms minimum) Summing, Tess than 5 ohms balanced |

## Circuit description

From [1978 - M497 - Dual-Master-Module (2).pdf](MANUALS/1978%20-%20M497%20-%20Dual-Master-Module%20(2).pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Parts List 2-1 to 2-23-1 to 3-4

I 4 Appendix 8-109 Description 8-109-1-1 to -3 I 8-109 Parts List 8-109 -2 -1 to -5

I S Drawings M49 7 Front Panel A4 97 -04-003 M49 7 Functional 8497-01 -00 1

**M49 7**

Schematic Component Layout 8497-02-001 8497 -06-00 1 M497 Connector Layout A4 97-04-002 I 8-109E Schematic 8-109E Component Layout 88-109 -02-00 6 88 -109-06 -006

**OCT. 1978**

['NBS] 841 P ROGt=lE S S AVENUE. S CARBOROl..JGH. ONTARIO M 1H axe TELEX 0 6 5 -2 5 3 9 9 TELEPHONE A 16 /4:36 -65!5 0

**WARRANTY**

defective material sand workman ship fora period o f one year from the date of shipment.

without charge, all said products or parts thereof which upon factory inspection prove to be defective during the warranty period, provided that:

1) the original serial numbers are intact and have not been tampered with,

2) the purchaser shall return any equipment or

after obtaining prior authorization and shipping instruct ions from the factory (Ward -Beck Systems Lto., reserves the right to inspector repair equip men ton the purchaser's premises), and

3) the purchaser assumes the obligation fora ll expenses incurred;n connection with the shipping and return of such goods, once authorization has been obtained.

This warranty does not cover items norma II y consider e d expendable, such a s fuses and lamps.

This warranty does not cover damages caused b y misuse, accident, neglect, un author i zed alteration, repair by unauthorized personnel, o r damage caused by act o f God, war, orc i v i lin su r r e c tion.

right to final determination as tot heap pl i cab i lit y of this warranty.

without notice, to make changes in its equipment, component specifications, or designs, as maybe war ranted by progress in

state o fth eart o r technology.

The warranty set forth herein i s;n lieu o fall other warranties,

expressed o r implied, including the war ran ties o f merc hantabi lit y and fitness.

**M49 7 OUAL MASTER MOOULE**

Gain: 8 dB ±0.5 dB nominal. A trim range of +2. -6 dB is provided.

Frequency Response: +0 -1 dB from 20 Hz t o 20 kHz (tailored frequency response).

Noise: 72 dB below +B dBm nominal output level (20 Hz t o 20 kHz).

Harmonic Distortion: Less than 0.25% THD. from 30 Hz to 20 kHz at +24 dBm output or less.

Less than 0.1% at 1 kHz at +24 dBm · output.

Source Imp~dances:

Summing: 30.000 ohm~ balanced.

External: 6000hms maximum, balanced.

Input Impedances:

Summing: less than 5 oh ms..

Externa 1: 30.000 ohms.

Input Level:

Exte rna 1: a dBm nom inal~ +16 dBm maximum. Out put I mpe dances:

Program: 6000hms. balanced.

Monitor: 600 ohms. balanced.

Mono: 75.000 ohms. ba I a nced.

Load Imped ances:

Program: 6000h ms. balanced.

Monitor: Brid9in9 ~ balanced (5kohms minimum).

Mono: Summing. less than S ohms. balanced.

**TECHNICAL DATA**

Out put Level:

Program: +8 dBm nominal, +24 dBm maximum. Monitor: +8 dBm nominal. +24 dBm maximum. Mono: +8 dBm nominal when summed into a second M4 97.

Channel Separation: 60 dB between Left and Right channels (50 Hz t o 15 kHz).

Phasing: Input and out put terminals designated by numbers are i n phase.

Power Requirements: ±25 volts d c, 50 rnA n u m t n a l, 200 rnA maximum.

Ambient Temperature: o to 60 degrees Celsius. Dimensions: 1.6&quot; wide X 7&quot; high X 6.5&quot; deep. (41 mm X 178 mm X 165 mm).

I CIRCUIT DESCRIPTION

I The M497 accommodates two separate signal channels. It i s designed tore c ei ve the mixed feeds from the left and right mixer buses of a console. The twos i gna l s are independently I processed and amplified to standard line levels. The outputs oft he M497 supply the main program outputs of the consoles ystem. Both channels operate ina similar manner. The I following description refers specifically t o the LEFT channel. Input I The signal or i gina ting from thee x te rna l mlxl ng network enters the module at pins I tA and;s app lied t o the summing current nodes of I I and 12.

III through Z3, with their associated components, provide ana c tively balanced input as well a s a balanced output. The output operates a t a nominal level of 0 dBm and appears at I pins 6/F.

Insert I A balanced INSERT point i s provided between pins 6/ Fan d 8/ J. permitting the insertion of a next erna l equalizer, filter orc ompr e s s or, either using an M499 insert switcher or by direct wiring.

Level Adjustment From the INSERT point, the signal is returned t o the module a t pins 8/J and fed to the 8-109 E output amplifier via ana tt e nuator network. R42 i sale vel trim potentiometer permitting adjustment of the module output level from -6 t o +2 dB with reference t o the nominal level of +8 dBm. A small hole in the module front panel allows access t o the trim control. Output The 8-109E output amplifier operates with again of 29 dB. It recovers the loss of the input network and provides additional gain t o produce a nominal line level o f +8 dBm a t the output

of the module.

A 600 ohm resist i ve dividing network. having a loss of 6 dB, is inserted between the 8-109E and the two module out puts a t

pins 12/ N and 13/ P. Each of the two outputs has ama ximum

drive ca pa bi 1i t y of +24 dBm into a 600 ohm load.

A separate MONITOR output is provided, designed to feed the M4 95 STEREO MONITOR module as well as to drive a standard VU meter.

RIGHT Channel and MONO Out put The right channel o f the M49 7 operates ina manners i mil ar to the left channel as described above.

Fort he MONO output, both channels are combined and appear at pins 111M. The signal level of this output iss uc h that, when connected to the summing input of a second M497, it will / produce a n output of +8 dBm, with the left o r right channel o f the first unit operating at +8 dBm.

Power Supply De coupling An active power supply decQupl ing network consisting of Q1 through Q6 provides isolation between the module and the ±25 volt supply rails. Transistors Q3 and Q6 monitor the supply current. Int he event of excessive power supply demands. such as from component failure o r amplifier overdrive. the current flowing through Ql and Q4 will be limited.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVDhIeGt3TmJsX3M/view?resourcekey=0-ZP3NLuTVm3gtY4G_c5vRew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVDhIeGt3TmJsX3M&resourcekey=0-ZP3NLuTVm3gtY4G_c5vRew" width="240" alt="1978 - M497 - Dual ACN Master Module.jpg"></a><br><sub>1978|11 · Dual ACN Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREs0ZVBmZ3VyZkE/view?resourcekey=0-cIX0fTaLMISsma9DoX6zjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREs0ZVBmZ3VyZkE&resourcekey=0-cIX0fTaLMISsma9DoX6zjA" width="240" alt="1978 - M497 - Dual Master Module.jpg"></a><br><sub>1978|11 · Dual Master Module</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1978|11 · wbsps - module - m497 dual acn master module_small](https://drive.google.com/file/d/0B0yR0b5T78SKeF9rZEZpWVVhYjA/view?resourcekey=0-8XS0A37VXlZsaEYQteFywA)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

Not on Google Drive yet: `1989 - 497-03-007 - HEATSINK - DRN GEB - ENG GEB - ISS 1.jpg`

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1xrvNp0WOHs6CsxncuCMRbW1CNLy4iHDY/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1xrvNp0WOHs6CsxncuCMRbW1CNLy4iHDY" width="240" alt="19xx - M497 - DOC - 497-02-001 - DUAL MASTER MODULE SCHEMATIC.jpg"></a><br><sub>19xx - M497 - DOC - 497-02-001 - DUAL MASTER MODULE SCHEMATIC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1IRahFbsPHBcdvuXsdKtytXjyfr8PAlmE/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1IRahFbsPHBcdvuXsdKtytXjyfr8PAlmE" width="240" alt="19xx - M497 - DOC - 600-02-001 - INPUT CHANNEL SCHEMA TIC.png"></a><br><sub>19xx - M497 - DOC - 600-02-001 - INPUT CHANNEL SCHEMA TIC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1qYVdoCMw_0tnSSR9HQ4a2T1bJ5mnNb9f/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1qYVdoCMw_0tnSSR9HQ4a2T1bJ5mnNb9f" width="240" alt="19xx - M497 - DOC - 600-02-002 - OUTPUT CHANNELS ARE WIRED.png"></a><br><sub>19xx - M497 - DOC - 600-02-002 - OUTPUT CHANNELS ARE WIRED</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1amsBk-uaVYY0-bMHN0mwsnVSGXnkx_U0/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1amsBk-uaVYY0-bMHN0mwsnVSGXnkx_U0" width="240" alt="19xx - M497 - DOC - 600-02-003 - WITH JUMPERS BETWEEN PINS AND BETWEEN PINS.png"></a><br><sub>19xx - M497 - DOC - 600-02-003 - WITH JUMPERS BETWEEN PINS AND BETWEEN PINS</sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 497-01-005 - DUAL MASTER MODULE FUNCTIONAL DIAGRAM - ISS 1.jpg`, `19xx - 497-02-002 - DUAL MASTER MODULE SCHEMATIC - DRN TR - ENG TR - ISS 1.jpg`, `19xx - 497-02-003 - DUAL MASTER MODULE SCHEMATIC - DRN DS - ENG PA - ISS 2.jpg`, `19xx - 497-02-004 - DUAL MASTER MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 1.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M497 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | LEFT SUM IN | in | SUM IN L | high |
| 2 | RIGHT SUM IN | in | SUM IN R | high |
| 3 | SHIELD | shield | shield | high |
| 4 | LEFT EXT IN | in | EXT IN L | high |
| 5 | RIGHT EXT IN | in | EXT IN R | high |
| 6 | LEFT PRE OUT | out | PRE OUT L | high |
| 7 | RIGHT PRE OUT | out | PRE OUT R | high |
| 8 | LEFT LEV CTL IN | control_in | LEV CTL IN L | high |
| 9 | RIGHT LEV CTL IN | control_in | LEV CTL IN R | high |
| 10 | SHIELD | shield | shield | high |
| 11 | MONO OUT | out | MONO OUT | high |
| 12 | LEFT OUT 1 | out | OUT 1 L | high |
| 13 | LEFT OUT 2 | out | OUT 2 L | high |
| 14 | LEFT MON OUT | out | MON OUT L | high |
| 15 | RIGHT OUT 1 | out | OUT 1 R | high |
| 16 | RIGHT OUT 2 | out | OUT 2 R | high |
| 17 | RIGHT MON OUT | out | MON OUT R | high |
| 18 | N/C | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | LEFT SUM IN | in | SUM IN L | high |
| B | RIGHT SUM IN | in | SUM IN R | high |
| C | SHIELD | shield | shield | high |
| D | LEFT EXT IN | in | EXT IN L | high |
| E | RIGHT EXT IN | in | EXT IN R | high |
| F | LEFT PRE OUT | out | PRE OUT L | high |
| H | RIGHT PRE OUT | out | PRE OUT R | high |
| J | LEFT LEV CTL IN | control_in | LEV CTL IN L | high |
| K | RIGHT LEV CTL IN | control_in | LEV CTL IN R | high |
| L | SHIELD | shield | shield | high |
| M | MONO OUT | out | MONO OUT | high |
| N | LEFT OUT 1 | out | OUT 1 L | high |
| P | LEFT OUT 2 | out | OUT 2 L | high |
| R | LEFT MON OUT | out | MON OUT L | high |
| S | RIGHT OUT 1 | out | OUT 1 R | high |
| T | RIGHT OUT 2 | out | OUT 2 R | high |
| U | RIGHT MON OUT | out | MON OUT R | high |
| V | N/C | nc |  | high |
| W | N/C | nc |  | high |
| X | N/C | nc |  | high |
| Y | N/C | nc |  | high |
| Z | N/C | nc |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSklOZWc3dWhnX3M/view?resourcekey=0-ddm8lODCQTRdakssfWsPrg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSklOZWc3dWhnX3M&resourcekey=0-ddm8lODCQTRdakssfWsPrg" width="240" alt="1978 - M497 - Dual-Master-Module (2).pdf"></a><br><sub>1978|11 · Dual-Master-Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUGowQnJNdnNzLWs/view?resourcekey=0-SXtRHOM7svAITIeJ9cVdmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUGowQnJNdnNzLWs&resourcekey=0-SXtRHOM7svAITIeJ9cVdmA" width="240" alt="1978 - M497 - Dual-Master-Module.pdf"></a><br><sub>1978|11 · Dual-Master-Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M497 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M497 - DOC - R1400-R2400 - 007</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmxvZGRGcWFZV0E/view?resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmxvZGRGcWFZV0E&resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" width="240" alt="19xx - M497 - DOC - R1400-R2400 - 012.jpg"></a><br><sub>19xx - M497 - DOC - R1400-R2400 - 012</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M497 - Dual-Master-Module p21.kicad_sch](KICAD/1978%20-%20M497%20-%20Dual-Master-Module%20p21.kicad_sch)
- [19xx - 497-01-005 - DUAL MASTER MODULE FUNCTIONAL DIAGRAM - ISS 1.kicad_sch](KICAD/19xx%20-%20497-01-005%20-%20DUAL%20MASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20ISS%201.kicad_sch)
- [19xx - 497-02-002 - DUAL MASTER MODULE SCHEMATIC - DRN TR - ENG TR - ISS 1.kicad_sch](KICAD/19xx%20-%20497-02-002%20-%20DUAL%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20TR%20-%20ENG%20TR%20-%20ISS%201.kicad_sch)
- [19xx - 497-02-003 - DUAL MASTER MODULE SCHEMATIC - DRN DS - ENG PA - ISS 2.kicad_sch](KICAD/19xx%20-%20497-02-003%20-%20DUAL%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20DS%20-%20ENG%20PA%20-%20ISS%202.kicad_sch)
- [19xx - 497-02-004 - DUAL MASTER MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 1.kicad_sch](KICAD/19xx%20-%20497-02-004%20-%20DUAL%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [M497.kicad_sym](KICAD/M497.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
