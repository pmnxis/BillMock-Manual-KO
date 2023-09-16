<!--
SPDX-FileCopyrightText: © 2023 Jinwoo Park (pmnxis@gmail.com)

SPDX-License-Identifier: MIT OR Apache-2.0
-->

# Port - ETC

## Credit Card Reader Port

![J1](./images/pcb_0v4_mini_port/J1.png)

<table>
<tr>
<td>

|                |
| -------------- |
|  |
|  |
| **Designator** |
|  J1  |
|  |
|  |
| **Role** |
| Card reader RS232+5V |
|  |
|  |
| **Connector** |
| Molex 5268-04 |
|  |
|  |
| **Housing** |
| Molex 5264-04 |
|  |
|  |
| **Crimp** |
| Molex 5263 |
</td>
<td>

| **Pin #** | **Pin Name**   | 설명 |
| :-------: | -------------- | --------- |
| `1`       | `GND` |  |
| `2`       | `TXD` | billmock In. |
| `3`       | `RXD` | billmock out. |
| `4`       | `5V`  | 5V Power out |

</td></tr>
</table>

-  5V 출력,  Peak 2.2A 300mS trip, 1.1A nominal MAX.

------------

### Program debugging (SWD/JTAG)

![DEBUG](./images/pcb_0v4_mini_port/debug_port.png)

|  |  |
| --- | --- |
| **Role** | STM32 SWD |
| **Connector** | TC2030 |

</td></tr>
</table>

- 디버그 인터페이스에 대해서는 이쪽에서 자세히 확인해주세요. [BillMock-HW-RELEASE](https://github.com/pmnxis/BillMock-HW-RELEASE)
