EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "N3B QO100 RX/TX Keyboard and TFT Display Interface"
Date ""
Rev "V1.0"
Comp "OH2UDS - WB2CBA"
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Switch:SW_Push SW1
U 1 1 66172D9B
P 7350 2200
F 0 "SW1" H 7350 2485 50  0000 C CNN
F 1 "KEY TX1" H 7350 2394 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 7350 2400 50  0001 C CNN
F 3 "~" H 7350 2400 50  0001 C CNN
	1    7350 2200
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW2
U 1 1 661738A9
P 7350 2850
F 0 "SW2" H 7350 3135 50  0000 C CNN
F 1 "KEY TX2" H 7350 3044 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 7350 3050 50  0001 C CNN
F 3 "~" H 7350 3050 50  0001 C CNN
	1    7350 2850
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW3
U 1 1 66173E00
P 7350 3550
F 0 "SW3" H 7350 3835 50  0000 C CNN
F 1 "KEY TX3" H 7350 3744 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 7350 3750 50  0001 C CNN
F 3 "~" H 7350 3750 50  0001 C CNN
	1    7350 3550
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW4
U 1 1 66174494
P 7350 4250
F 0 "SW4" H 7350 4535 50  0000 C CNN
F 1 "PTT" H 7350 4444 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 7350 4450 50  0001 C CNN
F 3 "~" H 7350 4450 50  0001 C CNN
	1    7350 4250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 2150 1550 2150
Wire Wire Line
	1900 2350 2100 2350
$Comp
L power:GNDPWR #PWR0101
U 1 1 661A4245
P 2350 2700
F 0 "#PWR0101" H 2350 2500 50  0001 C CNN
F 1 "GNDPWR" H 2354 2546 50  0000 C CNN
F 2 "" H 2350 2650 50  0001 C CNN
F 3 "" H 2350 2650 50  0001 C CNN
	1    2350 2700
	1    0    0    -1  
$EndComp
Wire Wire Line
	7550 4250 7900 4250
Wire Wire Line
	7550 3550 7900 3550
Wire Wire Line
	7550 2850 7900 2850
Wire Wire Line
	7550 2200 7900 2200
Wire Wire Line
	7150 2200 7150 2850
Wire Wire Line
	7150 2850 7150 3550
Connection ~ 7150 2850
Wire Wire Line
	7150 3550 7150 4250
Connection ~ 7150 3550
Text GLabel 7900 2200 2    50   Input ~ 0
KEYTX1
Text GLabel 7900 2850 2    50   Input ~ 0
KEYTX2
Text GLabel 7900 3550 2    50   Input ~ 0
KEYTX3
Text GLabel 7900 4250 2    50   Input ~ 0
PTT
Text GLabel 1550 2150 0    50   Input ~ 0
ROTX_A
Text GLabel 1900 2350 0    50   Input ~ 0
ROTX_B
Wire Wire Line
	2100 2250 2050 2250
Wire Wire Line
	2050 2250 2050 2700
$Comp
L Device:Rotary_Encoder_Switch SW5
U 1 1 661B53B7
P 2400 2250
F 0 "SW5" H 2400 2617 50  0000 C CNN
F 1 "TX Rotary" H 2400 2526 50  0000 C CNN
F 2 "Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm" H 2250 2410 50  0001 C CNN
F 3 "~" H 2400 2510 50  0001 C CNN
	1    2400 2250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2700 2350 2700 2700
Wire Wire Line
	2700 2700 2350 2700
Wire Wire Line
	2700 2150 2900 2150
Text GLabel 2900 2150 2    50   Input ~ 0
ROTX_SW
Connection ~ 2350 2700
Wire Wire Line
	2350 2700 2050 2700
