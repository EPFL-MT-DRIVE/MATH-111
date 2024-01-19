![8c8408e9a6ffab7c6f4e7620f109a34e.png](../../_resources/8c8408e9a6ffab7c6f4e7620f109a34e.png)
![38dabbf2d503689836a6a839b990dfe6.png](../../_resources/38dabbf2d503689836a6a839b990dfe6.png)
![76da046c9d9f48c99a61022d8d6d820f.png](../../_resources/76da046c9d9f48c99a61022d8d6d820f.png)
demander point C
$$A=\begin{pmatrix}
0 & 0 & 2 & 0\\
1 & 0 & 1 & 0\\
0 & 1 & -2 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}$$ 

$$B=\begin{pmatrix}
10 & -9 & 0 & 0\\
4 & -2 & 0 & 0\\
0 & 0 & -2 & 7\\
0 & 0 & 1 & 2\\
\end{pmatrix}$$ 

a)
$$A=\begin{pmatrix}
-t & 0 & 2 & 0\\
1 & -t & 1 & 0\\
0 & 1 & -2-t & 0\\
0 & 0 & 0 & 1-t\\
\end{pmatrix}$$
$$(1-t)(2-2t²-t³+t)$$
(SARRUS)
$$A=\begin{pmatrix}
-t & 0 & 2 \\
1 & -t & 1 \\
0 & 1 & -2-t \\
\end{pmatrix}$$
$$(1-t)(-t³-2t²+t+2)$$
$$(1-t)(t-1)(-t²-3t-2)$$
$$(t-1)(t-1)(t+1)(t+2)$$
1:
$$A=\begin{pmatrix}
-1 & 0 & 2 & 0\\
1 & -1 & 1 & 0\\
0 & 1 & -3 & 0\\
0 & 0 & 0 & 0\\
\end{pmatrix} \times \begin{pmatrix}
a \\ b \\ c \\ d \\
\end{pmatrix}$$
$$A=\begin{pmatrix}
-1 & 0 & 2 & 0\\
0 & -1 & 3 & 0\\
0 & 0 & 0 & 0\\
0 & 0 & 0 & 0\\
\end{pmatrix} \times \begin{pmatrix}
2 \\ 3 \\ 1 \\ 0 \\
\end{pmatrix} or 
 \begin{pmatrix}
0 \\ 0 \\ 0 \\ 1 \\
\end{pmatrix} $$
-1:
$$A=\begin{pmatrix}
1 & 0 & 2 & 0\\
0 & 1 & -1 & 0\\
0 & 0 & 0 & 2\\
0 & 0 & 0 & 0\\
\end{pmatrix} \times \begin{pmatrix}
-2 \\ 1 \\ 1 \\ 0 \\
\end{pmatrix}$$
-2:
$$A=\begin{pmatrix}
1 & 0 & 1 & 0\\
0 & 1 & 0 & 0\\
0 & 0 & 0 & 1\\
0 & 0 & 0 & 0\\
\end{pmatrix} \times \begin{pmatrix}
1 \\ 0 \\  -1 \\ 0 \\
\end{pmatrix}$$

Espace propre de A :
$$vect(\begin{pmatrix} 1 \\ 0 \\  -1 \\ 0 \\ \end{pmatrix}, 
\begin{pmatrix} -2 \\ 1 \\ 1 \\ 0 \\ \end{pmatrix},
\begin{pmatrix} 2 \\ 3 \\ 1 \\ 0 \\ \end{pmatrix},
 \begin{pmatrix} 0 \\ 0 \\ 0 \\ 1 \\ \end{pmatrix}) $$
 
 $$B=\begin{pmatrix}
10-t & -9 & 0 & 0\\
4 & -2-t & 0 & 0\\
0 & 0 & -2-t & 7\\
0 & 0 & 1 & 2-t\\
\end{pmatrix}$$ 
$$((10-t)(-2-t)+36)((-2-t)(2-t)-7)$$
$$(t²-8t+16)(t²-11)$$
 $$(t-4)(t-4)(t-\frac{\sqrt{44}}{2})(t+\frac{\sqrt{44}}{2})$$
 4:
 $$B=\begin{pmatrix}
