# MattairTech_Arduino
Arduino support files for MattairTech boards
https://www.mattairtech.com/

```
============================================ MattairTech MT-D21E (ATsamd21eXXa) =======================================
Comm/Other INT      PWM    Digital    Analog                               Digital   PWM       INT    Comm/other
=======================================================================================================================
                                                  -----------------------
Xin32                                            |   A0            RST   |                            Reset
Xout32                                           |   A1            NC    |
                             2     2 (ADC0, DAC) |   A2            NC    |
                             3     3 (ADC1, REF) |   A3            A31   |   31   TCC1/WO[1]  INT11   Button B / SWD IO
          INT4               4     4 (ADC4)      |   A4            A30   |   30   TCC1/WO[0]  INT10   SWD CLK
          INT5               5     5 (ADC5)      |   A5            NC    |
                             6     6 (ADC6)      |   A6            A28   |   28               INT8    LED
VDIV                         7     7 (ADC7)      |   A7            A27   |   27               INT15   Button A
          INTNMI TCC0/WO[0]  8     8 (ADC16)     |   A8            A23   |   23   TC4/WO[1]   INT7    SPI SS
          INT9   TCC0/WO[1]  9     9 (ADC17)     |   A9            A22   |   22   TC4/WO[0]   INT6    SPI MISO
TX (1)           TCC0/WO[2]  10    10 (ADC18)    |   A10           A19   |   19               INT3    SPI SCK
RX (1)           TCC0/WO[3]  11    11 (ADC19)    |   A11           A18   |   18               INT2    SPI MOSI
TX (2)    INT14  TC3/WO[0]   14                  |   A14           A17   |   17   TCC2/WO[1]  INT1    I2C/SCL
RX (2)           TC3/WO[1]   15                  |   A15           A16   |   16   TCC2/WO[0]  INT0    I2C/SDA
                                                 |   NC            NC    |
                                                 |   NC            NC    |
                                                 |   Vbus          3.3V  |
USB D-                                           |   A24-  _____   Vcc   |
USB D+                                           |   A25+ |     |  Vin   |
                                                 |   Gnd  | USB |  Gnd   |
                                                  -----------------------
```
