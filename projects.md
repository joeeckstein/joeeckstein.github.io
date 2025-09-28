---
layout: default
title: Projects
permalink: /projects/
redirect_from: "/projects"
last_modified_at: 2020-12-26
group: "navigation"
---

# Projects

## Universal Orlando - Mega Movie Parade

I was the lead Controls Engineer for TAIT's drive and S7-1500 ProfiSAFE supervisory system for the Mega Movie Parade.

## Wynn Las Vegas - Awakening

I was the lead Controls Engineer for TAIT's contributons to Wynn Las Vegas's Awakening.

<div class="vidcontainer">
<iframe src="https://www.youtube.com/embed/qg7lTmIAZ78?rel=0&modestbranding=1&fs=1" allowfullscreen class="video"></iframe>
</div>

A visual feast of performers, puppets, and props, Awakening at Wynn Las Vegas requires pinpoint machinery automation to enable the complex behind-the-scenes choreography and myriad audience-facing cues. TAIT had been successfully automating the iconic Le Reve show at the Wynn for the past 20 years, and with their proprietary TAIT Navigator Automation Platform providing all motion control and safety supervisory operations for its’ spectacular, Awakening Las Vegas show. [Read More on TAIT's Website](https://www.taittowers.com/work/wynn-awakening-las-vegas)

## Celebrity Cruises - Apex - Oculus Theater LED Wall

I was a member of the TAIT Integration team working on the Celebrity Apex LED Wall installation and commissioning. I focused on the anti-collision and safety function development on the Siemens S7-1500 safety PLC to protect both cast members and the machinery.

<img src="/assets/img/cecl_apex_LED_install_joe.jpg" alt="CECL Apex LED Wall Install Controls Work" width="49%">
<img src="/assets/img/cecl_apex_LED_install_wide.jpg" alt="CECL Apex LED Wall Install Wide Shot" width="49%">

> Celebrity Cruises imagined a ship’s theater that pushed the boundaries of live entertainment, capable of awe-inspiring performances and near-limitless creative possibilities. Celebrity Cruises came to TAIT to deliver on its vision for its new EDGE-class ship, Celebrity Apex.  With a perfect view from any seat, The Theater introduces all-new production shows and programming exclusive to Celebrity Apex and brought to life through state-of-the-art technology designed, engineered, and built by TAIT. A new 20-foot-tall 4K LED screen comprised of 17 million pixels curves 110 feet around the stage to immerse you like never before. A translucent, 360-degree circular scrim features eight 21K laser projectors for breathtaking wrap-around imagery and effects..

[Read More at TAIT's Website](https://www.taittowers.com/work/celebrity-apex)

<div class="vidcontainer">
<iframe src="https://www.youtube.com/embed/uPOXpqioZAY?rel=0&modestbranding=1&fs=1" allowfullscreen class="video"></iframe>  
</div>  
  
<div class="vidcontainer">
<iframe src="https://www.youtube.com/embed/AaZbgxzEg7M?rel=0&modestbranding=1&fs=1" allowfullscreen class="video"></iframe>  
</div>  
  
## Celine Dion - Courage World Tour

I was a member of the TAIT Integration team working on Celine Dion's Courage World Tour, working on the new TAIT Mod Lifts and a TAIT Nanowinch based lighting effect.

> After spending the last few years at her Las Vegas Residency in Caesar’s Palace, Celine Dion launched her 14th World Tour with another extraordinary set designed by an incomparable production team. For the Courage World Tour, TAIT engineered and manufactured an automated mainstage featuring a modular lift system equipped with 20 custom-built TAIT Mod Lifts.
> TAIT Mod Lifts are modular, high capacity lifts that are easy to use and almost infinitely configurable. Each Mod Lift is a 42 in. square and can lift a payload capacity of 2,000 lbs. at 1 ft. per second. They are engineered at that capacity with a 10:1 safety factor to ensure the safety of performers and reduces the risk of failure to nearly impossible.

<!-- [Read More at TAIT's Website](https://www.taittowers.com/portfolio/celine-dions-custom-built-modular-lift-system-for-the-courage-world-tour/) -->
<div class="vidcontainer">
<iframe src="https://www.youtube.com/embed/SCesxVYtjFo?rel=0&modestbranding=1&fs=1" allowfullscreen class="video"></iframe>  
</div>

<!-- ## Princess Cruises - Sea Princess - Princess Theater Controls Upgrade

I was a member of the TAIT integration team upgrading the existing automation control equipment to TAIT Navigator control and Siemens S120 series drives. This upgrade was performed during a voyage with significant coordination with the ship's entertainment staff to allow the theater to continue to operate during the upgrade. -->

## Window Fan Controller

Designed and built an Arduino based system to regulate the temperature of a room using a windows fan by comparing the indoor, outdoor, and desired temperatures.  The system would determine if it would be favorable to run the window fan, or if it would just push hot air inside. It also had built in over cycling detection to prevent small fluctuations in temperature from causing the system to rapidly turn the fan off and on.
[Read More...](https://github.com/joeeckstein/Thermostat)  

## Inkjet Printed Transistor

Worked under Dr. Tina Smilkstein with Nick Kaperilian and Neil Lamon to research the possibility of utilizing a Fujifilm Dimatix inkjet materials printer to produce an inkjet printed transistor. We ran into production issues that prevented the creation of functional transistors.
[Read Abstract and Report...](/projects/senior_project)

## Keysight ADS (Advanced Design Suite) Low-Pass Filter Design

Using Keysight's ADS I designed a 1GHz microstrip low pass filter before having it CNC milled. I then verified that the physical design met the specified performance for the filter. I designed an FM receiver and transmitter pair utilizing the ADS designed microstrip low pass filter, an audio amplifier, and AH1 RF Amplifier to transmit audio across an 800MHz channel.  
[Read More...](./assets/doc/projects/ADS_LPF.pdf)

## Remote Lux Meter

Designed and breadboarded a remote lux meter that utilized a current controlled oscillator to transmit an amplitude shift keyed ultrasonic signal from the sensing and transmission module to the receiver unit. The receiving module then provided a square wave output to an Arduino Uno which decoded the frequency of the signal and displayed the luminosity in foot-candles and the photodiode current on the onboard display.  
[Read More...](./assets/doc/projects/Remote_Lux_Meter.pdf)

## Scheduled Fish Feeder

As part of the CPE 329 Microcontrollers device was built to allow a user to select up to three times per day to feed a fish based upon the Texas Instruments MSP432 Launchpad platform. The onboard Real Time Clock functions were utilized to allow the microcontroller to be placed into a low power state and only wake up during required feeding times, to redraw the on-screen clock, or when a user requested the configuration menu. A user could view the last time that the fish was fed and manually feed the fish from the onboard control panel. Fish food dispensing was accomplished via a servo motor.
[Read More...](./assets/doc/projects/Fish_Feeder.pdf)

## Digital Design CPU (CPE 233 RAT CPU)

Based off of the RAT architecture as designed by Professor Brian Mealy, myself and a group of students designed a CPU which could execute assembly programs and drive a VGA display. Hardware design was completed in VHDL using the Vivado Design Suite for the Basys3 development board. As the final part of the project a Connect4 game board was designed and implemented using Assembly and a custom VHDL graphics decoding module. The source code for the project is available [here](https://github.com/joeeckstein/RAT-Connect4).

## iFixit Technical Writing Project

The iFixit Technical Writing Project's mission was to create an iFixit.com entry for the Ryobi P202 drill. This included both a repair guide and troubleshooting guide available at: [https://www.ifixit.com/Device/Ryobi_P202](https://www.ifixit.com/Device/Ryobi_P202). In a group of five people we divided writing, photography, and coordination of materials. In addition to the repair and troubleshooting guides, the project facilitated the creation of many other documents under the technical writing umbrella such as a project proposals, status reports, and group evaluations. This project also used wiki-syntax and was extensively peer reviewed for clarity and conciseness.

## IME 156 Power Supply Project

The IME 156 Introduction to Electronics Manufacturing course consists of a lecture and a lab detailing the creation of PCBs and semiconductors. The lab component of the class is largely focused on building skills such as: the use of CAD tools such as DipTrace, and fabrication techniques including PCB fabrication, soldering, crimping, and shop safety. The final project of the IME 156 lab is the creation of a dual voltage variable power supply based off of a pre-created design. While learning about the various mechanized and automatic manufacturing techniques of electronics, we learned about the skills to manually design printed circuit boards and integrate them. This class also was an introduction to designing for manufacturability.

<!-- ## Creative Poetry Reading

As part of the Senior Poetry Unit I created a creative reading of a poem of my choice. This video is contains video, still images, and time lapses. The majority of the content was captured with a Canon T3i.  
<div class="vidcontainer">
<iframe src="https://www.youtube.com/embed/B-JRbodfefw?rel=0&modestbranding=1&fs=0" class="video"></iframe>
</div>
   -->
