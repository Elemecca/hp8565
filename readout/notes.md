
Page 8-100


### Resolution Bandwidth

Selected by `LFSE-1`

|   Value | MX[6:1] |
| ------: | ------: |
| 100  Hz |     2Eh | requires Option 100
| 300  Hz |     1Eh | requires Option 100
|   1 kHz |     3Eh |
|   3 kHz |     3Dh |
|  10 kHz |     3Fh |
|  30 kHz |     3Bh |
| 100 kHz |     36h |
| 300 kHz |     35h |
|   1 MHz |     37h |
|   3 MHz |     33h |


### Input Attenuation

Selected by `LFSE-4`

| Value | MX[1:3] |
| ----: | ------: |
|  0 dB |       0 |
| 10 dB |       1 |
| 20 dB |       2 |
| 30 dB |       3 |
| 40 dB |       4 |
| 50 dB |       5 |
| 60 dB |       6 |
| 70 dB |       7 |

### Vertical Scale

Selected by `LFSE-5`

| Value     | MX[4:1]  |
| --------- | -------- |
| Linear    | 8h - Fh  | MX4 high
| 10 dB/div | 6h       | MX1 low
|  5 dB/div | 5h       | MX2 low
|  2 dB/div | 3h       | MX3 low

### Sweep Time

Selected by `LFSE-6`

| Value  | MX[6:1] |
| -----: | ------: |
|  10  s |       |
|   5  s |       |
|   2  s |       |
|   1  s |
| 500 ms |
| 200 ms |
| 100 ms |
|  50 ms |
|  20 ms |
|  10 ms |
|   5 ms |
|   2 ms |
|   1 ms |
| 500 us |
| 200 us |
| 100 us |
|  50 us |
|  20 us |
|  10 us |      48 |
|   5 us |      16 |
|   2 us |      32 |
| Auto   |      63 |
| Ext    |


Aux B

95   A29 XA18-43 STOP SWP (out)
94   A29 XA18-37 MARKER (out)
904  A29 XA19-14 YTF MOD (in)
913  A29 J1-17 B1 (out)
914  A29 J1-15 B2 (out)
915  A29 J1-11 B3 (out)
916  A29 J1-7  B4 (out)
917  A29 J1-3  B5 (out)
918  A29 J1-2  B6 (out)

968  A29 J2-29 SWEEP (out, via 5k11 resistor)


XA17-30 YTO FREQ ANALOG (TO XA18-30, XA19-30, XA20-30, REAR PNL)
AX17-31 YTF FREQ ANALOG (TO XA18-31, XA19-31, REAR PNL)



AUX A (J1)
1   NC
2   NC
3   NC
4   NC
5   NC
6   NC
7   925  NORMALIZER CONTROL IN    A10XA4-29 A10XA5-21 A10XA6-21
8   NC
9   NC
10  NC
11  968  HORIZONTAL SWEEP OUTPUT    A29J2-29 (via 5k11 resistor)
12  NC
13  NC
14  NC
15  NC
16  NC
17  NC
A1  978  VERTICAL OUTPUT    A29XA21-41
A2  957  PEN LIFT    A10XA4-4
A3  NC
A4  923  NORMALIZER X IN    A10XA6-18
A5  924  NORMALIZER Y IN    A10XA5-18
A6  NC
A7  926  NORMALIZER BLANK IN    A10XA4-27


AUX B (J2)
1   913  B1
2   914  B2
3   915  B3
4   916  B4
5   917  B5
6   918  B6
7   95   STOP SWP
8   904  YTF MOD
9   94   MARKER
10  NC
11  NC
12  NC
A1  NC
A2  NC
A3  C2   YTO FREQ ANALOG
A4  C3   YTF FREQ ANALOG
A5  NC
