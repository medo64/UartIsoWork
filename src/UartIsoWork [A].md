### UartIsoWork Parts

|  # | Part                                      | RefDes  | Preferred Part Number      |
|---:|-------------------------------------------|---------|----------------------------|
|  3 | C 100nF X7R 16V (0805)                    | C1-C3   | 478-5311-1-ND              |
|  1 | C 470nF X7R 16V (0805)                    | C4      | 1276-1199-1-ND             |
|  2 | C 10uF X5R 16V (0805)                     | C5-C6   | 1276-1096-1-ND             |
|  2 | DS LED (0805)                             | DS1-DS2 | 475-1415-1-ND              |
|  1 | J JST XH Vertical (4w)                    | J1      | 455-2249-ND                |
|  1 | P USB C, plug, straddle 0.8mm             | P1      | WM12855-ND                 |
|  1 | Q P-MOSFET DMP3099L-13 (SOT23)            | Q1      | DMP3099L-13DICT-ND         |
|  2 | R 1K 0.125W (0805)                        | R1-R2   | RMCF0805FT1K00CT-ND        |
|  1 | R 5.1K 0.125W (0805)                      | R3      | RMCF0805FT5K10CT-ND        |
|  1 | U MCP2221 (SOIC-14)                       | U1      | MCP2221-I/SL-ND            |
|  1 | U ADUM1281ARZ (SOIC-8)                    | U2      | ADUM1281ARZ-ND             |


#### Board Size

|       |      Dimensions | Area    | Thickness |
|-------|-----------------|---------|-----------|
| PCB   |  24.0 x 27.9 mm | 1.1 in² |    0.8 mm |


#### Power

| Property | Value  |
|----------|-------:|
| Voltage  |    5 V |
| Current  | 100 mA |


##### Non-Insulated Interface

If one doesn't need insulation (or you really hate your laptop), you can convert
the card into a non-insulated serial TTL 5V interface by soldering 0 Ω resistor
on the bottom pads (normally unpopulated) and omiting the following components:
* C2, C3
* C5, C6
* DS2
* Q1
* R2
* U2
