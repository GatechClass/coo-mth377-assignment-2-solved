# coo-mth377-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COO-MTH377 Assignment 2 Solved](https://mantutor.com/product/coo-mth377-coding-assignment-2-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112998&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COO-MTH377  Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions

2. Please upload your code as a jupyter notebook on Google Classrooom. Written work, if any, should be scanned as a pdf and then uploaded. You should preferably do your written work in the same jupyter notebook using markdown cells.

3. Please run your code and show the output by printing meaningful output statements.

4. Readability of code is a criterion for grading. So write code with ample comments.

5. You need the CVXPY package for the first two problems. Go and spend some time on www.cvxpy.org to familiarize yourself with the package and the syntax.

Prisoners’ Dilemma as a Bargaining Problem

The Prisoners’ Dilemma is a famous model for illustrating the conflict between social cooperation and self-interested behavior. Consider a two player Prisoners’ Dilemma in which the cooperative payoff possibilities are mathematically described by a polytope which is defined as the convex hull of the payoff vectors (4,4), (6,0), (0,6) and (0,0). Suppose we think of the Prisoners’ Dilemma as a bargaining situation where the disagreement point is d = (d1,d2). The notion of a disagreement point introduces a constraint that player i cannot get a payoff below her disagreement point payoff di.

Whether or not you want to invest in understanding this model, you can always start your work taking as given that the feasible set F of payoff vectors (u1,u2) for the bargaining problem is mathematically described as

u1 + 2u2 ≤ 12 2u1 + u2 ≤ 12 u1 ≥ d1, u2 ≥ d2

Problem 1 (5 points). (Linear optimization using CVXPY). Use the CVXPY package to do this problem.

Suppose the disagreement point is given by d = (3.5,2). A weighted utilitarian criterion is defined as

W(u1,u2) = θu1 + (1 − θ)u2 where θ ∈ [0,1]

The weighted utilitarian solution of the bargaining problem, defined as

max W(u1,u2) such that (u1,u2) ∈F

u1,u2

Plot player 1’s utilitarian optimum u1(θ) as the weight θ varies in [0,1].

Problem 2. (8 points). (Convex optimization using CVXPY). Use the CVXPY package to do this problem.

Suppose the disagreement point is given by d = (3.5,2). A Nash welfare criterion is defined as

N(u1,u2) = log(u1 − d1) + log(u2 − d2)

Find the Nash bargaining solution of the bargaining problem, defined as

such that (u1,u2) ∈F

(a) (4 points). In addition to displaying the Nash bargaining solution, display the primaloptimal value and the optimal dual variables for the constraints as well.

(b) (4 points). (Comparative statics). Now fix the disagreement payoff of player 2 at d2 = 2. In the same figure, plot how both players’ payoffs in the Nash bargaining solution vary as the disagreement payoff d1 of player 1 varies over the interval [2,5].

Problem 3. (7 points). (Convex optimization using interior point algorithm). You cannot use the CVXPY package here. Please implement the algorithm.

Suppose the disagreement point is given by d = (2,1). Solve Problem 2(a) by implementing the interior point algorithm that uses log barrier for inequality constraints. Display the following

(i) initial t and final t

(ii) Nash bargaining solution

(iii) primal optimal value (Maximized Nash welfare)

(iv) dual optimal variables for constraints

(v) inequality constraint function values at the optimum
