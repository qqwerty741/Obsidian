# 1
$$a\log^2_3-(a-3)\log_3x-2\ge0$$
$$t=\log_3x$$
$$at^2-(a-2)t-2\ge0$$
### При $a=0$
$$t-1\ge0\text{ - не подходит}$$
### При $a\ne0$ 
$$D=a^2-4a+4+8a=(a+2)^2$$
$$-\;\;\;a=-2,\;t=1$$
$$a(t-1)^2\ge0\Rightarrow(t-1)\le0\text{ - нам нравица}$$
$$a\ne-2\Rightarrow t=1,\;t=-\frac2a$$
##### $a>0$ не подходит по интервалам
##### $a<0$ не подходит т.к. $t_1\ne t_2$
### Отв.:$a=-2$
# 3
$$25^x-2(a+1)5^x+9a-5=0$$
$$t=5^x,\;t>0$$
$$t^2-2(a+1)t+9a-5=0$$
$$D=4(a^2+2a+1-36a+20)=4a^2-28a+24=4(a^2-7a+6)$$
### $D=0$
$$a^2-7a+6=0\Rightarrow (a-1)(a-6)=0\Rightarrow a_1=0,\;a_2=6$$
- $a=1\Rightarrow t=\frac{2(a+1)}{2}=2\Rightarrow x=\log_52$
- $a=6\Rightarrow t=\frac{2(a+1)}{2}=7\Rightarrow x=\log_72$
### $D>0$
$$a\in(-\infty;1)\cup(6;+\infty)$$
из которых 1 корень $\le0$, а другой корень $>0$:
$$f(0)\le0\Rightarrow9a-5\le0\Rightarrow a\le\frac59$$
### Отв.: $a\in(-\infty;\frac59]\cup\{1;6\}$
# 5
$$\frac{5a}{a-3}7^{|x|}=49^{|x|}+\frac{6a+7}{a-3}$$
$$t=7^{|x|},\;t>0$$
$$t^2-t\frac{5a}{a-3}+\frac{6a+7}{a-3}=0$$
$$D=\frac{25a^2}{(a-3)^2}-\frac{4(6a+7)(a-3)}{(a-3)^2}=\frac{a^2+44a+84}{(a-3)^2}$$
### $D=0$
$$a_1=-42,a_2=-2$$
- $a=-2,\;t=1\Rightarrow 7^{|x|}=1\Rightarrow x=0$ - неуд
- $a=-42,\;t=\frac73\Rightarrow x=\pm\log_7\frac73$
### $D>0$
$$f(0)<0\Rightarrow 1-\frac{5a}{a-3}+\frac{6a+7}{a-3}<0$$
$$a\in(-2;3)$$
### Отв.: $a\in\{-42\}\cup(-2;3)$

