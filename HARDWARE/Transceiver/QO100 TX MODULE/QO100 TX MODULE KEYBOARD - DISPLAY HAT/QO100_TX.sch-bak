EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "N3B QO100 TX Keyboard Display Interface"
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
P 2050 3700
F 0 "SW1" H 2050 3985 50  0000 C CNN
F 1 "KEY 1" H 2050 3894 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 2050 3900 50  0001 C CNN
F 3 "~" H 2050 3900 50  0001 C CNN
	1    2050 3700
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW2
U 1 1 661738A9
P 2050 4350
F 0 "SW2" H 2050 4635 50  0000 C CNN
F 1 "KEY 2" H 2050 4544 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 2050 4550 50  0001 C CNN
F 3 "~" H 2050 4550 50  0001 C CNN
	1    2050 4350
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW3
U 1 1 66173E00
P 2050 5050
F 0 "SW3" H 2050 5335 50  0000 C CNN
F 1 "KEY 3" H 2050 5244 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 2050 5250 50  0001 C CNN
F 3 "~" H 2050 5250 50  0001 C CNN
	1    2050 5050
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push SW4
U 1 1 66174494
P 2050 5750
F 0 "SW4" H 2050 6035 50  0000 C CNN
F 1 "PTT" H 2050 5944 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm" H 2050 5950 50  0001 C CNN
F 3 "~" H 2050 5950 50  0001 C CNN
	1    2050 5750
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
	2250 5750 2600 5750
Wire Wire Line
	2250 5050 2600 5050
Wire Wire Line
	2250 4350 2600 4350
Wire Wire Line
	2250 3700 2600 3700
Wire Wire Line
	1850 3700 1850 4350
Wire Wire Line
	1850 4350 1850 5050
Connection ~ 1850 4350
Wire Wire Line
	1850 5050 1850 5750
Connection ~ 1850 5050
Text GLabel 2600 3700 2    50   Input ~ 0
KEY1
Text GLabel 2600 4350 2    50   Input ~ 0
KEY2
Text GLabel 2600 5050 2    50   Input ~ 0
KEY3
Text GLabel 2600 5750 2    50   Input ~ 0
PTT
Text GLabel 1550 2150 0    50   Input ~ 0
ROT_A
Text GLabel 1900 2350 0    50   Input ~ 0
ROT_B
Wire Wire Line
	2100 2250 2050 2250
Wire Wire Line
	2050 2250 2050 2700
$Comp
L Device:Rotary_Encoder_Switch SW5
U 1 1 661B53B7
P 2400 2250
F 0 "SW5" H 2400 2617 50  0000 C CNN
F 1 "Rotary_Encoder_Switch" H 2400 2526 50  0000 C CNN
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
ROT_SW
$Comp
L Connector:Conn_01x04_Male J3
U 1 1 6619FBCD
P 6750 3550
F 0 "J3" H 6858 3831 50  0000 C CNN
F 1 "I2C LCD" H 6858 3740 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical" H 6750 3550 50  0001 C CNN
F 3 "~" H 6750 3550 50  0001 C CNN
	1    6750 3550
	1    0    0    -1  
$EndComp
Text GLabel 6950 3450 2    50   Input ~ 0
LCD_SCL
Text GLabel 6950 3550 2    50   Input ~ 0
LCD_SDA
$Comp
L power:+5V #PWR0102
U 1 1 661A10AA
P 6950 3650
F 0 "#PWR0102" H 6950 3500 50  0001 C CNN
F 1 "+5V" V 6965 3778 50  0000 L CNN
F 2 "" H 6950 3650 50  0001 C CNN
F 3 "" H 6950 3650 50  0001 C CNN
	1    6950 3650
	0    1    1    0   
$EndComp
$Comp
L power:GNDPWR #PWR0103
U 1 1 661A1B37
P 6950 4000
F 0 "#PWR0103" H 6950 3800 50  0001 C CNN
F 1 "GNDPWR" H 6954 3846 50  0000 C CNN
F 2 "" H 6950 3950 50  0001 C CNN
F 3 "" H 6950 3950 50  0001 C CNN
	1    6950 4000
	1    0    0    -1  
$EndComp
Wire Wire Line
	6950 3750 6950 4000
Connection ~ 2350 2700
Wire Wire Line
	2350 2700 2050 2700
Text GLabel 8500 3800 2    50   Input ~ 0
KEY1
Text GLabel 8500 3900 2    50   Input ~ 0
KEY2
Text GLabel 8500 4000 2    50   Input ~ 0
KEY3
Text GLabel 8500 4100 2    50   Input ~ 0
ROT_A
Text GLabel 8500 4200 2    50   Input ~ 0
ROT_B
Text GLabel 8500 4300 2    50   Input ~ 0
ROT_SW
Text GLabel 8500 4400 2    50   Input ~ 0
PTT
$Comp
L power:GNDPWR #PWR0104
U 1 1 661AECDE
P 8500 4850
F 0 "#PWR0104" H 8500 4650 50  0001 C CNN
F 1 "GNDPWR" H 8504 4696 50  0000 C CNN
F 2 "" H 8500 4800 50  0001 C CNN
F 3 "" H 8500 4800 50  0001 C CNN
	1    8500 4850
	1    0    0    -1  
