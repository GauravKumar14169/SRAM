# SRAM
This repository presents the design of SRAM implemented using eSim open source EDA tool.

# Table of Contents

- [Abstract](#Abstract)
- [Introduction](#Introduction)
- [6T Bit-cell](#6T-Bit-cell)
	- [Pre-rate circuit](#Pre-rate-circuit)
- [Tools Used](#Tools-Used)
	- [eSim](#eSim)
- [Schematics and Waveform](#Schematics-and-Waveform)
	- [Schematics](#Schematics)
	- [Waveform](#Waveform)
- [Author](#author)
- 
# Abstract
SRAM is a memory issue and is utilized in diverse VLSI chips because of its specific functionality to keep data. This memory cell has end up a topic of studies to satisfy the needs for destiny conversation systems.  In this  paper a  6T SRAM mobileular  is designed  via way of means of using  cadence virtuoso  EDA  device in  180nm CMOS technology. Its  overall performance traits such as  energy  dissipation,  postpone, and  energy  postpone product  are analysed. Power dissipation, postpone, and energy postpone made from the designed 6T SRAM cell


# INTRODUCTION
Static random access memory  (SRAM)  is a  static memory cell that is widely  used in various digital systems. It is quicker and consumes much less strength compared to different memory cells. It does now no longer require freshness periodically. Because of this, SRAM is the maximum famous reminiscence cell amongst VLSI designers. Hence non-stop evolution goes on for higher overall performance of SRAM cells. Due to this, distinct sorts of SRAM cells are to be had withinside the literature like 6T SRAM cell, 7T SRAM cell, 8T SRAM cell, 9T SRAM cell etc. Most, not unusual place SRAM cells utilized in the virtual gadget is the 6T SRAM cell. This cell can save a 1-little bit of data. The bit stays withinside the cell  as long as strength is supplied.  In this paper, design  and overall performance evaluation of a 6T SRAM cell  is discussed.  Performance evaluation is carried out by using  Cadence Virtuoso in  180nm  CMOS technology.

# 6T Bit-cell
6T Bit-cell is a usually used industrial well-known bit cell in SRAM cache memory layout. In order to very well apprehend the format layout of the 6T Bit-cell, it's far encouraged to recognize the examine and write operations of the 6T Bit-cell. With previous expertise of examine-write operations, you can still determine the widths of the 6 transistors withinside the 6T Bit-cell the smallest bit cell unit, which contributes to the full SRAM memory location at the chip. the 6T Bit-cell.

</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/88899069/170167154-4c566fab-7fc3-4497-ab2f-5e4675043f17.PNG'></br>
   fig.1: REFERENCE CIRCUIT 6T Bit-cell 
</p>

## Pre-rate circuit
Basically, pre-rate circuit shorts the Bit line and Bit line bar the use of one PMOS transistor on the middle and  ultimate PMOS transistors equalize each the bit lines to VDD.

</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/106176740/170168821-bebe27c9-d897-44ec-b855-f5547458bc46.PNG'></br>
   fig.2: REFERENCE Pre-rate circuit
</p>
# Tools Used:

## eSim:
[eSim](https://esim.fossee.in/home) is a CAD tool that helps electronic system designers to design, test and analyse their circuits. But the important feature of this  tool is that it is open source and hence the user can modify the source as per his/her need. The software provides a generic, modular and extensible platform for experiment with electronic circuits. This software runs on all Ubuntu Linux distributions and some flavours of Windows. It uses Python, KiCad and Ngspice.
  The objective behind the development of eSim is to provide an open source EDA solution for electronics and electrical engineers. The software should be capable of performing schematic creation, PCB design and circuit simulation (analog, digital and mixed signal). It should provide facilities to create new models and components. The architecture of eSim has been designed by keeping these objectives in mind.

</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/90523478/156241968-207d738d-9245-4e82-b101-2c957cfb3b17.png"></br>
  Fig.3: eSim open source EDA tool
</p>


# Schematics and Waveform:

## Schematics:
The schematic diagram  of the  designed 6T  SRAM cell. The  6T SRAM  cell  is designed by using eSim EDA tool in 180nm CMOS technology.
</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/106176740/170229855-d52d808a-d43e-4129-b553-c7e2a569ba0d.PNG'></br>
   fig.4: 6T SRAM
</p>

## Waveform
The transient waveform of the designed 6T SRAM cell for wordline, Bitline, y0 and y1. The performance characteristics such as power dissipation, delay, and power delay product of the designed 6T SRAM cell in 180nm CMOS technology at power supply voltage (VDD) of 1.8V. 

</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/106176740/170233030-9d233a28-eb57-42e5-8320-8fa0600625e6.PNG'></br>
   fig.5: 6T SRAM waveform
</p>

</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/106176740/170232658-222541b3-8c9f-4204-b92a-1ba4f4c882c3.PNG'></br>
   fig.6: 6T SRAM waveform
</p>

</p>
<p align="center">
  <img src='https://user-images.githubusercontent.com/106176740/170233185-85b0bd0b-a5bd-43a2-a408-caf485ff5f4b.PNG'></br>
   fig.7: 6T SRAM waveform
</p>

A 6T SRAM cell is designed and its performance characteristics such as power, delay, and power delay product are analysed in 180nm CMOS technology power dissipation, delay, and power delay product of the designed 6T SRAM cell. The bodily verification of all of the schematic drawn is executed and glued all violations. The 6T Bit cell format become designed with minimal and with none DRC violations. Bit cell location performed a totally critical function in determining the full SARM Core array location and SRAM memory density.

# Author:
• Gaurav kumar, B.Tech(ECE), Dronacharya Group of Institutions, Greater Nodia, Uttar Pradesh.
