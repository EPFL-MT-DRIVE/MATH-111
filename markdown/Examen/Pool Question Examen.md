---
title: Pool Question Examen
updated: 2022-01-02 20:48:51Z
created: 2022-01-01 20:19:57Z
latitude: 46.52670000
longitude: 6.62430000
altitude: 0.0000
---

2020
![d414c25a31c1df221e37ad88ed279ffd.png](../../_resources/d414c25a31c1df221e37ad88ed279ffd.png)
vérifier manuellement  les 4 matrices telle que le produit avec v1 v2 et v3 donne leurs valeurs propres donc  on trouve :
$$A= \begin{pmatrix}
1 & 0 & 0\\
0 & 1 & -1\\
0 & -1 & 1\\
\end{pmatrix}$$

![6f19c35ba41f972960dc692c47608397.png](../../_resources/6f19c35ba41f972960dc692c47608397.png)
on soustrait la valeurs propre a A et on échellonne.
on fait attentioni au collones de zero
$$A-I=\begin{pmatrix}
-3 & 0 & 0 & -2\\
0 & 0 & -2 & 0\\
0 & 0 & 0 & 4\\
0 & 0 & 0 & 2\\
\end{pmatrix}\begin{pmatrix}
0\\
a\\
0\\
0\\
\end{pmatrix}=0$$
la dimmension = 1
![cb4d5510aa98e1ca8d70bcfe0a7634d3.png](../../_resources/cb4d5510aa98e1ca8d70bcfe0a7634d3.png)
on inverse manuellement la matrices. ça prend du temps
$$A=\begin{pmatrix}
1 & 2 & 3 & | & 1 & 0 & 0\\
0 & 1 & 2& | & 0 & 1 & 0\\
4 & 0 & -1& | & 0 & 0 & 1\\
\end{pmatrix}$$
$$A=\begin{pmatrix}
1 & 0 & -1 & | & 1 & -2 & 0\\
0 & 1 & 2& | & 0 & 1 & 0\\
0 & 0 & 1& | & -4/3 & 8/3 & 1/3\\
\end{pmatrix}$$
$$A=\begin{pmatrix}
1 & 0 & 0 & | & -1/3 & 2/3 & 1/3\\
0 & 1 & 0 & | & 8/3 & -13/3 & -2/3\\
0 & 0 & 1 & | & -4/3 & 8/3 & 1/3\\
\end{pmatrix}$$
$$b_{23}=-2/3$$
![90d03e21f54562cc93c50bdd7e51a491.png](../../_resources/90d03e21f54562cc93c50bdd7e51a491.png)
on calcule le determinant avec -t sur la diagonale
$$A= \begin{pmatrix}
1-t & 0 & -1\\
4 & 1-t & 2\\
0 & 1 & 3-t\\
\end{pmatrix}$$
$$A= \begin{pmatrix}
1-t & 0 & -1\\
4 & 1-t & 2\\
0 & 1 & 3-t\\
\end{pmatrix}$$
soit sarrus soit introduction de zero
$$-2(1-t)-4+(1-t)(1-t)(3-t)$$

on regarde lecoeef du premier et dernier terme pour gagner du temps
$$-\lambda^3+5\lambda ^2-5\lambda-3$$
on vérifie
$$-t^3+5t^2-5t-3$$
![b5e120c269dca78d041c386d2b758b0a.png](../../_resources/b5e120c269dca78d041c386d2b758b0a.png)
méthode rapide de factorisation LU
on note dans la matrice L (identité carré les cooefficient de combien on enleve)
$$A= \begin{pmatrix}
1 & 2 & 0 & 1\\
2 & 3 & 1 & 0\\
0 & 1 & 2 & 4\\
1 & 0 & 3 & 2\\
\end{pmatrix}$$
$$L= \begin{pmatrix}
1 & 0 & 0 & 0\\
2 & 1 & 0 & 0\\
0 & 0 & 1 & 0\\
1 & 0 & 0 & 1\\
\end{pmatrix}$$
$$U= \begin{pmatrix}
1 & 2 & 0 & 1\\
0 & -1 & 1 & -2\\
0 & 1 & 2 & 4\\
0 & -2 & 3 & 1\\
\end{pmatrix}$$
$$L= \begin{pmatrix}
1 & 0 & 0 & 0\\
2 & 1 & 0 & 0\\
0 & -1 & 1 & 0\\
1 & 2 & 0 & 1\\
\end{pmatrix}$$
$$U= \begin{pmatrix}
1 & 2 & 0 & 1\\
0 & -1 & 1 & -2\\
0 & 0 & 3 & 2\\
0 & 0 & 1 & 5\\
\end{pmatrix}$$
$$L= \begin{pmatrix}
1 & 0 & 0 & 0\\
2 & 1 & 0 & 0\\
0 & -1 & 1 & 0\\
1 & 2 & 1/3 & 1\\
\end{pmatrix}$$
$$U= \begin{pmatrix}
1 & 2 & 0 & 1\\
0 & -1 & 1 & -2\\
0 & 0 & 3 & 2\\
0 & 0 & 0 & 13/3\\
\end{pmatrix}$$