$EndComp
Wire Wire Line
	8500 4700 8500 4850
Text GLabel 9550 3800 2    50   Input ~ 0
MCU_SCL
Text GLabel 9550 3900 2    50   Input ~ 0
MCU_SDA
Text GLabel 9550 4000 2    50   Input ~ 0
UART_TX
Text GLabel 9550 4100 2    50   Input ~ 0
UART_RX
Text GLabel 9550 4200 2    50   Input ~ 0
RST
Text GLabel 9550 4300 2    50   Input ~ 0
LCD_SCL
Text GLabel 9550 4400 2    50   Input ~ 0
LCD_SDA
$Comp
L power:GNDPWR #PWR0105
U 1 1 661AECEC
P 9550 4850
F 0 "#PWR0105" H 9550 4650 50  0001 C CNN
F 1 "GNDPWR" H 9554 4696 50  0000 C CNN
F 2 "" H 9550 4800 50  0001 C CNN
F 3 "" H 9550 4800 50  0001 C CNN
	1    9550 4850
	1    0    0    -1  
$EndComp
Wire Wire Line
	9550 4850 9550 4700
$Comp
L Connector:Conn_01x20_Male J1
U 1 1 661AECF3
P 8300 3700
F 0 "J1" H 8408 4781 50  0000 C CNN
F 1 "PATCH01" H 8408 4690 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical" H 8300 3700 50  0001 C CNN
F 3 "~" H 8300 3700 50  0001 C CNN
	1    8300 3700
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x20_Male J2
U 1 1 661AECF9
P 9350 3700
F 0 "J2" H 9458 4781 50  0000 C CNN
F 1 "PATCH02" H 9458 4690 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical" H 9350 3700 50  0001 C CNN
F 3 "~" H 9350 3700 50  0001 C CNN
	1    9350 3700
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR0106
U 1 1 661AECFF
P 8500 3700
F 0 "#PWR0106" H 8500 3550 50  0001 C CNN
F 1 "+3.3V" V 8515 3828 50  0000 L CNN
F 2 "" H 8500 3700 50  0001 C CNN
F 3 "" H 8500 3700 50  0001 C CNN
	1    8500 3700
	0    1    1    0   
$EndComp
$Comp
L power:+5V #PWR0107
U 1 1 661AED05
P 8500 3600
F 0 "#PWR0107" H 8500 3450 50  0001 C CNN
F 1 "+5V" V 8515 3728 50  0000 L CNN
F 2 "" H 8500 3600 50  0001 C CNN
F 3 "" H 8500 3600 50  0001 C CNN
	1    8500 3600
	0    1    1    0   
$EndComp
$Comp
L power:+12V #PWR0108
U 1 1 661AED0B
P 8500 3500
F 0 "#PWR0108" H 8500 3350 50  0001 C CNN
F 1 "+12V" V 8515 3628 50  0000 L CNN
F 2 "" H 8500 3500 50  0001 C CNN
F 3 "" H 8500 3500 50  0001 C CNN
	1    8500 3500
	0    1    1    0   
$EndComp
Wire Wire Line
	8500 4500 8500 4600
Wire Wire Line
	8500 4700 8500 4600
Connection ~ 8500 4700
Connection ~ 8500 4600
Wire Wire Line
	9550 4700 9550 4600
Connection ~ 9550 4700
Wire Wire Line
	9550 4600 9550 4500
Connection ~ 9550 4600
$Comp
L dk_Barrel-Power-Connectors:PJ-102A J4
U 1 1 661BD186
P 4200 5150
F 0 "J4" H 4133 5375 50  0000 C CNN
F 1 "PJ-102A" H 4133 5284 50  0000 C CNN
F 2 "digikey-footprints:Barrel_Jack_5.5mmODx2.1mmID_PJ-102A" H 4400 5350 60  0001 L CNN
F 3 "https://www.cui.com/product/resource/digikeypdf/pj-102a.pdf" H 4400 5450 60  0001 L CNN
F 4 "CP-102A-ND" H 4400 5550 60  0001 L CNN "Digi-Key_PN"
F 5 "PJ-102A" H 4400 5650 60  0001 L CNN "MPN"
F 6 "Connectors, Interconnects" H 4400 5750 60  0001 L CNN "Category"
F 7 "Barrel - Power Connectors" H 4400 5850 60  0001 L CNN "Family"
F 8 "https://www.cui.com/product/resource/digikeypdf/pj-102a.pdf" H 4400 5950 60  0001 L CNN "DK_Datasheet_Link"
F 9 "/product-detail/en/cui-inc/PJ-102A/CP-102A-ND/275425" H 4400 6050 60  0001 L CNN "DK_Detail_Page"
F 10 "CONN PWR JACK 2X5.5MM SOLDER" H 4400 6150 60  0001 L CNN "Description"
F 11 "CUI Inc." H 4400 6250 60  0001 L CNN "Manufacturer"
F 12 "Active" H 4400 6350 60  0001 L CNN "Status"
	1    4200 5150
	1    0    0    -1  