# 7
$$3\cdot4^x-6a\cdot2^x+3a^2+2a-14<0$$
$$t=2^x,\;t>0$$
$$3t^2-6at+3a^2+2a-14<0$$
$$D=36a^2-36a^2-24a+168=168-24a=24(7-a)$$
### $D<0$
$$7-a<0,\;a>7$$
### $D=0$
$t=7\Rightarrow 3*49-6*49+3*49+14-14<0\Rightarrow0<0$ - нить
### $D>0,\;a<7$
Оба корня $\le0$ 
$$\left\{
\begin{array}{lr}
D>0\\
x_0<0\\
f(0)\ge0
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
a<0\\
9-6a+3a^2+2a-14\ge0\\
a<7
\end{array}
\right.$$
$$3a^2+2a-14\ge0$$
$$D_1=4+168=(2\sqrt{43})^2$$
$$a=\frac{-2\pm2\sqrt{43}}{6}=\frac{-1\pm\sqrt{43}}{6}$$
$$a\in(-\infty;\frac{-1-\sqrt{43}}{3}]\cup[7;+\infty)$$
### Отв.: $a\in(-\infty;\frac{-1-\sqrt{43}}{3}]\cup[7;+\infty)$
# 9
$$\sin^2x+a\sin x=a^2-1$$
$$t^2+at-a^2+1=0$$
$$D=a^2+4a^2-4=5a^2-4$$
### $D=0$
$$a^2=\frac{4}{5}\Rightarrow a=\pm\frac{2}{\sqrt5}$$
$$t=-\frac{a}{2}=7\frac{1}{\sqrt5}$$
### $D>0$
Корни есть, если:
- оба в промежутке
$$a\in[-1;-\frac{2}{\sqrt5}]\cup[\frac{2}{\sqrt5};1]$$
- один из корней в промежутке
$$a\in[-2;-1]\cup[1;2]$$
### Отв.: $a\in[-2;-\frac{2}{\sqrt5}]\cup[\frac{2}{\sqrt5};2]$
# 11
$$4^{\sin x}+2^{\sin x}a+a^2-1=0$$
$$t=2^{\sin x}$$
$$T^2+at+a^2-1=0$$
$$D=a^2+4-4a^2=4-3a^2$$
### $D<0$
$$3a^2>4\Rightarrow a\in(-\infty; -\frac{2}{\sqrt3})\cup(\frac{2}{\sqrt3};+\infty)$$
### $D=0$
$$a=\pm\frac{2}{\sqrt3},\;t=\mp\frac{1}{\sqrt3}$$
### $D>0$
$$a\in(-\frac{2}{\sqrt3};\frac{2}{\sqrt3})$$
$$\left\{
\begin{array}{lr}
-\frac a2>2\\4+2a+a^2-1>0
\end{array}
\right.\Rightarrow a<-4$$
$$\left\{
\begin{array}{lr}
-\frac a2<\frac12\\\frac14+\frac12a+a^2-1>0
\end{array}
\right.\Rightarrow \left\{
\begin{array}{lr}
a>-1\\
\frac{1+2a+4a+4a^2-4}{4}>0
\end{array}
\right.$$
$$4a^2-2a-3>0$$
$$a_1=\frac{-2+2\sqrt{13}}{8},\;a_2=\frac{-2-2\sqrt{13}}{8}$$
$$a\in(\frac{-1+\sqrt{13}}{4};+\infty)$$
### Отв.: $a\in(-\infty;-\frac{2}{\sqrt3})\cup(\frac{-1+\sqrt{13}}{4};+\infty)$
# 13
$$(2ax+a-2a^2)(2a^2+2ax-1)<0$$
$$4a^2x^2+x(2a^3-2a+2a^2-4a^3)-4a^4+2a^3+2a^2-a<0$$
### $a=0,\;0<0$ - неуд
### Парабола вкл. в себя $[-2;2]$
$$\left\{
\begin{array}{lr}
f(-2)<0\\
f(2) <0
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
(-4a+a-2a^2)(2a^2-4a-1)<0\\
(4a+a-2a^2)(2a^2+4a-1)<0
\end{array}
\right.$$
$$a\in(-\infty;\frac{-2\sqrt6}{2})\cup(2,5;+\infty)$$
### Отв.: $a\in(-\infty;\frac{-2\sqrt6}{2})\cup(2,5;+\infty)$
# 15
$$t^2+(5a^2-a+4)t-a-2=0$$
$$-5a^2+a-4=0$$
$$D<0$$
### 2 корня
$$x_B>0\Rightarrow\frac{-5a^2+a-4}{2}>0\Rightarrow\varnothing$$
### 1 корень
$$f(0)<0\Rightarrow -a-2\le0\Rightarrow a\ge-2$$
### Отв.:$a\in[-2;+\infty)$
# 17
$$t^2+(3a^2-a+3)t+4a^2-a^4=0$$
$$3a^2-a+3\Rightarrow D<0$$
### 2 корня
$$\left\{
\begin{array}{lr}
f(0)\ge0\\
\frac{a-3a^2-3}{2}\ge0
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
a^2(2-a)(2+a)\ge0
\frac{3a^2-a+3}{2}\le0
\end{array}
\right.\Rightarrow\varnothing$$
### 1 корень
$$f(0)\le0\Rightarrow4a^2-a^4\le0\Rightarrow a^2(a-2)(a+2)\ge0$$
$$a\in(-a\infty;-2]\cup\{0\}\cup[2;+\infty)$$
### Отв.: $a\in(-\infty;-2]\cup\{0\}\cup[2;+\infty)$

# 19
$$\log_3(9^x+9a)=x,\;9^x+9a>0$$
$$9^x+9a-3^x=0$$
$$t^2-t+9a=0$$
$$D=1-36a,\;a<\frac1{36}$$
$$\left\{
\begin{array}{lr}
a<\frac1{36}\\
f(0)>0\\
x_B>0
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
a<\frac1{36}\\
9a>0
\end{array}
\right.\Rightarrow a\in(0;\frac1{36})$$

### Отв.:$a\in(0;\frac1{36})$
# 21
$$t^2-2(a+1)t+a^2+2a-8=0$$
$$D=4a^2+8a+4-4a^3-8a+32=36$$
$$f(0)<0\Rightarrow a^2+2a-8<0$$
$$(a+4)(a-2)<0$$
$$t_1=\frac{2a+8}{2}=a+4,\;t_2=a-2$$
$a+4>0$ и $a-2\le0\Rightarrow a>-4,\;a\<2$ 
### Отв.: $a\in(-4;2)$

# 23
$$2(x^2+2+\frac{1}{x^2})+(a-2)(x+\frac1x)-2=0\Rightarrow 2t^2+(a-2)t-2=0$$
$$D=a^2-4a+4+16\Rightarrow D\ge0$$
Т.к. $f(0)=-2$, корни разных знаков
$$x62-xt+1=0$$
$$D_1=t^2-4\Rightarrow |t|>2$$
$$2*4-2a+4-2<0\Rightarrow a>5$$
### Отв.: $a\in(5;+\infty)$
# 25
$$(x^2+3x)(x^2+3x+2)=0$$
$$t^2+2t-a=0$$
$t$:
$$t_B=-\frac32+\frac34$$
При $t=\frac34$ - только отр корень
При $t\in(-\frac34;0)$ - 2 корня отрицат.
$$\left\{
\begin{array}{lr}
f(-1)<0\\
f(-\frac94)>0
\end{array}
\right.\Rightarrow\left\{
\begin{array}{lr}
a>-1\\
a<\frac9{16}
\end{array}
\right.$$
$a=\frac9{16}$:
$$t^2+2t-\frac9{16}\Rightarrow D=\frac{25}4\Rightarrow t_1=\frac14,\;t_2=-\frac94$$
### Отв.: $a\in(-1;\frac9{16})$
# 27
$$t^2-4at+3a^2+4a-4=0$$
$$D=4(a-2)^2\Rightarrow a\ne2$$
$$t_1=3a-2,\;t_2=a+2\Rightarrow x>|a|$$
### $t=3a-2$
##### $a\ge0$ 
$$x=\frac{a(6^{3a-2}+1)}{6^{3a-2}}>a\Rightarrow \frac{2a}{6^{3a-2}-1}>0\Rightarrow a\in(\frac23;+\infty)$$
##### $a<0$
$$\frac{2*6^{3a-2}a}{6^{3a-2}-1}>0\Rightarrow a\in(-\infty;0)$$
### $t=a+2$
$$x=\frac{a(6^{3x-2}+1)}{6^{3a-2}-1}$$
##### $a\ge0$
$$a\in(0;+\infty)$$
##### $a<0$
$$a\in(-\infty;2)$$
### Отв.: $a\in(-\infty;-2)\cup(\frac23;2)\cup(2;+\infty)$
# 29
$$t^2-(a+9)t+2a(9-a)=0$$
$$D=(3a-9)^2=9(a-3)^2$$
### $a\ne3$:
$$t_1=2a,\;t_2=9-a$$
- $\frac{x^2-ax+1}{x-a}=2a\Rightarrow\frac{x^2-ax-2ax+1+2a^2}{x-a}=0$, $\frac{x^2-3ax+1+2a^2}{x-a}=0\Rightarrow$ ненада
- $\frac{x^2-ax+1}{x-a}=9-a\Rightarrow\frac{x^2-9x-9a-a^2+1}{x-a}=0$, $a\ne3$
### Отв.: $a\in(-\infty;-2)\cup(2;3)\cup(3;\frac72)\cup(\frac{11}2;+\infty)$

# 31
$$4\cos^2x+1-4-4\cos x-3a=0$$
$$4t^2-4t-3(1+a)=0$$
$$D=16(4+3a),\;a\ge-\frac43$$
### Больший подходит
$$\left\{
\begin{array}{lr}
f(1)\ge0\\
f(-1)\le0
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
1+a\le0\\
a\ge\frac53
\end{array}
\right.\Rightarrow\varnothing$$
### Меньший
$$\left\{
\begin{array}{lr}
f(1)\le0\\
f(-1)\ge0
\end{array}
\right.\Rightarrow a\in[-1;\frac53]$$
### оба
$$\left\{
\begin{array}{lr}
f(1)\ge0\\
f(-1)\ge0
\end{array}
\right.\Rightarrow a\in[-\frac43;1]$$
$$a\in[-\frac43;\frac53]$$
### Отв.: $-1;\;0;\;1$
# 33
$$at^2-t(6a+11)+11(a-3)<0$$
### $a=0$
$$-11\cos^2x-33<0\text{ - всегда}$$
### $a>0$
$$\left\{
\begin{array}{lr}
f(0)<0\\
f(1)<0
\end{array}
\right.\Rightarrow \left\{
\begin{array}{lr}
a<3\\
a<\frac{44}{6}
\end{array}
\right.\Rightarrow a\in(0;3)$$
### $a<0$
подходит все
### Отв.:$$a\in(-\infty;3)$$
# 35
$t^2+t(2-a)-(a-5)\le0$
### 1 корень
$$f(0)<0\Rightarrow a>5$$
### 2 корня
$$\left\{
\begin{array}{lr}
4-4a+a^2-20\ge0\\
\frac{a-2}2>0\\
a\le5
\end{array}
\right.\Rightarrow a\in[4;5]$$
### Отв.: $a\in[4;+\infty)$
# 37
$$\left\{
\begin{array}{lr}
5x^2+5-(ax^2+4x+a)\ge0\\
ax^2+4x+a>0
\end{array}
\right.$$
### 1
$$\left\{
\begin{array}{lr}
5-a>0\\
D\le0
\end{array}
\right.\Rightarrow\left\{
\begin{array}{lr}
a<5\\
(5-a)^2\ge4
\end{array}
\right.\Rightarrow a\in(-\infty;5]$$
### 2
$$\left\{
\begin{array}{lr}
a>0\\
D<0
\end{array}
\right.\Rightarrow\left\{
\begin{array}{lr}
a>0\\
a^2>4
\end{array}
\right.\Rightarrow(2;+\infty)$$
### Отв.:$a\in(2;3]$
# 39
$$2x+2y=3x^2+48y^2-a$$
$$a+\frac{17}{48}=(\sqrt3x-\frac1{\sqrt3})^2+(4\sqrt3-\frac1{4\sqrt3})$$
Уравнение окр. Единственный корень при $r=0$. $a=-\frac{17}{48}$
### Отв.: $a=-\frac{17}{48}$
# 41
$$t^2+(3+a)t-4=0$$
### 1
$$\left\{
\begin{array}{lr}
x_B\in(-1;1)\\
f(-1)\ge0\\
f(1)\ge0
\end{array}
\right.\Rightarrow a\in(-5;-1)$$
### 2
$$\left\{
\begin{array}{lr}
f(1)\le 0\\
f(-1) \ge
\end{array}
\right.\Rightarrow
a\in(-\infty;-6]$$
### 3
$$\left\{
\begin{array}{lr}
f(1)\ge0\\
f(-1)\le 0
\end{array}
\right.\Rightarrow
a\in[0;+\infty)$$
### Отв.: $a\in(-\infty;-6]\cup[0;+infty)$
# 42
$$x^2-x-(1+a)=0$$
$$x\ne0,\;1+a\ne0\Rightarrow a\ne-1$$
### $D=0$
$$a=-\frac54$$
$$x=\frac12$$
### $D>0,\; a>-\frac54$
$$\left\{
\begin{array}{lr}
f(-1)\ge0\\
f(1)>0
\end{array}
\right.\Rightarrow a\in(-\frac54;-1)$$
$$\left\{
\begin{array}{lr}
f(-1)\ge0\\
f(1)<0
\end{array}
\right.\Rightarrow
a\in(-1;1]$$
$$\left\{
\begin{array}{lr}
f(-1)\le0\\
f(1)>0
\end{array}
\right.\Rightarrow \varnothing$$
### Отв.: $a\in[-\frac54;-1)\cup(-1;1)$
# 43
$$\left\{
\begin{array}{lr}
a\le1+t-t^2\\
\left[
\begin{array}{lr}
t=-2\\
t=-\frac12
\end{array}
\right.
\end{array}
\right.$$
### $t=-\frac12$
$$a\le\frac14$$
### $t=-2a$
$$a\in(0;\frac12]$$
### Отв.: $a\in(-\infty;0]\cup\{\frac14\}$
# 44
$$t^2+t(a-8-3|a|)-(a-6)(3|a|+2)=0$$
### $a\ge0$
$$t^2-t(2a+8)-(a-6)(3a+2)=0$$
$$D=16(a-1)^2$$
$$a=1,\;t=5$$
$$a+4>0,\;f(0)\le0\Rightarrow a\in[6; +\infty)$$
###  $a<0$
$$t^2-t(4a-8)+(a-6)(3a-2)=0$$
$$D+4(a+2)^2$$
$$a=-2,\;t=8$$
$$4-2a>0,\;f(0)\le0\Rightarrow \varnothing$$
### Отв.: $a\in\{-2;1\}\cup[6;+\infty)$
# 45
$$\frac{t^2-t(2a+6)+a+3}{2t-1}$$
$$\left\{
\begin{array}{lr}
a>-3\\
a\le-2\\
a\in(-\infty;-3)\cup(-2;+\infty)\\
a\in(-3;-2]
\end{array}
\right.\Rightarrow\varnothing$$
$$\left\{
\begin{array}{lr}
f(0)>0\\
f(1)\le0
\end{array}
\right.\Rightarrow a\in[-2;+infty)$$
$$\left\{
\begin{array}{lr}
f(0)<0\\
f(1)\ge0
\end{array}
\right.\Rightarrow a\in(-\infty;-3)$$
### Отв.: $a\in(-\infty;-3)$
# 46
Используем 25
### Отв.: $a=\frac9{16}$
# 47
$$2at^2-t-1=0,\; a\ne0$$
$$\left\{
\begin{array}{lr}
D>0\\
f(i)>0\\
t_B>1
\end{array}
\right.\Rightarrow
\left\{
\begin{array}{lr}
a<\frac18\\
a>0\\
\frac{2a-1}{2a}<0
\end{array}
\right.\Rightarrow
a\in(0;\frac18)$$
### Отв.: $a\in(0;\frac18)$
