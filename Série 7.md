![254638d001d998fbda6b904835e91ac9.png](../../_resources/254638d001d998fbda6b904835e91ac9.png)
a) Dim(Ker(T))=2
b) Dim(Ker(T))=4
c) Dim(Ker(T))=3
![c510375ca75876ea7feddb7302353122.png](../../_resources/c510375ca75876ea7feddb7302353122.png)
1) T est linéaire car le zero est conservé et le critère de linéarité aussi
$$T*(\alpha*A)=\alpha*TA $$
2)
$$
\begin{pmatrix}
a & b\\
c & d\\
\end{pmatrix}
\to
\begin{pmatrix}
a & c+b\\
c+b & d\\
\end{pmatrix}
$$
$$
\begin{pmatrix}
1 & 0 & 0 & 0\\
0 & 1 & 1 & 0\\
0 & 1 & 1 & 0\\
0 & 0 & 0 & 1\\
\end{pmatrix}
$$ 
Donc le rang = 3, ker = 1
La matrice n'est pas surjective
3) La matrice n'est pas injective
4) c'est un SEV car il contient l'élément nul et est compatible avec le critère
$$
\begin{pmatrix}
0 & b\\
-b & 0\\
\end{pmatrix}$$
![dcce607927c6bc2d72e88a1441a8d192.png](../../_resources/dcce607927c6bc2d72e88a1441a8d192.png)
$$P_{BC}\begin{pmatrix}
2 & -1\\
-1 & 1\\
\end{pmatrix}$$

$$T_{CC}\begin{pmatrix}
1 & 1\\
3 & 1\\
\end{pmatrix}$$

$$P_{CB}\begin{pmatrix}
1 & 1\\
1 & 2\\
\end{pmatrix}$$
$$T_{BB}=P_{BC}T_{CC}P_{CB}=\begin{pmatrix}
2 & -1\\
-1 & 1\\
\end{pmatrix}\begin{pmatrix}
2 & 3\\
4 & 5\\
\end{pmatrix}=\begin{pmatrix}
0 & 1\\
2 & 2\\
\end{pmatrix}$$
![bbc277f319ded2c9de4acb9e6cca37cd.png](../../_resources/bbc277f319ded2c9de4acb9e6cca37cd.png)
$$P_{E'E}\begin{pmatrix}
0.5 & 0.5 & 0\\
0.5 & -0.5 & 0\\
 -0.5 & -0.5 & 1\\
\end{pmatrix}$$
$$
[T]_{EE}\begin{pmatrix}
2 & 1 & -1\\
3 & 4 & -5\\
3 & 3 & -4\\
\end{pmatrix}$$

$$P_{EE'} \begin{pmatrix}
1 & 1 & 0\\
1 & -1 & 0\\
1 & 0 & 1\\
\end{pmatrix}$$

$$T_{E'E'}=P_{E'E}T_{EE}P_{EE'}=\begin{pmatrix}
0.5 & 0.5 & 0\\
0.5 & -0.5 & 0\\
 -0.5 & -0.5 & 1\\
\end{pmatrix}\begin{pmatrix}
2 & 1 & -1\\
2 & -1 & -5\\
2 & 0 & -4\\
\end{pmatrix}=\begin{pmatrix}
2 & 0 & -3\\
0 & 1 & 2\\
0 & 0 & -1\\
\end{pmatrix}$$
![37a422bd09c6474af30ddca5c5710a56.png](../../_resources/37a422bd09c6474af30ddca5c5710a56.png)
![6d4c3c0f579f44bcdca600c0d8d268be.png](../../_resources/6d4c3c0f579f44bcdca600c0d8d268be.png)
1) il est de dimmension 1
2) on peut prendre la base cacnonique de R3
3) l'application est surjective mais pas injective

