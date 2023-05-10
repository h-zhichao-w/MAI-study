[toc]

# Parts and Assemblies Engineering Lab 2

Student Name: Zhichao Wang
Student Email: hansen_wong@sjtu.edu.cn
Varient №: 5
Unit System: Si unit (mm)

## 1. Task variant and Maximum Tensile Load
Type of stringers: **420069**
P, N: **2700**

$P_{max\_str} = 35100$ N

Dimensions:
![](https://notes.sjtu.edu.cn/uploads/upload_5779511386a6054fe568527ca5ecba95.png)


## 2. Materials of stringers, pad and skin
![](https://notes.sjtu.edu.cn/uploads/upload_08d1e096f782c7d9d67cf2e15c0d784a.png)

In this task I choose the **ВТ20** as the materials of stringers, pad and skin.


## 3. Diameter of rivet
$d_{rivet}=2\sqrt{t_{str}+t_{skin}+t_{pad}} = 2\sqrt{1.5 + 1.5 + 1.5}=4.243\rightarrow5$ mm

## 4. Tensile Stress
$\sigma = P_{max\_str} / A_{str\_without\_rivet} = 35100/(82-5\cdot1.5)=471.14$ MPa.
$[\sigma] = 0.8\cdot\sigma_{B,str} = 0.8\cdot1000=800$ MPa.

$\sigma \leq [\sigma]$ is **True**.

## 5. Coefficient of safety
$\eta=[\sigma]/\sigma=1.7$

## 6. Requirable Number of Rivets
According to OST 1 34104-80, the rivet shear force for double-sided riveting made of steel 12X18H9T with a diameter of 5 mm is 9810 N.

$n_{rivet}=P_{max\_str}/P_{max\_riv} = 35100/9810=3.58$

To increase the margin of safety, we choose the number of rivets n = 5.


## 7. Bearing Stringer
$\sigma=P_{max\_riv}/(d_{rivet}\cdot t_{str}) = 9810/(5\cdot1.5)=1308$ MPa $\leq 1.5\sigma_{B,str}=1500$ MPa.

## 8. Coefficient of safety
$\eta=[\sigma]/\sigma_{bearing}=1500/1308=1.15$

## 9. Edge Distance
$2\cdot d_{rivet} = 10$ mm
$2\cdot d_{rivet} + 2= 12$ mm

Set the edge distance $a=12$ mm.

## 10. Actual shear stress
$\tau_{act}=\frac{P_{max\_riv}}{2at_{str}}=\frac{9810}{2\cdot 12\cdot1.5}=272.5$ MPa $<\tau_B=500$ MPa.

## 11. Analysis of Pad
$\sigma_{bearing,pad}=\frac{P_{max\_riv}}{d_{rivet}\cdot t_{str}} = 9810/(5\cdot1.5)=1308$ MPa $\leq 1.5\sigma_{B,pad}=1500$ MPa.

## 12. Tension Failure of A-A
$b_{min,A-A}=\frac{k\cdot P_{max\_riv}}{t_{pad}\cdot\sigma_{B\_pad}}+n_{rivet,A-A}\cdot d_{rivet}=\frac{1.2\cdot9810}{1.5\cdot1000}+1\cdot5=12.85$ mm.

$\sigma_{A-A} = P_{str}/[t_{pad}\cdot(b_{min}-n_{rivet,A-A}\cdot d_{rivet})] =596.18$ MPa $\leq [\sigma]_{bear} = 1500$ MPa.

However, due to that the overlay should not be narrower than the stringer, which is 30 mm in width, the value is rounded to $b_{A-A}=32$ mm.

## 13. Tension Failure of B-B
$b_{min,B-B}=\frac{k\cdot P_{max\_riv}}{t_{pad}\cdot\sigma_{B\_pad}}+n_{rivet,B-B}\cdot d_{rivet}=\frac{1.2\cdot9810}{1.5\cdot1000}+1\cdot5=12.85$ mm.

$\sigma_{B-B} = P_{str}/[t_{pad}\cdot(b_{min}-n_{rivet,B-B}\cdot d_{rivet})] = 2675.16$ MPa $> [\sigma]_{bear} = 1500$ MPa.

The value is rounded to $b_{B-B}=35$ mm so that $\sigma_{B-B} = 700$ MPa is less than $[\sigma]_{bear}$.

## 14. Length of the rivet
$t_{stringer\_skin}=t_{str}+t_{skin}=1.5+1.5=3$ mm.
$t_{total}=t_{str}+t_{skin}+t_{pad}=1.5+1.5+1.5=4.5$ mm.

![](https://notes.sjtu.edu.cn/uploads/upload_ca1b57a0d19ab9ced2d6b615c4d23413.png)

According to the table, for the first case, the 10-ОСТ1 10642-72 rivet with the length of 6.5-8.0 mm. For the second case, the 11-ОСТ1 10642-72 rivet with the length of 8.0-9.5 mm.

## 15. The Sketch
![image-20230407204309488](C:\Users\hanse\AppData\Roaming\Typora\typora-user-images\image-20230407204309488.png)