$Comp
L dk_Barrel-Power-Connectors:PJ-102A J4
U 1 1 661BD186
P 2400 5800
F 0 "J4" H 2333 6025 50  0000 C CNN
F 1 "PJ-102A" H 2333 5934 50  0000 C CNN
F 2 "digikey-footprints:Barrel_Jack_5.5mmODx2.1mmID_PJ-102A" H 2600 6000 60  0001 L CNN
F 3 "https://www.cui.com/product/resource/digikeypdf/pj-102a.pdf" H 2600 6100 60  0001 L CNN
F 4 "CP-102A-ND" H 2600 6200 60  0001 L CNN "Digi-Key_PN"
F 5 "PJ-102A" H 2600 6300 60  0001 L CNN "MPN"
F 6 "Connectors, Interconnects" H 2600 6400 60  0001 L CNN "Category"
F 7 "Barrel - Power Connectors" H 2600 6500 60  0001 L CNN "Family"
F 8 "https://www.cui.com/product/resource/digikeypdf/pj-102a.pdf" H 2600 6600 60  0001 L CNN "DK_Datasheet_Link"
F 9 "/product-detail/en/cui-inc/PJ-102A/CP-102A-ND/275425" H 2600 6700 60  0001 L CNN "DK_Detail_Page"
F 10 "CONN PWR JACK 2X5.5MM SOLDER" H 2600 6800 60  0001 L CNN "Description"
F 11 "CUI Inc." H 2600 6900 60  0001 L CNN "Manufacturer"
F 12 "Active" H 2600 7000 60  0001 L CNN "Status"
	1    2400 5800
	1    0    0    -1  
$EndComp
Wire Wire Line
	2500 6000 2500 6400
Text Notes 1850 5900 0    50   ~ 0
DC 12V
$Comp
L power:+12V #PWR0112
U 1 1 661AECD0
P 2800 5800
F 0 "#PWR0112" H 2800 5650 50  0001 C CNN
F 1 "+12V" V 2815 5928 50  0000 L CNN
F 2 "" H 2800 5800 50  0001 C CNN
F 3 "" H 2800 5800 50  0001 C CNN
	1    2800 5800
	0    1    1    0   
$EndComp
$Comp
L power:GNDPWR #PWR0113
U 1 1 661AFA77
P 2500 6400
F 0 "#PWR0113" H 2500 6200 50  0001 C CNN
F 1 "GNDPWR" H 2504 6246 50  0000 C CNN
F 2 "" H 2500 6350 50  0001 C CNN
F 3 "" H 2500 6350 50  0001 C CNN
	1    2500 6400
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H1
U 1 1 661B0A86
P 1800 7350
F 0 "H1" H 1900 7399 50  0000 L CNN
F 1 "MountingHole_Pad" H 1900 7308 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 1800 7350 50  0001 C CNN
F 3 "~" H 1800 7350 50  0001 C CNN
	1    1800 7350
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H2
U 1 1 661B117D
P 2700 7300
F 0 "H2" H 2800 7349 50  0000 L CNN
F 1 "MountingHole_Pad" H 2800 7258 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 2700 7300 50  0001 C CNN
F 3 "~" H 2700 7300 50  0001 C CNN
	1    2700 7300
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H3
U 1 1 661B178B
P 3500 7300
F 0 "H3" H 3600 7349 50  0000 L CNN
F 1 "MountingHole_Pad" H 3600 7258 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 3500 7300 50  0001 C CNN
F 3 "~" H 3500 7300 50  0001 C CNN
	1    3500 7300
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H4
U 1 1 661B1AF8
P 4250 7250
F 0 "H4" H 4350 7299 50  0000 L CNN
F 1 "MountingHole_Pad" H 4350 7208 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 4250 7250 50  0001 C CNN
F 3 "~" H 4250 7250 50  0001 C CNN
	1    4250 7250
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0114
U 1 1 661B251F
P 1800 7450
F 0 "#PWR0114" H 1800 7250 50  0001 C CNN
F 1 "GNDPWR" H 1804 7296 50  0000 C CNN
F 2 "" H 1800 7400 50  0001 C CNN
F 3 "" H 1800 7400 50  0001 C CNN
	1    1800 7450
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0115
U 1 1 661B2F06
P 2700 7400
F 0 "#PWR0115" H 2700 7200 50  0001 C CNN
F 1 "GNDPWR" H 2704 7246 50  0000 C CNN
F 2 "" H 2700 7350 50  0001 C CNN
F 3 "" H 2700 7350 50  0001 C CNN
	1    2700 7400
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0116
U 1 1 661B39D8
P 3500 7400
F 0 "#PWR0116" H 3500 7200 50  0001 C CNN
F 1 "GNDPWR" H 3504 7246 50  0000 C CNN
F 2 "" H 3500 7350 50  0001 C CNN
F 3 "" H 3500 7350 50  0001 C CNN
	1    3500 7400
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0117
U 1 1 661B43F9
P 4250 7350
F 0 "#PWR0117" H 4250 7150 50  0001 C CNN
F 1 "GNDPWR" H 4254 7196 50  0000 C CNN
F 2 "" H 4250 7300 50  0001 C CNN
F 3 "" H 4250 7300 50  0001 C CNN
	1    4250 7350
	1    0    0    -1  