![7a148d041b1cb0df9c6793bd16a7ae21.png](../../_resources/7a148d041b1cb0df9c6793bd16a7ae21.png)
$$f(\lambda a + b)= \lambda f(a)+f(b)  $$
1) l'application est linéaire car elle restpecte le critère de linéairité a(T(x))=T(ax) et elle envoie le zero dans le noyau
2) la dimmension de l'image est 1, une base : {(1,1)}
3) le noyau est de dimmension 2
4) Base {(x^2-x),(x)}


![2b7e0ea8b7c9b242bb7cc97dad500b09.png](../../_resources/2b7e0ea8b7c9b242bb7cc97dad500b09.png)
$$ f(x,y,z)=(2x-4y+2z, 5x+3y-2z)$$
$$g(x,y)=(x,x+y,x-y, y) $$
a) matrice de f et g
$$[f]_{EE}: \begin{pmatrix}
2 & -4 & 2\\
5 & 3 & -2\\
\end{pmatrix}$$
$$[g]_{EE}: \begin{pmatrix}
1 & 0\\
1 & 1\\
1 & -1\\
0 & 1\\
\end{pmatrix}$$
b)
$$g \circ f = (2x-4y+2z,2x-4y+2z+5x+3y-2z,2x-4y+2z-5x-3y+2z, 5x+3y-2z)$$
$$g \circ f =[g]_{EE} [f]_{EE}=\begin{pmatrix}
2 & -4 & 2\\
7 & -1 & 0\\
-3 & -7 & 4\\
5 & 3 & -2\\
\end{pmatrix}$$

dimmesnion noyau : 1
dimmensio image = 2
base noyau : (1,7,13)
base image : {(2,7,-3,5),(-4,-1,-7,3)}

![7563e28f766d7f170d24b3b78d2f4b88.png](../../_resources/7563e28f766d7f170d24b3b78d2f4b88.png)
$$A= \begin{pmatrix}
1 & 3 & 3\\
-3 & -2 & 4\\
-2 & 1 & 7\\
\end{pmatrix}$$

$$A= \begin{pmatrix}
1 & 3 & 3\\
0 & 7 & 13\\
0 & 7 & 13\\
\end{pmatrix}$$

$$W= \begin{pmatrix}
18\\
-13\\
7\\
\end{pmatrix}$$

w est dans le noyau.
![6062cb06dcb89f98c3ddc867ba947288.png](../../_resources/6062cb06dcb89f98c3ddc867ba947288.png)
l'application est bijective si a est différent de 1
![f1d6d04e10ace144ba88c2d746eafd55.png](../../_resources/f1d6d04e10ace144ba88c2d746eafd55.png)
B : (A-I)(A+I)=A^2-I
![10d07ec252973a5a8a39332cd5aaa0af.png](../../_resources/10d07ec252973a5a8a39332cd5aaa0af.png)
B: dimV=8
![907e8114463e0100a01e65d803ad0600.png](../../_resources/907e8114463e0100a01e65d803ad0600.png)
C: 3x5
![4f1aaf1334f2108c514738beade158ae.png](../../_resources/4f1aaf1334f2108c514738beade158ae.png)
D: SEV R^2 de dim 1
![3baaf1d631229533800fe56853e14682.png](../../_resources/3baaf1d631229533800fe56853e14682.png)
C: SEV R^4 de dim 1
![e33c9d7715ed29094bd916f47bbc1594.png](../../_resources/e33c9d7715ed29094bd916f47bbc1594.png)
C:isomorphe
![bfed3eb49a67a2e14309a5c756116233.png](../../_resources/bfed3eb49a67a2e14309a5c756116233.png)
A : dim KerA =5 et dim ImA =2
![439c0c9ffe5e33ad2ec7049d990f4588.png](../../_resources/439c0c9ffe5e33ad2ec7049d990f4588.png)
ligne linéairement indépendante
![d7cb1f6bdebd4518748ad31194674e92.png](../../_resources/d7cb1f6bdebd4518748ad31194674e92.png)
dim kerT=2 dimImT =1
![c39250d1d8675917a3edc280bd57ff32.png](../../_resources/c39250d1d8675917a3edc280bd57ff32.png)
C : -2-t+3t^2, 2-3t^2
![44887c1f09be08c706cdc6a0bb07de95.png](../../_resources/44887c1f09be08c706cdc6a0bb07de95.png)
a)
Dim(Im(T))=2
base Im(T)={(1+t),(1+t^2)}
b)
dim Ker(T)=2
Base(Ker(2))={(-1+t),(-t^2+t^3)}
c)
dans la base : (5,2)
d)
dans la base : (-2,5)
![6418c55c06fad58e7ec1468029ee1cb4.png](../../_resources/6418c55c06fad58e7ec1468029ee1cb4.png)
1) 
plan donc deux vecteur directeur : 
{(1, -1, 1),(2, -1, 0)}
2)
l'application est surjective mais pas injective
3)
l'application est injective mais pas surjective
![3b0227778f1cca10832cd245c9d7f0ee.png](../../_resources/3b0227778f1cca10832cd245c9d7f0ee.png)
1)
$$[P]_{EE}=\begin{pmatrix}
1 & 1\\
1 & 1\\
\end{pmatrix}$$
$$[P]_{BB}=\begin{pmatrix}
1 & 0\\
0 & 0\\
\end{pmatrix}$$
$$[P]_{BE}=[I]_{BE}[P]_{EE}\begin{pmatrix}
1 & 1\\
0 & 0\\
\end{pmatrix}$$
$$[P]_{EB}=[P]_{BB}[I]_{BE}\begin{pmatrix}
1 & 0\\
1 & 0\\
\end{pmatrix}$$

