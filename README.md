# spice_sim
SPICE simulation files

Project naming conventions
==========================

Format: {project structure code}-{project name}

Project structure code:
  Audio Amplifiers - AA
  AAB - Audio Amplifier Buffer
    AABabc
    a - sign of the gain
      n - non-inverting
      i - inverting
  b - gain value
  c - number of channels

  AAT - Audio Tone control, analog
    AATab
    a - number of controls
    b - number of channels

  AAV - Audio Volume control
    AAVab
    a - number of controls
    b - type of control element
      p - potentiometer
      g - PGA IC

  AAD - Audio volume and/or Tone control, digital
    AADa
    a - number of channels

  AAP - Audio amplifier for Phones

Audio Power Amplifiers - PA
  PAA - Power Amplifier - class A
  PAB - Power Amplifier - class B
    PABabcd
    a - number of amplifying stages
    b - input stage type
      b - BJT single ended LTP
      B - BJT symmetrical LTP
      f - FET single ended LTP
      c - BJT single ended current feedback
      C - BJT symmetrical current feedback
      i - IC based input
    c - Voltage Amplifier stage (if present)
      b - non-symmetrical transimpedance stage
      B - symmetrical transimpedance stage
      d - differential transimpedance stage
      i - IC based transimpedance
    d - Type of output stage devices
      b - BJT
      h - HEXFET MOSFET
      l - lateral MOSFET
      i - IC based BJT
      I - IC based MOSFET
  PAH - Power Amplifier - class H
  PAG - Power Amplifier - class G
  PAD - Power Amplifier - class D
    PADab		
    a - Input stage type
      i - IC base input
    b - Type of output stage devices
      h - HEXFET MOSFET
      i - IC output


Power Amplifier Accessory - PC
  PCD - Power Amplifier DC offset compensation
    PCDa
    a - Type of compensation
      p - passive compensation, potentiometer
      a - active compensation
  PCO - Power Amplifier DC detector and protection
  PCP - Power Amplifier shortcircuit/SOA protection
  PCT - Power Amplifier Temperature protection
  PCC - Power Amplifier Clipping detector/protection
  PCM - Power Amplifier Mute facility
  PCZ - Power Amplifier Low Z at output detector
  PCV - Power Amplifier low power Voltage detector


Power Supplies - PS
  PSL - Power Supply, Linear
  PSW - Power Supply, switch


Library naming conventions
==========================

Short manufacturer names:
  TXN - Texas Instruments Inc.
  ADI - Analog Devices Inc.
  MXIM - Maxim Integrated Products
  BRCM - Broadcom Corp.
  ISIL - Intersil Corp.
  NSM - National Semicond. Corp.
  ONNN - ON Semicond. Corp.
  LLTC - Linear Technology Corp.
  QCOM - QUALCOMM Inc.
  ATML - Atmel Corp.
  STM - STMicroelectronics
  INTC - Intel Corp.
  NVDA - NVIDIA Corp.
  ATHR - Atheros Communications
  BRCM - Broadcom Corp.
  FCS - Fairchild Semicond.
  IRF - Intl. Rectifier Corp.
  NXPI - NXP Semicond.
  IFNNY - Infineon Tech. AG
  DIOD - Diodes Inc.
  VSH - Vishay Intertechnology
  AVX - AVX Corp.
  CNXT - Conexant Systems
  ZRAN - Zoran Corp.
  ALTR - Altera Corp.
  XLNX - Xilinx Inc.
  MCHP - Microchip Tech. Inc.
  CRUS - Cirrus Logic
  SLAB - Silicon Laboratories (SiLabs)
  TSE - Toshiba
  SANNY - Sanyo

Type of library components:
    BJT - Bipolar junction transistor
    IC - Integrated circuit
    D - Diode

