# cop4600---solved
**TO GET THIS SOLUTION VISIT:** [COP4600 – Solved](https://www.ankitcodinghub.com/product/cop4600-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109883&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP4600 -  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Assignment 1: Process API in Unix

Learning Objectives

The objective of this assignment is to experiment with process API in Unix and to better understand how the Unix shell works by trying to mimic its behavior.

Problem 1

Write a C program that does the following:

• Creates a new process (using fork());

• Makes the new process execute cmd with params as parameters, if given.

• Waits for the new process to finish executing, and then prints ++++ on a new line.

Problem 2

This problem builds significantly on the previous problem. Specifically, it asks you to again use fork() to create processes and exec() (or one of the many variants) to assign the newly created processes what to do. In addition, however, it asks you to mimic the behavior of a shell command such as:

ls | wc

What happens in the case above is the output of the first command (’ls’) becomes the input to the second command (’wc’). (Try it in a terminal on a Unix machine). Thus, you are required to write another program that:

• Expects an input of the form: cmd1 | cmd2

• Creates two processes

• Makes the first process run cmd1

• Makes the second process run cmd2

• Makes sure that the output of the first process becomes the input of the second process (using the function pipe()).

• Waits for the two processes to finish before it ends by printing ++++ on a new line.

1

What to Submit

Name your C files as problem1.c and problem2.c and place them in a folder called assignment1. Compress the folder into a .tar file:

tar -cvf assignment1.tar assignment1

This will download the tar file to the location this command was run from. Submit the tar file on Canvas.

Other Instructions and Suggestions

• The C functions (that, in fact, use system calls) you’ll need include: fork(), wait(), pipe(), exec() (or variants). You might want to also experiment with and use for debugging the functions getpid() and getppid().

• For on-line reference manuals use the command man as below:

man -s 2 pipe

man man man getppid man -s 2 exec