$EndComp
Wire Wire Line
	2500 5800 2800 5800
$Comp
L power:GNDPWR #PWR0118
U 1 1 661DC738
P 7150 4250
F 0 "#PWR0118" H 7150 4050 50  0001 C CNN
F 1 "GNDPWR" H 7154 4096 50  0000 C CNN
F 2 "" H 7150 4200 50  0001 C CNN
F 3 "" H 7150 4200 50  0001 C CNN
	1    7150 4250
	1    0    0    -1  
$EndComp
Connection ~ 7150 4250
Wire Wire Line
	2150 4300 1600 4300
Wire Wire Line
	1950 4500 2150 4500
$Comp
L power:GNDPWR #PWR0102
U 1 1 661FFA46
P 2400 4850
F 0 "#PWR0102" H 2400 4650 50  0001 C CNN
F 1 "GNDPWR" H 2404 4696 50  0000 C CNN
F 2 "" H 2400 4800 50  0001 C CNN
F 3 "" H 2400 4800 50  0001 C CNN
	1    2400 4850
	1    0    0    -1  
$EndComp
Text GLabel 1600 4300 0    50   Input ~ 0
ROTRX_A
Text GLabel 1950 4500 0    50   Input ~ 0
ROTRX_B
Wire Wire Line
	2150 4400 2100 4400
Wire Wire Line
	2100 4400 2100 4850
$Comp
L Device:Rotary_Encoder_Switch SW6
U 1 1 661FFA50
P 2450 4400
F 0 "SW6" H 2450 4767 50  0000 C CNN
F 1 "RX Rotary" H 2450 4676 50  0000 C CNN
F 2 "Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm" H 2300 4560 50  0001 C CNN
F 3 "~" H 2450 4660 50  0001 C CNN
	1    2450 4400
	1    0    0    -1  
$EndComp
Wire Wire Line
	2750 4500 2750 4850
Wire Wire Line
	2750 4850 2400 4850
Wire Wire Line
	2750 4300 2950 4300
Text GLabel 2950 4300 2    50   Input ~ 0
ROTRX_SW
Connection ~ 2400 4850
Wire Wire Line
	2400 4850 2100 4850
$Comp
L Switch:SW_Push SW7
U 1 1 662029CE
P 5400 2250
F 0 "SW7" H 5400 2535 50  0000 C CNN
F 1 "KEY RX1" H 5400 2444 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 5400 2450 50  0001 C CNN
F 3 "~" H 5400 2450 50  0001 C CNN
	1    5400 2250
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW8
U 1 1 662029D4
P 5400 2900
F 0 "SW8" H 5400 3185 50  0000 C CNN
F 1 "KEY RX2" H 5400 3094 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 5400 3100 50  0001 C CNN
F 3 "~" H 5400 3100 50  0001 C CNN
	1    5400 2900
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW9
U 1 1 662029DA
P 5400 3600
F 0 "SW9" H 5400 3885 50  0000 C CNN
F 1 "KEY RX3" H 5400 3794 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 5400 3800 50  0001 C CNN
F 3 "~" H 5400 3800 50  0001 C CNN
	1    5400 3600
	1    0    0    -1  
$EndComp
Wire Wire Line
	5600 3600 5950 3600
Wire Wire Line
	5600 2900 5950 2900
Wire Wire Line
	5600 2250 5950 2250
Wire Wire Line
	5200 2250 5200 2900
Wire Wire Line
	5200 2900 5200 3600
