#Patika.dev ınsertion sort projesi
[22,27,16,2,18,6] -> Insertion Sort
1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-)  a) [2,27,16,22,18,6]-> en küçük sayının 2 olduğunu belirledik ve 22 ile yer değiştirdik.
     b) [2,6,16,22,18,27]-> en küçük 2.sayının 6 olduğunu belirledik ve 27 ile yer değiştirdik.
     c) [2,6,16,22,18,27]-> en küçük 3.sayı 16  olduğu için yer değiştirilmedi.
     d) [2,6,16,18,22,27]-> en küçük 4.sayının 18 olduğunu belirledik ve 22 ile yer değiştirdik.
     e) [2,6,16,18,22,27]-> en küçük 5. sayı 22 olduğu için yer değişmedi.
     f) [2,6,16,18,22,27]-> en küçük 6.sayı 27 olduğu için yer değişmedi ve tamamlandı.
     
2-) O(n^2)

3-)Averge case: Aradığımız sayının ortada olması
   Worst case: Aradığımız sayının sonda olması
   Best case: Aradığımız sayını dizinin en başında olması.
   
4-)[2,6,16,18,22,27]-> sıralanmış dizide Averge case kapsamına girer.

5-) 1.Adım) [2,3,5,8,7,9,4,15,6]-> en küçük syının 2 olduğunu belirledik ve 7ile yer değiştirdik.
    2.Adım) [2,3,5,8,7,9,4,15,6]-> en küçük 2.sayının 3 olduğunu belirledik ve doğru yerde olduğu için sabit tuttuk.
    3.Adım) [2,3,4,8,7,9,5,15,6]-> en küçük 3.sayının 4 olduğunu belirledik ve 5 ile yer değiştirdik.
    4.adım) [2,3,4,5,7,9,8,15,6]-> en küçük 4.sayının 5 olduğunu belirledik ve 8 ile yer değiştirdik.
