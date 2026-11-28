# M460B Input Module · Input Pre Amps

Ward-Beck Systems M460B, 1974|7. Wiki page: [M460B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M460B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 52 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 12 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 298 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 13 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 15 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 59 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [12 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1976 - M460B - P002 - 1-1.jpg](MANUALS/1976%20-%20M460B%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivities** | ;8j 299~€=b 02 03 7u:67e076 T Fnf ';mA 3'aD Line 10 to +10 dBm (ref 600 ohm source Fj &lt; Mic Pad -50 20 dBm (ref 150 ohm source Mic -70 to -40 dBm (ref 150 onm source |
| **Frequency response** | ±0.25 dB from 30 Hz to 20 kHz (Equalizer bypa s $ Position. 125 dBm EIN at maximum SENSITIVITY (20 Hz to 20 kHz). |
| **Noise** |  |
| &nbsp;&nbsp;Harmonic distortion | Less than 0.259 THD from 30 Hz to 20 kHz at +28 dBm or Less Less than 0.1% at kHz at +28 dBm output. |
| **Source impedances** | Line Mic 150/600 ohms ba lanced/ unbalanced 150 ohms ba lanced/unbalanced |
| **Input impedances** | Line Mic 30,000 ohms 1,500 ohms than 100 ohms (at outputs of {ei89 or 8-1094 amplifiers only) _ 600 ohms balanced (at insertion point) |
| **Output impedance** |  |
| &nbsp;&nbsp;Load impedance | Output Leve] 10 dBm nomina ] +30 dBm maximum. (At outputs of 8-109 or 8-1094 amplifiers only) _ Input and output termina ] s designated by numbers are in Phase Pha $ ing: |
| **Power requirements** | +25 volts dc, 90 mA nomina], 250 mA maximum |

## Circuit description

From [1976 - M460B - Input Module (2).pdf](MANUALS/1976%20-%20M460B%20-%20Input%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

TIle M460B Is a co.binatlon INPUT/ EQUALIZER.odule, designed t o accept inputs i gna ls originating fro. either a. i c r o phone oral i ne source. The unit processes the inputs i gna las required and routes It to thea ppro pr fl te points wlthlrl the. lx lrl g console syste•.

.!l1..e!!.1 The INPUT SELECTORs wit th SWl provides a choice of connect ing the input transformer TIto either the MICROPHONE source directly, or vfl a 2D dB PAO. I neither case, the input impedance oft he unit 15 10 tines higher than the source Impedance. In the LINE position, the M4608 operates IS abridging amplifier, present ing 30t o hlll impedance tot hes our c e. Both HIC and LIME inputs are transformer coupled. With the I NPU-T SELECTOR i n the OFF posit ion, all inputs ere disconnected and the lI\odule input is terminated. Pream plifier The u co nda ry side of TI 15 connected tot he 4-11 D Pr U lllp / Hi g h_ pass filter. The 4-11 0 s e eves a s a low-noi u pn a_ p andre t s e s the input levels s u ff ic ie ntl y for further processing within the consoles ys tee. SENSITIVITY control RI2 per e t t s continuous level adjus t_ ent o fall input signals, allowing a total range of 30 dB.

HIGH-PASS Fl1ter SwitCh SW17 Is incorporated int he HIGH-PASS filter control RI D/II. Vith Rl0 / 11 positioned fully counterclockwise, SV17 oe s s es the output of the 4-11 0 directly t o the equalizer i nu rt switch SW13. Dnce R10/ll is rotated. way f rOlll the ex t r ell eco unterclockwiu position, '-12 dB/oct ave hig h-pus f ll ter is inserted. The -3 dB roll o H point is cont lrluous ly adjusta.ble fro. 25 to 250 Hz.

EQUALIZER Section p s.

The output of the 4 · 110 prea rlpl1fle r 15 routed too ne o·f the

normally closed ce neec es of the EQUALIZER INSERTs witch SW13 to allow bypassing oft he equalizer. Additionally, the pr eamp

output 15 fed t o ZI, the first of four cascaded summing

ampl1fi e rs Zl through Z4.

**CIRCUIT DESCRIPTIOII'**

ZI through Z4 serve a s.hi ng. nd t s e let t cn • • plff1 e r s. They. reused to.lx the prillary Inputs fg n.1 wlth I correction slgn ll de rill e d fro. til l!! outputs of the 4 -126 f f lUr networ h, resulting I n raising o r lowering the rev e t o f sete c eee portions oft he audios pec true. Addition. J1y, they ho late thl!! filter networks fro. each other and pre lle n t inU r action bet'lli en them, resulting fn accurate andre peat able equalizing pert c r-eene e •

Thl CUT/BOO ST controls R2l, R22 and R23 feed ani n phase or out o f phase proportional sf gna l tot he buffer alllpl if i er s Z5, Z6 and Z8 respect tve l y, The tevet o f the signal fed to the buffers is dependent on the CUT/800S T controls etti ng with maximum level occurring at either end of the potent te ee t e r, and a nulls e tt inge t the pot entiometer mid position. Full c t ec ke t se or full counterclockwise potent iometer settings '11111 result int he maximum eq ua ltza t ion o·f +15 dB and -15 dB respect iv el y.

The outputs of buffer amp lffi ers Z5, Z6 and Z8 are routed tot he 4-126 printed circuit board which contains three ba ndpa ss filters correspond ing to each of the threes e c t ions oft he equalizer.

The HIGH FREQUENCY section of the unit pr ov1de s SHELVIHG t)'P l!! o f equalization. R21 deter. fnes the • • ou nt of CUT or BOOST with a toUl range f rOIl -IS to +15 dB. Fr eq ue nc)' is c ee t t a uousl)' adjustable fro. 1.6 t o 25 kHz b)' Rl /R2. The f r e q ue nc)' cali brat ion refers t o the 3 dB r o l lo ff point when the unit is operating at the Ilu l. u. a u ihb le CUT o r BOOST o f 15 d B. The MID FREQUENC&quot;l!!qua liuti on is adjusted by R4/R5, covering a f req ue nc)' range fro. 0.4 t o 6.4 kHz. CUT/BOOST is controlled by R22. R6 adjusts the Q-hc tor. Po s ith e o r ne ga the bell shaped PEAKING e q ull l1 za t lon is ap pl1c~ bl ein the. l d -f re q ue nc)' range.