Connection ~ 5200 2900
Text GLabel 5950 2250 2    50   Input ~ 0
KEYRX1
Text GLabel 5950 2900 2    50   Input ~ 0
KEYRX2
Text GLabel 5950 3600 2    50   Input ~ 0
KEYRX3
$Comp
L power:GNDPWR #PWR0103
U 1 1 662029F3
P 5200 3600
F 0 "#PWR0103" H 5200 3400 50  0001 C CNN
F 1 "GNDPWR" H 5204 3446 50  0000 C CNN
F 2 "" H 5200 3550 50  0001 C CNN
F 3 "" H 5200 3550 50  0001 C CNN
	1    5200 3600
	1    0    0    -1  
$EndComp
Connection ~ 5200 3600
Text GLabel 10100 3050 2    50   Input ~ 0
RX_3.3V
Text GLabel 10100 2950 2    50   Input ~ 0
RX+5V
$Comp
L ILI9341:ILI9341 U1
U 1 1 6622144E
P 5300 5150
F 0 "U1" H 6178 4721 50  0000 L CNN
F 1 "ILI9341" H 6178 4630 50  0000 L CNN
F 2 "ILI9341_32:ILI9341_32" H 5300 5150 50  0001 C CNN
F 3 "" H 5300 5150 50  0001 C CNN
	1    5300 5150
	1    0    0    -1  
$EndComp
Text GLabel 3850 5700 0    50   Input ~ 0
ILI+5V
$Comp
L power:GNDPWR #PWR0107
U 1 1 66222A3E
P 4350 5350
F 0 "#PWR0107" H 4350 5150 50  0001 C CNN
F 1 "GNDPWR" H 4354 5196 50  0000 C CNN
F 2 "" H 4350 5300 50  0001 C CNN
F 3 "" H 4350 5300 50  0001 C CNN
	1    4350 5350
	1    0    0    -1  
$EndComp
Wire Wire Line
	5050 5100 4350 5100
Wire Wire Line
	4350 5100 4350 5350
Text GLabel 5050 5400 0    50   Input ~ 0
ILI_DC
Text GLabel 5050 5200 0    50   Input ~ 0
ILI_CS
Text GLabel 5050 5600 0    50   Input ~ 0
ILI_SCK
Text GLabel 5050 5300 0    50   Input ~ 0
ILI_RST
Text GLabel 5050 5500 0    50   Input ~ 0
ILI_MOSI
$Comp
L Device:R R1
U 1 1 6622575C
P 4150 5700
F 0 "R1" V 4100 5900 50  0000 C CNN
F 1 "560R" V 4200 6050 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 4080 5700 50  0001 C CNN
F 3 "~" H 4150 5700 50  0001 C CNN
	1    4150 5700
	0    1    1    0   
$EndComp
Wire Wire Line
	4300 5700 5050 5700
Wire Wire Line
	4000 5700 4000 5000
Wire Wire Line
	4000 5000 5050 5000
Wire Wire Line
	3850 5700 4000 5700
Connection ~ 4000 5700
$Comp
L Device:C C1
U 1 1 66228D74
P 4000 5850
F 0 "C1" H 4115 5896 50  0000 L CNN
F 1 "100nF" H 4115 5805 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm" H 4038 5700 50  0001 C CNN
F 3 "~" H 4000 5850 50  0001 C CNN
	1    4000 5850
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0109
U 1 1 66229716
P 4000 6000
F 0 "#PWR0109" H 4000 5800 50  0001 C CNN
F 1 "GNDPWR" H 4004 5846 50  0000 C CNN
F 2 "" H 4000 5950 50  0001 C CNN
F 3 "" H 4000 5950 50  0001 C CNN
	1    4000 6000
	1    0    0    -1  
$EndComp
Text GLabel 9050 3150 2    50   Input ~ 0
KEYTX1
Text GLabel 9050 3250 2    50   Input ~ 0
KEYTX2
Text GLabel 9050 3350 2    50   Input ~ 0
KEYTX3
Text GLabel 9050 3450 2    50   Input ~ 0
ROTX_A
Text GLabel 9050 3550 2    50   Input ~ 0
ROTX_B
Text GLabel 9050 3650 2    50   Input ~ 0
ROTX_SW
Text GLabel 9050 3750 2    50   Input ~ 0
PTT
$Comp
L power:GNDPWR #PWR0104
U 1 1 66216543
P 9050 4200
F 0 "#PWR0104" H 9050 4000 50  0001 C CNN
F 1 "GNDPWR" H 9054 4046 50  0000 C CNN
F 2 "" H 9050 4150 50  0001 C CNN
F 3 "" H 9050 4150 50  0001 C CNN
	1    9050 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	9050 4050 9050 4200
