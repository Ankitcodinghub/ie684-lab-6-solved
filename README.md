# ie684-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [IE684 Lab 6 Solved](https://www.ankitcodinghub.com/product/ie684-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97629&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE684 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 0: Convergence of sequences: (ONLY FOR PRACTICE, NOT FOR SUBMISSION)

Let {xk} be a sequence in Rn that converges to x∗. One possible classification of the convergence behavior is stated below:

<ul>
<li>􏰁 &nbsp;The convergence is Q-Linear if there is a constant r ∈ (0, 1) such that

||xk+1 − x∗|| ≤ r, for all k sufficiently large,</li>
<li>􏰁 &nbsp;The convergence is Q-superlinear if
lim ||xk+1 − x∗|| = 0.
</li>
</ul>
k→∞ ||xk − x∗||

􏰁 The convergence is Q-quadratic if there exists some M &gt; 0 such that we have ||xk+1 − x∗|| ≤ M, for all k sufficiently large.

rates of convergence:

(a) (1+0.005)−(2k), k=0,1,2,… (b) 1+(0.005)k, k=0,1,2,…

(c) 1+(0.005)(−k), k=0,1,2,…

(d) 1+k−k, k=0,1,2,…(assume00 =1)

You can check the rates by plotting the iterates.

</div>
</div>
<div class="layoutArea">
<div class="column">
||xk − x∗||

where the norm || · || is generally assumed to be the Euclidean norm.

</div>
</div>
<div class="layoutArea">
<div class="column">
||xk − x∗||2

1. For each of following three sequences check empirically how fast they converge and try to check the theoretical

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab

Lab 06 16-February-2022

In this lab, we will consider the ordinary least squares regression (OLSR) problem. We will discuss a few optimization algorithms to solve it. Please use only Python as your programming language.

Preparation Exercise (PREP):

<ol>
<li>Import the required Python packages using the following commands
import numpy as np

import matplotlib.pyplot as plt (Recall the functionality of these packages.)
</li>
<li>For replication purposes, initialize the random number generator using np.random.seed(1000)</li>
<li>Use the np.random.randn function to create A as a random numpy array of 1000 rows and 10 columns (recall the purpose of np.random.randn function). In data science parlance, we shall call A to be a data set of 1000 data points, each of dimension 10.</li>
<li>Create x ̄ = 􏰆x ̄1 x ̄2 . . . x ̄10􏰇⊤ as a random vector of size 10 × 1 such that when i is odd, each component x ̄i of x ̄ is sampled uniformly from [−(i + 1), −i] ⊂ R, and when i is even, each component x ̄i of x ̄ is sampled uniformly from [i, i + 1] ⊂ R (Use appropriate numpy function here).</li>
<li>Use np.random.randn to create ε as a random vector of size 1000 × 1.</li>
<li>Compute y = Ax ̄ + ε. Use an appropriate numpy function to do the matrix multiplication Ax ̄ efficiently.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab

Lab 06 16-February-2022

Exercise 1: Direct least squares loss minimization

Note that y is a noisy version of Ax ̄. We will now try to estimate x ̄ assuming that we are given y and A. One possible approach is to solve the following problem:

minf(x)= 1∥Ax−y∥2. (1) x2

The loss term ∥Ax − y∥2 is called the ordinary least squares (OLS) loss and the problem (1) is called the OLS Regression problem.