6& -9 & 0 & 0\\
4 & -6 & 0 & 0\\
0 & 0 & -6 & 7\\
0 & 0 & 1 & -2\\
\end{pmatrix}$$ 
 $$B=\begin{pmatrix}
2 & -3 & 0 & 0\\
0 & 0 & 0 & 0\\
0 & 0 & 1 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}\times \begin{pmatrix}
3 \\ 2 \\  0 \\ 0 \\
\end{pmatrix}$$

\frac{\sqrt{44}}{2}:
 $$B=\begin{pmatrix}
10-\sqrt{11} & -9 & 0 & 0\\
4 & -2-\sqrt{11} & 0 & 0\\
0 & 0 & -1 & -2+\sqrt{11}\\
0 & 0 & 0 & 0\\
\end{pmatrix}\times \begin{pmatrix}
0 \\ 0 \\  -2+\sqrt{11} \\ 1 \\
\end{pmatrix}$$ 

-\frac{\sqrt{44}}{2}:
 $$B=\begin{pmatrix}
10-3\sqrt{11} & 2-2\sqrt{11} & 0 & 0\\
4 & -2+\sqrt{11} & 0 & 0\\
0 & 0 & -2+\frac{\sqrt{44}}{2} & 7\\
0 & 0 & 1 & 2+\frac{\sqrt{44}}{2}\\
\end{pmatrix}\times \begin{pmatrix}
0 \\ 0 \\  -2-\sqrt{11} \\ 1 \\
\end{pmatrix}$$ 

Espace propre de B :
$$vect(\begin{pmatrix}0 \\ 0 \\  -2-\sqrt{11} \\ 1 \\\end{pmatrix},
\begin{pmatrix}0 \\ 0 \\  -2+\sqrt{11} \\ 1 \\ \end{pmatrix},
 \begin{pmatrix} 3 \\ 2 \\  0 \\ 0 \\ \end{pmatrix}) $$

b)
A est diagonalisablea
B n'est pas Diagonalisablea

c)
Question valeur propre de combinaison linéaire de matrice ?
seule A est diagonalisable
$$P^{-1}AP=P^{-1}\begin{pmatrix}
0 & 0 & 2 & 0\\
1 & 0 & 1 & 0\\
0 & 1 & -2 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}P=A=\begin{pmatrix}
1 & 0 & 0 & 0\\
0 & -1 & 0 & 0\\
0 & 0 & -2 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}$$
construire a partir des vecteur de la base
$$P_CB=\begin{pmatrix}
1 & -2 & 2 & 0\\
0 & 1 & 3 & 0\\
-1 & 1 & 1 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}$$

![1efa703b1cead08a6d8084f616d45dcf.png](../../_resources/1efa703b1cead08a6d8084f616d45dcf.png)

$$\pi-1, \pi+3$$
$$B=\begin{pmatrix}
\pi & 1 & 1 & 1 \\
1 & \pi  & 1 & 1 \\
1 & 1 & \pi & 1 \\
1 & 1 & 1 & \pi \\
\end{pmatrix}$$

$$B=\begin{pmatrix}
1 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 \\
\end{pmatrix} \times \begin{pmatrix}
1\\ -1\\ 0\\ 0 \\
\end{pmatrix}, \begin{pmatrix}
0\\ -1\\ 1\\ 0 \\
\end{pmatrix}, \begin{pmatrix}
0\\ 0\\ 1\\ -1 \\
\end{pmatrix}$$

$$B=\begin{pmatrix}
0 & 0 & 0 & 0 \\
1 & -3 & 0 & 0 \\
0 & 4 & -4 & 0 \\
0 & 0 & 4 & -4 \\
\end{pmatrix}\times \begin{pmatrix}
3\\ 1\\ 1\\ 1 \\
\end{pmatrix}$$



