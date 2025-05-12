# cse4020-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [CSE4020 Lab 5 Solved](https://www.ankitcodinghub.com/product/cse4020-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91689&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4020 Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Write down a Python program to draw transformed triangles and its local frame in a 3D space.

<ol>
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Use the following drawFrame() and drawTriangle() to draw the frame and triangle:</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
def drawFrame():

</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_LINES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 0, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([1.,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(0, 255, 0)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([0.,1.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
<div class="layoutArea">
<div class="column">
def drawTriangle():

</div>
</div>
<div class="layoutArea">
<div class="column">
glBegin(GL_TRIANGLES)

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,.5]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glVertex2fv(np.array([0.,0.])) glVertex2fv(np.array([.5,0.]))

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnd()

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
C. First draw an untransformed white triangle and a global frame.

<ol start="4">
<li>Then draw a transformed blue triangle and its local frame. The triangle should be first rotated by 30 degrees and then translated by (0.6, 0, 0) w.r.t. the global frame.</li>
<li>Then draw a transformed red triangle and its local frame. The triangle should be first translated by (0.6, 0, 0) and then rotated by 30 degrees w.r.t the global frame.</li>
<li>Expected result:
i.
</li>
</ol>
G. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

2. 􏰯􏰈 􏰆􏰖􏰂􏰃􏰓􏰘􏰂􏰖􏰊 􏰓􏰂 􏰃􏰗􏰖 􏰕􏰖􏰛􏰃􏰐􏰌􏰖􏰢 􏰒􏰆􏰘􏰅􏰓􏰂􏰔 􏰛􏰚􏰆􏰖􏰌􏰚􏰙 􏰚􏰂􏰊 􏰒􏰆􏰘􏰅􏰓􏰂􏰔 􏰪􏰘􏰌􏰕􏰊􏰙 􏰚􏰌􏰖 􏰃􏰪􏰘 􏰖􏰎􏰐􏰓􏰅􏰚􏰕􏰖􏰂􏰃 􏰘􏰠􏰖􏰌􏰚􏰃􏰓􏰘􏰂􏰈􏰫

</div>
</div>
<div class="layoutArea">
<div class="column">
Based on the following figure, replace the gluLookAt call() in the following code with two replace glRotatef() calls and one glTranslatef() call and complete the program.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
def render():

</div>
</div>
<div class="layoutArea">
<div class="column">
glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT)

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnable(GL_DEPTH_TEST)

</div>
</div>
<div class="layoutArea">
<div class="column">
glPolygonMode( GL_FRONT_AND_BACK, GL_LINE )

</div>
</div>
<div class="layoutArea">
<div class="column">
glLoadIdentity()

</div>
</div>
<div class="layoutArea">
<div class="column">
gluPerspective(45, 1, 1,10)

# Replace this call with two glRotatef() calls and one glTranslatef() call

gluLookAt(3,3,3, 0,0,0, 0,1,0) drawFrame()

</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 255, 255)

</div>
</div>
<div class="layoutArea">
<div class="column">
drawCubeArray()

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
A.

</div>
</div>
<div class="layoutArea">
<div class="column">
B. C.

D. E.

</div>
<div class="column">
Set the window title to your student ID and the window size to (480,480).

Find code for drawFrame(), drawCubeArray() from 5-RenderingPipeline,

viewing&amp;projection1 slides.

Your program should render the following scene:

i.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
F. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

</div>
</div>
</div>
