# Patika_projeler

INSERTION SORT

[22,27,16,2,18,6] --> Insertion Sort

Yukarýda verilen dizinin sort türüne göre aþamalarýný yazýnýz.
[22,27,16,2,18,6]--> n

[2,27,16,22,18,6]-->(n-1)

[2,6,16,22,18,27]-->(n-2)

[2,6,16,18,22,27]-->1

n*(n-1)/2			Big O notation =O(n^2)


Time Complexity:

1. Worst Case: Aradýðýmýz sayýnýn sonda olmasý, bu örnek için 27

2.Average Case: Aradýðýmýz sayýnýn ortada olmasý 16 ya da 18 

3. Best Case : Aradýðýmýz sayýnýn dizinin baþýnda olmasý, bu dizi için 2.


Dizi sýralandýktan sonra 18 sayýsý Average Case kapsamýndadýr.



[7,3,5,8,2,9,4,15,6] Dizisinin Insertion Sort'a göre ilk 4 adýmý

1.adým 
[2,3,5,8,7,9,4,15,6]

2.adým
[2,3,4,8,7,9,5,15,6]

3.adým
[2,3,4,5,7,9,8,15,6]

4.adým
[2,3,4,5,6,9,8,15,7]

