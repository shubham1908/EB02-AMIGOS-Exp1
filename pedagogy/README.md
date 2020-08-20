## Pedagogy (Round 1)
<p align="center">

<br>
<br>
<b> Experiment ABCDEF Lab  <a name="top"></a> <br>
</p>

<b>Discipline | <b>Electronics and Communication Engineering
:--|:--|
<b> Lab | <b> 8051 Microcontroller and Application Lab
<b> Experiment|     <b> 1. (RIC 651) Write a program to generate 10 KHz square wave using 8051.


<h4> [1. Focus Area](#LO)
<h4> [2. Learning Objectives ](#LO)
<h4> [3. Instructional Strategy](#IS)
<h4> [4. Task & Assessment Questions](#AQ)
<h4> [5. Simulator Interactions](#SI)
<hr>

<a name="LO"></a>
#### 1. Focus Area : Reinforce theoretical concept- re-registering concepts learnt previously

#### 2. Learning Objectives and Cognitive Level


Sr. No |	Learning Objective	| Cognitive Level | Action Verb
:--|:--|:--|:-:
1.| User will be able to develop the program in assembly language of 8051 for specific task or application Microcontroller | 3 | Develop
2.| User will be able to execute the program | 2 | Execute
3.| User will be able to execute the program in single instruction execution | 3 | Execute
4.| User will be able to point out the errors in Instruction | 4 | Analyze
4.| User will be able To check the output of the execution | 4 | Check

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="IS"></a>
#### 3. Instructional Strategy
###### Name of Instructional Strategy  :     Expository
###### Assessment Method: Formative assessment

<b>Description: </b> As it is known that square wave has equal ontime and offtime, also to generate the ontime that is logic 1 has to be outputted for particular duration ( that is duration 1/20 Khz), and logic 0 for offtime. Also we are aware of  instruction set of Microcontroller 8051. So instructional strategy is Expository and it is formative assessment</u>
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
1.| LO1 | Student will wtite the program instructions and observe the output. | 1. What should be the ontime for 10kHz square wave? <br> A. 20 microseconds <br> B. 50 mseconds <br> C. 10 meseconds <br> <strong>D. 50 microseconds </strong> <br> <br>2. What is the dutycycle of square wave? <br> <strong>A. 50 %</strong> <br> B. 70 % <br> C. 30 % <br> D. 100 % <br> 
2.| LO1 | Student will wtite the program instructions and observe the output. | 1. What should be the ontime for 10kHz square wave? <br> A. 20 microseconds <br> B. 50 mseconds <br> C. 10 meseconds <br> <strong>D. 50 microseconds </strong> <br> <br>2. What is the dutycycle of square wave? <br> <strong>A. 50 %</strong> <br> B. 70 % <br> C. 30 % <br> D. 100 % <br> 


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
1.| Student will enter First instruction | Simulator should complement the status of Port Pin 1.0 for Instruction CPL P1.0 5 v line or logic 1 status or High level should be observed with first time complement and it should remain till it changes. | To observe logic 1 (high) level/signal
2.| Student will enter Second instruction | For instruction ACALL DELAY It should provide the delay of ontime/offtime i.e. 50 microseconds  | To apply the delay of 50 microsecond for high level(logic 1 signal)
3.| Student will enter Third instruction | For Instruction SJMP SQWAVE, it should continue from step 1 | Repeat above process
4.| Student will observe the output | Observe the waveform at port pin 1.0 | Observe the output