<ol>
<li>Write Python functions using appropriate numpy routines to compute the objective function value, the gradient value and the Hessian of f.</li>
<li>[R] With a starting point of x0 = 􏰆0 0 . . . 0􏰇⊤ ∈ R10, solve problem (1) using the Newton’s method implemented with backtracking line search (use α0 = 0.99,ρ = 0.5,γ = 0.5 for backtracking line search and τ = 10−5). Comment on difficulties (if any) you face when computing the inverse of Hessian (recall that you need to use an appropriate Python function to compute the inverse of the Hessian). If you face difficulty in computing inverse of Hessian, try to think of some remedy so that you can avoid the issue.
<ul>
<li>􏰁 &nbsp;Let x∗ be the final optimal solution provided by your algorithm. Report the values of x∗ and x ̄, and discuss the observations.</li>
<li>􏰁 &nbsp;Plot the values log(||xk − x∗||2) against iterations k = 0, 1, 2, . . ..</li>
<li>􏰁 &nbsp;Prepare a different plot for plotting log(|f(xk) − f(x∗)|) obtained from Newton’s method against the
iterations.
</li>
<li>􏰁 &nbsp;Comment on the convergence rates of the iterates and the objective function values, by recalling the definitions given above.</li>
</ul>
</li>
<li>[R] With a starting point of x0 = 􏰆0 0 . . . 0􏰇⊤ ∈ R10, solve problem (1) using the BFGS method implemented in the previous lab with backtracking line search (use α0 = 0.99, ρ = 0.5, γ = 0.5 for backtracking line search and τ = 10−5).
<ul>
<li>􏰁 &nbsp;Let x∗ be the final optimal solution provided by your BFGS algorithm. Report the values of x∗ and x ̄, and discuss the observations.</li>
<li>􏰁 &nbsp;Plot the values log(||xk − x∗||2) against iterations k = 0, 1, 2, . . ..</li>
<li>􏰁 &nbsp;Prepare a different plot for plotting log(|f(xk)−f(x∗)|) obtained from BFGS method against the iterations.</li>
<li>􏰁 &nbsp;Comment on the convergence rates of the iterates and the objective function values obtained by BFGS method.</li>
</ul>
</li>
<li>[R] Compare and contrast the results obtained by Newton’s method and BFGS method and comment on the time taken by both the methods.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab

Lab 06 16-February-2022

Exercise 2: Regularized least squares loss minimization

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Let us now introduce the following regularized problem (with λ &gt; 0):

minfλ(x)= λx⊤x+ 1∥Ax−y∥2. (2)

</div>
</div>
<div class="layoutArea">
<div class="column">
x22

[R] Comment on the significance of the newly added regularizer term λ2 x⊤x, when compared to problem (1).

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Write Python functions to compute the function value, gradient and Hessian of fλ.</li>
<li>For λ ∈ {10−3, 10−2, 10−1, 1}, perform the following: with a starting point of x0 = 􏰆0 0 . . . 0􏰇⊤ ∈ R10, solve the problem (2) using Newton and BFGS methods with backtracking line search (use α0 = 0.99, ρ = 0.5, γ = 0.5 for backtracking line search and τ = 10−5).</li>
<li>[R] For Newton’s method prepare the following plots and discuss the relevant observations:
<ol>
<li>(a) &nbsp;Prepare a single plot where you depict the values log(||xk − x∗||2) against iterations k = 0, 1, 2, . . ., for each value of λ (use different colors for different λ values; if necessary, add zoomed versions of the plots to depict the behavior clearly, and use appropriate legend in your plots). Comment on the convergence rates of the iterates for each value of λ.</li>
<li>(b) &nbsp;Prepare a different plot for plotting log(|f(xk) − f(x∗)|) against the iterations, for each value of λ (use different colors for different λ value; if necessary, add zoomed versions of the plots to depict the behavior clearly, and use appropriate legend in your plots). Comment on the convergence rates of the objective function values.</li>
</ol>
</li>
<li>[R] For BFGS method prepare the following plots and discuss the relevant observations:
<ol>
<li>(a) &nbsp;Prepare a single plot where you depict the values log(||xk − x∗||2) against iterations k = 0, 1, 2, . . ., for each value of λ (use different colors for different λ values; if necessary, add zoomed versions of the plots to depict the behavior clearly, and use appropriate legend in your plots). Comment on the convergence rates of the iterates for each value of λ.</li>
<li>(b) &nbsp;Prepare a different plot for plotting log(|f(xk) − f(x∗)|) against the iterations, for each value of λ (use different colors for different λ value; if necessary, add zoomed versions of the plots to depict the behavior clearly, and use appropriate legend in your plots). Comment on the convergence rates of the objective function values.</li>
</ol>
</li>
<li>[R] Compare and contrast the results obtained by Newton’s method and BFGS method and comment on the time taken by both the methods for each value of λ.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
