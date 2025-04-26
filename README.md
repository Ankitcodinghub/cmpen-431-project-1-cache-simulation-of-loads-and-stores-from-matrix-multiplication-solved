# cmpen-431-project-1-cache-simulation-of-loads-and-stores-from-matrix-multiplication-solved
**TO GET THIS SOLUTION VISIT:** [CMPEN 431 Project 1 (cache simulation of loads and stores from matrix multiplication) Solved](https://www.ankitcodinghub.com/product/cmpen-431-project-1-cache-simulation-of-loads-and-stores-from-matrix-multiplication-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;11528&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPEN 431 Project 1 (cache simulation of loads and stores from matrix multiplication) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
0) Copy the tarball to a CSE machine (e.g. cse-p204inst10.cse.psu.edu ) and extract it into a local directory of your choosing. This project simulates putting the memory references and values generated through naive ( O(N3) ) matrix multiplication of square matrices of size N through a parameterized cache hierarchy. Most of the functionality for this program has already been provided. However, certain key functions needed to properly perform caching are currently implemented as stub functions that either do nothing or return zero, causing the program to crash if they are relied upon. Your job will be to implement these missing functionalities within the functions defined in “YOURCODEHERE.c”.

You will need/want to make use of the existing functions defined in csim.c, specifically “performaccess”. and the cache structure defined in csim.h For this reason, you will want to familiarize yourself with the existing functions and fields in the other files, although you are not allowed to modify them.

Your project, once complete, will be able to correctly execute all tests invoked by “make test” as well as other cache and matrix configurations not present in the test list. Only cache hierarchies with monotonically nondecreasing block sizes (in integer multiples of 8-bytes) throughout the cache hierarchy will be tested. Similarly, only cache hierarchies with monotonically nondecreasing capacity from upper to lower caches will be tested.

Additional details on acceptable inputs will be provided in a supplementary document.

1) Ensure that your environment is correctly configured (e.g. with default gcc, etc.) by running “make test”

You can verify correct initial state of your environment/files by noting the following:

a) the code should compile without any errors or warnings.

b) the first test case (no cache instantiated) should run to completion and match the output in the included copy of the output from running make test on a completed version of the program

c) the second test case should quickly generate a segfault

2) Modify YOURCODEHERE.c — this is the only file you will be modifying and turning in. Your project MUST compile without modification to the makefile, or any other source files. Your code will be recompiled against the other files in their original state, on CSE servers. Any reliance on additional modifications will likely result in non-compiling status under test and a zero for the project. Please ensure that any code you develop on a non-CSE platform works on the CSE servers, as the code is NOT GENERALLY PORTABLE.

There is missing code in each of the functions in YOURCODEHERE.c. Descriptions of the functionality of each function are in YOURCODEHERE.h and will be expanded upon further in a supplemental document on CANVAS.

Most of the function bodies can be written in 1-5 lines of normally-formatted C code, excepting the one that requires setting several variables in the cache structure. ( The solution version of YOURCODEHERE.c is 66 total lines, of which 11 are blank lines, and 12 consist only of ‘}’ — in short, the missing functionality can be tersely described.)

3) Continue to test your project. All tests in “make test” should run to completion (expected total run time 1-2 minutes, mostly in last test). Matrix sizes &lt;= N=8 should match the provided output. Statistics for larger matrix sizes should be very similar but output may not be identical.