The LOW FREQUENCY equalization operate s s 1ll11 a r1 y t o the high

f reque nc)' section. R7/RB adjusts the frequency r llnge frolll

25 to 400 Hz while R23 cont r o l s CUT or BOOST.

The threes i gna ls wh l c h lene the 4 -126 filter are &quot;c orr ectlo n slg na ls either in-phas e or IBO de gre!!s out -o f -p hase with the equalizer input and band pass 11111 ted as deterlilned by thee quel f z e r sect ion and control settings. These &quot; correction s lgnals ar-e then sUllllled together with the prl lury (Input) sfg n&quot;l by the operatlon&quot; l u p l if l e r s Zl, Z2 a.nd Z4 thus for ll1ng thee que t f zed outputs ignal.

Thh concept of adding&quot; corrections t qna l together with the 1ncomlng slgn&quot;l t o for lll the eqll&quot;lized s i llnal is directly responslble fort he low no he and distortion capabilities of this unit.

The compounds i gn alas lIene ra.ted al o nll the en t l r e process l ng che tn a ppe a r-s at the output of Z4. From here it is routed too ne oft he normally open contacts o f the EQUALIZER INSERTs witch S1I13.

t bus, w1t h SIII 3 depressed. the euu e t t aed s l gna l t s fed tot he output ampl t rte r a - to gA. In additlon. as SII13 1$ depressed. the LEO fndfca tor is ae t tve eee.

B-I09AOutput Arlpl1fl e r &quot;nd INSERT The a-l 0gA u pli f l e r ra.hes the signal t o -10 dB.. nOllf na ll y. The output 1$ acth e l y balanced and fed to the -lnsert polnt&quot; at pfns 22 and Z o f lIodule connector PI. Th h future allows the use of insert jacks. per.htlng t o lnse rt a.ncillary equlplle nt 1nto the lIa f n. hing slgna l pa.th.

PHASE Reversal The sf gna l 1$ returned to the llodule yia plns 21 andy of PI and routed through the PHASE REVERSAL swf tch SII2 t o the CHANNEL ON switch S1I21.

**PREFADE -LIS TEN (PFL)**

The b rfdgfng takeoff for the PFL output r s p fcked up between

SII2 and 51121.

WAF;O ·SECK SYSTEMS LTC.

**K4 60 B INPUT KOOULE**

CHANNEL ON Switcli Tile CHANNEL ON switc ll SWZI controls all outputs oft ile 1I0 d u ie with tile exception oft ile PFl out put.

iM!IB.

Following SWZ l, tiles i gnal is brouglit out of tile e e e ute via pins ZO and X of PI for insertion of a balanced fad er. Tile output oft he fade r is returned to thea e d ul eon pins 19 and W of P1. The Input side o f the fader also serves as a pickup point fort he PREFADE REVERBERATION SEND (RS). the PREFADE FOl DBACK (FB) and the PREFADE PUBLIC ADDRESS { Pl.} channels y ia switches SillS. SWIg and SW4 respectively.

8 ·109 Booster AMp l i fie r The B·I 09 booster a llpl 1fier operates with a ga 1n of 15 dB andre c o.,ers t hl! loss tnc urr-e e wilen the fader is placed i nits nOllli nal 15 dB in · ha ndpos i t ion.

Main Outputs and PAN Control The outputs ig nal o f the 8 ·l09 e ep t t tt er feedS the left and right. a 1n outputs.,ia PAN switch SW14 and PAN control RZ4 through RZ7. It also provides the feed for the DIRECT output. and. via SWI6. for the SOLO output. Additionally. feeds are supplied to tile POSTFADE RS. FB and PI. channels.,1a tile appropriate switches and level controls.

