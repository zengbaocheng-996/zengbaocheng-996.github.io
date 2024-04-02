---
title: "meta"
collection: math
permalink: /math/meta
---

# 集合 运算 关系

## 运算

### 交

<img src="1.png" style="zoom: 33%;" />
$$
A\cap B\\
AB
$$

### 并

<img src="2.png" style="zoom: 25%;" />
$$
A\cup B\\
A+B
$$

### 差

<img src="3.png" style="zoom: 25%;" />
$$
A-B\\
A\backslash B
$$

### 补

<img src="4.png" style="zoom: 33%;" />
$$
\overline A
$$

## 关系

### 包含

<img src="5.png" style="zoom:33%;" />
$$
A\sub B
$$

### 互斥（不相容）

<img src="6.png" style="zoom: 50%;" />
$$
\forall x\in A\Rightarrow x\notin B,
\forall x\in B\Rightarrow x\notin A\\
即AB=\emptyset
$$

### 对立

<img src="7.png" style="zoom:10%;" />
$$
\forall x\in A\Rightarrow x\notin B,
\forall x\in B\Rightarrow x\notin A\\
且x\in\Omega\Rightarrow x\in A或x\in B\\
即AB=\emptyset且A+B=\Omega\\
或\overline A=B
$$

---

<img src="8.png" style="zoom: 25%;" />
$$
A=(A-B)+AB\\
且A-B与AB互斥
$$

$$
A+B=(A-B)+AB+(B-A)\\
且A-B,AB,B-A两两互斥
$$

# 三角 反三角

## 三角

$$
\sec x=\frac{1}{\cos x}\\
\csc x=\frac{1}{\sin x}\\
$$

$$
\sec^2x=1+\tan^2x\\
\csc^2x=1+\cot^2x
$$

$$
\sin\frac{x}{2}=\pm\sqrt{\frac{1-\cos x}{2}}\\
\csc\frac{x}{2}=\pm\sqrt{\frac{1+\cos x}{2}}
$$

## 反三角

$$
y=f(x)单调\Rightarrow\exist反函数
$$

$$
y=\sin x, x\in[-\frac{\pi}{2},\frac{\pi}{2}]\\
y=\cos x, x\in[0,\pi]\\
$$

---

<img src="9.png" style="zoom: 33%;" />
$$
y=\arcsin x
$$

$$
\begin{align}
&1.~x\in[-1,1],y\in[-\frac{\pi}{2},\frac{\pi}{2}]\\
&2.~y=\arcsin x为奇函数
\end{align}
$$

---

<img src="10.png" style="zoom: 33%;" />
$$
y=\arccos x
$$

$$
x\in[-1,1],y\in[0,\pi]\\
$$

---

<img src="11.png" style="zoom:25%;" />
$$
y=\arctan x
$$

$$
\begin{align}
&1.~x\in(-\infin,+\infin),y\in(-\frac{\pi}{2},\frac{\pi}{2})\\
&2.~y=\arctan x为奇函数
\end{align}
$$

---

<img src="12.png" style="zoom:8%;" />
$$
y=arccot ~x
$$

$$
x\in(-\infin,+\infin),y\in(0,\pi)
$$

---

$$
\begin{align}
&1.~\arcsin x+\arccos x =\frac{\pi}{2},(-1\leq x\leq 1)\\
&2.~\arctan x+arccot~x =\frac{\pi}{2},(-\infin\leq x\leq+\infin)\\
\end{align}
$$

# 常见不等式与数列

$$
\begin{align}
&1.~0\leq ||a|-|b||\leq|a\pm b|\leq |a|+|b|\\
&2.~a_i\geq0(1\leq i\leq n)\\
&~~~~\sqrt[n]{a_1...a_n}\leq\frac{a_1+...+a_n}{n}\\
&~~~~几何平均数\leq代数平均数
\end{align}
$$

