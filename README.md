Download Link: https://assignmentchef.com/product/solved-math4387-homework-2
<br>
<h1>Problem 1</h1>

The linear regression model can be written in matrix notation as <em>y </em>= <em>Xβ </em>+ . Create the table shown below and describe what each term (<em>y,X,β,</em>) represents (interpretation), specify the dimension of each term (size), indicate whether we model the term as random or non-random, and whether the term is observed or unobserved.

<table width="324">

 <tbody>

  <tr>

   <td width="47">Term</td>

   <td width="39">Size</td>

   <td width="97">Interpretation</td>

   <td width="71">Random?</td>

   <td width="70">Observable?</td>

  </tr>

  <tr>

   <td width="47"><em>y β</em><em>X</em> </td>

   <td width="39"></td>

   <td width="97"></td>

   <td width="71"></td>

   <td width="70"></td>

  </tr>

 </tbody>

</table>

<h1>Problem 2</h1>

Assuming a simple linear regression model, derive the ordinary least squares estimators of <em>β</em><sub>0 </sub>and <em>β</em><sub>1</sub>. Do not use matrix notation in deriving your solution.

<strong>Problem 3</strong>

Let <em>H </em>= <em>X</em>(<em>X<sup>T</sup>X</em>)<em><sup>−</sup></em><sup>1</sup><em>X<sup>T </sup></em>is the hat matrix. Prove that <em>I−H </em>is a projection matrix (Symmetric + Idempotent).

<h1>Problem 3</h1>

While proving that <em>β</em><sup>ˆ</sup><sub>1 </sub>is an unbiased estimator of <em>β</em><sub>1</sub>, we represented the OLS estimate as <em>β</em><sup>ˆ</sup><sub>1 </sub>= <sup>P</sup><em>k<sub>i</sub>Y<sub>i</sub></em>, where <em>k<sub>i </sub></em>= <sub>P</sub><em><u><sup>X</sup></u></em><sub>(<em>X</em></sub><em><u><sup>i−</sup></u></em><em>i<sub>−</sub><u><sup>X</sup></u><sub>X</sub></em><sub>)</sub>2. Use it with the properties of <em>k<sub>i</sub></em>, that we already have proved, to derive the variance of <em><sup>β</sup></em><sup>ˆ</sup><sub>1</sub>. (Hint: in linear regression framework we assume <em>V ar</em>(<em><sub>i</sub></em>) = <em>σ</em><sup>2 </sup>and <em>Cov</em>(<em><sub>i</sub>,<sub>j</sub></em>) = 0 when <em>i 6</em>= <em>j</em>)

<h1>Problem 4</h1>

P(<em>y</em><em>i</em><em>−y</em>ˆ<em>i</em>)2

Under simple linear regression model, the Mean Squared Error (MSE) is defined as <em><sub>n−</sub></em><sub>2 </sub>where <em>n </em>is the number of observations. MSE is an unbiased estimator of <em>σ</em><sup>2</sup>, where <em>σ</em><sup>2 </sup>is the variance of <em><sub>i</sub></em>. What is an unbiased estimator of the variance of <em>β</em><sup>ˆ</sup><sub>1</sub>?

<h1>Problem 5</h1>

The square root of the variance of an estimator is the standard error (SE). You can derive the SE (<em>β</em><sup>ˆ</sup>) from problem 4. According to theory,

1

<em>β</em>ˆ1 <em>− β</em>1

<em>∼ t<sub>n</sub></em><em>−</em>2

<em>SE</em>(<em>β</em><sup>ˆ</sup><sub>1</sub>)

where <em>t<sub>n−</sub></em><sub>2 </sub>represents a Student’s <em>t </em>distribution with <em>n − </em>2 degrees of freedom. Find an expression for 95%

confidence interval of <em>β</em><sub>1</sub>.

<strong>Problem 6</strong>

If <em>β</em><sup>ˆ</sup><sub>1 </sub>= 2, <em>SE</em>(<em>β</em><sup>ˆ</sup><sub>1</sub>) = 0<em>.</em>02, and <em>n </em>= 50 calculate 95% confidence interval for <em>β</em><sub>1</sub>.

<h1>Problem 7</h1>

Based on the confidence interval on problem 6, perform the hypothesis test,

<em>H</em><sub>0 </sub>: <em>β</em><sub>1 </sub>= 0           Vs. <em>H</em><sub>1 </sub>: <em>β</em><sub>1 </sub><em>6</em>= 0

<h1>Problem 8</h1>

Use the simu_hw1.txt data and fit a multiple linear regression model with response as the response variable and pred1, pred2, and pred3 as predictors. Write down the equation of the fitted line (fitted model).