$EndComp
Wire Wire Line
	4300 5350 4300 5750
Text Notes 3650 5250 0    50   ~ 0
DC 12V
$Comp
L power:+12V #PWR0112
U 1 1 661AECD0
P 4600 5150
F 0 "#PWR0112" H 4600 5000 50  0001 C CNN
F 1 "+12V" V 4615 5278 50  0000 L CNN
F 2 "" H 4600 5150 50  0001 C CNN
F 3 "" H 4600 5150 50  0001 C CNN
	1    4600 5150
	0    1    1    0   
$EndComp
$Comp
L power:GNDPWR #PWR0113
U 1 1 661AFA77
P 4300 5750
F 0 "#PWR0113" H 4300 5550 50  0001 C CNN
F 1 "GNDPWR" H 4304 5596 50  0000 C CNN
F 2 "" H 4300 5700 50  0001 C CNN
F 3 "" H 4300 5700 50  0001 C CNN
	1    4300 5750
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H1
U 1 1 661B0A86
P 6200 5650
F 0 "H1" H 6300 5699 50  0000 L CNN
F 1 "MountingHole_Pad" H 6300 5608 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 6200 5650 50  0001 C CNN
F 3 "~" H 6200 5650 50  0001 C CNN
	1    6200 5650
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H2
U 1 1 661B117D
P 7100 5600
F 0 "H2" H 7200 5649 50  0000 L CNN
F 1 "MountingHole_Pad" H 7200 5558 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 7100 5600 50  0001 C CNN
F 3 "~" H 7100 5600 50  0001 C CNN
	1    7100 5600
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H3
U 1 1 661B178B
P 7900 5600
F 0 "H3" H 8000 5649 50  0000 L CNN
F 1 "MountingHole_Pad" H 8000 5558 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 7900 5600 50  0001 C CNN
F 3 "~" H 7900 5600 50  0001 C CNN
	1    7900 5600
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole_Pad H4
U 1 1 661B1AF8
P 8650 5550
F 0 "H4" H 8750 5599 50  0000 L CNN
F 1 "MountingHole_Pad" H 8750 5508 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3_DIN965_Pad" H 8650 5550 50  0001 C CNN
F 3 "~" H 8650 5550 50  0001 C CNN
	1    8650 5550
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0114
U 1 1 661B251F
P 6200 5750
F 0 "#PWR0114" H 6200 5550 50  0001 C CNN
F 1 "GNDPWR" H 6204 5596 50  0000 C CNN
F 2 "" H 6200 5700 50  0001 C CNN
F 3 "" H 6200 5700 50  0001 C CNN
	1    6200 5750
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0115
U 1 1 661B2F06
P 7100 5700
F 0 "#PWR0115" H 7100 5500 50  0001 C CNN
F 1 "GNDPWR" H 7104 5546 50  0000 C CNN
F 2 "" H 7100 5650 50  0001 C CNN
F 3 "" H 7100 5650 50  0001 C CNN
	1    7100 5700
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0116
U 1 1 661B39D8
P 7900 5700
F 0 "#PWR0116" H 7900 5500 50  0001 C CNN
F 1 "GNDPWR" H 7904 5546 50  0000 C CNN
F 2 "" H 7900 5650 50  0001 C CNN
F 3 "" H 7900 5650 50  0001 C CNN
	1    7900 5700
	1    0    0    -1  
$EndComp
$Comp
L power:GNDPWR #PWR0117
U 1 1 661B43F9
P 8650 5650
F 0 "#PWR0117" H 8650 5450 50  0001 C CNN
F 1 "GNDPWR" H 8654 5496 50  0000 C CNN
F 2 "" H 8650 5600 50  0001 C CNN
F 3 "" H 8650 5600 50  0001 C CNN
	1    8650 5650
	1    0    0    -1  
$EndComp
Wire Wire Line
	4300 5150 4600 5150
$Comp
L power:GNDPWR #PWR0118
U 1 1 661DC738
P 1850 5750
F 0 "#PWR0118" H 1850 5550 50  0001 C CNN
F 1 "GNDPWR" H 1854 5596 50  0000 C CNN
F 2 "" H 1850 5700 50  0001 C CNN
F 3 "" H 1850 5700 50  0001 C CNN
	1    1850 5750
	1    0    0    -1  
$EndComp
Connection ~ 1850 5750
$EndSCHEMATC