PRE/P OST Selector Switches and Level Controls PRE/POST selection of tile RS, FB and PI. channels is facilitated by switcll es SWlB. SW19 and S\l4 respect ive l y; each s wl t c ll is followed by its associated level cont r-cl. The outputs of the tevet controls are fed t o the summing outputs via tile appropriate switches and level controls.

Auxiliary Functions

DC controls and logic functions are provided t hrcuqh the INPUT SELECTOR swltcll Sill and the CHANNEL ON switch SWZl to operate

**&quot;46DB INPUT KODULE**

e xte r-na l Mute control functions independently forboth etc r cphone and lines ou rces, as.. ay be required ina particular console SysteM. Additional de control cont acts area va ila bl eon the SOLO swt t c h, the PA switch, the PFL switch and the CHANNEl ON switch to allow operation of external relays and /o rillUMination of the CHAItNEL ON button.

Power Supply Decoup ltng

An acr t ve power supply decoupllng net wo r l:. consisting of Ql through Q6 provides a high degree of holatio n between the M460B and the tZs volt supply r e t ts. Transistors Q5 and Q6 ser-ve a s current e c n t t cr-s and will 11Q1it the current flowing thr-o ugh the pus t ranshto rs Q3 and Q4 i nth e event that excessive power supply de. a nds should arts e a s ares u lt of COMponent f.flure.

p s.

FREOUENcy RESPONSE CHARACTERISTICS

**11460B INPUT MODULE EOUAL I I ER**

., &quot;i,I

**I I**

LOW FREOUEN CY section -, Ii CUT/ BOOST: tl Sea. -,

FREQUENCY: 25 &amp; 400 Hz.

**I I**

&quot;'&quot; 101&lt;»0.000

**7: III**

-, I;.: I 'I

**-, S 1**

&quot;I D FREQUENCY section

CUT/ BOOST: !15dB. -,

FREQUENCY: 0.4 &amp; 6.4 kHz.

