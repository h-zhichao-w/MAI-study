# Lab 2 Report

Student Name: Zhichao Wang

Student Email: hansen_wong@sjtu.edu.cn

[toc]

## Parameters

![image-20230330222137519](C:\Users\hanse\AppData\Roaming\Typora\typora-user-images\image-20230330222137519.png)

## Sketch of the Part

![image-20230330231827664](C:\Users\hanse\AppData\Roaming\Typora\typora-user-images\image-20230330231827664.png)

## Dimensional Chain

### Determination

The nominal value of the closing link is calculated by the formula:  

$\mathrm{A}_{0}=\sum^{n} A \uparrow-\sum^{p} A \downarrow = 100 - (32+45)=23 \text{ mm}\\$

The limiting dimensions of the closing link are written out according to the formulas:  

$A_{0 \max }=\sum^{n} A_{\max } \uparrow-\sum^{p} A_{\min } \downarrow = 100.054-(32+45)=23.054 \text{ mm}\\$ 

$A_{0 \min }=\sum^{n} A_{\min } \uparrow-\sum^{p} A_{\max } \downarrow = 100 - (32.039+45.039) = 22.922 \text{ mm}\\$

### Calculation

According to the data given,

$\begin{array}{l}
\mathrm{ES}\left(\mathrm{A}_{1}\right)=54 ; \mathrm{EI}\left(\mathrm{A}_{1}\right)=0 \\
\mathrm{ES}\left(\mathrm{A}_{2}\right)=39 ; \mathrm{EI}\left(\mathrm{A}_{2}\right)=0 \\
\mathrm{ES}\left(\mathrm{A}_{3}\right)=39 ; \mathrm{EI}\left(\mathrm{A}_{3}\right)=0
\end{array}$

Deviations of the closing link are calculated by the formulas:  

$\operatorname{ES}\left(A_{0}\right)=\sum^{n} E S(A \uparrow)-\sum^{p} E I(A \downarrow) = 54 - (0+0)=54 \text{ }\mu\text{m}\\$

$\operatorname{EI}\left(A_{0}\right)=\sum^{n} E I(A \uparrow)-\sum^{p} E S(A \downarrow) = 0 - (39+39)=-78 \text{ }\mu\text{m}\\$

The tolerance of the closing link is determined by the formula:  

$T_{A_0} =\operatorname{ES}\left(A_{0}\right)-\operatorname{EI}\left(A_{0}\right)=54-(-78)=132 \text{ }\mu\text{m}$

## Q&A

1. What is called a dimensional chain?

   A dimensional chain determines the distance or relative rotation between the surfaces or axes of the part surfaces in the product, i.e., a dimensional chain is for solving tasks of ensuring accuracy in the design of products  

2. What is called the closing link of the dimensional chain?

   The closing link ($A_0$) is an element in a dimensional chain that is the initial one when setting a task or the last one as a result of its solution.  

3. Which chain links are called increasing, and which are decreasing?  

   A link is called increasing if such an element of the dimensional chain increase with the closing element, and it is called reducing if such an element increases while the closing element reduces.