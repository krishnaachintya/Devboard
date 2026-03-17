# Devboard.csv

my custom devboard :)

has debug leds and a 9-DOF IMU composed of multiple 3-axis sensors

in the format of a rpi pico

<img width="732" height="817" alt="image" src="https://github.com/user-attachments/assets/7d79ec80-b7f7-49fe-9cc2-802deb6c80ed" />


# BOM

| Id | Designator                                  | Footprint                                   | Quantity | Comment          | Estimated Price (INR) |
| -- | ------------------------------------------- | ------------------------------------------- | -------- | ---------------- | --------------------- |
| 1  | R5,R7                                       | R_0402_1005Metric                           | 2        | 1K               | ₹2               |
| 2  | C16,C15                                     | C_0402_1005Metric                           | 2        | 33pF             | ₹3               |
| 3  | C10,C11,C5,C8,C3,C2,C7,C6,C4,C17,C1,C20,C18 | C_0402_1005Metric                           | 13       | 0.1uF            | ₹20             |
| 4  | D3,D1,D2                                    | LED_0603_1608Metric                         | 3        | LED              | ₹15              |
| 5  | Y1                                          | Crystal_SMD_3225-4Pin_3.2x2.5mm             | 1        | 12MHz            | ₹40             |
| 6  | R10,R9,R8                                   | R_0402_1005Metric                           | 3        | 680              | ₹3               |
| 7  | J4                                          | PinHeader_1x03_P2.54mm_Vertical             | 1        | Conn_01x03       | ₹10              |
| 8  | C9,C12                                      | C_0402_1005Metric                           | 2        | 1uF              | ₹6               |
| 9  | U1                                          | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm         | 1        | RP2040           | ₹350           |
| 10 | R4,R3                                       | R_0402_1005Metric                           | 2        | 27               | ₹2               |
| 11 | U3                                          | Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm | 1        | W25Q128JVS       | ₹150            |
| 12 | J3,J2                                       | PinHeader_1x20_P2.54mm_Vertical             | 2        | Conn_01x20       | ₹40             |
| 13 | C21                                         | C_0402_1005Metric                           | 1        | 2.2uF            | ₹5               |
| 14 | C13,C14                                     | C_0201_0603Metric                           | 2        | 10uF             | ₹30             |
| 15 | U4                                          | LGA-16_3x3mm_P0.5mm_LayoutBorder3x5y        | 1        | ICM-20602        | ₹900           |
| 16 | U2                                          | SOT-23                                      | 1        | MCP1700x-330xxTT | ₹40             |
| 17 | J1                                          | USB_C_Receptacle_HRO_TYPE-C-31-M-12         | 1        | USB-C            | ₹120            |
| 18 | SW1                                         | SW_Push_SPST_NO_Alps_SKRK                   | 1        | Switch           | ₹15              |
| 19 | R6                                          | R_0402_1005Metric                           | 1        | 10K              | ₹1             |
| 20 | R2,R1                                       | R_0402_1005Metric                           | 2        | 5.1K             | ₹2               |
| 21 | C19                                         | C_0402_1005Metric                           | 1        | 10nF             | ₹2               |

