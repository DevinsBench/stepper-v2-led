# stepper-v2-led
Hacker Fab V2 Stepper UV LED PCB

Files imported from [Google drive](https://drive.google.com/drive/u/1/folders/1X3nmuruO58prPQBm8DrWUhfM-LNq0qWm)

Supported projectors:
  * DLPDLCR471TPEVM: the classic V2 projector
  * DLP4710EVM-LC: experimental projector due to part shortage

LED compatibility:

| Pin      | DLPDLCR471TPEVM | DLP4710EVM-LC |
| -------- | --------------- | ------- |
| 10       | N/C             | Common   |
| 9        | N/C             | Common   |
| 8        | LED+            | Common   |
| 7        | LED+            | Common   |
| 6        | LED+            | Common   |
| 5        | LED+            | LED1+   |
| 4        | LED-            | LED1+   |
| 3        | LED-            | LED1+   |
| 2        | LED-            | LED2+   |
| 1        | LED-            | LED2+   |

"You can order it through your PCB manufacturer of choice (we used JLCPCB). However, note that the PCB is copper core. This is because the LEDs draw several amps of current in operation. To ensure that the PCB doesn't melt, you should use copper core to facilitate better heat flow."

"When ordering the PCB, the manufacturer might send you an email asking about a missing heatsink file. In this case, please respond that this project does not include a direct heatsink, as the copper core PCB itself is designed to handle the thermal management."

DLPDLCR471TPEVM (4 LED) BOM:

| Vendor    | Model | Price each (2025) | Quantity | Link |
| -------- | ------- | ------- | ------- | ------- |
|  	Lumileds |  L1F3-U400200012000  | $10.50   |  4  |  [Digikey](https://www.digikey.com/en/products/detail/lumileds/L1F3-U400200012000/7389568)  |
| Molex  |  0874371043  | $0.71   |  1  |  [Digikey](https://www.digikey.com/en/products/detail/molex/0874371043/717647)  |

Notes:
* DLP4710EVM-LC
  * Instead use [Molex 0874381043](https://www.digikey.com/en/products/detail/molex/0874381043/699154)
  * [FOSSF Silicon notes](https://docs.google.com/document/d/1Yg9_48nFprNLK36mjKuTRpAcMww_u_pMMim5-wJe3lg/edit?tab=t.0#heading=h.3c9frve8h9fi)
* Connectors mate with [Molex 0874391000](https://www.digikey.com/en/products/detail/molex/0874391000/561773)
  * Pins: suggest [Molex 874210000](https://www.digikey.com/en/products/detail/molex/0874210000/2037270)

# History

FIXME. What is the 4 vs 6 LED history?