![f99d471c70a9485c36162a433d616137.png](../../_resources/f99d471c70a9485c36162a433d616137.png)
$$A=PDP^{-1}=\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix} \times \begin{pmatrix}
x^n & 0 \\
0 & y^n \\
\end{pmatrix} \times \frac{1}{ad-bc}\begin{pmatrix}
d & -b \\
-c & a \\
\end{pmatrix} = \begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix} \times \begin{pmatrix}
x^nd & -x^nb \\
-cy^n & y^na \\
\end{pmatrix}=\begin{pmatrix}
ax^nd-bcy^n & aby^n-ax^nb \\
cx^nd-dcy^n & ady^n-cx^nb \\
\end{pmatrix}$$

$$\begin{pmatrix}
5-t & -6 \\
3 & -4-t \\
\end{pmatrix} $$
$$(t²-t-2)=(t-2)(t+1)$$
2:
$$\begin{pmatrix}
3 & -6 \\
0 & 0 \\
\end{pmatrix}=(2,1) $$
-1:
$$\begin{pmatrix}
6 & -6 \\
0 & 0 \\
\end{pmatrix}=(1,1) $$

$$A=PDP^{-1}=\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix} \times \begin{pmatrix}
1024 & 0 \\
0 & 1 \\
\end{pmatrix} \times \begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}=\begin{pmatrix}
1024 & -1024 \\
-1 & 2 \\ 
\end{pmatrix} = \begin{pmatrix}
2047 & -2046 \\
1023 & -1022 \\
\end{pmatrix}$$



![eff2825d629f5180ee9f7f57dfb4809d.png](../../_resources/eff2825d629f5180ee9f7f57dfb4809d.png)
$$\begin{pmatrix}
2 & 0  & -1\\
0 & -1 & 0\\
-1 & 0 & 2\\
\end{pmatrix} $$
a)
$$\begin{pmatrix}
2-t & 0  & -1\\
0 & -1-t & 0\\
-1 & 0 & 2-t\\
\end{pmatrix} $$
(-1-t)(t^2-4t+3)
(-1-t)(t-1)(t-3)
-1      1      3
b)
-1:
$$\begin{pmatrix}
1 & 0  & 0\\
0 & 0 & 0 \\
0 & 0 & 1\\
\end{pmatrix} =(0,1,0)$$

1:
$$\begin{pmatrix}
1 & 0  & -1\\
0 & -2 & 0\\
0 & 0 & 0\\
\end{pmatrix} =(1,0,1)$$

3:
$$\begin{pmatrix}
-1 & 0  & -1\\
0 & -4 & 0\\
0 & 0 & 0\\
\end{pmatrix} =(1,0,-1)$$


on montre que l'espace propre est égal à S2 en montrant que les vecteur de la base propre sont combinaison linaéire de C
c)
$$\begin{pmatrix}
-1 & 0  & 0\\
0 & 1 & 0\\
0 & 0 & 3\\
\end{pmatrix}$$
d)
$$A_B=(2,2,-1)$$
$$T^{10}=\begin{pmatrix}
1 & 0  & 0\\
0 & 1 & 0\\
0 & 0 & 59 049\\
\end{pmatrix}$$
$$T(A_B)=(2,2,-59 049)$$
$$P_{CB}\begin{pmatrix}
0 & 1  & 1 \\
1 & 0 & 0  \\
0 & 1 & -1 \\
\end{pmatrix}$$

$$T(A)_C=(-59 047, 2,59 051)$$

