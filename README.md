# cs4392-assignment-1--rotating-bunny-solved
**TO GET THIS SOLUTION VISIT:** [CS4392 Assignment 1- Rotating bunny Solved](https://www.ankitcodinghub.com/product/cs-4392-001-computer-animation-assignment-1-10-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;111236&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4392 Assignment 1- Rotating bunny Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (6 votes)    </div>
    </div>
Write an OpenGL program that display a rotating bunny.

1) Initially place a bunny 5 units along the x-axis at (5, 0, 0) of world coordinate system. This is already implemented in the provided starting code.

2) Draw a ground plane and y-axis of world coordinate system. Draw xyz axis from an arrow object. This is already implemented in the provided starting code.

3) Rotate the bunny around the global y-axis of world coordinate system (WCS) and at the same time rotate around its own x-axis of local coordinate system (LCS).

For the rotating bunny, do the following transformation in order:

a. rotate the bunny around its own x-axis of local coordinate system by ‘a’ degree; (grade: 4 points)

b. then rotate the bunny by ‘b’ degrees around the global y-axis of world coordinate system. (grade: 3 points)

Note that the rotation around its own x-axis will not change the center position of bunny. The center position of bunny is changed when it rotates around the global y-axis. Some implementation hints are given below.

4) The program should have user-interaction controls to allow users to interactively increase and decrease a and b. The controls can be buttons, checkboxes, mouse clicks, mouse motion, etc. as long as it is easy to use. (grade: 2 points)

A starting code (C++) animating a bunny has been provided. GUI is implemented by Nanogui and GLFW. To build the code, the following libraries are needed: GLEW, GLFW, Nanogui.

Hints:

1. Every bunny transformation can be implemented by modifying the “Model” matrix in the OpenGL code. The Model matrix is used to transform the vertex coordinates from model’s local coordinate system (LCS) to world coordinate system (WCS).

2. How to rotate the bunny around its own x-axis of local coordinate system (LCS)? Here are some hints that you can consider:

a. Track the direction of the bunny’s x-axis of LCS and represent it in WCS.

b. Construct a rotation matrix, with the rotation axis to be the bunny’s x-axis and the rotation angle to be ‘a’ degree. Rodrigues’ rotation formula gives the form of this matrix.

c. The rotation pivot point is the origin of bunny’s LCS, but not the origin of WCS. Think about how to make the bunny rotate around its own origin.
