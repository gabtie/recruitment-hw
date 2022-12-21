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

Develop a DCDC converter with power monitoring:

 - Input voltage range: 11V-27V
 - Two outputs of:
   - 5V3A
   - 3.3V0.5A
 - Monitor the input current with a shunt
    - Blink a LED, driven by a transistor, at a frequency between 3-5 Hz when the power at the input is greater than 10W
    - The LED should be off when power is below 3W
    - Use non programmable circuits
    
<img src="https://user-images.githubusercontent.com/64556568/200391668-f1a20344-d1ed-48c2-b3f5-f6b0fa3b0dc5.jpg" width="513">

 - In the schematic use also a hierarchical sheet
   - _It's not a good practice for this small of a project but it's for letting you learn about hierarchy without the hassle of a more complex assignment_

 - Add comments for the necessary calculations of values

 - Consider JLC PCB as the board manufacturer

## Instructions

 - Create a repository on your GitHub account and copy this project in it. **Do not clone this repository!**
 - Branch the master into one called `name_surname` where the work will be done
 - Commit your progress along the way. **Do not commit just the finished project**, use Git for what it's made for!
 - When you are done, generate the schematic output inside `docs/` and the production (gerber) files in `output/`
 - If you haven't already, submit the recruitment form [here](https://eagletrt.it/apply)
 - If you have any questions feel free to contact us at [electronics@eagletrt.it](mailto:electronics@eagletrt.it)
 - Feel free to also come to our lab (Povo2 floor -2) if we are slow at replying
 - You have **2 weeks** (14 days) to work on this project (**we evaluate if you meet deadlines**)