$$T(A)=\begin{pmatrix}
0 & 2  & -59 049 \\
2 & 0 & 0  \\
0 & 2 & 59 049 \\
\end{pmatrix}$$
![58ebf2516c99f66841999dc35ba58554.png](../../_resources/58ebf2516c99f66841999dc35ba58554.png)
a) 1 3 et 4
b) sa dimmension est comprise en 3 et 6
c) sa dimmension est 6
d) il existe au moins une valeurs propre en commun avec A
e)
$$C=\begin{pmatrix}
1 & 0 & 0 & 0 & 0 & 0\\
0 & 3 & 0 & 0 & 0 & 0\\
0 & 0 & 3 & 0 & 0 & 0\\
0 & 0 & 0 & 4 & 0 & 0\\
0 & 0 & 0 & 0 & 4 & 0\\
0 & 0 & 0 & 0 & 0 & 4\\
\end{pmatrix}$$
$$D=\begin{pmatrix}
1 & 0 & 0 & 0 & 0 & 0\\
0 & 3 & 1 & 0 & 0 & 0\\
0 & 0 & 3 & 0 & 0 & 0\\
0 & 0 & 0 & 4 & 0 & 0\\
0 & 0 & 0 & 0 & 4 & 0\\
0 & 0 & 0 & 0 & 0 & 4\\
\end{pmatrix}$$
on rajoute un 1 entre deux valeurs propre identique ( ne change pas la valeurs propre mais introduit un pivot quand on calcul le vecteur propre de la dit valeur qui fout le bordel)
t^2-16
![5b8ae34d8b46ec48a0fc83911248cf7d.png](../../_resources/5b8ae34d8b46ec48a0fc83911248cf7d.png)
1) non
2) non
3) (0, 30)
4) v est le plus distant

![93af4cd8a2cda186a8b40e16d4b5ab95.png](../../_resources/93af4cd8a2cda186a8b40e16d4b5ab95.png)
u=(3,-1,5)
v=(6,-2,3)
1)
$$u * v=36$$
$$u * u=35$$
$$v * v=49$$
$$||u||=\sqrt{35}$$
$$||v||=7$$
2)
$$||u-v||=\sqrt{9+1+4}=\sqrt{14}$$
3)
$$(3,-1,5)-\frac{36}{35}(6,-2,3)$$
$$((3,-1,5),((3,-1,5)-\frac{36}{35}(6,-2,3))))$$
ou alors la droite perpendiculaire :
(1, 3, 0)
(produit vectorielle)
![8b82f5f9b97399e38c4840700f8b7ff9.png](../../_resources/8b82f5f9b97399e38c4840700f8b7ff9.png)
![5a8a5f7e64faf9f26d37bc896cf3e164.png](../../_resources/5a8a5f7e64faf9f26d37bc896cf3e164.png)
$$\braket{f,g}=\int_0^{1}(f'(x)g'(x)+f(x)g(x))=\int_0^{1}(g'(x)f'(x)+g(x)f(x))=\braket{g,f}$$

