X skup; S polje skalara
X je konv ako: Vx1, x2 in X: a*x1 + b*x2 in X,
x1, x2 in S

f = 1/x

f(ax+(1-a)y) < af(x) + (1-a)f(y) ?
1/(ax+(1-a)y) < a/x + (1-a)/y    ?
1/(ax+(1-a)y) < (ay+x(1-a))/xy ?
xy < (ay+x(1-a))*(ax+(1-a)y)    ?
xy < [a(y-x) + x]*[a(x-y) + y]
xy < -a**2(x-y)**2 + ay(y-x) + ax(x-y) + xy
0 < -a**2(x-y)**2 +(x-y)(-ay+ax)
0 < -a**2(x-y)**2 + a(x-y)**2
0 < (a-a**2)(x-y)**2
0 < a(1-a)(x-y)**2

eksperiment -> ishodi [1, 2, 3, 4, 5, 6]
prostor_ishoda {1, 2, 3, 4, 5, 6}
dogadjaj in prostor_ishoda {1, 3, 5}: pao je neparan broj
funkcija_verovatnoce: ishod -> verovatnoca
P(1) = P(2) = P(3) = ... = P(6) = 1/6

tri bacanja novcica: _, _, _
prostor_ishoda: {PPP, PPG, PGP, GPP, ..}? 2*2*2 = 8 (0.125)
dogadjaj = {GPP, PGP, PPG} - pala je jedna glava: 3/8

prostor_ishoda I
P: I -> R, funkcija verovatnoce ako:
* 0 <= P(w) <= 1, w in I
* sum {w in I} P(w) = 1

P(i^C) = 1 - P(i), i in I

P(i1 U i2) = P(i1) + P(i2) - P(i1 ^ i2)