Q: 2. ·&quot;tllIl.,~... _ •.co.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXVtTEEzdVhQaG8/view?resourcekey=0-ONi1R7eDsie3DFALzi5M_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXVtTEEzdVhQaG8&resourcekey=0-ONi1R7eDsie3DFALzi5M_Q" width="240" alt="1976 - M460B - 001.jpg"></a><br><sub>1976|9 · 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXdaR0ZlYVloSjg/view?resourcekey=0-WUfcI0vsLbS-PbttJPIxxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXdaR0ZlYVloSjg&resourcekey=0-WUfcI0vsLbS-PbttJPIxxw" width="240" alt="1976 - M460B - 002.jpg"></a><br><sub>1976|9 · 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclA1X2F3aGlrWFU/view?resourcekey=0-n41wuInes6SsJldUARwkGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclA1X2F3aGlrWFU&resourcekey=0-n41wuInes6SsJldUARwkGw" width="240" alt="1976 - M460B - 003.jpg"></a><br><sub>1976|9 · 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzF4RFQ0dEZ0ZjA/view?resourcekey=0-4AK0eu4V6rhloDngWam70Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzF4RFQ0dEZ0ZjA&resourcekey=0-4AK0eu4V6rhloDngWam70Q" width="240" alt="1976 - M460B - 004.jpg"></a><br><sub>1976|9 · 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHFEWm9PUDB1NGs/view?resourcekey=0-yIUwp_47w_9VxIyOcFw9Dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHFEWm9PUDB1NGs&resourcekey=0-yIUwp_47w_9VxIyOcFw9Dg" width="240" alt="1976 - M460B - 005.jpg"></a><br><sub>1976|9 · 005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc0hLOE5kZVVfTnM/view?resourcekey=0-Yfed_Nw-YaQCDbpTLVKDrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc0hLOE5kZVVfTnM&resourcekey=0-Yfed_Nw-YaQCDbpTLVKDrA" width="240" alt="1976 - M460B - 006.jpg"></a><br><sub>1976|9 · 006</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUi15NzBFS0pfSGM/view?resourcekey=0-v9ZKAUZfDXwtOYDRX4J4ig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUi15NzBFS0pfSGM&resourcekey=0-v9ZKAUZfDXwtOYDRX4J4ig" width="240" alt="1976 - M460B - 007.jpg"></a><br><sub>1976|9 · 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEhOdFJTR2I4Qk0/view?resourcekey=0-dBLCuZ2DdLN-7s3u0xg0zA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEhOdFJTR2I4Qk0&resourcekey=0-dBLCuZ2DdLN-7s3u0xg0zA" width="240" alt="1976 - M460B - 008.jpg"></a><br><sub>1976|9 · 008</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFVDWXJxUGZ6MUk/view?resourcekey=0-QBuUylfKhjObXNxRzW1-sQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFVDWXJxUGZ6MUk&resourcekey=0-QBuUylfKhjObXNxRzW1-sQ" width="240" alt="1976 - M460B - 009.jpg"></a><br><sub>1976|9 · 009</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUm1FWGlzVEdUUTQ/view?resourcekey=0-RKsrG1P42Z5Zd4GxpCjxMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUm1FWGlzVEdUUTQ&resourcekey=0-RKsrG1P42Z5Zd4GxpCjxMw" width="240" alt="1976 - M460B - 010.jpg"></a><br><sub>1976|9 · 010</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHYzUmp5UVRvNHM/view?resourcekey=0-2mLXvOtwO4ssKLCC_P1rjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHYzUmp5UVRvNHM&resourcekey=0-2mLXvOtwO4ssKLCC_P1rjw" width="240" alt="1976 - M460B - 011.jpg"></a><br><sub>1976|9 · 011</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ1JmQzM3Y2dzMEE/view?resourcekey=0-icUeomWp2fnEKmRN5iSTyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ1JmQzM3Y2dzMEE&resourcekey=0-icUeomWp2fnEKmRN5iSTyw" width="240" alt="1976 - M460B - file.jpg"></a><br><sub>1976|9 · file</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2xCY0dESjgtTmc/view?resourcekey=0-thMDqiQmJzzmixXRQ-7DAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2xCY0dESjgtTmc&resourcekey=0-thMDqiQmJzzmixXRQ-7DAw" width="240" alt="1976 - M460B - 460-04-013 - IXI CONTROL FUNCT IONS- NOTE THAT THE.jpg"></a><br><sub>1976|9 · 460-04-013 - IXI CONTROL FUNCT IONS- NOTE THAT THE · <a href="MECHANICAL/1976%20-%20M460B%20-%20460-04-013%20-%20IXI%20CONTROL%20FUNCT%20IONS-%20NOTE%20THAT%20THE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUxGSm5QdjZhc3c/view?resourcekey=0-aRtlufgDK-_uJqZMAVCv9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUxGSm5QdjZhc3c&resourcekey=0-aRtlufgDK-_uJqZMAVCv9A" width="240" alt="1977 - M460B - 460-04-007 - LUL CONNECTOR REAR VEW.jpg"></a><br><sub>1977|10 · 460-04-007 - LUL CONNECTOR REAR VEW · <a href="MECHANICAL/1977%20-%20M460B%20-%20460-04-007%20-%20LUL%20CONNECTOR%20REAR%20VEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0kwWG96cGxRWXM/view?resourcekey=0-Cm-Vi3kDLEwIVnW6qB_rtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0kwWG96cGxRWXM&resourcekey=0-Cm-Vi3kDLEwIVnW6qB_rtw" width="240" alt="1976 - M460B - 4-110-02-001 - MPONENT DESICN RIG CIG.jpg"></a><br><sub>1976|9 · 4-110-02-001 - MPONENT DESICN RIG CIG · <a href="SCHEMATICS/1976%20-%20M460B%20-%204-110-02-001%20-%20MPONENT%20DESICN%20RIG%20CIG%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRlFIMVlGdDh4VEU/view?resourcekey=0-zSAVDv5Nv8KT9WVr6lhpWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRlFIMVlGdDh4VEU&resourcekey=0-zSAVDv5Nv8KT9WVr6lhpWQ" width="240" alt="1976 - M460B - 4-110-06-001 - FOR SCAEMATIC SEE DRA WING.jpg"></a><br><sub>1976|9 · 4-110-06-001 - FOR SCAEMATIC SEE DRA WING · <a href="SCHEMATICS/1976%20-%20M460B%20-%204-110-06-001%20-%20FOR%20SCAEMATIC%20SEE%20DRA%20WING%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFJRVi1hQ05VZkk/view?resourcekey=0-psRv2rCyLZUn3-Z9SO5-RQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFJRVi1hQ05VZkk&resourcekey=0-psRv2rCyLZUn3-Z9SO5-RQ" width="240" alt="1976 - M460B - 4-126-02-001 - GCALE AMPLIFIER SCHEMATH.jpg"></a><br><sub>1976|9 · 4-126-02-001 - GCALE AMPLIFIER SCHEMATH · <a href="SCHEMATICS/1976%20-%20M460B%20-%204-126-02-001%20-%20GCALE%20AMPLIFIER%20SCHEMATH%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNm9ibFQ3ZEtLTnM/view?resourcekey=0-Uu-xv-k9BNiNVKMM02ivqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNm9ibFQ3ZEtLTnM&resourcekey=0-Uu-xv-k9BNiNVKMM02ivqw" width="240" alt="1976 - M460B - 4-126-06-001 - SOCKETS ACCEI.jpg"></a><br><sub>1976|9 · 4-126-06-001 - SOCKETS ACCEI · <a href="SCHEMATICS/1976%20-%20M460B%20-%204-126-06-001%20-%20SOCKETS%20ACCEI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbklyMWdQTVZGajg/view?resourcekey=0-tGwGLwXO5FU5vJtJr_nuLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbklyMWdQTVZGajg&resourcekey=0-tGwGLwXO5FU5vJtJr_nuLg" width="240" alt="1976 - M460B - 4-136-06-003 - MIISH DATL NOV.jpg"></a><br><sub>1976|9 · 4-136-06-003 - MIISH DATL NOV · <a href="SCHEMATICS/1976%20-%20M460B%20-%204-136-06-003%20-%20MIISH%20DATL%20NOV%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRmxvN3p0M29jWE0/view?resourcekey=0-LHWhTppvs-2X4BHiURrfyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRmxvN3p0M29jWE0&resourcekey=0-LHWhTppvs-2X4BHiURrfyA" width="240" alt="1976 - M460B - 460-01-003 - CONTROL CONTROL COMMON.jpg"></a><br><sub>1976|9 · 460-01-003 - CONTROL CONTROL COMMON · <a href="SCHEMATICS/1976%20-%20M460B%20-%20460-01-003%20-%20CONTROL%20CONTROL%20COMMON%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUzRnQnFBdzBiaHc/view?resourcekey=0-M1BhC9H-EXaQAqVicMMBpw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUzRnQnFBdzBiaHc&resourcekey=0-M1BhC9H-EXaQAqVicMMBpw" width="240" alt="1976 - M460B - 460-02-003 - DIL NOL INPUT MODULE CKDE SCHRMATC.jpg"></a><br><sub>1976|9 · 460-02-003 - DIL NOL INPUT MODULE CKDE SCHRMATC · <a href="SCHEMATICS/1976%20-%20M460B%20-%20460-02-003%20-%20DIL%20NOL%20INPUT%20MODULE%20CKDE%20SCHRMATC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0h0UlpZejhPS1E/view?resourcekey=0--zgo5_gle094UKdltYwnQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0h0UlpZejhPS1E&resourcekey=0--zgo5_gle094UKdltYwnQw" width="240" alt="1976 - M460B - 8-109-02-001.jpg"></a><br><sub>1976|9 · 8-109-02-001 · <a href="SCHEMATICS/1976%20-%20M460B%20-%208-109-02-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeVNJRGlnVjdvWFU/view?resourcekey=0-_IjtBUMU5TzrNPtZleDH1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeVNJRGlnVjdvWFU&resourcekey=0-_IjtBUMU5TzrNPtZleDH1w" width="240" alt="1976 - M460B - 8-109-06-001 - RYLU COMPONENT LAYOUT.jpg"></a><br><sub>1976|9 · 8-109-06-001 - RYLU COMPONENT LAYOUT · <a href="SCHEMATICS/1976%20-%20M460B%20-%208-109-06-001%20-%20RYLU%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUl5VXRsLXRDM1k/view?resourcekey=0-znHsyXJhKsgo83fsGsLiuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUl5VXRsLXRDM1k&resourcekey=0-znHsyXJhKsgo83fsGsLiuA" width="240" alt="1976 - M460B - 8-109-06-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1976|9 · 8-109-06-002 - OUTPUT AMPLIFIER · <a href="SCHEMATICS/1976%20-%20M460B%20-%208-109-06-002%20-%20OUTPUT%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1f4yPwIY21WfTisRgUt7D-UEhYfkNBNrM/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1f4yPwIY21WfTisRgUt7D-UEhYfkNBNrM" width="240" alt="1976 - M460B - Input Module Schematic.jpg"></a><br><sub>1976|9 · Input Module Schematic · <a href="SCHEMATICS/1976%20-%20M460B%20-%20Input%20Module%20Schematic%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1974 - 4-110-02-001 - 4-110 PRE-AMP HP FILTER SCHEMATIC - DRN DM - ISS 8.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M460B - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts, 39 contacts (J4), 22 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | MIC IN | in | A1 + | high |
| 2 | FFI | other |  | medium |
| 2 | CH ON | control |  | low |
| 3 | IC | nc |  | medium |
| 5 | NC | nc |  | medium |
| 5 | BUS RIGHT OUT | out | A3 + | high |
| 6 | IC | nc |  | medium |
| 8 | SOLO | audio |  | medium |
| 9 | IC | nc |  | medium |
| 11 | NC | nc |  | medium |
| 12 | PFL CONTROL | control |  | medium |
| 12 | DIRECT OUT | out | A4 + | high |
| 14 | NC | nc |  | medium |
| 15 | MUTE CONTROL | control |  | medium |
| 17 | NC | nc |  | medium |
| 17 | LINE IN | in | A2 + | high |
| 18 | CONTROL COM | ground |  | medium |
| 18 | COMMON | ground |  | high |
| 19 | FADER RETURN | in | B4 + | high |
| 19 | -25 V | power |  | high |
| 20 | ATT. IN SHIELD TIE | ground |  | medium |
| 20 | CH ON SWITCH OUT | control | B3 + | high |
| 20 | COMMON | ground |  | high |
| 21 | 25V | other |  | medium |
| 21 | INSERT RETURN | in | B2 + | high |
| 21 | +25 V | power |  | high |
| 22 | INSERT OUT | out | B1 + | high |
| 22 | CHASSIS | ground |  | high |
| 39 |  | unread |  | low |
| A | MIC IN | in | A1 - | high |
| B | PFL | audio |  | medium |
| C | IC | nc |  | medium |
| C |  | unread |  | low |
| E | NC | nc |  | medium |
| E | BUS RIGHT OUT | out | A3 - | high |
| F | TC | other |  | medium |
| J | SOLO | audio |  | medium |
| K | NC | nc |  | medium |
| M | NC | nc |  | medium |
| N | PA CONTROL | control |  | medium |
| N | DIRECT OUT | out | A4 - | high |
| R | NC | nc |  | medium |
| S | MUTE CONTROL | control |  | medium |
| U | NC | nc |  | medium |
| U | LINE IN | in | A2 - | high |
| V | SOLO CONTROL | control |  | medium |
| W | FADER RETURN | in | B4 - | high |
| W |  | unread |  | low |
| X | ATT. IN SHIELD TIE | ground |  | medium |
| X | CH ON SWITCH OUT | control | B3 - | high |
| X |  | unread |  | low |
| Y | CH ON | control |  | medium |
| Y | INSERT RETURN | in | B2 - | high |
| Y | +24 V | power |  | high |
| Z | INSERT OUT | out | B1 - | high |