$$\braket{e+f,g}=\int_0^{1}((f'(x)+h'(x))g'(x)+(e(x)+f(x))g(x))=\int_0^{1}(f'(x)g'(x)+h'(x)g'(x)+e(x)g(x)+f(x)g(x))=\braket{hg}+\braket{f,g}$$

$$\alpha \braket{f,g}=\alpha \int_0^{1}(f'(x)g'(x)+f(x)g(x))=\int_0^{1}(\alpha g'(x)f'(x)+\alpha g(x)f(x))=\braket{\alpha g,f}=\braket{g,\alpha 
f}$$

$$\braket{f,f}=\int_0^{1}(f'(x)f'(x)+f(x)f(x))\geq 0$$
----
$$p(x)=a_0+a_1x+a_2x²$$
$$\braket{p,q}=a_0b_0+2a_1b_1+3a_2b_2$$

$$\braket{p,q}=a_0b_0+2a_1b_1+3a_2b_2=b_0a_0+2b_1a_1+3b_2a_2=\braket{q,p}$$
$$\braket{n+p,q}=(x_0+a_0)b_0+2(x_1+a_1)b_1+3(x_2+a_2)b_2=x_0b_0+2x_1b_1+3x_2b_2+b_0a_0+2b_1a_1+3b_2a_2=\braket{p,q}+\braket{n,q}$$

$$\alpha \braket{p,q}=\alpha (a_0b_0+2a_1b_1+3a_2b_2)=\alpha b_0a_0+\alpha 2b_1a_1+\alpha 3b_2a_2=\braket{\alpha q,p}=\braket{q,\alpha p}$$

$$\braket{p,p}=a_0a_0+2a_1a_1+3a_2a_2 \geq 0$$
(car (-1)(-1)=1 et (1)(1)=1)

----
$$v=(v_1, v_2, v_3, v_4)$$
$$\braket{v,w}=v_1w_1+2v_2w_2+v_3w_3+3v_4w_4$$

$$\braket{v,w}=v_1w_1+2v_2w_2+v_3w_3+3v_4w_4=w_1v_1+2w_2v_2+w_3v_3+3w_4v_4=\braket{w,v}$$

$$\braket{u+v,w}=(u_1+v_1)w_1+(u_1+2v_2)w_2+(u_1+v_3)w_3+(u_1+3v_4)w_4=w_1u_1+2w_2u_2+w_3u_3+3w_4u_4+w_1v_1+2w_2v_2+w_3v_3+3w_4v_4=\braket{v,w}+\braket{u,w}$$

$$\braket{v,v}=v_1v_1+2v_2v_2+v_3v_3+3v_4v_4\geq 0$$
(car (-1)(-1)=1 et (1)(1)=1)
![f3e6df1a9cc059973dbd0641cc672f68.png](../../_resources/f3e6df1a9cc059973dbd0641cc672f68.png)
dim KerA=0 mais 0 n'est pas valeur prorpre de A
![1207498c582e833ab39bdf5e3ae3e984.png](../../_resources/1207498c582e833ab39bdf5e3ae3e984.png)
A a pour valeur propre de A 1 et -1
![f1f9a6529f4478543b4caa9206c65d1e.png](../../_resources/f1f9a6529f4478543b4caa9206c65d1e.png)
a) faux,
1 0
0 0 
est diagonal donc diagonalisable mais pas inversible
b)
vrai
c) Faux (multiplicité géométrique de 1 peut etre égal a 1 )
d) Vrai
![3b249f3d1f36f3fc15e6fbe249b577a8.png](../../_resources/3b249f3d1f36f3fc15e6fbe249b577a8.png)
$$\int^{\pi}_{-\pi}cos(nx)cos(mx)dx=0$$
cos est une fonction paire
le produit de deux fonction paire est paire
l'intégrale d'une fonction paire est  impaire
f(x)+f(-x)=0
![1228270d35874b7ad4c2762d118dbf1c.png](../../_resources/1228270d35874b7ad4c2762d118dbf1c.png)
$$A=\begin{pmatrix}
3 & -1\\
1 & 5\\
\end{pmatrix}$$
1)
$$(3-t)(5-t)+1=t^2-8t+16=(t-4)^2$$
2)
$$A=\begin{pmatrix}
3-4 & -1\\
1 & 5-4\\
\end{pmatrix}$$
$$A=\begin{pmatrix}
-1 & -1\\
1 & 1\\
\end{pmatrix}$$
$$A=\begin{pmatrix}
-1 & -1\\
0 & 0\\
\end{pmatrix}$$
$$v_4=(1,-1)$$
espace propre est une droite.

----
$$B=\begin{pmatrix}
4 & 0 & 0\\
1 & 4 & 0\\
0 & 0 & 5\\
\end{pmatrix}$$
1)
$$(t-5)(t-4)(t-4)$$
4:
$$B=\begin{pmatrix}
0 & 0 & 0\\
1 & 0 & 0\\
0 & 0 & 5\\
\end{pmatrix}$$
$$v_4=(0,1,0)$$
5:
$$B=\begin{pmatrix}
-1 & 0 & 0\\
0 & -1 & 0\\
0 & 0 & 0\\
\end{pmatrix}$$
$$v_4=(0,0,1)$$

l'espace propre est un plan de base 
$$B((0,0,1), (0,1,0))$$
----