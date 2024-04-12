# FC_ESC_STM32F405RG_26x26

### 1. Overview

All-in-One (AIO) circuit for quadcopter. STM32F405 is the main controller for FC and EFM8BB21 is the main controller for ESC. Screw hole dimension is 26x26 mm that compatible for almost tiny drone frame. 

![3d_top](assets/demo/BoardDemo.png)

Everything about this board: Schematic, PCB gerber and BOM are free to distribute under open-source license for users.

### 2. Specifications

| Items               | Specifications                                               |
| ------------------- | ------------------------------------------------------------ |
| Power supply        | Pin LiPo 2-4 cell                                            |
| Microcontroller     | STM32F405RGT6 / 32-bit ARM Cortex-M4 with FPU(168MHz, 225DMIPS) |
| Sensors             | MPU6000 (3 axis gyroscope, 3 axis accelerometer) <br />BMP280 (barometer)<br />INA186 (current) |
| Programmer          | JTAG/SWD connector                                           |
| Communicaton Ports  | UART x 4<br />I2C x 1<br />SPI x 1                           |
| OSD                 | Built-in AT7456                                              |
| LEDs and Buttons    | LED RED: 3V3 power on<br />LED BLUE: User status             |
| Output power source | TPS5430 5V@5A<br />RT9013 3V3@500mA                          |
| Dimensions          | 34 x34 mm<br />Screw hole 26 x 26 mm                         |

**NOTE:**

This board use jumper to select 5V power source and to enable 3V3 power supply.

### 3. Layout / Pin map

| Function    | Pin                                                          |
| ----------- | ------------------------------------------------------------ |
| UART1       | PA9: TX<br />PA10: RX                                        |
| UART3       | PB10: TX<br />PB11: RX                                       |
| UART4       | PA0: TX<br />PA1: RX                                         |
| UART6       | PC6: TX<br />PC7: RX                                         |
| SPI2        | PB12: CS<br />PB13: CLK<br />PB14: MISO<br />PB15: MOSI      |
| I2C2        | PB10: SCL<br />PB11: SDA                                     |
| LED         | LED status: PB7<br />LED strip: PB6                          |
| BUZZER      | PC13                                                         |
| USB Port    | D-: PA11<br />D+: PA12                                       |
| Measurement | Current sens: PC1<br />Voltage sens: PC2<br />USB voltage sens: PC5 |

### 4. Hardware design

#### Schematic

[![schematic](assets/demo/schematic.png)](assets/demo/OpenDrone_AIO_FC_F405_HW_v1.pdf)

#### PCB F.Cu

![3d_top](assets/demo/PCB_F.Cu.png)

#### PCB In1.Cu

![3d_top](assets/demo/PCB_In1.Cu.png)

#### PCB In2.Cu

![3d_top](assets/demo/PCB_In2.Cu.png)

#### PCB In3.Cu

![3d_top](assets/demo/PCB_In3.Cu.png)

#### PCB In4.Cu

![3d_top](assets/demo/PCB_In4.Cu.png)

#### PCB In5.Cu

![3d_top](assets/demo/PCB_In5.Cu.png)

#### PCB In6.Cu

![3d_top](assets/demo/PCB_In6.Cu.png)

#### PCB B.Cu

![3d_top](assets/demo/PCB_B.Cu.png)

#### Dimension

![3d_top](assets/demo/dimension.png)

#### 3D Top

![3d_top](assets/demo/3d_top.png)

#### 3D Bot

![3d_bot](assets/demo/3d_bot.png)

### 5. Bill of Materials (BOM)

### 6. Gerber
