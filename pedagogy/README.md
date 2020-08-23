## Pedagogy (Round 1)

<b>Discipline | <b>Electronics and Communication Engineering
:--|:--|
<b> Lab | <b>8051 Microcontroller and Application Lab
<b> Experiment|     <b>1. Write a program to generate 10 KHz square wave using 8051.


<h4> [1. Focus Area](#LO)
<h4> [2. Learning Objectives ](#LO)
<h4> [3. Instructional Strategy](#IS)
<h4> [4. Task & Assessment Questions](#AQ)
<h4> [5. Simulator Interactions](#SI)
<hr>

<a name="LO"></a>
#### 1. Focus Area : Instrumentation and Practical Skills

#### 2. Learning Objectives and Cognitive Level


Sr. No |	Learning Objective	| Cognitive Level | Action Verb
:--|:--|:--|:-:
1.| User will be able to understand the use of timer/counter in the program as a delay routine.| Understand | Understand
2.| User will be able to Calculate the delay required for said frequency of square wave. | Apply | Calculate
3.| User will be able to develop the assembly program for square wave generation. | Apply | Develop
4.| User will be able to analyze the execution of program by observing output. | Analyze | Analyze
5.| User will be able to analyze error in the program through pitfalls. | Analyze | Analyze

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="IS"></a>
#### 3. Instructional Strategy
###### Name of Instructional Strategy  : Guided Enquiry
###### Assessment Method: Formative assessment

<b>Description: </b> As it is known that square wave has equal ontime and offtime, also to generate the ontime that is logic 1 has to be outputted for particular duration ( that is duration 1/20 Khz), and logic 0 for offtime. Also the frequency of the waveform can be changed by changing delay. So instructional strategy is Guided enquiry and it is formative assessment as it is assessed instruction wise.</u>
<br>

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="AQ"></a>
#### 4. Task & Assessment Questions:



Sr. No |	Learning Objective	| Task to be performed by <br> the student  in the simulator | Assessment Questions as per LO & Task
:--|:--|:--|:-:
1.| User will be able to understand the use of timer/counter in the program as a delay routine. | Select the timer/counter for frequency selection. | 1. How do you decide the frequency of square wave to be applied? <br> A. Circuit <br> B. Frequency generator <br> <strong> C. Delay  </strong><br> D. Voltmeter <br> <br> 2. What is block used for frequency simulation? <br> <strong>A. Timer/ counter</strong> <br> B. Ammeter<br> C. Frequency generator <br> D. Voltmeter <br> 
2.| User will be able to Calculate the delay required for said frequency of square wave. | Calculate the delay based on frequency given and set the timer/counter. | 1. What should be the ontime for 10kHz square wave? <br> A. 20 microseconds <br> B. 50 mseconds <br> C. 10 mseconds <br> <strong>D. 50 microseconds </strong> <br> <br>2. What is the dutycycle of square wave? <br> <strong>A. 50 %</strong> <br> B. 70 % <br> C. 30 % <br> D. 100 % <br> 
3.| User will be able to develop the assembly program for square wave generation. | Write the assembly language program | 1. What is CPL instruction stands for? <br><strong> A. Invert</strong>  <br> B. Compare <br> C. Calculate <br> D. Correlate <br> <br>2. What is the significance of ACALL DELAY in this program? <br> A. Setting voltage level <br><strong> B. Setting frequency </strong><br> C. Setting current leve <br> D. Setting Power <br> <br>3. What is the significance of SJMP in this program? <br> A. End progrm <br> B. Start program <br> <strong>C. Jumping to first instruction </strong><br> D. Execute program <br> 
4.| User will be able to analyze the execution of program by observing output. | Execute the program and observe the output | 1. Where will the output be availabe? <br> A. Port 0 <br> B. Port 1 <br> C. Port 2 <br> <strong>D. Port 1.0 </strong> <br> <br>2. Where will the output be observed? <br> <strong>A. CRO</strong> <br> B. Voltmeter <br> C. Ammeter <br> D. Galvanometer <br> 
5.| User will be able to analyze error in the program through pitfalls. | Will make error in writing any instruction | 1. What will happen if SJMP not written properly <br> A. No continuous square wave <br> B. No output <br> C. Hanging of system <br> <strong>D. Warning to user </strong> <br>


<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="SI"></a>

#### 4. Simulator Interactions:
<br>

Sr.No | What Students will do? |	What Simulator will do?	| Purpose of the task
:--|:--|:--|:--:
1.| Student will put the Simulator On | Simulator will allow to enter the program  | To start the operation
2.| Student will enter First instruction | Simulator should complement the status of Port Pin 1.0 for Instruction CPL P1.0 5 v line or logic 1 status or High level should be observed with first time complement and it should remain till it changes.  | To observe logic 1 (high) level/signal to generate the square wave and it will be displayed on CRO. It will be displayed as logic 1 till the status on port pin 1.0 changes
3.| Student will enter Second instruction | For instruction ACALL DELAY It should provide the delay of ontime/offtime i.e. 50 microseconds (for 10 KHz square wave) with timer/counter | To apply the delay of 50 microsecond for high level(logic 1 signal) to display logic 1 for that period.
4.| Student will enter Third instruction | Simulator should complement the status of Port Pin 1.0 for Instruction CPL P1.0 ,0 v line or logic 0 status or low level should be observed with first time complement and it should remain till it changes.  | For Instruction SJMP SQWAVE, it should continue from step 2 for continuous generation of square wave.
5.| Student will observe the output | Execute the instruction ACALL DELAY for another 50 microseconds | Observe the output
6.| Student will stop the program after few seconds | Simulator will stop the operation | No display of square wave on CRO.
7.| Student will make the mistake in writing the instruction in syntax | Simulator will warn the student by alerting about 'error' | To indicate the mistake to user.