**Straps:** CH ON LAMP: JMP.Z.W · CH ON GND : JMP.X.18 · 24V Jumper: JMP.Y.21 · CH ON GND : JMP.3 · Insert +: JMP.22.21 · Insert -: JMP.Z.Y · Fader +: JMP.20.19 · Fader - : JMP.X.W

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUV9ZWHg1S0ZQa0k/view?resourcekey=0-shM4O_HkhJg-iJgszSn6Mw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUV9ZWHg1S0ZQa0k&resourcekey=0-shM4O_HkhJg-iJgszSn6Mw" width="240" alt="1976 - M460B - Input Module (2).pdf"></a><br><sub>1976|9 · Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdEVkYWhMR2R6UW8/view?resourcekey=0-dbRF1Ug1dOchfouqWDgesQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdEVkYWhMR2R6UW8&resourcekey=0-dbRF1Ug1dOchfouqWDgesQ" width="240" alt="1976 - M460B - Input Module.pdf"></a><br><sub>1976|9 · Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXdSVUEyWjdFYzA/view?resourcekey=0-iO8HGV1oUWGMT0DPZMWcJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXdSVUEyWjdFYzA&resourcekey=0-iO8HGV1oUWGMT0DPZMWcJw" width="240" alt="1976 - M460B - P001 - Title Page.jpg"></a><br><sub>1976|9 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNW5FcWM2NHJ4U1E/view?resourcekey=0-WyaoS-tgHZ_6aYlTyyseiA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNW5FcWM2NHJ4U1E&resourcekey=0-WyaoS-tgHZ_6aYlTyyseiA" width="240" alt="1976 - M460B - P002 - 1-1.jpg"></a><br><sub>1976|9 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWjlQbk1INUFuZXM/view?resourcekey=0-wJdQKtcktNZdNegoGvW8tA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWjlQbk1INUFuZXM&resourcekey=0-wJdQKtcktNZdNegoGvW8tA" width="240" alt="1976 - M460B - P003 - 1-2.jpg"></a><br><sub>1976|9 · P003 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOFZuMS0zMVVTTTg/view?resourcekey=0-PRMMOtLotOPKKe9ObEeAQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOFZuMS0zMVVTTTg&resourcekey=0-PRMMOtLotOPKKe9ObEeAQA" width="240" alt="1976 - M460B - P004 - 2-1.jpg"></a><br><sub>1976|9 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUVDQk9XRmVBRFU/view?resourcekey=0-CkT1ncsB1-m1aeUlHHswSA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUVDQk9XRmVBRFU&resourcekey=0-CkT1ncsB1-m1aeUlHHswSA" width="240" alt="1976 - M460B - P005 - 2-2.jpg"></a><br><sub>1976|9 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSlZ1XzRqNnR0cGc/view?resourcekey=0-wAjCCDPvwauL1x_1FW1neQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSlZ1XzRqNnR0cGc&resourcekey=0-wAjCCDPvwauL1x_1FW1neQ" width="240" alt="1976 - M460B - P006 - 2-3.jpg"></a><br><sub>1976|9 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWQtQ2ppY2pPU3M/view?resourcekey=0-JcVjsyXuUPGLM0WjL2nUfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWQtQ2ppY2pPU3M&resourcekey=0-JcVjsyXuUPGLM0WjL2nUfg" width="240" alt="1976 - M460B - P007 - 2-4.jpg"></a><br><sub>1976|9 · P007 - 2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejBiV0kwbDVqRlE/view?resourcekey=0-PqaBehHZpzV_0UQfNG2J1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejBiV0kwbDVqRlE&resourcekey=0-PqaBehHZpzV_0UQfNG2J1A" width="240" alt="1976 - M460B - P008 - 2-5.jpg"></a><br><sub>1976|9 · P008 - 2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDFBUG5OWjFQRHM/view?resourcekey=0-K_sMn3WFS3wK8lYRN4o9qA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDFBUG5OWjFQRHM&resourcekey=0-K_sMn3WFS3wK8lYRN4o9qA" width="240" alt="1976 - M460B - P009 - 3-1.jpg"></a><br><sub>1976|9 · P009 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2xZbE1ZTlNJUVk/view?resourcekey=0-wM8QhffbonWt8zqZt0XJXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2xZbE1ZTlNJUVk&resourcekey=0-wM8QhffbonWt8zqZt0XJXQ" width="240" alt="1976 - M460B - P010 - 3-2.jpg"></a><br><sub>1976|9 · P010 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXNZMVpBSTZtWWM/view?resourcekey=0--7Y-khYXkjtpGKdIBbiW5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXNZMVpBSTZtWWM&resourcekey=0--7Y-khYXkjtpGKdIBbiW5g" width="240" alt="1976 - M460B - P011 - 4-1.jpg"></a><br><sub>1976|9 · P011 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGJPWDlnOGc1Rnc/view?resourcekey=0-ew1q0mk6Jg8znmz_Y1bPXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGJPWDlnOGc1Rnc&resourcekey=0-ew1q0mk6Jg8znmz_Y1bPXw" width="240" alt="1976 - M460B - P012 - 4-2.jpg"></a><br><sub>1976|9 · P012 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWpjZnYwN25VM0E/view?resourcekey=0-1BStupt3_UUSVPZgT2xKdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWpjZnYwN25VM0E&resourcekey=0-1BStupt3_UUSVPZgT2xKdw" width="240" alt="1976 - M460B - P013 - 4-3.jpg"></a><br><sub>1976|9 · P013 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmZXY0tzcFQtRmM/view?resourcekey=0-cQRjljPUNaW05Em_RE36eg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmZXY0tzcFQtRmM&resourcekey=0-cQRjljPUNaW05Em_RE36eg" width="240" alt="1976 - M460B - P014 - 4-4.jpg"></a><br><sub>1976|9 · P014 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRzVhM2piSml6UEU/view?resourcekey=0-1dahsfNeV4fP2UGdq3Y5ow" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRzVhM2piSml6UEU&resourcekey=0-1dahsfNeV4fP2UGdq3Y5ow" width="240" alt="1976 - M460B - P015 - 4-5.jpg"></a><br><sub>1976|9 · P015 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDFEcFVFeHd0UWc/view?resourcekey=0-T1DSrgQBjhDQITTNcZ4U0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDFEcFVFeHd0UWc&resourcekey=0-T1DSrgQBjhDQITTNcZ4U0Q" width="240" alt="1976 - M460B - P016 - 4-6.jpg"></a><br><sub>1976|9 · P016 - 4-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkpucExvaUFCdFk/view?resourcekey=0-nipC_xTteeBsJV5bNw9kAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkpucExvaUFCdFk&resourcekey=0-nipC_xTteeBsJV5bNw9kAA" width="240" alt="1976 - M460B - P017 - 8-109-1-1.jpg"></a><br><sub>1976|9 · P017 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRkNOTDJpMU9iYUE/view?resourcekey=0-Rfu7dMUfRiAPcmeuDYKppg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRkNOTDJpMU9iYUE&resourcekey=0-Rfu7dMUfRiAPcmeuDYKppg" width="240" alt="1976 - M460B - P018 - 8-109-1-2.jpg"></a><br><sub>1976|9 · P018 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGVMakIzQlZpN2M/view?resourcekey=0-tZ1D0Qvd0UhF5MU74xvk_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGVMakIzQlZpN2M&resourcekey=0-tZ1D0Qvd0UhF5MU74xvk_A" width="240" alt="1976 - M460B - P019 - 8-109-2-1.jpg"></a><br><sub>1976|9 · P019 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHVTY1lwTmlhdDg/view?resourcekey=0-wm2nKtHe2TEz27TG1PVjOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHVTY1lwTmlhdDg&resourcekey=0-wm2nKtHe2TEz27TG1PVjOg" width="240" alt="1976 - M460B - P020 - 8-109-2-2.jpg"></a><br><sub>1976|9 · P020 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2tBQVU1ak1tYXc/view?resourcekey=0-RH7RiN_2LDrta78xY9QMcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2tBQVU1ak1tYXc&resourcekey=0-RH7RiN_2LDrta78xY9QMcA" width="240" alt="1976 - M460B - P021 - 8-109-2-3.jpg"></a><br><sub>1976|9 · P021 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEFmS1BCdFd4ZUE/view?resourcekey=0-Y2vE3v4FclsaWRTh1TjJew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEFmS1BCdFd4ZUE&resourcekey=0-Y2vE3v4FclsaWRTh1TjJew" width="240" alt="1976 - M460B - P022 - 8-109-2-4.jpg"></a><br><sub>1976|9 · P022 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZEs1dDRNQVczd1U/view?resourcekey=0-2iZ7Stvq4p3K-aH0ixE8Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZEs1dDRNQVczd1U&resourcekey=0-2iZ7Stvq4p3K-aH0ixE8Lw" width="240" alt="1976 - M460B - P023 - 8-109-2-5.jpg"></a><br><sub>1976|9 · P023 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdHk1dFY5SWtPTGM/view?resourcekey=0-pjBLUyh0bPVnHqsckyT7fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdHk1dFY5SWtPTGM&resourcekey=0-pjBLUyh0bPVnHqsckyT7fw" width="240" alt="1976 - M460B - P024 - 4-110-1-1.jpg"></a><br><sub>1976|9 · P024 - 4-110-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdnZUQVd2bEhfSEE/view?resourcekey=0-kxcUMOWsnZLk6FrKxDByGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdnZUQVd2bEhfSEE&resourcekey=0-kxcUMOWsnZLk6FrKxDByGg" width="240" alt="1976 - M460B - P025 - 4-110-2-1.jpg"></a><br><sub>1976|9 · P025 - 4-110-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRExrR3hYS2RsWEk/view?resourcekey=0-1fYf8aA67QgWvT4WXsUcdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRExrR3hYS2RsWEk&resourcekey=0-1fYf8aA67QgWvT4WXsUcdw" width="240" alt="1976 - M460B - P026 - 4-110-3-1.jpg"></a><br><sub>1976|9 · P026 - 4-110-3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUlBOG8zaVpVODA/view?resourcekey=0-zg_pj0-cJJAapktXMR0kxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUlBOG8zaVpVODA&resourcekey=0-zg_pj0-cJJAapktXMR0kxg" width="240" alt="1976 - M460B - P027 - 4-110-3-2.jpg"></a><br><sub>1976|9 · P027 - 4-110-3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHFMVUlPdXZKWlk/view?resourcekey=0-BiJqGaBw2G6lDl2njc3Jkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHFMVUlPdXZKWlk&resourcekey=0-BiJqGaBw2G6lDl2njc3Jkg" width="240" alt="1976 - M460B - P028 - 4-126-1-1.jpg"></a><br><sub>1976|9 · P028 - 4-126-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2t1WnN6UVV2UmM/view?resourcekey=0-Iup4NiX0e7BJ-goBWBMYcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2t1WnN6UVV2UmM&resourcekey=0-Iup4NiX0e7BJ-goBWBMYcg" width="240" alt="1976 - M460B - P029 - 4-126-2-1.jpg"></a><br><sub>1976|9 · P029 - 4-126-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWThyekl0bkFOUDQ/view?resourcekey=0-1CV3k9hXlG3ho9bYgKscTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWThyekl0bkFOUDQ&resourcekey=0-1CV3k9hXlG3ho9bYgKscTg" width="240" alt="1976 - M460B - P030 - 4-126-2-2.jpg"></a><br><sub>1976|9 · P030 - 4-126-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLXZvakw2LVJqWTA/view?resourcekey=0-ZUeTi_sL-Uc02KGn5rcXNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLXZvakw2LVJqWTA&resourcekey=0-ZUeTi_sL-Uc02KGn5rcXNQ" width="240" alt="1976 - M460B - P031 - 4-126-2-3.jpg"></a><br><sub>1976|9 · P031 - 4-126-2-3</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - 4-110-02-001 - 4-110 PRE-AMP HP FILTER SCHEMATIC - DRN DM - ISS 8.kicad_sch](KICAD/1974%20-%204-110-02-001%20-%204-110%20PRE-AMP%20HP%20FILTER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%208.kicad_sch)
- [1976 - M460B - 4-110-02-001 - MPONENT DESICN RIG CIG.kicad_sch](KICAD/1976%20-%20M460B%20-%204-110-02-001%20-%20MPONENT%20DESICN%20RIG%20CIG.kicad_sch)
- [1976 - M460B - 4-126-02-001 - GCALE AMPLIFIER SCHEMATH.kicad_sch](KICAD/1976%20-%20M460B%20-%204-126-02-001%20-%20GCALE%20AMPLIFIER%20SCHEMATH.kicad_sch)
- [1976 - M460B - 460-01-003 - CONTROL CONTROL COMMON.kicad_sch](KICAD/1976%20-%20M460B%20-%20460-01-003%20-%20CONTROL%20CONTROL%20COMMON.kicad_sch)
- [1976 - M460B - 460-02-003 - DIL NOL INPUT MODULE CKDE SCHRMATC.kicad_sch](KICAD/1976%20-%20M460B%20-%20460-02-003%20-%20DIL%20NOL%20INPUT%20MODULE%20CKDE%20SCHRMATC.kicad_sch)
- [1976 - M460B - 8-109-02-001 - ISSUDATE REVISION.kicad_sch](KICAD/1976%20-%20M460B%20-%208-109-02-001%20-%20ISSUDATE%20REVISION.kicad_sch)
- [1976 - M460B - 8-109-02-001.kicad_sch](KICAD/1976%20-%20M460B%20-%208-109-02-001.kicad_sch)
- [1976 - M460B - Input Module (2) p33.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20(2)%20p33.kicad_sch)
- [1976 - M460B - Input Module Schematic.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20Schematic.kicad_sch)
- [1976 - M460B - Input Module p33.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20p33.kicad_sch)
- [1976 - M460B - Input Module p34.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20p34.kicad_sch)
- [1976 - M460B - Input Module p39.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20p39.kicad_sch)
- [1976 - M460B - Input Module p41.kicad_sch](KICAD/1976%20-%20M460B%20-%20Input%20Module%20p41.kicad_sch)
- [M460B.kicad_sym](KICAD/M460B.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
