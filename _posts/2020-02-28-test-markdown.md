---
layout: post
title: Soal Mingguan 1 - 13/07/2023
tags: [soalmingguan, aljabar, sedang]
comments: true
---

### Soal
Diketahui $a, b, c, d$ real sehingga,

$a^n+b^n+c^n=d^n\ \forall\ n=1, 2,\text{dan}\ 3.$

Tentukan semua $(a, b, c, d)$ yang memenuhi.
### Solusi
Perhatikan bahwa,
$a+b+c=d,$

$a^2+b^2+c^2=d^2,$

$a^3+b^3+c^3=d^3.$
Akibatnya

$ab+bc+ca=\dfrac{(a+b+c)^2-(a^2+b^2+c^2)}{2}=0$

dan

$a^3+b^3+c^3+3abc=(a+b+c)(a^2+b^2+c^2-ab-bc-ca)\implies	abc=\dfrac{d(d^2-0)-d^3}{3}=0.$

Bila $a, b, c$ merupakan bilangan real yang memenuhi persamaan $px^3+qx^2+rx+s=0$, maka

$-\dfrac{q}{p}=d,	\dfrac{r}{p}=0, -\dfrac{s}{p}=0.$

Akibatnya dapat dipastikan $s=r=0$ dan $q=-pd$. Maka $a, b, c$ merupakan bilangan real yang memenuhi persamaan $px^3-pdx^2=0$, kemudian karena $p\ne0$ akibatnya $x^3-dx^2=0\implies x^2(x-d)=0$ sehingga $x=0$ atau $x=d$. Maka $(a, b, c)=(d, 0, 0), (0, d, 0),$ dan $(0, 0, d)$ untuk setiap $d$ real.
		
Jadi $(a, b, c, d)=(d, 0, 0, d), (0, d, 0, d),$ dan $(0, 0, d, d)$.

{: .box-error}
**Error:** This is an error box.
