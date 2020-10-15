## Introduction (Round 0)

<b>Discipline | <b>Electronics and Communication Engineering
:--|:--|
<b> Lab | <b>8051 Microcontroller and Application Lab
<b> Experiment|     <b>1. Write a program to generate 10 KHz square wave using 8051.

<h5> About the Lab (Objective) : </h5>

User should be able to write the assembly language code of 8051 Microcontroller and should be able to check it's results after execution. User should be able to understand the functioning of simulator to write the assembly language program of 8051 for given task. User should be able to apply the suitable input and observe the output by understanding functioning of assembly language program. 8051 microcontroller has four input output ports. User should be able to use these ports for the application program.

<h5> About the Experiment : </h5>

It is required to generate the square wave with 8051 Microcontroller , First user has to decide the port pin where square wave is to be generated. Here port 1.0 pin is selected.Depending upon crystal frequency , number of count to be used in delay program Instructions are calculated. Here crystal frequency is assumed 12 MHz. So each count is of 1 microsecond. 10 khz square wave means ontime plus off time is 100 microseconds. That is ontime 50 microseconds and offtime 50 microsecond. To generate these timings, a counter/timer is simulated which will work according to delay required and should have facility to change the value of delay to generate the square wave of different frequencies. To observe this output ,a CRO is to be connected at the port pin 1.0. First the Port pin 1.0 is complemented so whatever is available on port pin will be inverted. That is logic 0 woill become logic 1 and Logic 1 will become logic 0. Then timer will work for 50 microseconds. Because the port pins are latched for 50 microseconds logic level let's say 1 will remain on port pin 1.0. Then it is complemented and again the timer of same count is run. Now logic 0 will appear on port pin 1.0 for 50 microseconds and the process is repeated to generate the continuous square wave. This waveform is observed on CRO.

<h5> Target Audience : </h5>

This experiment is useful for the students as well as the faculty members who are involved in teaching-learning process of the course in Microcontroller-8051.

<h5> Course Alignment : </h5>

Microcontroller 8051 for Instrumentation Engineering, Microprocessor and Microcontroller Lab for Electronics and Communication Engineering as per new third year curriculum of AKTU.

<h5> Universities Mapped : </h5>

Dr. A.P.J. Abdul Kalam Technical University, Uttar Pradesh, Lucknow

<b>Name of Developer | <b> Satish Kumar Singh
:--|:--|
<b> Institute | <b> BIET Jhansi
<b> Email id|     <b> satishsingh.in@gmail.com
<b> Department | Electronics and Communication Engg.

#### Mentor Details

<b>Mentored by | <b> Arvind Pandey
:--|:--|
<b> Institute | <b> MIET Meerut
<b> Email id|     <b> arvind.pandey@miet.ac.in
<b> Department | Electronics and Communication Engg.

#### Contributors List

SrNo | Name | Faculty or Student | Department| Institute | Email id
:--|:--|:--|:--|:--|:--|
1 | Abhishri Dwivedi | Student | Electronics and Communication Engineering | BIET, Jhansi | abhi300699@gmail.com
2 | Neharika Saxena | Student | Information Technology | BIET, Jhansi | imneharika11@gmail.com
3 | Ruchika Mishra | Student | Information Technology | BIET, Jhansi | ruchika6254@gmail.com
4 | Shubham Gupta | Student | Information Technology | BIET, Jhansi | shubham1908gupta@gmail.com
