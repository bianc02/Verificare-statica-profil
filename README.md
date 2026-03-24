date intrare:caracteristici profil (I, h)
dimensiuni (L)
acțiuni (presiune vânt p)
dimensiuni geam
Am transformat presiunea vântului în încărcare liniară:
q=p⋅ltributar
rezistența materialelor:
​​Moment:M=qL2/8
Deformație:f=5qL4/384EI​
Tensiune:o=M/W,W≈ I/h/2​
​
Am calculat greutatea geamului:g=(t1+t2)x2.5

au fost implementate în JavaScript.​

Am transformat presiunea de vânt în încărcări liniare folosind lățimi tributare, apoi am evaluat răspunsul structural prin relațiile clasice pentru moment maxim, săgeată și tensiune.

Am estimat modulul de rezistență pe baza inerției profilului pentru a obține tensiunile și am verificat criteriile de serviciu (deformații tip L/300) și rezistență (σ admisibil).​