Text GLabel 10100 3150 2    50   Input ~ 0
MCU_SCL
Text GLabel 10100 3250 2    50   Input ~ 0
MCU_SDA
Text GLabel 10100 3350 2    50   Input ~ 0
TXUART_TX
Text GLabel 10100 3450 2    50   Input ~ 0
TXUART_RX
Text GLabel 9050 2750 2    50   Input ~ 0
RST_TX
Text GLabel 10100 3650 2    50   Input ~ 0
LCD_SCL
Text GLabel 10100 3750 2    50   Input ~ 0
LCD_SDA
$Comp
L power:GNDPWR #PWR0105
U 1 1 66216551
P 10100 4200
F 0 "#PWR0105" H 10100 4000 50  0001 C CNN
F 1 "GNDPWR" H 10104 4046 50  0000 C CNN
F 2 "" H 10100 4150 50  0001 C CNN
F 3 "" H 10100 4150 50  0001 C CNN
	1    10100 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	10100 4200 10100 4050
$Comp
L Connector:Conn_01x20_Male J1
U 1 1 66216558
P 8850 3050
F 0 "J1" H 8958 4131 50  0000 C CNN
F 1 "PATCH01" H 8958 4040 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical" H 8850 3050 50  0001 C CNN
F 3 "~" H 8850 3050 50  0001 C CNN
	1    8850 3050
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x20_Male J2
U 1 1 6621655E
P 9900 3050
F 0 "J2" H 10008 4131 50  0000 C CNN
F 1 "PATCH02" H 10008 4040 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical" H 9900 3050 50  0001 C CNN
F 3 "~" H 9900 3050 50  0001 C CNN
	1    9900 3050
	1    0    0    -1  
$EndComp
$Comp
L power:+12V #PWR0106
U 1 1 66216564
P 9050 2850
F 0 "#PWR0106" H 9050 2700 50  0001 C CNN
F 1 "+12V" V 9065 2978 50  0000 L CNN
F 2 "" H 9050 2850 50  0001 C CNN
F 3 "" H 9050 2850 50  0001 C CNN
	1    9050 2850
	0    1    1    0   
$EndComp
Wire Wire Line
	9050 3850 9050 3950
Wire Wire Line
	9050 4050 9050 3950
Connection ~ 9050 4050
Connection ~ 9050 3950
Wire Wire Line
	10100 4050 10100 3950
Connection ~ 10100 4050
Wire Wire Line
	10100 3950 10100 3850
Connection ~ 10100 3950
Text GLabel 9050 2150 2    50   Input ~ 0
ILI_DC
Text GLabel 9050 2250 2    50   Input ~ 0
ILI_CS
Text GLabel 9050 2350 2    50   Input ~ 0
ILI_MOSI
Text GLabel 9050 2450 2    50   Input ~ 0
ILI_SCK
Text GLabel 9050 2550 2    50   Input ~ 0
ILI_RST
Text GLabel 10100 2850 2    50   Input ~ 0
RX_UART_RX
Text GLabel 10100 2750 2    50   Input ~ 0
RX_UART_TX
Text GLabel 10100 3550 2    50   Input ~ 0
RST_RX
Text GLabel 9050 2650 2    50   Input ~ 0
ILI+5V
Text GLabel 9050 2950 2    50   Input ~ 0
TX+5V
Text GLabel 9050 3050 2    50   Input ~ 0
TX+3.3V
Text GLabel 10100 2550 2    50   Input ~ 0
KEYRX1
Text GLabel 10100 2450 2    50   Input ~ 0
KEYRX2
Text GLabel 10100 2350 2    50   Input ~ 0
KEYRX3
Text GLabel 10100 2650 2    50   Input ~ 0
ROTRX_SW
Text GLabel 10100 2250 2    50   Input ~ 0
ROTRX_A
Text GLabel 10100 2150 2    50   Input ~ 0
ROTRX_B
$EndSCHEMATC
