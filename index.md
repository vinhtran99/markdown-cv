---
layout: cv
title: 
---
# Vinh Tran
Curriculum Vitae

<div id="webaddress">
<a href="mailto:thevinh130799@gmail.com">Email</a>
| <a href="https://www.linkedin.com/in/vinh-tran-5b83ab178/">LinkedIn</a>
  | <a href="https://github.com/vinhtran99">Github</a>
</div>


## About me

I am a student seeking a job opportunity as a software engineer. Having programming for 3+ years, with a wide range of knowledge, I am pretty confident with my skills. As a person with huge curiosity I always eager to learn new things and latest technologies. When working on softwares, I care about clean code and good practices. And I am not afraid to face new problems because I love to tackle them everyday. 

I used to practice programming on leetcode-style problems at Codeforces.com (__[my profile](https://codeforces.com/profile/the-vinh)__). In my spare time I read about various computer topics, playing with <a href="https://en.wikipedia.org/wiki/Amiga_500">old hardware</a> and contributing to Wikipedia.

## Skills and knowledge

__Proficient__

ANSI C, Java (SE), Microcontrollers (programming in bare metal C with AVR, ARM, ESP), Circuit board design, Software development skills (version control, agile, testing, etc.)

__Intermediate__

Python, C++ 17, C# (.NET), Linux, Electronics, Networking

__Beginner__

VHDL, Rust, Javascript, bash, Concurrency, Signal processing, Web development (plain Java, or with Spring)


## Education

`2014-2017`
__Luong The Vinh High School for the gifted__

Major in Mathematics

`2017-2021`
__Vaasan ammattikorkeakoulu__

Bachelor of Enginnering, with major in Embedded Systems, minor in Software Engineering

## Projects

`2018`
__Live sound chart__

Application development course project. System originally runs on a Raspberry Pi, but actually on any system runs Linux. Connect a USB sound card, and run the program. See the sound levels live inside your terminal or inside browser.

Sound is recorded to a .wav file, the program extracts sound levels from it and displays inside the terminal using VT100 escape sequences. When enabled, it also sends the data to the school web server with PHP for rendering. Whole program is done in C and relied on single third party library *libcurl*. 

I learn quite a lot from this project: network configuration on Linux, device setup (USB mic) from command line, gnu make, git, program organization, file handling

`2018`
__Snake in terminal__

Play the classic game in any terminal emulator that supports VT100. 

I implement the snake as a linked-list to ease moving the snake as well as adding length. Game elements displayed in the terminal as block characters and their movement using escape sequences. To read keypress I use POSIX calls and raw terminal objects. I also made another version for Windows console.

This is the project that helped me learn more about C (especially pointers) and simple data structures.

`2019`
__Energy usage charting__

Object oriented programming course project. A GUI program allowing read/write/edit and viewing the amount of energy used in months as barcharts. 

The data contains pairs of (key, value) where key is the month and value is the amount of energy consumed in that month. These pairs are kept in text files in human-readable format. The program has all features of a basic GUI program: menu, input checking, dialog boxes for warnings, etc. The difficult part is events and exceptions handling, all written in Java code without a GUI creator. 

`2020`
__Intrusion detection__ 

The system is to manage the property monitoring and control. The device can be used as an anti-crime device, home appliances and can be installed at the buildings’ entrance or other places that require motion monitoring. The system can be used to detect motion at the maximum range of 5 meters, beam angle of 100 degrees, movement speed from 0.8 to 1.2m/s and target size of 700mm x 250mm. 

Hardware: STM32 Nucleo board will be the central unit to receive data that was read by the sensor. The data will then be converted in XBEE data frame format and sent to the server. On the receiver side, a Raspberry Pi as a central unit, connected with another XBEE module handling on receiving the data. Received data then can be processed as desired.

`2020`
__Home automation system__ 

A group project (5 people). Aim is to develop and build a secure and scale-able property control and monitoring system. System is meant to be used for property caretakers, homeowners and for anyone who have multiple separate locations to control remotely.

Role: Hardware developer. I develop the custom electronics which handling the transmission systems between the wireless sensors and the ESP32 and test the software with ESPHome integrated in Home Assistant


<!-- ### Footer

Last updated: May 2013 -->


