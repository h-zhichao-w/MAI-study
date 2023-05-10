# Lab 3

Student Name: Zhichao Wang

Student E-mail: hansen_wong@sjtu.edu.cn

Unit System: Si unit

[toc]

## Pre-setting

![](https://notes.sjtu.edu.cn/uploads/upload_3ee75c5480fe8b421ff228e64ddc733b.png)

Variant №: 1

For fixed joint, $P=160000$ N, and for sliding joint, $P=145000$ N.

![](https://notes.sjtu.edu.cn/uploads/upload_080067914895fa52093de2b69e94ec67.png)

Materials of eye and double eye are chosen to be **ВТ20** while the material of the bolt complex is chosen to be **30ХГСА**.

## Fixed joint

### Determine the bolt diameter

#### From shear stress

$\tau_{cut}=\frac{P_{cut}}{A_{cut}}=\frac{2P}{\pi d^2}\Rightarrow d_{bolt}\geq\sqrt{\frac{2P}{\pi \tau_{ult}}}=12.12 \text{ mm}\\$

We round up to 16 mm.

$\tau_{cut}=\frac{2P}{\pi d^2}=398 \text{ MPa}\\$

$\eta = \frac{\tau_{ult}}{\tau_{cut}} = 1.7\\$

#### From max cutting load of the bolt

![](https://notes.sjtu.edu.cn/uploads/upload_9df100997cd84411f9201ac80b185750.png)

According to the table, $[P_{cut}]=120700 \text{ N}$

$P_{cut} = 80000 \text{ N} \leq [P_{cut}]=120700 \text{ N}$ is true.

$\eta = \frac{[P_{cut}]}{P_{cut}} = 1.5\\$

### Crumpling stress of the eye

For the eye, $a_{eye}=\frac{P}{d\cdot \sigma_{ult}} =\frac{160000}{0.016\cdot 10^9} =10 \text{ mm}\\$.

For the double eye, $a_{double\_eye}=\frac{P/2}{d\cdot \sigma_{ult}} =\frac{80000}{0.016\cdot 10^9} =5 \text{ mm}\\$.

Thus, $[\sigma_{crump}]=K\sigma_{ult}=1000 \text{ MPa}$

$\sigma_{eye}=\frac{P}{d\cdot a_{eye}}=\frac{160000}{0.016\cdot0.01}=1000 \text{ MPa}\\$

$\sigma_{double\_eye}=\frac{P/2}{d\cdot a_{double\_eye}} =\frac{80000}{0.016\cdot 0.005} =1000\text{ MPa}\\$

$\eta_{eye}=\eta_{double\_eye}=1$

### Determine the length of the bolt

![img](http://www.ost-1.ru/image/data/ost/ost_1_33047-80_ost_1_33048-80_ost_1_33049-80_ost_1_33050-80_ost_1_33051-80_ost_1_33052-80_ost_1_33053-80_ost_1_33054-80_ch.jpg)

We will use a low self-locking hex nut. According to *ОСТ 1 33048-80 Гайки шестигранные прорезные низкие сталь*, we select a nut from steel 30ХГСА. Thread - M16x1.5. Nut height $H=9$ mm. Turnkey size $S=22$ mm. Head diameter $D_1=24.6$ mm and $D_2=21$ mm.

![img](http://www.ost-1.ru/image/data/ost/ost_1_34505-80_ost_1_34506-80_ost_1_34507-80_ost_1_34508-80_ost_1_34509-80_ost_1_34510-80_ost_1_34511-80_ost_1_34512-80_ost_1_34513-80_ch.jpg)

Take the washer from steel 30ХГСА according to *ОСТ 1 34507-80 Шайбы сталь*, we have $d_1=17$ mm and $d_2=32$ mm, and its height is 2 mm.

Taking into account the protruding threaded part of the bolt from the nut and its chamfer (according to the design rules, the threaded part of the bolt should protrude from the nut by 1-2 turns), then add the following value in addition to the bolt size:

$\Delta l=1.5\times2+1.5=4.5$ mm.

$L = a_{eye} + 2a_{double\_eye} +\delta_{washer}+\delta_{nut}=10+10+9+2+4.5=35.5$ mm.

We round up to $L=36$ mm.

There is a standard bolt length according to *ОСТ 1 31132-80 Болты с шестигранной уменьшенной головкой и короткой резьбовой частью сталь* 36 mm.

### Strength Design on break load

For the eye structure,

${x={\frac{P_{\mathrm{break}}}{2\cdot a\cdot\sigma_{\mathrm{ut}}}}}=\frac{160000}{2\cdot0.01\cdot10^9}=8\\$ mm.

$\sigma_{\mathrm{break,eye}}={\frac{P_{\mathrm{break}}}{A_{\mathrm{break}}}}={\frac{P_{\mathrm{break}}}{(b-d)\cdot a}}=\frac{P_{\mathrm{break}}}{2\cdot a\cdot x}=\frac{160000}{2\cdot0.01\cdot 0.008}=1000\text{ MPa}\\$

$[\sigma_{\mathrm{break,eye}}] = K_\text{break}\sigma_\text{ult}=\left(0.565+0.48\cdot{\frac{y}{x}}-0,1\cdot{\frac{b}{a}}\right)\sigma_\text{ult}=(0.565+0.48\cdot1.4-0.1\cdot2)\cdot1000=1037 \text{ MPa}$

$\sigma_{\mathrm{break,eye}}\leq[\sigma_{\mathrm{break,eye}}]$ is true.

$\eta_\text{eye}=\frac{[\sigma_{\mathrm{break,eye}}]}{\sigma_{\mathrm{break,eye}}}= 1.037\\$

For the double-eye structure,

$\sigma_{\mathrm{break,double-eye}}={\frac{P_{\mathrm{break}}}{A_{\mathrm{break}}}}={\frac{P_{\mathrm{break}}}{(b-d)\cdot a}}=\frac{P_{\mathrm{break}}}{2\cdot a\cdot x}=\frac{80000}{2\cdot0.005\cdot 0.008}=1000\text{ MPa}\\$

$[\sigma_{\mathrm{break,double-eye}}] = K_\text{break}\sigma_\text{ult}=\left(0.565+0.48\cdot{\frac{y}{x}}-0,1\cdot{\frac{b}{a}}\right)\sigma_\text{ult}=(0.565+0.48\cdot1.4-0.1\cdot2)\cdot1000=1037 \text{ MPa}$

$\sigma_{\mathrm{break,double-eye}}\leq[\sigma_{\mathrm{break,double-eye}}]$ is true.

$\eta_\text{double-eye}=\frac{[\sigma_{\mathrm{break,double-eye}}]}{\sigma_{\mathrm{break,double-eye}}}= 1.037\\$

### Strength Design on cutting

From the drawing, $y^*=16.3$ mm.

For the eye structure,

$\tau_{\mathrm{cut,eye}}={\frac{P_{\mathrm{cut}}}{F_{\mathrm{cut}}}}={\frac{P_{\mathrm{cp}}}{2\cdot a\cdot y^{*}}} = \frac{160000}{2\cdot 0.01\cdot0.0163}=490.8\\$ MPa.

$[\tau_\text{cut,eye}]=500$ MPa.

$\tau_{\mathrm{cut,eye}}\leq[\tau_\text{cut,eye}]$ is true.

$\eta_\text{eye}=\frac{[\tau_\text{cut,eye}]}{\tau_{\mathrm{cut,eye}}}=1.02\\$.

For the double-eye structure,

$\tau_{\mathrm{cut,double-eye}}={\frac{P_{\mathrm{cut}}}{F_{\mathrm{cut}}}}={\frac{P_{\mathrm{cp}}}{2\cdot a\cdot y^{*}}} = \frac{80000}{2\cdot 0.005\cdot0.0163}=490.8\\$ MPa.

$[\tau_\text{cut,double-eye}]=500$ MPa.

$\tau_{\mathrm{cut,double-eye}}\leq[\tau_\text{cut,double-eye}]$ is true.

$\eta_\text{double-eye}=\frac{[\tau_\text{cut,double-eye}]}{\tau_{\mathrm{cut,double-eye}}}=1.02\\$.

## Sliding joint/Small-sliding joints

### Determine the bolt diameter

#### From shear stress

$\tau_{cut}=\frac{P_{cut}}{A_{cut}}=\frac{2P}{\pi d^2}\Rightarrow d_{bolt}\geq\sqrt{\frac{2P}{\pi \tau_{ult}}}=11.54 \text{ mm}\\$

We round up to 14 mm.

$\tau_{cut}=\frac{2P}{\pi d^2}=471\text{ MPa}\\$

$\eta = \frac{\tau_{ult}}{\tau_{cut}} = 1.47\\$

#### From max cutting load of the bolt

According to the table, $[P_{cut}]=10500\text{ N}$

$P_{cut} = 72500 \text{ N} \leq [P_{cut}]=105000\text{ N}$ is true.

$\eta = \frac{[P_{cut}]}{P_{cut}} = 1.45\\$

### Eye thickness

![img](http://www.ost-1.ru/image/data/ost/ost_1_11123-73_ost_1_11124-73_ost_1_11125-73_ost_1_11126-73_ost_1_11127-73_ch.jpg)

#### Сrumpling along the inner diameter *d* of the bush

$[\sigma_{\mathrm{CM}}]=K_{\mathrm{CM}}\cdot\sigma_{\mathrm{B}}=0.2\cdot1000=200$ MPa.

$\sigma_{\mathrm{CM}}=\frac{P_{\mathrm{CM}}}{F_{\mathrm{CM}}}=\frac{P_{\mathrm{CM}}}{2 \cdot d \cdot\left(L_{\mathrm{BT}}+b\right)} \Rightarrow \left(L_{\mathrm{BT}}+b\right)=\frac{P_{\mathrm{CM}}}{2 \cdot d \cdot\left[\sigma_{\mathrm{CM}}\right]}=\frac{145000}{2 \cdot 14 \cdot 200}=25.9 \\$ mm.

According to *ОСТ 1 11127-73 Втулки с буртиком для запрессовки бронза*, $b=1.5$ mm. We choose $L_\text{BT}=30$ mm.

$a_1=2\cdot30+2=62$ mm

$\sigma_{\mathrm{CM}}={\frac{P_{\mathrm{CM}}}{F_{\mathrm{CM}}}}={\frac{P_{\mathrm{CM}}}{2\cdot d\cdot(L_{\mathrm{BT}}+b)}}={\frac{145000}{2\cdot14\cdot(30+1.5)}}=164.4\\$ MPa.

$\eta=\frac{[\sigma_\text{CM}]}{\sigma_\text{CM}}=\frac{200}{164.4}=1.22\\$.

#### Сrumpling along the outer diameter *D* of the bush

According to *ОСТ 1 11127-73 Втулки с буртиком для запрессовки бронза*, $D=17$ mm and $D_1=21$ mm.

$[\sigma_{\mathrm{CM}}]=K\cdot\sigma_{\mathrm{B}}=1\cdot1000=1000$ MPa.

$L_\text{BT}=\frac{P_\text{CM}}{2\cdot D\cdot \sigma_B}=\frac{145000}{2\cdot17\cdot1000}=4.26\rightarrow6\\$ mm. 

$a_2=2\cdot6+2=14$ mm.

$\sigma_\text{CM}=\frac{P_\text{CM}}{2\cdot D\cdot L_\text{BT}}=\frac{145000}{2\cdot17\cdot6}=710.78\\$ MPa.

$\eta=\frac{[\sigma_\text{CM}]}{\sigma_\text{CM}}=\frac{1000}{710.78}=1.41\\$.

Of the two options, choose the largest eye thickness. Then $a=62$ mm.

### Bolted connection parameters

We will use a low self-locking hex nut. According to *ОСТ 1 33048-80 Гайки шестигранные прорезные низкие сталь*, we select a nut from steel 30ХГСА. Thread - M14x1.5. Nut height $H=8$ mm. Turnkey size $S=19$ mm. Head diameter $D_1=21.1$ mm and $D_2=18$ mm.

Take the washer from steel 30ХГСА according to *ОСТ 1 34507-80 Шайбы сталь*, we have $d_1=15$ mm and $d_2=28$ mm, and its height is 2 mm.

$\Delta l=1.5\times2+1.5=4.5$ mm.

$L = 62+10+2\cdot1.5+8+2+4.5=89.5$ mm.

We round up to 90 mm.

### Check on tensile strength

$K_{\mathrm{break}}=0.565+0.48\cdot1-0.1\cdot2=0.845$

$\left[\sigma_{\mathrm{break}}\right]=K_{\mathrm{break}}\cdot\sigma_{\mathrm{B}}=0.845\cdot1000=845$ MPa.

$x={\frac{P}{2\cdot{a}\cdot K_{\mathrm{break}}\cdot\sigma_{\mathrm{B}}}}={\frac{145000}{2\cdot62\cdot0.845\cdot1000}}=1.38\Rightarrow x=2\\$ mm.

$b=2x+D=2\cdot2+17=21$ mm.

$\sigma_{\mathrm{break}}=\frac{P}{F_{\mathrm{break}}}=\frac{P}{(b-D)\cdot a}=\frac{145000}{(21-17)\cdot62}=584.68\\$ MPa.

$\eta=\frac{\left[\sigma_{\mathrm{break}}\right]}{\sigma_{\mathrm{break}}}=\frac{845}{584.68}=1.45\\$.

### Check on shear strength

From the drawing, $y^*=9.7$ mm.

$\tau_{\mathrm{cp}}=\frac{P_{\mathrm{cp}}}{2\cdot a\cdot y^{*}}=\frac{145000}{2\cdot62\cdot9.7}=120.55\\$ MPa.

$[\tau_{\mathrm{cp}}]=\tau_{\mathrm{B}}=500$ MPa.

$\eta=\frac{[\tau_{\mathrm{cp}}]}{\tau_{\mathrm{cp}}}=\frac{500}{120.55}=4.15\\$.

## Design Parameters

### Fixed joint

#### Eye

Material: ВТ20

Thickness: $a=10$ mm

Diameter: $d=16$ mm

$x=8$ mm

$y^*=16.3$ mm

$b=32$ mm

#### Double Eye

Material: ВТ20

Thickness: $a=5$ mm

Diameter: $d=16$ mm

$x=8$ mm

$y^*=16.3$ mm

$b=32$ mm

#### Bolt

Material: 30ХГСА

Diameter: $d=16$ mm

Height:  $H=9$ mm

Turnkey size: $S=22$ mm

Head diameter: $D_1=24.6$ mm and $D_2=21$ mm

Length: $L=36$ mm

#### Washer

Material: 30ХГСА

$d_1=17$ mm 

$d_2=32$ mm

Height: $h=2$ mm

### Sliding joint

#### Eye

Material: ВТ20

Diameter: $d=17$ mm

$a=62$ mm

$x=2$ mm

$b=21$ mm

$y^*=9.7$ mm

#### Double eye

Material: ВТ20

Diameter: $d=14$ mm

$x=2$ mm

$b=21$ mm

$y^*=9.7$ mm

#### Bolt

Material: 30ХГСА

Diameter: $d=14$ mm

Height: $H=8$ mm

Turnkey size $S=19$ mm

Head diameter $D_1=21.1$ mm and $D_2=18$ mm

$L=90$ mm

#### Sleeve

Material: Bronze

$b=1.5$ mm

$L = 30$ mm

$D=17$ mm

$D_1=21$ mm

$d=14$ mm

#### Washer

Material: 30ХГСА

$d_1=15$ mm and $d_2=28$ mm

Height: $h=2$ mm

## Sketch

![image-20230409162302540](C:\Users\hanse\AppData\Roaming\Typora\typora-user-images\image-20230409162302540.png)

![image-20230424230248001](C:\Users\hanse\AppData\Roaming\Typora\typora-user-images\image-20230424230248001.png)