$$[I]_{BE}=\begin{pmatrix}
1 & 1\\
1 & -1\\
\end{pmatrix}
$$
2)
$$[P]_{EE}=\begin{pmatrix}
0 & 1\\
1 & 0\\
\end{pmatrix}$$
$$[P]_{BB}=\begin{pmatrix}
1 & 0\\
0 & -1\\
\end{pmatrix}$$
$$[P]_{BE}=[I]_{BE}[P]_{EE}\begin{pmatrix}
1 & 1\\
1 & -1\\
\end{pmatrix}$$
$$[P]_{EB}=[I]_{BE}[P]_{EE}\begin{pmatrix}
0.5 & -0.5\\
-0.5 & -0.5\\
\end{pmatrix}$$

3)
$$
\begin{pmatrix}
0 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1\\
\end{pmatrix}$$
4)
$$fait:\begin{pmatrix}
0 & 1\\
1 & 0\\
\end{pmatrix}\begin{pmatrix}
0 & 1\\
1 & 0\\
\end{pmatrix}=\begin{pmatrix}
1 & 0\\
0 & 1\\
\end{pmatrix}$$
![02f68adde429117e8c44bcc386e5c897.png](../../_resources/02f68adde429117e8c44bcc386e5c897.png)
1) 
l'application n'est ni surjective ni injective
2) dim(Ker(T))=4  dim(Im(T))=2
3).
4)
![7672dc1e1b2ff31e215cba8bfbb02cfb.png](../../_resources/7672dc1e1b2ff31e215cba8bfbb02cfb.png)

![dc9219067e0d8978b0dd2648d2428cf9.png](../../_resources/dc9219067e0d8978b0dd2648d2428cf9.png)


$$
\begin{pmatrix}
5 & 1 & 2 & 2 & 0\\
3 & 3 & 2 & -1 & -12\\
8 & 4 & 4 & -5 & 12\\
2 & 1 & 1 & 0 & -2\\
\end{pmatrix}$$

$$\begin{pmatrix}
1 & 2 & 1 & -1 & -14\\
0 & -3 & -1 & 2 & 26\\
0 & 0 & 0 & 1 & -8\\
0 & 0 & 0 & 0 & 1\\
\end{pmatrix}$$
1)
Dim(Ker(C))=1
ker(C)={}

2)
Im(C)={(1,0,0,0),(0,1,0,0),(0,0,1,0),(0,0,0,1)}

3)
l'application est surjecgtive mais pas injective.
