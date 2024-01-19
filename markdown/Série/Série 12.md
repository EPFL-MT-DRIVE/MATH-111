---
title: Série 12
updated: 2021-12-11 23:44:25Z
created: 2021-12-07 12:25:51Z
latitude: 46.53880000
longitude: 6.58860000
altitude: 0.0000
---

![36bca8adfce43fdc149c1134ea4e67e4.png](../../_resources/36bca8adfce43fdc149c1134ea4e67e4.png)
1)
$$(-2, 2, 3, 5)-(1,-1,0,2)=(-3, 3, 3, 3)$$
$$Q=\begin{pmatrix}
1 & -3 \\
-1 & 3 \\
0 & 3 \\
2 & 3 \\
\end{pmatrix}$$
$$R=\begin{pmatrix}
6 & 6 \\
0 & 36 \\
\end{pmatrix}$$
$$\begin{pmatrix}
1 & -1 & 0 & 2 \\
-3 & 3 & 3 & 3 \\
\end{pmatrix}\begin{pmatrix}
1 & -3 \\
-1 & 3 \\
0 & 3 \\
2 & 3 \\
\end{pmatrix} \begin{pmatrix}
x\\
y \\
\end{pmatrix} =\begin{pmatrix}
1 & -1 & 0 & 2 \\
-3 & 3 & 3 & 3 \\
\end{pmatrix}\begin{pmatrix}
3 \\
1 \\
-4 \\
2 \\
\end{pmatrix} $$

$$\begin{pmatrix}
6 & 6 \\
0 & 36 \\
\end{pmatrix} \begin{pmatrix}
x\\
y \\
\end{pmatrix} =\begin{pmatrix}
6 \\
-12 \\
\end{pmatrix} $$

$$\begin{pmatrix}
1/6 & -1/36 \\
0 & 1/36 \\
\end{pmatrix} \begin{pmatrix}
6 \\
-12 \\
\end{pmatrix} =\begin{pmatrix}
4/3\\
-1/3 \\
\end{pmatrix} $$

2)

$$\begin{pmatrix}
1 & -2 \\
-1 & 2 \\
0 & 3 \\
2 & 5 \\
\end{pmatrix} \begin{pmatrix}
4/3\\
-1/3 \\
\end{pmatrix} =\begin{pmatrix}
2 \\
-2 \\
-1 \\
1 \\
\end{pmatrix} $$
$$||\begin{pmatrix}
2 \\
-2 \\
-1 \\
1 \\
\end{pmatrix} -\begin{pmatrix}
3 \\
1 \\
-4 \\
2 \\
\end{pmatrix}||=||\begin{pmatrix}
-1 \\
-3\\
3 \\
-1 \\
\end{pmatrix}||=\sqrt{20}$$
erreur  = racine(20)
![44fee60c0b56e42c663bc077bc99a1d4.png](../../_resources/44fee60c0b56e42c663bc077bc99a1d4.png)
$$X\beta=y$$
$$\begin{pmatrix}
0 & 1\\
0 & 1\\
0 & 1\\
1 & 1\\
\end{pmatrix}\begin{pmatrix}
\beta_1 \\
\beta_0 \\
\end{pmatrix}=\begin{pmatrix}
0\\
1\\
2\\
3\\
\end{pmatrix}$$
$$Q=\begin{pmatrix}
0 & 1/\sqrt(3)\\
0 & 1/\sqrt(3)\\
0 & 1/\sqrt(3)\\
1 & 0\\
\end{pmatrix}$$
$$R=\begin{pmatrix}
1 & 1\\
0 & 3/\sqrt(3)\\
\end{pmatrix}$$
$$R^{-1}=\begin{pmatrix}
1 & -1\\
0 & \sqrt(3)/3\\
\end{pmatrix}$$
$$\beta= R^{-1}Q^Ty$$
$$\begin{pmatrix}
1 & -1\\
0 & \sqrt(3)/3\\
\end{pmatrix}\begin{pmatrix}
3\\
3/\sqrt{3}\\
\end{pmatrix}=\begin{pmatrix}
3-3/\sqrt{3}\\
1\\
\end{pmatrix}$$
$$y=1+(3-3/\sqrt{3})x$$
![01a66dee2583a7f6282287bb3d088f81.png](../../_resources/01a66dee2583a7f6282287bb3d088f81.png)
![3cb36077101eaea3a390994dccc99498.png](../../_resources/3cb36077101eaea3a390994dccc99498.png)
ATTENTION A METTRE LES VECTEUR COLLONE DE AX+B DANS LE BON ORDRE
$$X\beta=y$$
$$\begin{pmatrix}
-1 & 1\\
0 & 1\\
1 & 1\\
2 & 1\\
\end{pmatrix}\begin{pmatrix}
\beta_1 \\
\beta_0 \\
\end{pmatrix}=\begin{pmatrix}
0\\
1\\
2\\
4\\
\end{pmatrix}$$
$$v_1=x_1$$ 
$$v_2=x_2-\frac{\braket{u_2, v_1}}{||v_1||^2}v_1$$
$$(1,1,1,1)-1/3(-1,0,1,2) =(4/3, 1, 2/3, 1/3)$$
$$14/9+9/9+4/9+1/9=\sqrt(28)/3$$
$$Q=\begin{pmatrix}
-1/\sqrt6 & 4/\sqrt(28)\\
0 & 3/\sqrt(28)\\
1/\sqrt6 & 2/\sqrt(28)\\
2/\sqrt6 & 1/\sqrt(28)\\
\end{pmatrix}$$

