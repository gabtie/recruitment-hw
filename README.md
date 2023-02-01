# Recruitment for E-Agle TRT (HW)

Welcome to the recruitment _test_ for the electronics team at E-Agle TRT.

This _test_ is meant to give us the possibility to have a first understanding of the capabilities of our applicants without the them having the pressure of seeing it as an exam.

Moreover it's studied so that the applicants get a first taste of the tools used so that once in the team they can get up and running quickly into the team workflow without having to learn stuff under pressure when it's needed.

## What we'll look into

 - Understanding of basic electronics
 - Components choice and their suitability
 - KiCad
   - Schematic choices, tidyness and good practices
   - Board layout understanding and, again, good practices
 - `git` usage: fork, branch, clone, commit, push, pull
 - Not only _tecnical correctness_ but we'll also evaluate actual usability.

## Assignment

Develop an overtemperature and overcurrent monitoring system (**monitor**) to perform plauysibility checks of a secondary system (**load**).

The **monitor** has the following specs:
- Supplied by an unstable DC voltage line, ranging from 9V to 17V
- Has a normally open relay connected in series with the load
- Has a hall effect sensor that measures the current througuh the load

The **load** has the following specs:
- Voltage range: 24V - 48V
- Current range: -3A - 25A

The **monitor** must check the power supplied to the **load** and must ensure that the relay is open if the power is above 500W.
Once open, it must not be possible to close the relay unless the system is power cycled.

## COMPONENTS CONTRAIN

- No programmable circuits are allowed.
- The Hall effect based sensor can be choosen from the Allegro ACS781xLR family of devices. Other sensors may be suitable as long as they comply with the specs.

Below you can find a general diagram of the system
<img src=".\general diagram.png" width="400">



 - In the schematic use also a hierarchical sheet
   - _It's not a good practice for this small of a project but it's for letting you learn about hierarchy without the hassle of a more complex assignment_

 - Add comments for the necessary calculations of values

 - Consider JLC PCB as the board manufacturer

## Instructions

 - Create a repository on your GitHub account and copy this project in it. **Do not clone this repository!**
 - Branch the master into one called `name_surname` where the work will be done
 - Commit your progress along the way. **Do not commit just the finished project**, use Git for what it's made for!
 - When you are done, generate the schematic output inside `docs/` and the production (gerber) files in `output/`
 - If you haven't already, submit your application form [here](https://eagletrt.it/apply)
 - If you have any questions feel free to contact us at [electronics@eagletrt.it](mailto:electronics@eagletrt.it)
 - Feel free to also come to our lab (Povo 2 floor -2) if we are slow at replying
 - You have **2 weeks** (14 days) to work on this project (**we evaluate if you meet deadlines**)
