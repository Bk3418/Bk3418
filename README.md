#Patika.dev ınsertion sort projesi
[22,27,16,2,18,6]
1-)dizinin sort türüne göre aşamalarını yazınız?
   a)[2,27,16,22,18,6]-> en küçük sayı 2 olduğu için 22 ile yer değiştirdik.
   b)[2,6,16,22,18,27]-> en küçük 2.sayı 6 olduğu için 27 ile yer değiştirdik.
   c)[2,6,16,22,18,27] -> en küçük 3.sayı 16 olduğu için yer değişmedi
   d)[2,6,16,18,22,27]-> en küçük 4.sayı 18 olduğu için 22 ile yer değiştirdik.
   e)[2,6,16,18,22,27]-> en küçük 5.sayı 22 olduğu için yer değişmedi
   f)[2,6,16,18,22,27]->en küçük 6.saayı 27 olduğu için yerdeğişmedi.
   
2-)O(n^2)

3-) Averge case: aradığımız sayının ortada olması 
    worst casse: aradığımız sayının sonda olması
    best case: aradığımız sayının dizinin en başında olması.
    
 4-)[2,6,16,18,22,27] sıralanmış dizi averge case kapsamına girer.
 5-) 1.adım) [2,3,5,8,7,9,4,15,6]-> en küçük sayını 2 olduğu için 7 ile yer değiştirdik
     2.adım) [2,3,5,8,7,9,4,15,6]-> en küçük 2.sayı 3 olduğu için yer değiştirmedik.
     3.adım) [2,3,4,8,7,9,5,15,6]-> en küçük 3.sayı 4 olduğu için 5 ile yer değiştirdik.
     4.adım) [2,3,4,5,7,9,8,15,6]-> en küçük 4.sayı 5 olduğu için 8 ile yer  değiştirdik.

