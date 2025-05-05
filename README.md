# mgt483-project-solved
**TO GET THIS SOLUTION VISIT:** [MGT483 Project Solved](https://www.ankitcodinghub.com/product/mgt483-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95217&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;MGT483&nbsp;Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

Linear regression relates a multivariate input x ∈ Rd to a scalar output y ∈ R

via a linear model, that is, y ≈ θ⊤x for some parameter vector θ ∈ Rd. The goal

of linear regression is to learn θ from a finite dataset D = {(x(i),y(i))}Ni=1. In

practical applications only part of the output can be explained by the inputs,

and therefore we have y(i) = θ⊤x(i) + ξ(i), where the error ξ(i) is a realization

of a noise random variable with zero mean. In this case, the best one can hope

for is to find an estimator θ􏰄 ≈ θ constructed from the data. The estimator θ􏰄

can be used to predict the output y corresponding to a new unseen input x,

which is at the core of many applications in statistics and machine learning. We

assume throughout this project that x(i) = 1 for all i ∈ [N], and thus θ can be 11

interpreted as a bias term that represents the mean or the median of y(i).

In this project you will derive and implement several linear programming-

based methods to learn the unknown parameter vector θ from data.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
MSE MAE

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
4.5 4.0 3.5 3.0 2.5 2.0 1.5 1.0

Figure 1: MSE vs. MAE estimators for a dataset with 1 outlier (red dot)

Mean-Absolute-Error Penalized Regression

</div>
</div>
<div class="layoutArea">
<div class="column">
210123

</div>
</div>
<div class="layoutArea">
<div class="column">
There exist different methods to construct the estimator θ. The most widely used approach minimizes the mean-squared-error (MSE) corresponding to the given data to obtain the MSE estimator

1 􏰃N

(y(i) − θ⊤x(i))2. (1) Alternatively, one can minimize the mean-absolute-error (MAE) to obtain the

more robust MAE estimator

1 􏰃N

θMAE ∈ arg min θN

i=1

Question 1 Figure 1 visualizes the outputs predicted by the MSE and MAE estimators on a dataset with 1 outlier. Explain the difference between the two estimators intuitively. Hint: Compare how (1) and (2) penalize errors.

In case of high-dimensional inputs (d &gt; N), it makes sense to seek a sparse parameter vector θ. This means that many components of θ should be zero. The non-zero components of θ then correspond to the key features or key inputs that have a significant impact on the outputs. Sparsity can be induced by adding an l1-penalty to the objective function of (1) or (2), which yields the least absolute shrinkage and selection operator (LASSO) method of regression analysis. In case of the MAE objective, the resulting LASSO estimator satisfies

1 􏰃N

θ􏰄 ∈ arg min θN

i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
θMSE ∈ arg min θN

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰄

</div>
<div class="column">
|y(i) − θ⊤x(i)|. (2)

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
|y(i) − θ⊤x(i)| + λ∥θ∥1, (3) 2

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰄

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
where ∥θ∥1 = 􏰂di=1 |θi| denotes the l1-norm of θ, and λ ≥ 0 is a hyperparameter that represents the weight of the penalty. In practice, λ is typically chosen by cross validation. That is, we randomly partition D into a training dataset Dtrain and a validation dataset Dval. We then solve (3) using only Dtrain for different values of λ and select the estimator that has minimal MAE on Dval.

Question 2 .

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2.

3.

</div>
<div class="column">
Rewrite (3) as a linear program (not necessarily in standard form).

Implement this linear program in MATLAB or Python and solve it on the Diabetes Dataset for λ = 0.5. Use the code skeletons provided on Moodle. The diabetes dataset links a feature vector x comprising patient information (age, sex, body mass index) and blood measurements (blood pressure, T-Cells, lipoproteins, thyroid, lamotrigine and blood sugar) to an output y quantifying the progression of the diabetes disease. Compute the MAE of the resulting estimator on the separate test sets provided on Moodle. Compare the test performance against the training performance. Hint: Do not forget to append a constant bias term to the features.

Use cross-validation to tune the hyperparameter λ. Randomly select 75% of the data to construct Dtrain and use the rest of the data to construct Dval. Use 50 logarithmically spaced values between [10−5, 10−1] as candidates for λ, select the one performing best on the validation set in terms of MAE. Compare again the test performance against the training performance.

Convex Hulls

</div>
</div>
<div class="layoutArea">
<div class="column">
Standard linear programs involve only real decision variables. However, many applications require binary decision variables that are restricted to {0, 1}. Such variables emerge, for example, if you have to decide whether a project should be implemented or not or whether an item should be loaded on a truck or not etc. A linear optimization problem with binary decision variables is given below.

min −x1−2×2 x1 ,x2

s.t. x1+x2≤1 (4) x1,x2 ∈{0,1}

Any binary linear program (such as problem (4)) is equivalent to a standard linear program, which is obtained by replacing the original feasible set with its convex hull, that is, the smallest convex set containing all feasible points.

Definition 3.1 (Convex hull). The convex hull of an arbitrary (possible non- convex) set X ⊂ Rn is defined as

􏰀nn 􏰁 conv(X)= z∈Rn :z=􏰃θixi, 􏰃θi =1, xi ∈X,θi ≥0∀i∈[n] .

i=1 i=1

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Question 3. Denote by X the feasible set of problem (4). Describe the convex hull of X and find its vertices. Plot both X and conv(X).

Question 4 . Replace the feasible set of problem (4) with its convex hull and solve the resulting linear program using MATLAB or Python. Re- port the optimal decision variables. Explain why they must be binary. Hint: Characterize the BFS of the convex hull of the feasible set.

4 Zero-Sum Games

In the standard cross validatioin scheme described in Section 2, training and validation sets were constructed randomly. In the remainder of the project we will explore an adversarial cross validation procedure, where the training set is chosen by a fictitious adversary who aims to maximize the prediction error of our estimator. This procedure will give rise to a MinMax problem of the form:

min max f(x,z). (5) x∈X z∈Z

MinMax problems are zero-sum games, where one player’s profit is the other player’s loss. They are more intricate than standard minimization problems. We will see, however, that problem (5) can sometimes be simplified to a standard minimization problem if Z is convex and f(x,z) is concave in z for all x ∈ X.

As an example, suppose you own $10,000, which you want to hide in your apartment. There are I hiding spots with capacities of Ci dollars, i ∈ [I]. In case of a burglary, you want to lose as little money as possible. Assume that the police need T minutes to reach your apartment, and therefore any thief must leave within T minutes to avoid arrest. Assume further that the amount of money found in hiding spot i equals xi ·zi ·pi, where xi stands for the amount of money hidden, zi denotes the amount of time the thief spends searching spot i and pi represents a constant reflecting the difficulty of searching spot i. If the thief spends an amount of time exceeding 1/pi in location i, then all the money hidden in that spot will be found. It therefore makes sense to restrict zi ≤ 1/pi.

We seek a plan for hiding the money in the best possible way. Specifically, we hope to loose the least amount of money in the worst case, that is, if a very efficient thief shows up. This problem can be modeled as a zero-sum game against the thief (indeed, our loss is the thief’s profit).

Question 5 (20 points: 3+3+3+8+3). This question will guide you through formulating and solving the problem of finding the best hiding strategy.

1. Characterize your decision variables and your feasible set.

2. Characterize the thief’s decision variables and feasible set.

3. Use the solutions of the first two questions to formulate a MinMax problem with objective function

I

f(x,z) = 􏰃xizipi.

i=1

4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
5

</div>
</div>
<div class="layoutArea">
<div class="column">
4.

5.

</div>
<div class="column">
Dualize the inner maximization problem to reformulate the MinMax prob- lem as a standard minimization problem, which can be addressed with lin- ear programming solvers. Hint: The decision variables of the outer mini- mization problem represent constants for the inner maximization problem.

Implement the resulting linear program in Python or MATLAB and solve it for the provided input data p, C ∈ RI and T ∈ R. Use the code skeletons available from Moodle. Report the worst amount of money you lose, the optimal plan for hiding the money and the thief’s optimal search strategy. Hint: Think about the meaning of the problem’s dual variables.

Adversarial Training

</div>
</div>
<div class="layoutArea">
<div class="column">
Standard cross validation partitions D randomly into a training set Dtrain and a validation set Dval of prescribed cardinalities. Hence, it could happen that the training set contains no outliers (lucky) or all outliers (unlucky). The resulting estimator θ􏰄 thus depends on the choice of the training set. We now propose an alternative approach to construct θ􏰄 in an adversarial (worst-case optimal) manner. Specifically, we will train the regression model on the worst possible training set Dtrain we could have possibly constructed from D.

We now construct the best estimator for the worst-case training set con- taining k = ⌊0.75 · N ⌋ samples, where ⌊y⌋ denotes the largest integer smaller or equal to y. To that end, we formulate a MinMax problem, where the inner max- imization problem optimizes over the binary variables zi, i ∈ [N], corresponding to the N samples. The binary variable zi is set to 1 if sample (y(i),x(i)) is in- cluded in the training set and to 0 otherwise. The outer optimization problem over θ aims to minimize the MAE with LASSO penalty in view of the worst-case training set. In summary, we thus find the following MinMax problem.

1 􏰃N

k

i=1 N

􏰃zi =k (6) i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
min max

θ z1,…,zN

s.t.

</div>
<div class="column">
zi|y(i) − θ⊤x(i)| + λ∥θ∥1

</div>
</div>
<div class="layoutArea">
<div class="column">
zi∈{0,1} ∀i∈[N]

This MinMax problem can be interpreted as a zero-sum game between the

statistician and an evil adversary who selects the worst possible training set. Question 6 (15 points). Derive the convex hull of the adversary’s feasible set

􏰀N􏰁

Z= z∈RN:􏰃zi=k,zi∈{0,1}∀i∈[N] , (7)

i=1

where k is an integer. Prove that your formulation is indeed the convex hull.

Hint: Two sets A and B are equivalent if A ⊆ B and B ⊆ A. 5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Question 7 (25 points: 10+10+5).

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

</div>
<div class="column">
Show that the MinMax problem (6) is equivalent to the following linear program. Hint: Use the insights from Sections 3 and 4.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.

3.

</div>
<div class="column">
−bj ≤θj ≤bj ∀j∈[d]

Give an interpretation for β. Explain how one can extract the validation

set from a solution of this problem.

Implement the linear program (8) in MATLAB or Python using the skele- ton code we provide on Moodle and solve it for 50 logarithmically spaced values of λ in the interval [10−5,10−1]. For each of these values compute the MAE of the corresponding estimator on the validation set, and select the best robust estimator. To assess the benefits of robust cross validation over standard cross validation, compare the MAE of the robust estimator against the MEA of the estimator found in Question 2.3. In both cases the MEA should be computed on the test set.

For the robust estimator found above, compare also the MEA on the test set against the MEA on the training set. Is there a significant difference to what you observed in Question 2.3.? Interpret your observations?

No More Toy-Examples/Optimization Prize

</div>
</div>
<div class="layoutArea">
<div class="column">
Nd min kα+􏰃βi +λ􏰃bi

θ,α,βi ,bi

i=1 j=1

s.t. α + βi ≥ (y(i) − θ⊤x(i))/k

α + βi ≥ −(y(i) − θ⊤x(i))/k βi≥0 ∀i∈[N]

</div>
<div class="column">
∀i ∈ [N] (8) ∀i ∈ [N]

</div>
</div>
<div class="layoutArea">
<div class="column">
So far, you have applied different regression techniques to the “Diabetes” data- set. In this open question, we ask you to apply one of the regression techniques seen in Sections 2 and 5 to a regression problem of your liking.

Question 8 (10 points). Apply one of the regression techniques seen in Sec- tions 2 and 5 to a dataset of your choice. Hint: Good sources of datasets include Kaggle and the UCI archive. In answering this question, put emphasis on interpreting your results and on justifying the chosen optimization scheme.

Question 9 (Voluntary bonus question, 10 points). If you like, prepare a short presentation of your answer of Question 8 (about 5 minutes) for the exercise session on May 20th. This will allow you to present your dataset and insights to your fellow students. We will give you bonus points for volunteering to do the presentation, but we will not grade its contents. Everyone present in the exercise session will be able to vote on the best presentation. The group attracting the most votes will receive an optimization prize.

6

</div>
</div>
</div>