$$R=\begin{pmatrix}
\sqrt6 & 1/3*\sqrt6\\
0 & 5/\sqrt{7}\\
\end{pmatrix}$$
$$R^{-1}=\begin{pmatrix}
1/\sqrt6 & -1/15*\sqrt7\\
0 & \sqrt7/5\\
\end{pmatrix}$$
$$\beta= R^{-1}Q^Ty$$

$$\begin{pmatrix}
1/\sqrt6 & -1/15*\sqrt7\\
0 & \sqrt7/5\\
\end{pmatrix}\begin{pmatrix}
-1/\sqrt6 & 4/\sqrt(28)\\
0 & 3/\sqrt(28)\\
1/\sqrt6 & 2/\sqrt(28)\\
2/\sqrt6 & 1/\sqrt(28)\\
\end{pmatrix}\begin{pmatrix}
0\\
1\\
2\\
4\\
\end{pmatrix}=\begin{pmatrix}
1/\sqrt6 & -1/15*\sqrt7\\
0 & \sqrt7/5\\
\end{pmatrix}\begin{pmatrix}
10/\sqrt6\\
 11/2\sqrt{7}\\
\end{pmatrix}=\begin{pmatrix}
113/70\\
11/1\\
\end{pmatrix}$$

$$y=113/70+11/10$$

$$\begin{pmatrix}
-1 & 1\\
0 & 1\\
1 & 1\\
2 & 1\\
\end{pmatrix} \begin{pmatrix}
113/70\\
11/10\\
\end{pmatrix} =\begin{pmatrix}
-36/70 \\
11/10 \\
190/70 \\
303/70 \\
\end{pmatrix} $$
![3d77a6004f8d1b6341c1c3e154d60604.png](../../_resources/3d77a6004f8d1b6341c1c3e154d60604.png)
![27d0c656d57a7e27aa5349fcd6d399a5.png](../../_resources/27d0c656d57a7e27aa5349fcd6d399a5.png)
$$R=\begin{pmatrix}
7 & 7\\
0 & 7\\
\end{pmatrix}$$
![9855b14d49a558add4868d256f21e89a.png](../../_resources/9855b14d49a558add4868d256f21e89a.png)
$$\begin{pmatrix}
1 & 2 & 5\\
-1 & 1 & -4\\
-1 & 4 & -3\\
1 & -4 & 7\\
1 & 2 & 1\\
\end{pmatrix}$$
$$v_2=x_2-\frac{\braket{u_2, v_1}}{||v_1||^2}v_1$$
$$(1, -1, -1, 1, 1)/\sqrt{5}$$
$$(2, 1, 4, -4, 2)+5/5(1, -1, -1, 1, 1)=(3,0,3,-3,3)/6$$
$$(5, -4, -3, 7, 1)-4(1, -1, -1, 1, 1)+3(3,0,3,-3,3)=(10,0, 10, -6, 6)/\sqrt{272}$$
$$Q= \begin{pmatrix}
1 & 1/2 & 10/\sqrt{272}\\
-1 & 0 & 0\\
-1 & 1/2 & 10/\sqrt{272}\\
1 & -1/2 &  -6/\sqrt{272}\\
1 & 1/2 & 6/\sqrt{272}\\
\end{pmatrix}$$

$$R= \begin{pmatrix}
5/\sqrt{5} & -5/\sqrt{5} & 20/\sqrt{5}\\
0 & 6 & -2\\
0 & 0 & -16/\sqrt{272}\\
\end{pmatrix}$$
![fe96398c9ca9f741577144b00cc91e1a.png](../../_resources/fe96398c9ca9f741577144b00cc91e1a.png)

$$\begin{pmatrix}
1/3 & -5\\
0 & 1 \\
\end{pmatrix}\begin{pmatrix}
2/3 & 2/3 & 1/3\\
-1/3 & 2/3 & -2/3\\
\end{pmatrix}\begin{pmatrix}
7\\
3\\
1\\
\end{pmatrix}=\begin{pmatrix}
1/3 & -5\\
0 & 1 \\
\end{pmatrix}\begin{pmatrix}
7\\
-1\\
\end{pmatrix}=\begin{pmatrix}
22/3\\
-1\\
\end{pmatrix}$$