ATTENTION AU SIGNE INVERSE ET A FINIR LES LIGNES

![37c8d5fa418af5a3885e8f6393076c8a.png](../../_resources/37c8d5fa418af5a3885e8f6393076c8a.png)
rang= dimmension espace arrivé
donc collones linéairemetn dépendante pour <3

$$A= \begin{pmatrix}
1 & 1 & 3\\
1 & 3 & 4\\
-2 & -4 & \alpha\\
\end{pmatrix}$$
$$A= \begin{pmatrix}
1 & 1 & 3\\
0 & 2 & 1\\
0 & -2 & 6+\alpha\\
\end{pmatrix}$$
$$A= \begin{pmatrix}
1 & 1 & 3\\
0 & 2 & 1\\
0 & 0 & 7+\alpha\\
\end{pmatrix}$$
$$si \alpha = -7$$
alors rang < 3

![5a92f7fe5e795a8e96bef162744ec046.png](../../_resources/5a92f7fe5e795a8e96bef162744ec046.png)
vérifier si base orthogonale et normale des propositions.
si toutes conditions alors gramschmidt
pas orthogonal
orthogonal
pas orthognal
pas orthogonal
on vérifier que la base orthognal est bien l'autre.
(meme pas besoin car R3 et 3 vecteur indépendant
donc on as 
0    1    -4/3
1    1     2/3
1   -1    -2/3
![5b0ac32f3a42507d4745a7fded57da5a.png](../../_resources/5b0ac32f3a42507d4745a7fded57da5a.png)
on regarde si on as des vecteur orthogonaux qui engendre le meme espaceque u1 et u2 (les deux premier vecteu de la base trouvé avant car leurs combinaison linéaire donne u1 et u2)
puis on fait la projection du vecteur sur chaque vecteur de la base et on recombine
-4
2
-2
comme vecteur perpendiculaire a la projection
$$proj_v(u)=\frac{\braket{u,v}}{\braket{v,v}}v$$
projection orthogonale de u sur v
3/2(0,1,1)+(5/3)(1,1,-1)=(5/3, 19/6, -1/6)
$$A= \begin{pmatrix}
5/3\\
19/6\\
-1/6\\
\end{pmatrix}$$
![53408ca01f530e223f5f6c783bb2544e.png](../../_resources/53408ca01f530e223f5f6c783bb2544e.png)
on applique la formule des moindre carré
$$A^T A \hat x=A^Tb$$
3 -1   a  -2
-2 3   b  4
3/7 1/7    -2/7
2/7 3/7    8/7

$$\hat x_2 = 8/7$$
![361e64bea4c1b64a7eb360bc250aa3c7.png](../../_resources/361e64bea4c1b64a7eb360bc250aa3c7.png)
pareil mais en plus long et chiant
$$A^T A \hat x=A^Tb$$
$$\begin{pmatrix}
10 & 8 & 7\\
8 & 9 & 12\\
7 & 12 & 21\\
\end{pmatrix}\begin{pmatrix}
x\\
y\\
z\\
\end{pmatrix}=\begin{pmatrix}
4\\
6\\
9\\
\end{pmatrix}$$
$$\begin{pmatrix}
10 & 8 & 7 & 4\\
8 & 9 & 12 & 6 \\
7 & 12 & 21 & 9\\
\end{pmatrix}=\begin{pmatrix}
x\\
y\\
z\\
\end{pmatrix}=$$
$$\begin{pmatrix}
1 & -3 & -9 & -3 \\
0 & 38 & 97 & 34\\
0 & 33 & 84 & 30\\
\end{pmatrix}=\begin{pmatrix}
x\\
y\\
z\\
\end{pmatrix}=$$
$$\begin{pmatrix}
1 & -3 & -9 & -3 \\
0 & 5 & 13 & 4\\
0 & 0 & -1 & 2\\
\end{pmatrix}=\begin{pmatrix}
x=\\
y=6\\
z=-2\\
\end{pmatrix}=$$
on check si des combinaison de collones évidente.
on inverse la matrice
![1219b94e243551487f995b8ef8c6667c.png](../../_resources/1219b94e243551487f995b8ef8c6667c.png)
$$[Id]_{CB}\begin{pmatrix}
1 & 0 \\
1 & 1 \\
\end{pmatrix}$$
$$[Id]_{C_pD}\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 1 \\
0 & 1 & -1 \\
\end{pmatrix}$$
$$[Id]_{C_pC}\begin{pmatrix}
0 & 0\\
1 & 0\\
0 & 1\\
\end{pmatrix}$$
$$[Id]_{DC_p}[Id]_{C_pC}[Id]_{CB}$$
$$[Id]_{DC_p}\begin{pmatrix}
1 & 0 & 0 & | & 1 & 0 & 0 \\
0 & 1 & 0 & | & 0 & 1/2 & 1/2 \\
0 & 0 & 1& | & 0 & 1/2 & -1/2 \\
\end{pmatrix}$$
$$[Id]_{DC_p}\begin{pmatrix}
 1 & 0 & 0 \\
0 & 1/2 & 1/2 \\
0 & 1/2 & -1/2 \\
\end{pmatrix}$$
$$[Id]_{DC_p}[Id]_{C_pC}[Id]_{CB}=$$
$$\begin{pmatrix}
0 & 0\\
1 & 1/2\\
0 & -1/2\\
\end{pmatrix}$$
![6aa6aa5cfdb1cac55d8f8d8242ee5dcb.png](../../_resources/6aa6aa5cfdb1cac55d8f8d8242ee5dcb.png)
$$C_{53}=A_{L5}B_C3=4+7+27=38$$
![04f4a40834a3cce32903cea451dee33f.png](../../_resources/04f4a40834a3cce32903cea451dee33f.png)
$$Bb=Y$$
$$\begin{pmatrix}
1 & 1\\
1 & -1\\
1 & 0\\
\end{pmatrix}\begin{pmatrix}
b_0\\
b_x\\
\end{pmatrix}=\begin{pmatrix}
2\\
5\\
3\\
\end{pmatrix}$$
$$B^TBb=B^TY$$
$$\begin{pmatrix}
3 & 0\\
0 & 2\\
\end{pmatrix}\begin{pmatrix}
b_0\\
b_x\\
\end{pmatrix}=\begin{pmatrix}
10\\
-3\\
\end{pmatrix}$$
10/3 pour le b_0 car on peut éliminer 2 solution
$$\begin{pmatrix}
3 & 0\\
0 & 2\\
\end{pmatrix}\begin{pmatrix}
10/3\\
-3/2\\
\end{pmatrix}=\begin{pmatrix}
10\\
-3\\
\end{pmatrix}$$
![733e6c9508e1ea07779ac4e2b5bba2bc.png](../../_resources/733e6c9508e1ea07779ac4e2b5bba2bc.png)
$$\begin{pmatrix}
-1 & 0 & 2 & | & 1 & 0 & 0\\
1 & 2 & -1& | & 0 & 1 & 0\\
0 & -1 & 3& | & 0 & 0 & 1\\
\end{pmatrix}$$

$$\begin{pmatrix}
1 & 0 & 0 & | & -1+2/7 & 2/7 & 2/7\\
0 & 1 & 0& | & 1/2-1/14 & 1/2-1/14 & -1/14\\
0 & 0 & 1& | & 1/7 & 1/7 & 2/7\\
\end{pmatrix}$$

$$\begin{pmatrix}
-5/7 & 2/7 & 2/7\\
6/14 & 6/14& -1/14\\
1/7 & 1/7 & 2/7\\
\end{pmatrix}\begin{pmatrix}
0\\
1\\
-8\\
\end{pmatrix}=-15/7$$


![e852c792c6a57b4fdeee755e92fd3b10.png](../../_resources/e852c792c6a57b4fdeee755e92fd3b10.png)

$$\begin{pmatrix}
1 & 4 & 9 & -2\\
3 & 2 & 1 & 0\\
1 & 1 & 2 & 1\\
2 & 1 & -1 & 0\\
\end{pmatrix}$$

$$\begin{pmatrix}
3 & 6 & 13 & 0\\
3 & 2 & 1 & 0\\
1 & 1 & 2 & 1\\
2 & 1 & -1 & 0\\
\end{pmatrix}$$
$$(-1)\begin{pmatrix}
29 & 19 & 0 \\
5 & 3 & 0 \\
2 & 1 & -1\\
\end{pmatrix}$$
$$(-1)(-1)\begin{pmatrix}
29 & 19 \\
5 & 3 \\
\end{pmatrix}=87-95=-8$$
![a05720476a9a596b0e2124d2f3913171.png](../../_resources/a05720476a9a596b0e2124d2f3913171.png)
-1/2

-1          1/4=h
-1/2 5/4*2    =2
-2         0.5=2h
-2         -2

$$ h=1/4$$
![8ad99ff8f232db6851bc19605f1ca69b.png](../../_resources/8ad99ff8f232db6851bc19605f1ca69b.png)
bien faire le dessin pour se rendre compte quil y a rien a faire a par ecrire la matrice
$$\begin{pmatrix}
1 & 2 &4 \\
3 & 0 & 1\\
0 & 1 & 3\\
\end{pmatrix}$$
donc 
$$p_{12}=2$$
![a329ad0141cdcaefa72a3cebac869acf.png](../../_resources/a329ad0141cdcaefa72a3cebac869acf.png)
$$\begin{pmatrix}
2 & 1 & 3 & -4 \\
1 & 2 & 3 & -1 \\
3 & 2 & 1 & -2 \\
\end{pmatrix}$$
$$\begin{pmatrix}
1 & 2 & 3 & -1 \\
0 & -3 & -3 & -2 \\
0 & -4 & -8 & 1 \\
\end{pmatrix}$$
$$\begin{pmatrix}
1 & 2 & 3 & -1 \\
0 & 1 & 5 & -3 \\
0 & 0 & 1 & -11/12 \\
\end{pmatrix}$$
$$\begin{pmatrix}
1 & 2 & 0 & -1+33/12 \\
0 & 1 & 0 & -3+55/12 \\
0 & 0 & 1 & -11/12 \\
\end{pmatrix}$$
$$\begin{pmatrix}
1 & 0 & 0 & 5-77/12 \\
0 & 1 & 0 & -3+55/12 \\
0 & 0 & 1 & -11/12 \\
\end{pmatrix}$$
$$r_{24}=19/12$$
![800e3cb719e53ea745138a7e8887e2f0.png](../../_resources/800e3cb719e53ea745138a7e8887e2f0.png)
est inversible et sont inverse orthogonalement diagonalisaeble car elle est symmétrique

![5cd5fcadaa188f511065c8a501d844d7.png](../../_resources/5cd5fcadaa188f511065c8a501d844d7.png)
on soustrait la valeur propre et on veux que le determinantn soit nul
$$\begin{pmatrix}
-5 & k & 0 \\
5 & -4 & 1\\
0 & l & -5\\
\end{pmatrix}$$
$$\begin{pmatrix}
-5 & k & 0 \\
5 & 1 & 1\\
0 & l-25 & -5\\
\end{pmatrix}$$
$$\begin{pmatrix}
-5 & k & 0 \\
0 & 1+k & 1\\
0 & l-25 & -5\\
\end{pmatrix}$$
$$-5(1+k)+(25-l)$$
$$20=l+5k$$
![12149771a9d7aa7b7b90f3d3f157b1f1.png](../../_resources/12149771a9d7aa7b7b90f3d3f157b1f1.png)



![cd27375b89e4d4f154a37079fe8bd1b0.png](../../_resources/cd27375b89e4d4f154a37079fe8bd1b0.png)

![964745b212c6c4ab3e98bf9bf86190c8.png](../../_resources/964745b212c6c4ab3e98bf9bf86190c8.png)

![1970685c71284328e99ea465eba1c451.png](../../_resources/1970685c71284328e99ea465eba1c451.png)

![8fa0d8c6454fe043634d8cf751a54bde.png](../../_resources/8fa0d8c6454fe043634d8cf751a54bde.png)

![fa71b4fdbddfa686a0c196a8f18943ab.png](../../_resources/fa71b4fdbddfa686a0c196a8f18943ab.png)

![836db93e614f3cfe7232dbc93cb921dc.png](../../_resources/836db93e614f3cfe7232dbc93cb921dc.png)

![86865437a5ccd0fb51357185e299c69d.png](../../_resources/86865437a5ccd0fb51357185e299c69d.png)

![16acb2aef4daaf92afe0d53c0b23ca35.png](../../_resources/16acb2aef4daaf92afe0d53c0b23ca35.png)

![fd68701e054a068e441c6537897512cb.png](../../_resources/fd68701e054a068e441c6537897512cb.png)

![3a68da66507715f5aa53b5325c9e81f8.png](../../_resources/3a68da66507715f5aa53b5325c9e81f8.png)

![94e31f4c233e49aa3f45ea730b7531e9.png](../../_resources/94e31f4c233e49aa3f45ea730b7531e9.png)

![939da1e168c3f2876f21db635d4cf280.png](../../_resources/939da1e168c3f2876f21db635d4cf280.png)

![12f0bc32b314fe10674ce80947233676.png](../../_resources/12f0bc32b314fe10674ce80947233676.png)

![eae2b1fa6a5d0289ac6be56fe5ddecb1.png](../../_resources/eae2b1fa6a5d0289ac6be56fe5ddecb1.png)

![adf21546574ada9373411faed3d02db6.png](../../_resources/adf21546574ada9373411faed3d02db6.png)

![0fbcd4cba955ffef27e717f426a6891e.png](../../_resources/0fbcd4cba955ffef27e717f426a6891e.png)

![cc08be3ca11ec4f6eca8dbbc87f57589.png](../../_resources/cc08be3ca11ec4f6eca8dbbc87f57589.png)

![41ca596d8a117396412e0e5b3f0f17b3.png](../../_resources/41ca596d8a117396412e0e5b3f0f17b3.png)

![3171f502bb8e84da971c8d77c218eff5.png](../../_resources/3171f502bb8e84da971c8d77c218eff5.png)

2019
![e1bc00248a2c5e8c7f06164f0ea253a3.png](../../_resources/e1bc00248a2c5e8c7f06164f0ea253a3.png)


![b3c4e04c1ed48001d9c35276cc91f147.png](../../_resources/b3c4e04c1ed48001d9c35276cc91f147.png)

![aac9138669909ee16e403daceeba2272.png](../../_resources/aac9138669909ee16e403daceeba2272.png)

![3bab992a3a606120d8f0f701f8667a65.png](../../_resources/3bab992a3a606120d8f0f701f8667a65.png)

![a487a1bb75ccf6dee4ac028ec6122c84.png](../../_resources/a487a1bb75ccf6dee4ac028ec6122c84.png)

![9a227f0923b6adc4d96a22e3e62ecbe5.png](../../_resources/9a227f0923b6adc4d96a22e3e62ecbe5.png)

![9100042901b08ddf119d103871f18675.png](../../_resources/9100042901b08ddf119d103871f18675.png)

![6e74e119ff799f7b8923a2facbb4000d.png](../../_resources/6e74e119ff799f7b8923a2facbb4000d.png)

![bffd2e7b374221b91cb802efb43743a0.png](../../_resources/bffd2e7b374221b91cb802efb43743a0.png)

![53a68642bb2f59381925852ecc48bb1e.png](../../_resources/53a68642bb2f59381925852ecc48bb1e.png)

![120e54277d1b214b6d278e50bc1e08ac.png](../../_resources/120e54277d1b214b6d278e50bc1e08ac.png)

![cf88536e8a13d915016b3677cf5d939f.png](../../_resources/cf88536e8a13d915016b3677cf5d939f.png)

![c3be1261323ccbfbfeead2c417a3dc89.png](../../_resources/c3be1261323ccbfbfeead2c417a3dc89.png)

![3066e02ab1c9361d2ce4d9cfcdebe5e3.png](../../_resources/3066e02ab1c9361d2ce4d9cfcdebe5e3.png)

![047dd6084f81ef937d54b367cfd66b3d.png](../../_resources/047dd6084f81ef937d54b367cfd66b3d.png)

![4639382aaec583df072bbfe72b00bf92.png](../../_resources/4639382aaec583df072bbfe72b00bf92.png)

![df444896dae8f67dbea8ccc97a378f49.png](../../_resources/df444896dae8f67dbea8ccc97a378f49.png)

![bf69e6dd85694e972009fb704849795f.png](../../_resources/bf69e6dd85694e972009fb704849795f.png)

![7efeb7b90fa2d260c52e8b7d022869d1.png](../../_resources/7efeb7b90fa2d260c52e8b7d022869d1.png)

![5dcc7a4b1e6bc37f06d9fc6da24e6f1c.png](../../_resources/5dcc7a4b1e6bc37f06d9fc6da24e6f1c.png)

![3ac2c1a80a9453f6b2b1d8c1faf2179a.png](../../_resources/3ac2c1a80a9453f6b2b1d8c1faf2179a.png)

2018

![00357833a5a1c1a1dad46fd866f30344.png](../../_resources/00357833a5a1c1a1dad46fd866f30344.png)


![06922a3b2ddefa21fdf211672175d51e.png](../../_resources/06922a3b2ddefa21fdf211672175d51e.png)

![79d75917969df2e480888706c10c6505.png](../../_resources/79d75917969df2e480888706c10c6505.png)

![5b81c827da67a8943f539b2c35244c45.png](../../_resources/5b81c827da67a8943f539b2c35244c45.png)

![69b5a3018d05e8af9fe3201096409bdd.png](../../_resources/69b5a3018d05e8af9fe3201096409bdd.png)

![1d93e8aae4ff40bc45857ea66701e10f.png](../../_resources/1d93e8aae4ff40bc45857ea66701e10f.png)

![0c5c9cfa4de1c66a9cedaa94a92afae4.png](../../_resources/0c5c9cfa4de1c66a9cedaa94a92afae4.png)

![72cb7ca34700c2b4c740673de3420f76.png](../../_resources/72cb7ca34700c2b4c740673de3420f76.png)

![3c26820ebb963dc746fef1446db6aeaa.png](../../_resources/3c26820ebb963dc746fef1446db6aeaa.png)

![f89118e45dd0e554c7050f094b1ca36e.png](../../_resources/f89118e45dd0e554c7050f094b1ca36e.png)

![d9e4ffc59c30d2c3235204b9bcf73b18.png](../../_resources/d9e4ffc59c30d2c3235204b9bcf73b18.png)

![18e62826f63485024f2313e722d772f7.png](../../_resources/18e62826f63485024f2313e722d772f7.png)

![e7bd5b3e22def1674ed7a7dfff3faac9.png](../../_resources/e7bd5b3e22def1674ed7a7dfff3faac9.png)

![a39193337a7a26c2a040961b220402d4.png](../../_resources/a39193337a7a26c2a040961b220402d4.png)


![c2420c7aa6463d9345f1acf061da3d7c.png](../../_resources/c2420c7aa6463d9345f1acf061da3d7c.png)

![f55abce96731cf2d785450910958e6c3.png](../../_resources/f55abce96731cf2d785450910958e6c3.png)

![57b1be037b55998945ea698a96e96496.png](../../_resources/57b1be037b55998945ea698a96e96496.png)

![9f91475f1a04fe32132479fad84117a5.png](../../_resources/9f91475f1a04fe32132479fad84117a5.png)

![2eb071ce9ae88c8ac4c8d05a5fc40579.png](../../_resources/2eb071ce9ae88c8ac4c8d05a5fc40579.png)

![b52ef0dc3c3623d411a4379b5e451903.png](../../_resources/b52ef0dc3c3623d411a4379b5e451903.png)

![387a63f9ada2ffd95ea9b31bb59489c6.png](../../_resources/387a63f9ada2ffd95ea9b31bb59489c6.png)

![55cefd60fab14816f92ec0ef0c47cfd1.png](../../_resources/55cefd60fab14816f92ec0ef0c47cfd1.png)

![3bc5c4dd1cad3944f7de200d22aec19f.png](../../_resources/3bc5c4dd1cad3944f7de200d22aec19f.png)

![cebfefb4dcb4e244bb2748f15ecfeb20.png](../../_resources/cebfefb4dcb4e244bb2748f15ecfeb20.png)

2017

![fdda34a84bf10b23636d52aea14fffb0.png](../../_resources/fdda34a84bf10b23636d52aea14fffb0.png)

![c2d0d6e5514c920b7b6376c70ec5792e.png](../../_resources/c2d0d6e5514c920b7b6376c70ec5792e.png)

![bf514376548477df048c8c3e4e9395a2.png](../../_resources/bf514376548477df048c8c3e4e9395a2.png)

![8c616664fcf693f9ceb95c4d1acc29e8.png](../../_resources/8c616664fcf693f9ceb95c4d1acc29e8.png)

![342816d89e836997acf505084c646760.png](../../_resources/342816d89e836997acf505084c646760.png)

![e5fb744fefe2b3695d8e4913e3043119.png](../../_resources/e5fb744fefe2b3695d8e4913e3043119.png)

![89a9bf060a99f2f39fcea245e1b7269f.png](../../_resources/89a9bf060a99f2f39fcea245e1b7269f.png)

![cc3a76cdc54a93297f69e31ebbb50d7d.png](../../_resources/cc3a76cdc54a93297f69e31ebbb50d7d.png)

![da5c707b82f2a955d591bb627e1483a0.png](../../_resources/da5c707b82f2a955d591bb627e1483a0.png)

![a57a008bce6e46bff0c2c4d99929279d.png](../../_resources/a57a008bce6e46bff0c2c4d99929279d.png)

![ab254a38f30d5973dcf1800e602adc0f.png](../../_resources/ab254a38f30d5973dcf1800e602adc0f.png)

![acfea1f762beb0ab375cbc9656f21cc4.png](../../_resources/acfea1f762beb0ab375cbc9656f21cc4.png)

![83b49ac84e7db8dca4cfb33ff27f8de6.png](../../_resources/83b49ac84e7db8dca4cfb33ff27f8de6.png)

![5aef4905894f85680b36a571d84e62d3.png](../../_resources/5aef4905894f85680b36a571d84e62d3.png)

![57b193ea9c5966c89875944d64f48af0.png](../../_resources/57b193ea9c5966c89875944d64f48af0.png)

![662f6b51e5e7e7645a9bb61f721b32eb.png](../../_resources/662f6b51e5e7e7645a9bb61f721b32eb.png)

![1e49e96138f35047ec8cdaef183ffa59.png](../../_resources/1e49e96138f35047ec8cdaef183ffa59.png)

![6a0dcf7a76a46ce95b021a8222b4c82e.png](../../_resources/6a0dcf7a76a46ce95b021a8222b4c82e.png)

![eba100f1978f7e0986fc5c079bd4b502.png](../../_resources/eba100f1978f7e0986fc5c079bd4b502.png)

![bb3c4949b2997ada216722ab15eaa8a6.png](../../_resources/bb3c4949b2997ada216722ab15eaa8a6.png)

![41144bd81cda53f107bbcafdad1d7563.png](../../_resources/41144bd81cda53f107bbcafdad1d7563.png)

![25c96f0383e303f5c49ee34b094823e1.png](../../_resources/25c96f0383e303f5c49ee34b094823e1.png)

![dde4e827f231d68480337e6eebf1d3a9.png](../../_resources/dde4e827f231d68480337e6eebf1d3a9.png)

![9fb8444b1280ed79c1ee7036957ae593.png](../../_resources/9fb8444b1280ed79c1ee7036957ae593.png)

