Download Link: https://assignmentchef.com/product/solved-engr421-project-2-discrimination-by-regression
<br>
In this homework, you will implement a discrimination by regression algorithm for multiclass classification in Matlab, Python, or R. Here are the steps you need to follow:

<ol>

 <li>Read Section 10.7.3 (4<sup>th</sup> edition) or Section 10.8 (3<sup>rd</sup> edition) from the textbook.</li>

</ol>




<ol start="2">

 <li>You are given a multivariate classification data set, which contains 195 handwritten letters of size 20 pixels × 16 pixels (i.e., 320 pixels). These images are from five distinct classes, namely, A, B, C, D, and E, where we have 39 data points from each class. The figure below shows five sample figures from each class. You are given two data files:

  <ol>

   <li>csv: letter images,</li>

   <li>csv: corresponding class labels.</li>

  </ol></li>

</ol>







<ol start="3">

 <li>Divide the data set into two parts by assigning the first 25 images from each class to the training set and the remaining 14 images to the test set.</li>

 <li>Learn a discrimination by regression algorithm using the sigmoid function for this multiclass classification problem. You can use the following learning parameters.</li>

</ol>

<table width="144">

 <tbody>

  <tr>

   <td width="106">eta &lt;- 0.01</td>

   <td width="38"> </td>

  </tr>

  <tr>

   <td colspan="2" width="144">epsilon &lt;- 1e-3</td>

  </tr>

 </tbody>

</table>

<ol start="5">

 <li>Draw the objective function values throughout the iterations. Your figure should be similar to the following figure.</li>

</ol>

Iteration

<ol start="6">

 <li>Calculate the confusion matrix for the data points in your training set using the discrimination rule you will develop using the estimated parameters. Your confusion matrix should be similar to the following matrix.</li>

</ol>




y_train y_predicted  1  2  3  4  5           1 25  0  0  0  0

<ul>

 <li>0 25 0  0  0</li>

 <li>0 0 25  0  0</li>

 <li>0 0  0 25  0</li>

 <li>0 0  0  0 25</li>

</ul>




<ol start="7">

 <li>Calculate the confusion matrix for the data points in your test set using the parametric discrimination rule you will develop using the estimated parameters. Your confusion matrix should be similar to the following matrix.</li>

</ol>




y_test y_predicted  1  2  3  4  5           1 13  1  0  0  0

<ul>

 <li>1 11 0  0  2</li>

 <li>0 0 14  0  0</li>

 <li>0 1  0 14  0</li>

 <li>0 1  0  0 12</li>

</ul>


