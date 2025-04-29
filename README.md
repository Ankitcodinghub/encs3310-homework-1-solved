# encs3310-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [ENCS3310 Homework 1 Solved](https://www.ankitcodinghub.com/product/encs3310-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112974&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENCS3310 Homework 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Objective:

The task is to design a solution to real problem which is the traffic light design for two roads. You should search for information about the following: Finite State Machine.

The Task:

Your task is to create a solution for traffic light system shown in Figure 1:

Figure 1: Highway and Farm Roads

And here is the block diagram for the traffic lights which shows how the design should work:

You will design a traffic light controller for the highway and farm road intersection shown in Figure 1. The traffic light controller outputs four 2-bit signals, highway Signal 1 and highway signal 2 and farm Signal 1 and 2, for the highway road and the farm road, respectively. The following encoding is used for both signals:

00 : Green

01 : Yellow (when changing from green) 10 : Red

11 : Red-Yellow (when changing from red)

(Note: You can also consider the four outputs as 3-bit signals).

Table 1 : All the states of the traffic light

State Highway TL1 Highway TL2 Farm TL1 Farm TL2 Delay [Sec]

S0 Red Red Red Red 1

S1 Red-Yellow Red-Yellow Red Red 2

S2 Green Green Red Red 30

S3 Green Yellow Red Red 2

S4 Green Red Red Red 10

S5 Yellow Red Red Red 2

S6 Red Red Red Red 1

S7 Red Red Red-Yellow Red-Yellow 2

S8 Red Red Green Green 15

S9 Red Red Green Yellow 2

S10 Red Red Green Red 5

S11 Red Red Yellow Red-Yellow 2

S12 Red Red Red Green 10

S13 Red Red Red Yellow 2

S14 Red Red Red Red 1

S15 Red Red-Yellow Red Red 2

S16 Red Green Red Red 15

S17 Red Yellow Red Red 3

Description of the signals:

Your design has 3 inputs which are:

“Rst” : It returns the design to state 0, and counter to 0.

“Go”: The default is that go = 1 in order to change between different states. However, if go is forced to 0 then the counter will stop counting (freeze).

“clk” : Synchronous system.

After building the design, you have to build a simple testbench which will implement a test for all cases (states).

Format of the report:

This project should be written as formal report. The report should include sections on the following:

• Brief introduction and background

• Design philosophy

• Results

• Conclusion and Future works

The report must be submitted as pdf file and the code should be submitted as .v file (or on note bad as .txt).

Key Points:

• The design description should include diagrams of the design, and give a justification of the decisions made.

• Technical achievement in design is linked to the degree of functionality that was attempted, as explained below.

• Technical achievement in implementation is based on the quality of your Verilog code. This includes issues such as legibility of code, use of meaningful variable names, good comments, clear structure, and modifiability of the design.

• Technical achievement in evaluation is based on the quality of your simulation results.

Assessment Form (Feedback):

The following is the assessment form for this project:

Electrical and Computer Engineering Department

Project Assessment Feedback

Advanced Digital Design (ENCS3310)

Dr. Abdellatif Abu-Issa

Student Name:………………………………….. Student ID:………………….

Report Presentation (10%)

Language (Spelling and Grammar), style of the report, caption of figures, page numbering…etc.

Design Process and Outcome (70%)

• Description of the system and design process (20%)

• Technical Achievement in System Design and Evaluation (50%)

Judgement and Creativity (20%)

Demonstration of good judgment, imagination and creativity in selecting and applying design methods. Good discussion and analysing of the system and suggested improvements.

Total Mark (Out of 100)

FINAL ALLOCATED MARK (Out of 100)

Any evidence for any type of cheating: yes no
